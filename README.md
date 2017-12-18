# Notebook

To run the app, run this command:  
```
npm install  
npm run dev  
```
Wait for the webpack to fully start if nothing shows up. Refresh once completed and you should see results. 

# Overview
Notebook is a rich-text editing desktop application that supports collaboration. Users can create, view, edit and shrae their documents. Currently, popular desktop text editors such as Evernote, iNotes do not provide real-time, collaborative editing and are a big memory killer. Those that do support real-time, multi-user editing are web applications and too can quickly slow down your computer. 

## Architecture Overview
Notebook uses React to manage document state enabling users to view collaborators' edits and view edit history. We used MongoDB to support document persistence and user registration and credentials. Server uses NodeJS and Express and socket.io for multi-user support and real-time editing.

## Features
* Rich-text formatting
  * Bold
  * Italics
  * Underline
  * Font color and size
  * Text alignment
  * Bullet and Numbered lists
* Persistent Login
* Document-specific URLs for sharing and quick access
* Multi-user support. Users can view others' edits in real time.
  * Different colors assigned to each user to track where they are on the page
  * Collaborators see text selections and cursors in users' assigned colors
* Document version histories
  * Users can revert back to old document states
* Secure documents with passwords
* Auto-saving



![](https://cl.ly/2d211U3z1q2U/Screen%20Recording%202017-08-01%20at%2008.44%20PM.gif)

![](https://cl.ly/252B331P0g2U/Screen%20Recording%202017-08-01%20at%2008.46%20PM.gif)

![](https://cl.ly/3M363x3X450Y/Screen%20Recording%202017-08-01%20at%2009.01%20PM.gif)
