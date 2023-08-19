# Pdf_Merger

The website would help in merging 2 or more pdf files.

### Site URL
```bash
https://meghajain0799.github.io/Pdf_Merger/templates/
```

## Installation

To deploy this project run

```bash
  npm install
```
Runs the app in the development mode.

Open http://localhost:3000 to view it in your browser.

## Description

1. Upload files to be merged and click on submit.
2. The files will be merged in the order of file upload.
Initial limit to merge pdf files is set to 2.

The limit can be modified by changing the number in below function present in server.js file.


### Code

```bash
  app.post('/merge', upload.array('pdfs', 2), async function (req, res, next)
```
## Features

- Web App can merge any no. of pdfs
