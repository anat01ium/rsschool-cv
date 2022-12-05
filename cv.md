# Anatoly Sizyakin
_Frontend Developer_
## ✉ Contacts
- E-mail: [_rx.anat01ium@gmail.com_](mailto:rx.anat01ium@gmail.com)
- Telegram: [_@anat01ium_](https://t.me/anat01ium)
- Discord: [_Anatoly Sizyakin (@anat01ium)_](https://discord.com/users/313319068138602508)

## 👤 About
_My interest in the IT industry appeared instantly when I first saw a personal computer during school time in the 90s.
There was no doubt that I would connect my life with computers and after graduation I entered the university to become a programmer._

_After receiving higher education, my work has always been related to IT, although it did not concern programming.
But, throughout the whole time, the thought that I always wanted to write code did not leave me._

_Thanks to Internet sources and educational online platforms, I began to study frontend development.
Some time after I started studying, I realized that my dream of writing code and working as a programmer is still burning in me._

## 💪 Skills
- HTML
- CSS
- JavaScript
- ReactJS
- Git
- VS Code, Vim
- Figma, Photoshop
- GNU/Linux

## 📝 Code
#### Task:
_Implement the function which takes an array containing the names of people that like an item. It must return the display text as shown in the examples:_
```
[]                                -->  "no one likes this"
["Peter"]                         -->  "Peter likes this"
["Jacob", "Alex"]                 -->  "Jacob and Alex like this"
["Max", "John", "Mark"]           -->  "Max, John and Mark like this"
["Alex", "Jacob", "Mark", "Max"]  -->  "Alex, Jacob and 2 others like this"
```
> _For 4 or more names, the number in "and 2 others" simply increases._

#### Solution:
```js
function likes(names) {
  switch(names.length) {
    case 0:  return `no one likes this`;
    case 1:  return `${names[0]} likes this`;
    case 2:  return `${names[0]} and ${names[1]} like this`;
    case 3:  return `${names[0]}, ${names[1]} and ${names[2]} like this`;
    default: return `${names[0]}, ${names[1]} and ${names.length - 2} others like this`;
  }
}
```

## 👔 Work
##### `2003-2008` \| «Rusich» OOO
- _Computer Operator_

##### `2009-2011` \| OOO «Arbalet»
- _IT Specialist_

##### `2011-2016` \| «Polyus-M» OOO
- _Website Administrator_

##### `2016-....` \| Self-Employed
- _Maintenance and repair of PCs and laptops_
- _Smartphone repair_
- _Maintenance of payment terminals_
- _Installation, configuration of network equipment_

## 🎓 Education
##### `1999-2004` \| Moscow Goverment Social Univercity
- Automated information processing and management systems
  - _Engineer_

##### `2019-2020` \| GeekBrains
- Web Development
  - _Frontend Developer_

##### `2020` \| Zar Zakharov JavaScript Marathon

##### `2021` \| Zar Zakharov ReactJS Marathon

## 🌍 Languages
- Russian: _Native_
- English: [_EF SET English Certificate 47/100 (B1 Intermediate)_](https://www.efset.org/cert/3jqk8w)
