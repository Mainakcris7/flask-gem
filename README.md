# FlaskGem (v1.1.0)

## Introduction

Welcome to FlaskGem, an AI-based web application created using Flask. FlaskGem utilizes the Gemini AI platform to provide text and image query capabilities. This documentation will guide you through the features and usage of FlaskGem.

Access the web-app: https://flask-gem.onrender.com

![Logo](./static/flask_gem_avatar.png)

### Release Note: v1.1.0

#### New Feature: Chat Based on History

- Introducing the new "Chat Based on History" feature in FlaskGem v1.1.0!
- Users can now access previous chat history within the application.
- Easily review past conversations and continue discussions seamlessly.
- Enhances user experience by providing context and continuity in chats.

## Features

1. **Text and Image Queries**: FlaskGem allows users to make both text and image queries to the Gemini AI platform.
2. **Session Storage**: User queries and corresponding answers are stored in the sessionStorage, ensuring that chats are retained even after page reloads.
3. **Fetch API**: The Fetch API is used to send requests to the Flask server, enabling seamless communication without page reloads.

## Getting Started

### Requirements

- Web browser (Chrome, Firefox, Safari, etc.)
- Internet connection

### Installation

1. Clone the FlaskGem repository from GitHub.
   ```bash
   git clone https://github.com/Mainakcris7/flask-gem.git
   ```
2. Navigate to the FlaskGem directory.
   ```bash
   cd flask-gem
   ```
3. Install the packages from requirements.txt (may exclude `Gunicorn`)
   ```bash
   pip install -r requirements.txt
   ```
4. Run `python app.py` from your preferred terminal.

### Usage

1. **Text Queries**:
   - Enter your text query in the text input field.
   - Press the "Send" button or hit Enter to submit the query.
   - View the response from the Gemini AI platform in the chat interface.

2. **Image Queries**:
   - Click the "Upload Image" button.
   - Select an image file from your device.
   - Enter your specific query for the image.
   - Wait for the response from the Gemini AI platform, which will be displayed in the chat interface.

3. **Session Storage**:
   - User queries and responses are stored in sessionStorage.
   - This ensures that chats are retained even if the page is reloaded or navigated away from.

4. **Fetch API**:
   - The Fetch API is used to send requests to the Flask server.
   - This communication method avoids page reloads, providing a smoother user experience.

### Considerations

1. **Gemini Free Version**:
   - FlaskGem uses the free version of the Gemini AI platform, which has limited API call capabilities.
   - Consider upgrading to a paid plan for increased API call limits.

2. **Potential Mistakes**:
   - The Gemini AI platform may make mistakes in processing queries.
   - Review responses carefully and verify information when needed.

3. **API Key**:
   - Please obtain your own API key from the Gemini AI platform at [https://ai.google.dev/](https://ai.google.dev/).
   - Replace the placeholder API key in the (`.env`) file with your own API key for proper functionality.

## Support and Feedback

For support or feedback regarding FlaskGem, please contact [mainakcr72002@gmail.com](mainakcr72002@gmail.com).
