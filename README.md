# Dispatch Strip Board

A lightweight browser-based dispatch board for tracking train/dispatch strips across multiple columns.

## Features

- Create, edit, and delete dispatch strips
- Organize work by custom board columns
- Drag strips between columns
- Reorder strips within a column
- Drag columns to reorder the board layout
- Import and export strip data as JSON
- Persistent local storage so your board remains saved in the browser
- Support for strip types such as Local, Passenger, Fast Freight, and Switcher
- Notes field with normal text entry and readable formatting

## Project Files

- `Flight_Strip_Board template Library.html` — main application file
- `Dispatch_Strip_Board_1.0.html` — alternate board version
- `template-library/` — related template assets

## Installation / Setup

This project is a static HTML app, so there is no package installation required.

### Option 1: Open directly in a browser

1. Open the folder containing the project files.
2. Double-click `Flight_Strip_Board template Library.html`.
3. The board will open in your default web browser.

### Option 2: Run a local web server

If you prefer to serve it locally:

1. Open a terminal in the project folder.
2. Run one of the following commands:

   Windows PowerShell:
   ```powershell
   py -m http.server 8000
   ```

   Or:
   ```powershell
   python -m http.server 8000
   ```

3. Open:
   ```text
   http://localhost:8000/
   ```
4. Select the HTML file in the browser to load the app.

## Usage

- Click `+ Dispatch Strip` to add a new strip.
- Click `+ Column` to create a new board column.
- Drag strips between columns or reorder them inside a column.
- Use the controls on each strip to edit, move, or delete it.
- Use `Import` or `Import Strip` to load saved board data.
- Use `Export` to save board data to JSON.

## Notes

- Data is saved in the browser using `localStorage`.
- If you clear browser storage, the saved board data will be removed.
