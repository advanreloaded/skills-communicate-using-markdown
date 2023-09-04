# GitHub Skills

## Communicate using markdown

- [x] Create the repo from the template
- [x] Create a pull request
- [ ] Edit the index.md file
- [ ] Create different examples with markdown

### Yaktocat
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

### *Example 1:* Fibonacci Series Up to n Terms
```javascript
const number = parseInt(prompt('Enter the number of terms: '));
let n1 = 0, n2 = 1, nextTerm;

console.log('Fibonacci Series:');

for (let i = 1; i <= number; i++) {
    console.log(n1);
    nextTerm = n1 + n2;
    n1 = n2;
    n2 = nextTerm;
}
```
