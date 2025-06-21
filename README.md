# ALX_Simple_Quiz

A minimal interactive quiz built with HTML, CSS, and JavaScript.

## Overview

This project demonstrates a basic quiz where users select an answer and receive instant feedback on whether their choice is correct or incorrect.

The quiz asks: **What is 2 + 2?**  
Users select from multiple radio button options and click **Submit Answer** to check their response.

## Features

- Simple user interface with clear question and answer options  
- Real-time validation of user’s selected answer  
- Immediate feedback displayed below the button  
- Prevents submission without selecting an answer

## Technologies Used

- HTML5  
- CSS3  
- Vanilla JavaScript

## How to Use

1. Open in a web browser.  
2. Select one of the answer options.  
3. Click the **Submit Answer** button.  
4. See feedback below the button indicating if your answer was correct or incorrect.

## Code Highlights

- The `checkAnswer` function retrieves the selected radio button using `document.querySelector('input[name="quiz"]:checked')`.  
- The user’s answer is compared to the correct answer (`"4"`).  
- Feedback is dynamically updated based on the user's selection.  
- An event listener on the submit button triggers the `checkAnswer` function without reloading the page.
