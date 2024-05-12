---
title: YT-Fetcher
summary: A web application for downloading audio and video content from YouTube. Built with React front-end and Python back-end.
tags:
  - Others
date: '2017-04-20T00:00:00Z'
weight: 3

# Optional external URL for project (replaces project detail page).
external_link: 'https://github.com/tusharmalankiya/yt-fetcher'

image:
  caption: Photo by Tushar Malankiya
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/
# url_code: ''
# url_pdf: ''
# # url_slides: ''
# url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

This is a simple YouTube downloader web application that allows users to download audio and video from YouTube. It consists of a frontend built with React and a backend built with Python.

## Features

- Download audio (MP3) and video (MP4) from YouTube videos.
- Easy-to-use web interface.
- Responsive design for desktop and mobile devices.

## Technologies Used

- **Frontend**:
  - React
  - HTML
  - CSS

- **Backend**:
  - Python
  - Flask

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/tusharmalankiya/yt-fetcher.git
   ```

2. Install dependencies for frontend:

   ```bash
   cd client
   npm install
   ```
3. Create a virtual environment for backend

   ```bash
   cd server
   python3 -m venv venv
   ```

4. Activate the virtual environment

- **For windows**:
   ```bash
   .\venv\Scripts\activate
   ```

  **Or**

- **For Linux/Mac**
   ```bash
   source venv/bin/activate
   ```



5. Install dependencies for backend (assuming you have Python and pip installed):

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Start the backend server:
   > Activate the virtual environment if it is not activated.

   ```bash
   cd server
   python app.py
   ```

3. Start the frontend development server:
    ```bash
    cd client
    npm start
    ```

4. Open your web browser and navigate to http://localhost:3000 to access the application.

5. Paste youtube link and download preferred type of content (either audio or video). 
