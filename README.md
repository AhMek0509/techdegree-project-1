# Techdegree Project 1
 /******************************************
Treehouse FSJS Techdegree:
project 1 - A Random Quote Generator
******************************************/

// For assistance: 
  // Check the "Project Resources" section of the project instructions
  // Reach out in your Slack community - https://treehouse-fsjs-102.slack.com/app_redirect?channel=chit-chat

/*** 
 * `quotes` array 
***/
const quotes = [
  {quote: 'People throw rocks at things that shine', 
   source:'Taylor Swift',
   citation: 'Ours',
   year:'2010'
  },
  {quote: 'When you commit to transforming your life you commit to getting very uncomfortable over and over and over again.',
   source: 'Jen Sincero'
  },
  {quote:'Complexity is the enemy of execution',
   source:'Tony Robbins'
  },
  {quote:'You do not find the happy life. You make it.',
   source:'Camilla Eyring Kimball'
  },
  {quote: 'Stay close to anything that makes you glad you are alive.',
   source: 'Hafez'
  }
];

console.log(quotes);

/***
 * `getRandomQuote` function
***/

function getRandomQuote () {
  const randomNumber = Math.floor(Math.random()*5);
  return quotes[randomNumber];
}

/***
 * `printQuote` function
***/
function printQuote (){
  const randomQuote = getRandomQuote();
  const quoteProperties = <p class="quote"> randomQuote.quote </p> <p class="source"> randomQuote.source
  if (quote.citation){
  <span class="citation">randomQuote.citation</span>
  if (quote.year)
  <span class="year">randomQuote.year</span></p>
  } 
  </p>
  }


/***
 * click event listener for the print quote button
 * DO NOT CHANGE THE CODE BELOW!!
***/

document.getElementById('load-quote').addEventListener("click", printQuote, false);
