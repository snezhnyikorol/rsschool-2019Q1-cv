# Aleksei Raketskii
### Contacts
- **Telephone and messengers(Viber, Telegram, WhatsApp)**: [+375295265817](tel:+375295265817)
- **Email**: [raketskij@gmail.com](mailto:raketskij@gmail.com)
- **Facebook**: [Алексей Ракетский](https://www.facebook.com/profile.php?id=100015919805797)
### Summary
From the age of 11 I have been involved in sports programming, so I fancy about programming and everything connected with Information Technologies at all. My positive traits, such as ambitiousness, responsibility and ability to learn quickly allow me to "grasp on the fly".
### Skills
- Programming languages
  - C/C++
  - C#
  - Python
  - JS
- Frameworks
  - React
  - Angular
- Databases
  - Microsoft SQL Server
  - SQLite
- VCS's
  - Git
### Code Samples
Code sample from Brackets RS JS Task
```javascript
function check(str, bracketsConfig) {
  let stack = [];
  let arr = new Array(bracketsConfig.length).fill(false);
  for (let i = 0; i < str.length; i++) {
    for(let j = 0; j < bracketsConfig.length; j++) {
      if (str[i] == bracketsConfig[j][0] && !(arr[j])) {
        stack.push(str[i]);
        if (bracketsConfig[j][0] == bracketsConfig[j][1]) {
          arr[j] = true;
        }
      } else {
      if (str[i] == bracketsConfig[j][1]) {
        let el = stack.pop();
        if (bracketsConfig[j][0] == bracketsConfig[j][1]) {
          arr[j] = false;
        }
        if (el != bracketsConfig[j][0]) {
          return false;
        }
      }
      }
    }
  }
  if (stack.pop() != undefined) {
    return false;
  }
  return true;
}
```
### Experience
- Working with telegram API and writing bots
  - [Schedule bot](https://github.com/snezhnyikorol/coursework) (*coursework*)
  - [AlcoBot](https://github.com/snezhnyikorol/AlcoBot) (*first attempt to work with Telegram API*)
  - [Guess the melody](https://github.com/snezhnyikorol/pypybot)
- React SPA
  - [Mekler Command](https://github.com/snezhnyikorol/mekler) (*on development stage*)
- Rolling Scopes JS tasks
  - [Warm up!](https://github.com/snezhnyikorol/warmup-1)
  - [Love Triangles](https://github.com/snezhnyikorol/love-triangle)
  - [Sudoku](https://github.com/snezhnyikorol/sudoku)
  - [Advanced Zeros](https://github.com/snezhnyikorol/advanced-zeros)
  - [Brackets](https://github.com/snezhnyikorol/brackets)
  - [Money Exchange](https://github.com/snezhnyikorol/money-exchange)
- Laboratory practices and olympiad tasks (C/C++)
### Education
#### Belarusian National Technical University
*(2017 - 2021)*

Information Technologies and Robotics Faculty

*Information Systems and Technologies (1-400101-01)*
### English level
**Upper Intermediate** (according to [Streamline language school test](test.str.by))