<div align="center">

![Profile picture](./assets/img/profile.png)
# Anatoly Sizyakin
_~ Frontend Developer ~_
</div>

### ✉️ Contacts
- E-mail: [_rx.anat01ium@gmail.com_](mailto:rx.anat01ium@gmail.com)
- Telegram: [_@anat01ium_](https://t.me/anat01ium)
- Discord: [_anat01ium_](https://discord.com/users/313319068138602508)

### 👤 About
_Interested in Web development._

### 🌍 Languages
- Russian: _Native_
- English: _B1 Intermediate_ [_(EF SET English Certificate 47/100)_](https://www.efset.org/cert/3jqk8w)

### 💪 Skills
##### Languages:
- HTML5
- CSS3
- JavaScript (ES6+)

##### Key Skills:
- Responsive Design, Flexbox, CSS Grid
- Sass
- Gulp
- GNU/Linux

##### Tools:
- Git, GitHub, SSH
- Chrome DevTools
- VS Code, (Neo)Vim
- Figma, Gimp

### 🎓 Education
##### `1999-2004` \| Moscow Goverment Social Univercity
- Automated information processing and management systems
  - _Engineer_

##### `2023` \| Hexlet
- [JavaScript: Perfect for Beginners](https://code-basics.com/languages/javascript)

##### `2024` \| Hexlet
- [HTML: Perfect for Beginners](https://code-basics.com/languages/html)

##### `2024` \| Hexlet
- [CSS Online Course: Lessons &amp; Execises](https://code-basics.com/languages/css)

### 👔 Work
##### `2003-2008` \| «Rusich» OOO
- _IT specialist_

##### `2009-2011` \| OOO «Arbalet»
- _IT specialist_

##### `2011-2016` \| «Polyus-M» OOO
- _Web administrator_

##### `2016-....` \| Self-Employed
- _Maintenance and repair of PCs and laptops_
- _Smartphone repair_
- _Maintenance of payment terminals_
- _Installation, configuration of network equipment_

### 👨🏼‍💻 Code
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
     case 0: return `no one likes this`;
     case 1: return `${names[0]} likes this`;
     case 2: return `${names[0]} and ${names[1]} like this`;
     case 3: return `${names[0]}, ${names[1]} and ${names[2]} like this`;
    default: return `${names[0]}, ${names[1]} and ${names.length - 2} others like this`;
  }
}
```
