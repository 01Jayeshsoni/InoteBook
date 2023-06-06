# iNoteBook

iNoteBook is a web application that allows users to create and manage their notes online. It provides a user-friendly interface for creating, editing, and organizing notes. The frontend of the application is built using React.js, while the backend is developed using Node.js.

## Features

- **User Registration and Authentication**: Users can create an account and securely authenticate themselves to access their notes.
- **Create and Edit Notes**: Users can create new notes, edit existing notes, and add relevant details such as title, description, and tags.
- **Categorize and Organize Notes**: Users can categorize their notes by assigning tags and organize them based on different categories or subjects.
- **Search Functionality**: Users can easily search for specific notes by title, description, or tags.
- **Rich Text Editing**: The application provides a rich text editor to format and style notes with options for bold, italics, bullet points, etc.
- **Collaboration**: Users can share notes with other registered users, allowing for collaboration and teamwork.
- **Reminders and Notifications**: Users can set reminders for important notes and receive notifications when a reminder is due.
- **Responsive Design**: The application is designed to be responsive, ensuring a seamless user experience across different devices and screen sizes.

## Installation and Setup

### Prerequisites

- Node.js and npm (Node Package Manager) should be installed on your machine.

### Frontend Setup

1. Clone the repository:

   ```shell
   git clone https://github.com/01Jayeshsoni/InoteBook.git
   ```

2. Navigate to the frontend directory:

   ```shell
   cd InoteBook/frontend
   ```

3. Install the dependencies:

   ```shell
   npm install
   ```

4. Start the frontend development server:

   ```shell
   npm start
   ```

   This will start the React development server, and the frontend application will be accessible at `http://localhost:3000`.

### Backend Setup

1. Navigate to the backend directory:

   ```shell
   cd InoteBook/backend
   ```

2. Install the dependencies:

   ```shell
   npm install
   ```

3. Set up the environment variables:
   - Create a `.env` file in the backend directory.
   - Add the following environment variables to the `.env` file:
     - `MONGODB_URI`: MongoDB connection URI.
     - `JWT_SECRET`: Secret key for JWT authentication.

4. Start the backend server:

   ```shell
   npm start
   ```

   This will start the backend server, and it will be accessible at `http://localhost:5000`.

## Contributing

Contributions to iNoteBook are welcome! If you find any bugs, have suggestions for improvements, or would like to contribute new features, please feel free to submit an issue or create a pull request.

## License

iNoteBook is open source and distributed under the [MIT License](https://opensource.org/licenses/MIT).

## Contact

If you have any questions or inquiries, please contact [your-email@example.com](mailto:your-email@example.com).

## Acknowledgements

- [React](https://reactjs.org/)
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/)
