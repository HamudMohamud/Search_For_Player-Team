## Team Selector JavaScript App

This is a simple JavaScript app that allows users to input their favorite team’s name and get a response basedon whether they’ve chosen “Chelsea” or “Liverpool”. Ifthe user enters “Chelsea” or “Liverpool”, the app will display a message appreciating their choice of an amazing team. Otherwise, the app will encourage them to pick a better team in the English Premier League.

## How to Use

1. Open the index.html file in a web browser.

2. In the web page, there’s an input field where you can type the name of your favorite team.

3. After typing the team name, press the “Enter” key.

4. If your favorite team is “Chelsea” or “Liverpool”, you will see a message saying you’ve picked an amazing team.

5. If your favorite team is neither “Chelsea” nor “Liverpool”, the app will display a message suggesting you pick a better team in the Premier League.

## Code Explanation

In this JavaScript code snippet, the main focus lies inusing conditional statements to examine whether the user’s input matches either “Chelsea” or “Liverpool”. If the provided input does not match either of these teams,the code will log a message encouraging the user to select a superior team within the Premier League. Conversely, if the input corresponds to “Chelsea” or “Liverpool”, the code will display an appreciative message.

## Code:

let teamName = "one";

if (teamName !== "Chelsea" && teamName !== "Liverpool") {
    console.log("You gotta pick a better team in the Premier League, Brodie.");
    } else {
        console.log("You picked an amazing team, my friend.");

## Code Explanation 


This code snippet initializes the teamName variable with the value “”. It then uses an if statement to determine if the teamName is neither “Chelsea” nor “Liverpool”. If this condition is met, the code logs an encouragement to select a more impressive team. On the contrary, if the teamName corresponds to either “Chelsea” or “Liverpool”, the code logs an appreciative message.	
