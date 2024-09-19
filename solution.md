## Return Negative

```js
function makeNegative(num) {
    if (num > 0) {
        return num - num - num
    } else if (num <= 0) {
        return num
    } else {
        return 'please enter a number'
    }
}

makeNegative (42)
```

## Sum of Positive

```js
const numbers = [1,-4,7,12]

function positiveSum(arr) {
    let sum = 0
    for (let i = 0; i < arr.length; i++) {
        if (arr[i] > 0) {
            sum += arr[i]
        }
    }
    return sum
}

positiveSum(numbers)
```

## Function 2

```js
function square(num) {
  return (num ** 2)
}
              
square(3);
```

## Sum Arrays

```js
function sum (numbers) {
  "use strict";
  let total = 0;
  for(let i = 0; i < numbers.length; i++) {
    total += numbers[i];
  }
  return total;
};
```

## Reversed Strings

```js
function solution(str){
  let gnirts = ""
  for (let i = str.length - 1; i >= 0; i --) { 
        gnirts += str[i];
  }
  return gnirts
}
```


### Comprehension
  1-5

  4. I completed today's deliverable, and I feel I have a good grasp on the concepts, but wouldn't mind review.

### Completion
  1-5

  4. I completed the requiremnts in a way that I hope is conplete and correct. 


### Additional Comments
I'm mostly confused today about the submission requirements. I am really struggling to figure out the Pull Request stuff. I couldn't find anything that said compare across forks, so I'm assuming I navigated to the wrong location? This confused me a lot, I would like clarification if I could get any. 