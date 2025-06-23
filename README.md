# REAL-TIME-COLLABORATION-TOOL

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: MOHAMMED YASIR

*INTERN ID*: CITSOD414

*DOMAIN*: SOFTWARE DEVELOPMENT

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

#DESCRIPTION

As part of my internship, I was assigned the task of developing a real-time collaborative tool for text editing, similar in concept to applications like Google Docs. The goal was to allow multiple users to edit the same document simultaneously, with all changes reflected instantly across all connected clients. This project required implementing a client-server architecture using WebSockets to ensure real-time, bidirectional communication between the server and users' browsers.

To accomplish this, I built the backend using Node.js with Express.js, and integrated Socket.IO to handle WebSocket communication. The frontend was created with HTML, CSS, and vanilla JavaScript, providing a simple and intuitive text editor interface within the browser. When a user types in the editor, their changes are broadcast to all other connected users using Socket.IO events, enabling real-time synchronization of the document across multiple tabs or devices.

The server listens for content-change events from any client and immediately emits the updated content to all other users using broadcast.emit. This ensures that when one user edits the document, all other clients receive and apply the change in real time. To avoid recursive updates or flickering, the client uses a flag (ignoreChange) to differentiate between user-generated input and externally received updates.

The client interface consists of a single shared <textarea> element styled for readability and responsiveness. It is embedded in a clean, minimal interface with a heading that clearly labels the application as a real-time collaborative editor. The setup also includes a basic server configuration that serves static files and listens on a specified port (port 3000).

This tool is ideal for live note-taking, collaborative writing, or educational platforms where synchronous editing is required. While the current implementation uses a shared document model, the architecture can be extended to support multiple rooms or sessions by assigning room IDs or unique session tokens.

During this project, I gained hands-on experience working with real-time web technologies, especially how WebSocket communication differs from traditional HTTP requests. I also improved my understanding of event-driven programming, frontend-backend interaction, and how to manage shared state across multiple clients in real-time scenarios. This project provided a practical foundation for building collaborative web applications and deepened my knowledge of building scalable and interactive systems.

The final deliverable included all source code, a working demo, and documentation on how to set up and test the application locally. It can be further enhanced by adding features like user presence tracking, chat integration, cursor sharing, access control, or even integrating a rich-text editor like CodeMirror or Quill.js for better code editing and formatting support. Overall, this task showcased my ability to design and implement a functional, multi-user collaborative tool using WebSocket-based communication.

#OUTPUT

![Image](https://github.com/user-attachments/assets/6aeea7f6-6602-4d89-8c50-e8821d103f34)

