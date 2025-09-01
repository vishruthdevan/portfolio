---
title: Covi-Track
hidemeta: false
disableshare: true
summary: 
draft: false
weight: 12
---

**Covi-Track** is a web application designed for tracking COVID-19 hotspots. Leveraging GeoIP2, Google Maps Javascript API, and the Django web framework, this tool provides an interactive and informative platform for users to stay updated on COVID-19 cases.

## Features

The website predominantly features an interactive map where each marker represents a user. The markers are categorized based on the user's COVID-19 status, such as:

- **Contracted COVID-19**: Users who have been diagnosed with COVID-19.
- **Vaccinated**: Users who have received the COVID-19 vaccine.
- **Recovered**: Users who have successfully recovered from COVID-19.

This categorization provides a visual representation of COVID-19 data, allowing users to quickly grasp the current status of individuals in different categories across geographical locations.

## Technologies Used

- **Django**: A high-level Python web framework for building robust web applications.
- **GeoIP2**: A library that enables the retrieval of geographical information based on IP addresses, enhancing the accuracy of location tracking.
- **Google Maps Javascript API**: Empowers the application with dynamic and interactive mapping capabilities.

## Related Links

- [GitHub Repository](https://github.com/vishruthdevan/covi-track/)

*Note: Ensure proper setup and configuration, including API keys for Google Maps, for the seamless functioning of the application.*
