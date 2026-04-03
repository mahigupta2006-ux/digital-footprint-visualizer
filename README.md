# digital-footprint-visualizer

This is a simple web project I made to understand how much time we spend on different digital activities and how it affects our overall digital exposure.

The idea behind this project is that most people use apps daily but don’t really think about how much data or presence they are creating online. So I tried to build a small tool that gives a basic “privacy score” based on usage.

## Features
- User login (stored locally using browser storage)
- Input daily usage (social media, browsing, messaging, gaming)
- Calculates total screen time
- Gives a privacy/exposure score
- Shows a pie chart using Chart.js
- Stores weekly data and displays last 7 days
- Option to download saved data

## Technologies Used
- HTML
- CSS
- JavaScript
- Chart.js

## How it Works
The user enters the number of hours spent on different activities. Based on that, a simple formula is used to calculate a privacy score. Higher usage leads to lower score (more exposure).

The data is saved in localStorage so it stays even after refreshing the page.

## What I Learned
- How to take user input and process it
- DOM manipulation in JavaScript
- Using localStorage for saving data
- Integrating external libraries like Chart.js
- Basic UI design using CSS

## Limitations
- Data is not stored on a server (only browser storage)
- No real tracking (user has to enter data manually)
- Basic scoring logic

## Future Improvements
- Add backend (like Firebase)
- Track real screen time automatically
- Better UI and mobile responsiveness
- Smarter recommendations

## Live Project
https://digital-footprint-visualizer.netlify.app/

