# HelloWorld
First Repository

Hello! My name is Christie and I live in Rhode Island.


// assignment 2
//alert("HelloWorld");
//console.log("Changing the output");

//let Favoritefruit = "apples";
//console.log("your favorite fruit is " + Favoritefruit);

//let favoritecolor = prompt("What is your favorite color?");
//console.log("To confirm your favorite color is " + favoritecolor);

//let UserName = prompt("What is your name?");
//console.log("Hello, welcome " + UserName);

//assignment3

//let Favoritefood = prompt("What is your favorite food?")
//if (Favoritefood === "pizza") {
//  console.log("Duck loves pizza too!")
//}else{
//  console.log("Ok")
//}

//Coin Flip assignmentl

//let play = prompt("Heads or Tails?")

//let randomNumber = Math.random()
//let result = ""
//if(randomNumber < 0.5) {
//  result = "Heads"
//} else {
//   result = "Tails"
//}
//console.log("The coin shows" + result)
//if(play === result) {
//console.log("You won!")
//} else{
// console.log("you lost!")
//}

// Assignment 4

//function greet(name) {
//  return "hello " + name
//}

//console.log(greet("Christie"))
//console.log(greet("Jennifer"))
//console.log(greet("Joeseph"))

//function area(width, height){
//  return width * height
//}
//console.log(area(3,4))
//console.log(area(5,6))

function FlipCoin() {
  let randomNum = Math.random();
  if (randomNum < 0.5) {
    return "heads";
  } else {
    return "tails";
  }
}

function callFlip(userGuess) {
  let flipResult = FlipCoin();
  if (userGuess === flipResult) {
    return "True";
  } else {
    return "False";
  }
}

//let gameresult = FlipCoin()
//console.log("The Flip was "+ gameresult)

let userGuess = prompt("Heads or Tails?");
console.log("You Guessed: " + userGuess);
if (callFlip(userGuess)) {
  console.log("You won!)");
} else {
  console.log("You Lost.");
}
