# Vision-AI-Chatbot
This is a Chatbot Web Application that allows the users to send messages(queries) and receive AI-generated responses. The chatbot even supports the file uploads and dynamically adjusts the chat interface.

Features:
Send and receive text messages
File upload support (images and other file types)
Dynamic chat interface
API integration for chatbot responses
User-friendly UI with smooth scrolling and animations
Keyboard and button support for message sending

Technologies Used
HTML, CSS, JavaScript (Frontend)
Fetch API for API requests
FileReader API for handling file uploads

How It Works
The user enters a message and clicks the send button (or presses Enter on desktop).
The message is displayed in the chat window.
The chatbot avatar appears with a loading animation.
A request is sent to the API to fetch a response.
The response is displayed in the chat window.

File Upload Handling
Users can upload a file by clicking the file upload button.
The file is read using FileReader and converted to Base64 format.
The uploaded file is displayed in the chat along with the message.
The chatbot processes the uploaded file if supported.

Future Enhancements
Improve UI with additional animations
Support voice input for messages
Enhance file type support for better processing
Improve API response handling for more natural conversations
