# Analog Clock ⏰

A simple analog clock built using HTML, CSS, and JavaScript that displays real-time hours, minutes, and seconds with smooth rotation.

## 🚀 Live Demo
https://analog-clockbyjs.netlify.app/

## 📸 Screenshot
<img width="1912" height="858" alt="image" src="https://github.com/user-attachments/assets/8301b4a1-49e4-4601-9f5f-8e43b9a0b647" />


## 📌 Features
- Real-time clock updates every second
- Smooth rotation of hour, minute, and second hands
- Clean and minimal UI
- Fully built with vanilla JavaScript (no frameworks)

## 🛠️ Technologies Used
- HTML
- CSS
- JavaScript

## 📂 Project Structure
project-folder/
│── index.html
│── style.css
│── script.js
│── clock.png
│── clock_sound.wav
│── Favicon.png
│── README.md

## ⚙️ How It Works
- JavaScript uses the `Date` object to get current time
- Seconds, minutes, and hours are converted into degrees
- CSS `transform: rotate()` is used to move clock hands
- `setInterval()` updates the clock every second

## 🧠 What I Learned
- Working with JavaScript Date object
- Converting time units into angles
- Using CSS transforms for animation
- DOM manipulation and real-time updates

## ⚠️ Problems & Challenges Faced
- Calculating correct angles for hour, minute, and second hands required understanding of time-to-degree conversion.
- Handling smooth movement of clock hands without jittering.
- Synchronizing all hands accurately with real system time.
- Managing continuous updates using `setInterval()` without performance issues.
- Ensuring proper rotation origin so that clock hands rotate from the center.
- Fixing alignment and positioning issues in CSS for a clean circular layout.

## ⭐ If you like this project
Give it a star on GitHub!

## 🙌 Author
Krishna
GitHub: https://github.com/yourusername
