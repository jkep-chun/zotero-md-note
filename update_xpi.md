Run the following in terminal to update `zoter-md-note.xpi`:
```
Compress-Archive -Path .\manifest.json, .\bootstrap.js, .\zotero-md-note.js -DestinationPath .\zotero-md-note.zip -Force
Move-Item .\zotero-md-note.zip .\zotero-md-note.xpi -Force
```