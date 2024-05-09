# Video App

This is a video app that allows users to upload and search for videos.

## Setup

1. Install Node.js and npm.
2. Install PostgreSQL and create a database.
3. Update the database configuration in `backend/src/config/database.js`.
4. Navigate to the `frontend` directory.
5. Run `npm install` to install the frontend dependencies.
6. Navigate to the `backend` directory.
7. Run `npm install` to install the backend dependencies.

## Usage

1. Start the backend server by running `npm start` in the `backend` directory.
2. Start the frontend development server by running `npm start` in the `frontend` directory.
3. Access the application in your web browser at `http://localhost:3000`.

## Project Structure

- frontend/ (directory)
  - src/ (directory)
    - components/ (directory)
      - VideoUploadForm.js (file)
    - pages/ (directory)
      - VideoSearchPage.js (file)
    - services/ (directory)
      - api.js (file)
  - public/ (directory)
    - index.html (file)
  - package.json (file)
  - README.md (file)
- backend/ (directory)
  - src/ (directory)
    - controllers/ (directory)
      - VideoController.js (file)
    - routes/ (directory)
      - videoRoutes.js (file)
    - models/ (directory)
      - Video.js (file)
    - config/ (directory)
      - database.js (file)
    - app.js (file)
  - package.json (file)
  - README.md (file)
- database/ (directory)
  - schema.sql (file)
- README.md (file)
- package.json (file)
