# Notes Web App

A simple, responsive web application for creating, editing, and deleting notes. Notes can include a title, text, and an optional image attachment. All notes are saved locally in the browser using `localStorage`, ensuring privacy and persistence across sessions.

## Features

- **Add Notes**: Enter a title, content, and optionally upload an image to create a note.
- **Edit Notes**: Update the note’s title, content, or image at any time.
- **Delete Notes**: Remove notes you no longer need.
- **Responsive Design**: Works well on both desktop and mobile devices.
- **Local Storage**: Notes are stored in your browser with no backend or account required.

## Usage

1. Open the app in your browser (simply open `index.html`).
2. Fill out the note form with a title and text. You may also choose an image to attach.
3. Click **Add Note** to save your note.
4. Your notes will appear below the form. Use the **Edit** or **Delete** buttons as needed.

## Technologies Used

- **HTML5** for structure and markup.
- **CSS3** for styling and responsive layout.
- **Vanilla JavaScript** for all app logic and DOM manipulation.  
- **localStorage** for client-side data persistence.

## Project Structure

- `index.html`: Contains all HTML, CSS, and JavaScript needed for the app (single-file application).

## How it Works

- All notes are created, edited, and deleted on the client side only.
- When you add or edit a note, it is saved to `localStorage`.
- Image attachments are encoded and stored as data URLs.
- On page load, previously saved notes are automatically loaded from storage.

## Screenshots

<!-- You can add screenshots by uploading image files and referencing them here. -->

## License

This project is open-source and free to use under the MIT License.

---

**Enjoy taking notes with your browser!**
