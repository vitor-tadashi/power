## Lesson 1

1. Explain the `console.log`
2. Print `"Hello World"` and `2+2`
3. Ask the student to calculate compound interest rate
```
let money = 1000
money = money * 0.1 + money //first month
money = money * 0.1 + money //second month
console.log(money)
```
4. Explain `while` looping statement
```
let count = 0
while (count < 2) {
    console.log(count)
    count++
}
```
5. Ask the student to calculate compound interest rate without repeating the code
```
let month = 1
let money = 1000
while (month <= 12) {  
    money = money * 0.1 + money
    month++
}
console.log(money)
```
6. Explain `for` looping statement
```
for (let i = 1; i < 12; i++) {
    console.log(i)
}
```
7. Ask the student to calculate compound interest rate using `for`
```
let money = 1000
for (let month = 1; month <= 12; i++) {
    money = money * 0.1 + money
}
console.log(money)
```