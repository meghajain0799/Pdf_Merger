# Pdf_Merger
The website would help in merging 2 or more pdf files.
Upload files to be merged and click on submit. The files will be merged in the order of file upload.
Initial limit to merge pdf files is set to 2.
The limit can be modified by changing the number in below function present in server.js file.
"app.post('/merge', upload.array('pdfs', 2), async function (req, res, next)"
