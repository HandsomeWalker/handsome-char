generate string as you like, only English letters and Numbers supported

## Usage

```
npm install handsome-char --save
```

```
import char from 'handsome-char';
var str1 = char('1-5|(2-9)^2|(3*7)^5|a-d|(c-e)^6|(d*g)^5|A-D|(C-E)^6|(D*G)^5');
var str2 = char('20');
```

## Rule

NOTE: only 1 param of type string required\
using '|' to split diffrent conditions, result in turn will be outputted according to the sequence of rule

'1-5': 1~5 in turn

'(2-9)^2': repeat 2 times of 2~9 in turn

'(3*7)^5': pick 5 random numbers from range of 3~7

and so is the "lowerCase" or "upperCase"

enjoy🙉
