Spotify Clone

A simple Spotify Clone web application built using HTML, CSS, and JavaScript.
This project demonstrates the core functionality of a music player, including playing songs, pausing, switching tracks, and displaying song information with cover images.

Features

→ Play and pause music
→ Next and previous track controls
→ Song progress bar
→ Display song name and cover image
→ Clean and responsive UI
→ Lightweight and beginner-friendly project

Technologies Used

→ HTML5
→ CSS3
→ JavaScript (Vanilla JS)

Project Structure
Spotify-Clone/
│
├── index.html
├── style.css
├── script.js
│
├── songs/
│   ├── 1.mp3
│   ├── 2.mp3
│   ├── 3.mp3
│   └── ...
│
├── cover/
│   ├── 1.jpg
│   ├── 2.jpg
│   ├── 3.jpg
│   └── ...
│
└── README.md

Songs & Cover Image Setup (Important)

You must create two folders manually in the project root:

1. songs Folder

→ This folder acts as the database for audio files
→ Store all your .mp3 files here
→ Name the files as:

1.mp3, 2.mp3, 3.mp3, ...

2. cover Folder

→ This folder acts as the database for song cover images
→ Store all song cover images here
→ Name the files as:

1.jpg, 2.jpg, 3.jpg, ...

⚠️ Naming Rule (Very Important)

✔️ Song name and cover image number must match

Example:
→ 1.mp3 → 1.jpg
→ 2.mp3 → 2.jpg

If the numbering does not match, the cover image will not display correctly.

▶️ How to Run the Project

Clone the repository:

git clone https://github.com/akki040/Spotify-Clone.git


Open the project folder:

cd Spotify-Clone


Open index.html in your browser
(No server required)

📸 Preview

The UI is inspired by Spotify and focuses on simplicity and clarity while learning JavaScript-based media handling.
