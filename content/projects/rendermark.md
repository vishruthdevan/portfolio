---
title: RenderMark
disableshare: true
summary: 
draft: false
hidemeta: false
weight: 13
---


The **RenderMark** project is a web-based application designed to render parsed Markdown text on video templates, providing a convenient platform for users to create and download customized videos.

## Functionalities

- **Markdown Editor**: Allows users to enter text and images using a Markdown editor.
  
- **Image Conversion**: Converts images pasted from the clipboard into links for efficient rendering.
  
- **Template Management**: Displays a list of available video templates for user selection.
  
- **Markdown Parsing**: Parses Markdown files to extract text and images for video rendering.
  
- **Task Creation**: Enables users to create rendering tasks, specifying the video template and input data.
  
- **Video Rendering**: Utilizes MoviePy, a video editing module, to render the video using the selected template and extracted data.
  
- **Task Management**: Provides a task management system for monitoring and tracking rendering tasks.
  
- **Task Status Viewing**: Allows users to view the status of their rendering tasks in real-time.
  
- **Video Download**: Enables users to download the rendered video upon completion.

## Technologies Used

- **FastAPI**: A Pythonic framework for building the backend, providing a fast and efficient web application.
  
- **Celery Tasks**: A task queue or job queue based on distributed message passing, enhancing the application's scalability.
  
- **MoviePy**: A versatile video editing module for basic operations, video compositing, and more, utilizing ffmpeg.
  
- **Docker**: Containerizes the application for easy deployment and scalability.

## Related Links

- [GitHub Repository](https://github.com/vishruthdevan/RenderMark-backend/)

Experience the power of RenderMark, where creativity meets efficiency in rendering customized videos.
