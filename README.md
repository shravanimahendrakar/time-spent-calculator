# Time Spent Calculator

A small static website that reads a "Time Spent" column from a screenshot or an Excel sheet and adds it up in hours and minutes.

Example: 1hr 20m, 20m, 3hr 33m, 40m gives 5 hr 53 m.

## How it works

- Excel files (.xlsx, .xls) are read with SheetJS. The page finds the "Time Spent" header and reads the cells below it.
- Images are read with Tesseract.js (OCR) in the browser, then each line is checked for a time like `1hr 20m`.
- Each entry is converted to minutes, summed, and shown as hours and minutes.
- Everything runs in the browser. No files are uploaded to a server.

## Try it

Live page: `https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/`

## Run locally

Download `index.html` and open it in a browser. No install needed.

## About me

Shravani Mahendrakar (@shravanimahendrakar)
