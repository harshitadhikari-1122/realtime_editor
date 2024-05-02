# Real-time Code Editor
- This project is a real-time code editor built using React, Node.js, and WebSockets.

## Features
- Real-time Editing: Multiple users can edit the same piece of code simultaneously, with changes being reflected in real time.
- Syntax Highlighting: Code is displayed with syntax highlighting for a better editing experience.
- Collaboration: Users can collaborate on coding tasks, making it ideal for pair programming or team projects.
- Code Sharing: Ability to share the code editor link with others for collaborative editing.
  
## Technologies Used
- Frontend: React
- Backend: Node.js
- WebSockets: For real-time communication
- CodeMirror: For the code editor component
  
## How to Run
- Clone the repository: git clone https://github.com/harshitadhikari-1122/realtime_editor.git
#### Set up the backend:
- Navigate to the server.js file.
- Install dependencies: npm install
- Start the Node.js server: npm start
#### Set up the frontend:
- Navigate to the src folder.
- Install dependencies: npm install
- Start the React development server: npm start
- Access the application at http://localhost:3000 in your web browser.

## Configuration
- You can configure the WebSocket server URL in the frontend code (src/socket.js) if needed.
  
## Future Enhancements
- Add support for different programming languages with language-specific syntax highlighting.
- Implement user authentication and permissions for collaborative editing.
  
## Contributing
- Contributions are welcome! Feel free to fork the repository and submit pull requests.
