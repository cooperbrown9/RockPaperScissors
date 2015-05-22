# RockPaperScissors
Rock Paper Scissors game. 

var win = "You beat the CPU!";
var loss = "The CPU beat you!";
var tie = "It's a tie! Go again!";
var rock = 0.33;
var paper = 0.66;
var scissors = 0.67;
var userChoiceC;
var cpu = Math.random();
var userChoice = prompt("Rock, paper or scissors?") {
    if (userChoice = "rock") {
        userChoiceC = rock;
        if (cpu < rock) {
            confirm(tie);
        } else if (cpu > scissors) {
            confirm(win);
        } else {
            confirm(loss);
        }
    } else if (userChoice = "paper") {
        userChoiceC = paper;
        if (cpu < rock) {
            confirm(win);
        } else if (cpu > scissors) {
            confirm(loss);
        } else {
            confirm(tie);

        }
    } else if (userChoice = "scissors") {
        userChoiceC = scissors;
        if (cpu < rock) {
            confirm(loss);
        } else if (cpu > scissors) {
            confirm(tie);
            userChoice();
        } else {
            confirm(win);
        }
    } else {
        confirm("Enter rock, paper or scissors.");
    }
}
