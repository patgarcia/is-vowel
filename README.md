# is-vowel
Check if character is a vowel

```javascript
const isVowel = char => /aeiou/i.test(char);
```

It could be used in a recursive way to count vowels in a string
```javascript
const countVowels = str => !str?.length ? 0 : isVowel(str[0]) + countVowels(str.slice(1));
```
