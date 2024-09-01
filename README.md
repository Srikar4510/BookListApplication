# Booklist Application

This is a simple Booklist application built with React.js. The application allows users to add, edit, and delete books from a list. It uses a JSON server to simulate a backend API for storing books.

## Table of Contents

- [Demo](#demo)
- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [License](#license)

## Demo

You can see the demo of the application stackblitz.com/edit/vitejs-vite-ciugny. 

## Features

- **Add a Book**: Users can add new books to the list.
- **Edit a Book**: Users can edit the title of an existing book.
- **Delete a Book**: Users can delete a book from the list.
- **Persistent Storage**: The book data is stored in a JSON server, simulating a real backend API.

## Getting Started

To get a local copy up and running, follow these steps.

### Prerequisites

- Node.js installed on your machine.
- JSON Server for the fake REST API.

### Installation

1. Clone the repository

   ```bash
   git clone https://github.com/Srikar4510/BookListApplication.git
2. Install NPM packages

```bash
   npm install
```
3. Install JSON Server globally (if not already installed)

```bash

npm install -g json-server
```
### Running the Application
Start the JSON Server:

```bash
npm run server
```
Start the React application:

```bash
npm start
```

Open ``` http://localhost:5173 ``` to view the app in the browser.

### Project Structure

- components: Contains React components like BookCreate, BookEdit, BookList, and BookShow.
- context: Contains the context file for managing the state and actions related to books.
- ooks: Contains custom hooks like useBooksContext for accessing context values.
- db.json: JSON file used by the JSON Server to simulate a backend database.


### Dependencies
React.js
Axios
JSON Server
### License
This project is licensed under the MIT License - see the LICENSE file for details.
