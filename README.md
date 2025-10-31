# Database Lookup

This repository hosts a split database of messages in the `data/` directory, along with an `index.html` page to look up messages by file number.

## Usage

- Open `index.html` in a browser (or deploy it to Netlify/GitHub Pages).
- Enter a file number between 1 and 103 and click "Lookup" to fetch and display the content from the corresponding file in `/data/`.

## Data Structure

- Database is divided into 103 files: `data/part1.txt`, ..., `data/part103.txt`.
- Each file contains a portion of the database in plain text format.