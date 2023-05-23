// Initialize variables
/*var sum = 0;
var numberOfInputs = 10;

// Loop to take inputs from the user
for (var i = 1; i <= numberOfInputs; i++) {
  var input = parseFloat(prompt("Enter number " + i + ":"));
  
}

// Display the average
console.log("The average of the 10 numbers is: " + average); */
/*let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
console.log(i) */
/*
function getEvenSum(max = 10) {
    let sum = 0;
  
    for (let i = 2; i <= max; i += 2) {
      sum += i;
    }
  
    return sum;
  }
  console.log(getEvenSum())



  function getOddSum(max = 10) {
    let sum = 0;
  
    for (let i = 1; i <= max; i += 2) {
      sum += i;
    }
  
    return sum;
  }
  console.log(getOddSum())

 
  function getProductOfDigits(num) {
    let product = 1;
    const digits = String(num).split('');
  
    for (let digit of digits) {
      product *= parseInt(digit);
    }
  
    return product;
  } */
  function getOutput(name) {
    if (name === 'Arya') return 'You are arya';
    if (name === 'John') return 'You are john';
    return 'Who are you';
  }
  
  getOutput('Arya'); // what will be the output
  getOutput('John'); // what will be the output
  getOutput(); // what will be the output


  yes a function have a multiple return examples are folkowing

  function checkNumber(num) {
    if (num > 0) {
      return "Positive";
    } else if (num < 0) {
      return "Negative";
    } else {
      return "Zero";
    }
  }
  
