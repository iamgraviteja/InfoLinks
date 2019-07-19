1. Add padding zeros

```javascript
  "1".padStart(3, 0) // results "001"
  // 3 - denotes total places
  // 0 - thing/num you want to pad
```

```javascript
// Other trick 
const padToThree = num <= 999 : `00${num}`.slice(-3) : num;
```
