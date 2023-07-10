# Google Meet Clone

This is a clone of Google Meet, a video conferencing web application. It allows users to create and join video meetings, communicate through chat, and share a whiteboard for collaborative drawing.

## Features

- User authentication using Google OAuth 2.0
- Create a new meeting room
- Join an existing meeting room using a Room ID
- Video conferencing with real-time audio and video streams
- Mute/unmute audio during the meeting
- Stop/start video during the meeting
- Participants list to view the attendees of the meeting
- Chat functionality to send messages to other participants
- Whiteboard feature for collaborative drawing

## Technologies Used

- Node.js
- Express.js
- Socket.IO
- Passport.js (for authentication)
- Google OAuth 2.0 API
- Peer.js (for WebRTC)
- HTML, CSS, JavaScript

## Getting Started

### Prerequisites

- Node.js installed on your machine

### Installation

1. Clone the repository:

  using git clone <repository-url>

2. Install the dependencies:

  npm install

3. Set up Google OAuth credentials:

- Create a project in the Google Developers Console (https://console.developers.google.com/)
- Enable the Google OAuth 2.0 API and get the client ID and client secret
- Replace the placeholders for `GOOGLE_CLIENT_ID` and `GOOGLE_CLIENT_SECRET` in `server.js` with your actual credentials

### Usage

1. Start the server:
npm start

2. Open your web browser and navigate to `http://localhost:3000`

3. You will be redirected to the login page. Click on the "Sign in with Google" button to authenticate with your Google account.

4. After successful authentication, you will be redirected to the home page.

5. To start a new meeting, click on the "New Meeting" button.

6. To join an existing meeting, enter the Room ID provided by the host in the "Enter Room ID" input field and click on the "Join Room" button.

7. In the meeting room, you can mute/unmute your audio, stop/start your video, and use the chat feature to communicate with other participants.

8. To leave the meeting, click on the "Leave" button or close the browser tab.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

## Acknowledgements

- This project is inspired by Google Meet and built as a learning exercise.
- Special thanks to the creators and contributors of the open-source libraries and frameworks used in this project.

## Contact

For any inquiries or questions, please contact [Krishna Kireeti G V] at [krishnakireetigv@gmail.com].


