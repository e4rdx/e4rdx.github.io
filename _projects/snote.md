---
layout: project
name: sNote
description: Everything about the sNote note taking app
order: 2
---

<img src="/assets/snote_Main.jpg" alt="drawing" width="300"/>
<img src="/assets/snote_checklist.jpg" alt="drawing" width="300"/>

This is a note taking app for Android 10 and above.\\
With sNote you can create multiple notebooks. There are two types of notebooks: External and normal notebooks. Normal notebooks are saved in the data directory of the app. External notebooks can be anywhere in the storage, for example on a network drive to keep your notebook synced between devices. Normal notebooks have an export feature, so make sure you always have a backup!\\
Notebooks support different types of notes:
* Text - As simple as it sounds
* Checklist - I've spend a lot of time here
* Link - A single link that will be displayed with Android WebView
* Image from camera - Take an image with your camera and store it in your notebook

There's also a tag system that allows you to add tags to your notes(currently only checklists support this). Then you can filter your notes by tags.\\
In one of the next updates, tasks will be coming. To see planned features, checkout [the project on github](https://github.com/e4rdx/sNote/projects).

## Translations
The project supports currently the following languages:
* English
* German

## The .snote fileformat
... is same as .zip! It's just a renamed zip archive. It contains a file with all the notes and a compressed attachments folder. All attachments like images are in there, with a unique name. In the note file are all the notes, serialized with JSON.
Every note has name and type key. But the different types have some special keys only for the type, for example the checklist has the entrys key that stores all the entrys in a JSON array.

## Background
I started this project to have an app my voice assistant can interact with. It's also my first Android Studio project. I have already made some apps for Android with App-Inventor. So far, this is my biggest project, I've never produced that much code! I started this project with Java, but the I decided to learn Kotlin. Now I always make use of Kotlin for new classes and activities.

## Gallery
<img src="/assets/snote_SideMenu.jpg" alt="drawing" width="300"/>
<img src="/assets/snote_Tags.jpg" alt="drawing" width="300"/>