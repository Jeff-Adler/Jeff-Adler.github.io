---
title: 'Trivia Attack!'
subtitle: 'High-octane trivia app to pass the time'
date: 2020-08-25 00:00:00
description: This app generates timed and non-timed quizzes from the Open Trivia Api, and logs scores to a leaderboard.
featured_image: '/images/demo/trivia-friends.jpg'
---

![](/images/demo/trivia_banner.jpg)

<strong>Keywords:</strong> Javascript, Ruby on Rails, HTML, CSS, Quiz, Trivia

<strong>Description:</strong> This app allows users to choose from a dynamically-generated list of trivia categories, a difficulty level, and a quiz type (regular vs. timed). The backend takes the selected category and difficulty to call the <a href= "https://opentdb.com/">Open Trivia Database</a> and receive a list of trivia question in a JSON. The frontend then renders the JSON into a set of multiple-choice questions. If the user chose a timed quiz, the user is shown questions in succession until the timer runs out. Given the user's answers, they receive a score, and the score is saved to the database, to be shown on the leaderboard. The app has a Javascript frontend, Rails backend, and a minimalist CSS style.

Github:
<a href= "https://github.com/Jeff-Adler/mod-3-project-backend">Backend</a>
<a href= "https://github.com/Jeff-Adler/mod-3-project-trivia-app">Frontend</a>