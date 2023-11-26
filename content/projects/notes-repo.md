---
title: 'Notes Repository - Django Backend'
disableshare: true
summary: 
draft: false
hidemeta: true
---

**Notes Repository** is a feature-rich website backend built using the Django framework. It facilitates users to view, download, like, and comment on lecture notes for various courses. Additionally, users can contribute by uploading their own notes, fostering a collaborative learning environment.

## Features

- **Course-Based Organization:** Notes are categorized by courses, providing a structured layout for users to easily find relevant materials.

- **User Interaction:** Users can view, download, like, and comment on existing lecture notes, fostering engagement and collaboration.

- **Upload Functionality:** Users have the capability to upload their own lecture notes, contributing to the repository's content.

## Instructions for further development
Run the following commands:
- `git clone https://github.com/vishruthdevan/notes-repo.git` into any directory <dir_name>
- `cd <dir_name>`
- `pip install -r requirements.txt` (make a virutal env if needed)
- `python manage.py makemigrations`
- `python manage.py migrate`
- `python manage.py runserver`

## Usage

- Access the Django admin panel at http://localhost:8000/admin/ to manage courses, notes, and user interactions.

- Visit the main site at http://localhost:8000/ to explore, download, and interact with lecture notes.

## Related Links

- [GitHub Repository](https://github.com/vishruthdevan/notes-repo/)