# Dispatch Strip Board

A lightweight browser-based dispatch board for tracking train progress in Railroader

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

- `README.md` — project description
- `Dispatch_Strip_Board_1.0.html` — main application file

## Installation / Setup

This project is a static HTML app, so there is no package installation required.

1. Download the project,
2. Open the folder containing the project files.
3. Double-click `Dispatch_Strip_Board_1.0.html`.
4. The board will open in your default web browser.

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
