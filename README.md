# solved-tasks

```javascript



//Breaking chocolate problem
function breakChocolate(n,m) {
 let numberOfBreaks = n * m -1;
 if (numberOfBreaks <= 0){return 0}
  return numberOfBreaks;
}
//Divide and Conquer
function divCon(x){
 sumInt = 0;
 sumStr = 0;
for (let i=0;i<x.length;i++){
 if (typeof x[i] == "string"){
  sumStr = sumStr + Number(x[i])} else sumInt = sumInt +x[i]
}
return sumInt-sumStr;
}
//Sort and Star
function twoSort(s) {
  s.sort();
  let x = s.slice(0,1);
  x = x.toString();
  let i=0;
  let y = x[i++];
  while(i<=x.length-1){
    y =y+'***' + x[i];
    i++;
  }
 return y;
}
//Count the Monkeys!
function monkeyCount(n) {
  let countArr=[];

  let i = 0;
  while (i<=n-1){
   countArr[i]= i;
  countArr[i] =countArr[i]+1;
   i++;
  }
  return countArr
}
//The Wide-Mouthed frog!
function mouthSize(animal) {
  if( animal == "ALLIGATOR"|| animal == "alligator"){
  return "small"} else return "wide";
}
//Basic Mathematical Operations
function basicOp(operation, value1, value2)
{
  switch(operation) {
    case "+":
      return value1 + value2;
      break;
    case "-":
      return value1 - value2;
      break;
    case "*":
      return value1 * value2;
      break;
    default:
      return value1 / value2;
  }
}
```