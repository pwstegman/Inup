Inup
====

Infinite backup (yes, really)

1. Connect to Google Drive
2. Upload file
3. File is base64 encoded, then split into 1 Mb pieces
4. A folder is made in the specified folder id in the code (folder in a folder)
5. Pieces are uploaded to this folder in a folder
6. Download button reassembles the pieces and decodes them
