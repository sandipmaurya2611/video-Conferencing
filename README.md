# Video Conferencing App

This project is a simple video conferencing application built using the Agora API, HTML, CSS, and JavaScript. The app allows multiple users to join a video call and interact in real-time.

## Features

- **Real-time Video and Audio Communication**: Connect with multiple users simultaneously.
- **User Interface**: Simple and intuitive UI built with HTML and CSS.
- **Mute/Unmute Audio**: Control your audio during the call.
- **Enable/Disable Video**: Control your video feed during the call.

## Getting Started

### Prerequisites

- A modern web browser
- Agora account and API key

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/video-conferencing-app.git
    cd video-conferencing-app
    ```

2. Open `index.html` in your preferred web browser.

### Configuration

1. Obtain an Agora API key by signing up at [Agora](https://www.agora.io/).
2. Update the Agora API key in the JavaScript file:

    ```javascript
    const AGORA_APP_ID = 'your-agora-app-id';
    ```

## Usage

1. Open the `index.html` file in your web browser.
2. Enter a channel name and click 'Join'.
3. Allow the browser to access your camera and microphone.
4. You are now connected to the video call.

## Project Structure

```plaintext
├── css/
│   ├── style.css       # Contains the styles for the application
├── js/
│   ├── agora-rtc-sdk.js # Agora SDK
│   ├── main.js         # Main JavaScript logic for the application
├── index.html          # Main HTML file
└── README.md           # Project documentation
