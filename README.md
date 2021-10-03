# array_methods_ws

## Exc_1: Array Squared

##### Square value of every element in the array. Presume that you will get only numbers in the input array.

#### Input

```js
const input = [1, 2, 3, 4, 5];
```

#### Result

```js
[1, 4, 9, 16, 25];
```

---

## Exc_2: Sum of every positive element

##### Input is an array of numbers, return the sum of all of the positives ones. If the array is empty or there aren't any positive numbers return 0.

#### Input

```js
const input = [1, -4, 12, 0, -3, 29, -150];
```

#### Result

```js
42;
```

---

## Exc_3: Calculate median and mean

##### Calculate the mean and median values of the number elements from the input array.

#### Input

```js
const input = [12, 46, 32, 64];
```

#### Result

```js
  { mean: 38.5, median: 32 }
```

---

## Exc_4: Get Name initials

##### Input is a string of multiple words with a single space between each of them. You should abbreviate the name and get the name initials.

#### Input

```js
const input = 'George Raymond Richard Martin';
```

#### Result

```js
'GRRM';

```

---

## Exc_5: Age Difference from the youngest and oldest

##### Find the difference in age between the oldest and youngest family members, and return their respective ages and the difference.

#### Input

```js
const input = [
  {
    name: 'John',
    age: 13,
  },
  {
    name: 'Mark',
    age: 56,
  },
  {
    name: 'Rachel',
    age: 45,
  },
  {
    name: 'Nate',
    age: 67,
  },
  {
    name: 'Jeniffer',
    age: 65,
  },
];
```

#### Result

```js
[13, 67, 54];
```

---

## Exc_6: Numeronyms

##### Devs like to abbreviate everything: k8s means Kubernetes, a11y means accessibility, l10n means localization. You get the Dev numeronyms by taking the first and the last letter and counting the number of letters in between. Words that have less than 4 letters aren't abbreviated, because that would be just odd. The input is a sentence, and you should abbreviate every word that is 4 letters long or longer. There won't be any punctuation in the sentence. g2d l2k e6e

#### Input

```js
const input = 'Every developer likes to mix kubernetes and javascript';
```

#### Result

```js
'E3y d7r l3s to mix k8s and j8t';

```

---

## Exc_7: n! with map and reduce

##### Input is a number and you should return the factorial of that number. The factorial of a natural number n is the product of the positive integers less than or equal to n. So, 2! = 2, 3! = 6, 4! = 24 and so on.

###### Hint

```js
const array = new Array(input).fill(null);
// array is [null, null, null, null, null, null]

array.map(function (currentValue, index) {
  return index + 1;
});

// your code here ...
```

#### Input

```js
const input = 6;
```

#### Result

```
720
```

---
