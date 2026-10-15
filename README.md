* función 1

function squareSum(numbers){
  let sum = 0;
  for (let num of numbers) {
    sum += num * num;
  }
  return sum;
}

* función 2 

function greet() {
  const dictionary = new Proxy({}, {
    get: (_, prop) => prop
  });

  return `${dictionary.hello} ${dictionary.world}!`;
} 

* función 3 

function doubleInteger(i) {
  
  return i+i;
}
