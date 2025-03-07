#### Technologies:

- Google OAuth 2.0 API for user authentication.
- Google Picker API for file uploads and reading data in JSON format.
- A WebSocket for real-time communication between users.

#### Requirements:

1. Google Authentication Flow

   - Create an endpoint that initiates the Google Auth flow.
   - Implement a callback URL where Google sends the authentication data.
   - Simply return the data received from Google.

2. Google Drive Integration

   - Develop an endpoint that allows users to connect their Google Drive.
   - Implement functionality for users to upload files to their Google Drive.
   - Provide an option to fetch and download files locally from Google Drive.

3. WebSocket for User Chat
   - Implement a WebSocket that enables real-time chat between two pre-configured users.
   - Ensure that messages are sent and received in real-time.

#### Guidelines:

- Provide a Postman collection that includes all the API endpoints you have created.
- Ensure that the Postman collection is well-documented, detailing the request and response formats.
