## Maksym Voloshyn

## Junior Frontend Developer

### Contact information:

**Location:** Ukraine, Kriviy Rih\
**E-mail:** zanderproteam@gmail.com\
**Phone:** +30678859225\
**Telegram:** @Maksym_Voloshyn\
**Discord:** Maksym_Voloshyn

---

### About myself:

---

### Skills:

- HTML, CSS
- Javascript
- Git, GitHub
- VS Code
- Figma, Avacode

---

### Code example:

**DESCRIPTION:**

Given the triangle of consecutive odd numbers:

```
             1
          3     5
       7     9    11
   13    15    17    19
21    23    25    27    29
```

Calculate the sum of the numbers in the $$\n^**th**$$ row of this triangle (starting at index 1) e.g.: (**_Input --> Output_**)

```
1 --> 1
2 --> 3 + 5 = 8
```

```javascript
function rowSumOddNumbers(n) {
  let number = 1;
  const numbers = [1];
  let result = 0;

  for (let i = 1; i < n; i += 1) {
    for (let j = 0; j < i + 1; j += 1) {
      number += 2;
      numbers.push(number);
    }
  }

  for (let i = numbers.length - n; i < numbers.length; i += 1) {
    result += numbers[i];
  }

  return result;
}
```

---

### Courses:

- **CS50 Basics of Programming** [Prometheus](https://prometheus.org.ua)
- **Basics of UI development [Lviv IT school]** [Prometheus](https://prometheus.org.ua)

---

### Languages:

- **Ukrainian:** native\
- **Russian:** native\
- **English:** A2 [Certificate_EF_SET](https://www.efset.org/cert/yGmiem)\
