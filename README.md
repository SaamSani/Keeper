# Keeper App

Keeper App is a simple React-based note-keeping application inspired by Google Keep. It allows users to create, view, and delete notes dynamically. This project is part of learning React concepts such as components, state management, and props.

## Features

- **Dynamic Notes**: Add, view, and delete notes instantly.
- **Modular Design**: Includes reusable React components like `Header`, `Footer`, `Note`, and `CreateArea`.
- **Responsive Styling**: Clean and responsive CSS for an enhanced user experience.

## Project Structure

```
src/
├── components/
│   ├── App.jsx          // Main component managing application state
│   ├── Header.jsx       // Renders the application header
│   ├── Footer.jsx       // Displays footer with the current year
│   ├── Note.jsx         // Represents an individual note
│   ├── CreateArea.jsx   // Input form for creating new notes
├── index.js             // Renders the App component
public/
├── styles.css           // Contains styles for the application
index.html               // Main HTML file
package.json             // Project configuration
```

## Prerequisites

- **Node.js**: Make sure you have Node.js installed.
- **React**: This project uses React version `16.8.6`.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/keeper-app.git
   cd keeper-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open your browser and visit `http://localhost:3000` to view the app.

## Usage

- Use the input fields to create a new note by providing a title and content.
- Click the "Add" button to save the note.
- Click the "DELETE" button on any note to remove it.

## Built With

- [React](https://reactjs.org/) - Frontend JavaScript library
- [React DOM](https://reactjs.org/docs/react-dom.html) - DOM bindings for React
- [React Scripts](https://www.npmjs.com/package/react-scripts) - Configuration and scripts for Create React App

---

Feel free to contribute to this project by submitting issues or pull requests!
