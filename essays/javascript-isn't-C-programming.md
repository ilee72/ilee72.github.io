---
layout: essay
type: essay
title: Javascript isn't C programming!
date: 2019-01-17
labels:
  - Technical Essay
  - Javascript
  - Software Engineering
---
## Introduction
Through my electrical engineering pathway for the Unversity of Hawaii at Manoa, I had to learn C and C++ for my cirriculum. These languages were very harsh about syntax. Although harsh, these languages were the old and powerful languages that many before us coded in. They were primitive, but effective in terms of laying out code that was able to be used.

## Javascript is so much different 
First and foremost, the Javascript and C language have familiar feelings for syntax, but there are major differences. Javascript has been very difficult to understand in terms of the logic compared to the C language. The addition of strings and small differences in key syntax have been the most difficult to adjust to. These differences have made it very difficult for me in terms of how I should approach a problem. More importantly, the combination of having to understand new syntax rules, new features like ".length" or "math.pow" open up more possibilities of approaching a problem. Having so many different ways to do something with Javascript is good and bad. It's great to be able to approach and solve a problem with more tools, but it also increases the complexity and difficulty for the user to memorize, understand, and apply those tools in a way to solve the problem. With the simple C language, I understood the limits and rules of my language so that I could solve problems based on my limits and rules. 
Javascript opens up so many more possibilities that allows for creativity to solve problems, albeit, difficult for me to adjust to.

## Javascript feels the superior of C and C++
I can see the advantages of Javascript to be very liberating. Having objects, functions, and certain tools already to organize or premade really allow for quick, robust, and creative programming to occur. With my experience with C, it has been very limiting in terms of what you could do. It felt primitive and limiting having to be controlled by rules that require hours of thinking and practice to understand limits to your way of thinking. Javascript, in my opinion, is so much more useful and powerful as a programming language than C. It is very forgiving for syntax compared to C as well as how you call out certain words, which makes this very friendly towards people new to programming. It also allows for mistakes and errors to be located faster compared to C, which you would literally spend hours skimming through code to find what was wrong with your syntax. Javascript is very powerful, and it is very similar to Python. Python and Javascript seem more user friendly and forgiving of errors.

## New method of learning and testing
For this class, ICS 314, the WODs have been the source of most of my stress. Having to be timed with problems have been very tough for the way I code. From my experiences, I've always had plenty of time to look at my problem, understand my parameters and what my output should be. I could use the internet and take hours to complete any assignment I was given for EE 160 for C programming. With this new method of teaching, I was stressing out on how I should be able to approach and problem and remembering syntax and tools for Javascript. 

## Review of the WOD
Looking at my inability to work well under stress, I went to the WOD with Brandon, the Teaching Assistant for ICS 314. There I was able to get valuable insight, however, my time was cut short due to other classes at the time. Looking at the week for javascript, I was thrown right into it with little preparation due to my scheduling and this experience will warrant my reevaulation on how to manage my time for future modules and tasks. Looking at the WOD, the problem was to count the vowels in lowercase of "a, e, i, o, or u" within a string. To do this we were given parameters and a function name. My attempt started with switch statements but ultimately failed as I argued with myself on how to create a loop with either a while or for loop. In the end, I was not able to complete this WOD. No excuses, but I felt that time was my enemy in this assignment. I hope to bounce back and attempt to get better at Javascript.
## Difference of code for vowelCount
```
function countVowels(string){
let count = 0;
for(let i = 0; i < string.length; i++){
	if(string[i] === 'a' || string[i] === 'e' || string[i] === 'i' || string[i] === 'o' || string [i] ==='u'){
  count++;
  }
  return count;
}
}

console.log(countVowels("i am in ics 314"));   // Prints 4 to the console
console.log(countVowels("I am in ICS 314"));   // Prints 2 to the console
console.log(countVowels("bcdfgh"));            // Prints 0 to the console
```
Above is the one of the correct answers to work the vowelCount WOD

```
function countVowels(string){

let i = 0;

switch(string){
    case "a":
  i++;
  break;
  case "e":
  i++;
  break;
  case "i":
  i++;
  break;
  case "o":
  i++;
  break;
  case "u":
  i++;
  break;
  default:
  return i
    }

  print (i);
}

console.log(countVowels("i am in ics 314"));   // Prints 4 to the console
console.log(countVowels("I am in ICS 314"));   // Prints 2 to the console
console.log(countVowels("bcdfgh"));            // Prints 0 to the console
```
Above is the code I attempted. I wasn't able to get a loop going to go through every single individual character in the string.

## Thoughts on Improvement
Overall, I attempted the problem for the WOD. It was disheartening as the time went out as I tried to rack my brain to find a solution to using a way to check every letter of the string. However, looking at the answer, I am now much more focused and "traumatized" on learning Javascript so I don't make the same mistake of freezing and not knowing what to do. I hopefully will do better next time.
