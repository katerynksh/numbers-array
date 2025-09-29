# numbers-array
цей код виводить набір чисел і виводить 2 найменших з них


  const numArr = []
   for (let i = 0; i < 10; i++) {
      numArr[i] = Math.round(Math.random() * 100 - 50);
   }
   
   console.log(numArr)
let minmin1 = numArr [0]
let minmin2 = numArr [1]
  for (let i = 1; i < numArr.length; i++) {
     if (minmin1>= numArr [i]){
        minmin2 = minmin1
         minmin1 = numArr[i]
        
     }
     else if(minmin2 >= numArr[i]){
        minmin2 = numArr[i]
     }

   }
console.log(minmin1)
console.log(minmin2)
