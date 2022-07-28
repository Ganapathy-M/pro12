const cars =["BMW", "Volvo", "Saab", "Benz"];
cars [2] = "Audi";
let car5 = cars.length;
console.log(car5);

let fruits = ["Banana", "Mango", "Orange", "Grapes", "Apple"];

console.log(fruits.toString());
console.log(fruits.join("/"));
console.log(fruits.splice(2,1,"Kiwi"));

console.log(fruits.slice(1,3));


let fru =  numbers.sort((a1, b2) => {
    return a1 - b2;
    });

    console.log(fru);

const cars = [
    {type:"Volvo", year:2016},
    {type:"Saab", year:2001},
    {type:"BMW", year:2010}
  ];
  let car = cars.sort((a,b) => {
    return a.year -b.year;
  });
  console.log(car);

let numbers = [234,5,547,78,12,758,2345,674];
let num = numbers.reduce((preval,curval) => {
    return preval + curval;
});
console.log(num);