# Toy Tales

A React app for managing Andy's toy collection, connected to a json-server backend with full CRUD functionality.

![Toy Tales screenshot](docs/screenshot.png)

## Description
Toy Tales connects an existing React front end to a RESTful API. Users can view all toys, add new ones, like their favorites, and donate toys they no longer want.

## Features
- View all toys on page load (GET)
- Add a new toy using the form (POST)
- Increase a toy's likes (PATCH)
- Donate a toy to remove it (DELETE)

## Installation
1. Clone the repository: `git clone https://github.com/simiyusean99-web/react-hooks-toy-tales-vite.git`
2. Install dependencies: `npm install`
3. Start the backend: `npm run server`
4. In another terminal, start the app: `npm run dev`

## Usage
Open the local URL shown by Vite. Click **Add a Toy** to show the form, **Like** to add a like, and **Donate to GoodWill** to remove a toy.

## Testing
Run the test suite with `npm run test`.

## Technologies
React, Vite, json-server, Vitest, React Testing Library

## Author
Sean Simiyu