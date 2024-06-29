# Notes-App
## Overview
The Notes-App is a simple note-taking application built using Svelte. It allows users to create, edit, and save notes. The notes are stored in the local storage of the browser, ensuring that the data persists even after refreshing the page.

## Features
Create and manage multiple notes.
Edit the title and content of each note.
Save notes to local storage.
Simple and clean user interface.

## Installation
To get started with the Notes-App, follow these steps:
1. Clone the repository
2. Install the dependencies
3. Run the application
4. Open your browser and navigate to http://localhost:5000.

## Usage
Add a New Note: Click the "+ Add Page" button to create a new note.
Select a Note: Click on a note title from the sidebar to view and edit it.
Edit Note Title: Click on the note title and start typing to edit it.
Edit Note Content: Write your note content in the text area provided.
Save Note: Click the "Save" button to save the current note to local storage.

## Explanation
State Management: The component manages the state of pages, currentPageIndex, title, and note.
Lifecycle Hook: onMount is used to load the pages and notes from local storage when the component is first mounted.

## Functions:
saveNote: Saves the current note to local storage.
addPage: Adds a new note page.
selectPage: Selects a specific note page based on the index.

## Styling
Light Gray Background: .bg-light-gray class for the sidebar.
Dark Gray Background: .bg-dark-gray class for the active note.
