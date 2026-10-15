funcion 1 

function squareSum(numbers){
  let sum = 0;
  for (let num of numbers) {
    sum += num * num;
  }
  return sum;
}


funcion 2 

function greet() {
  const dictionary = new Proxy({}, {
    get: (_, prop) => prop
  });

  return `${dictionary.hello} ${dictionary.world}!`;
} 
