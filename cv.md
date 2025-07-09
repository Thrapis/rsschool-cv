# Artsiom Belski

## Contacts

<img src="img/content/photo-blur-cut.jpg" height=128 style="border-radius:16px; float:right;">

**Phone:** +375 (44) 74-64-364\
**Email:** artbelski@gmail.com\
**GitHub:** [Thrapis](https://github.com/Thrapis)\
**LinkedIn:** [artbelski](https://www.linkedin.com/in/artbelski/)\
**Discord:** @Thrapis - Artsiom Belski (@Thrapis)\
**Location:** Minsk, Belarus

## About Me

4 years of experience in developing web and desktop applications with C#. Practical experience with SQL Databases: Oracle, Microsoft SQL Server, and Postgres. Successfully obtained Golang United School Certificate (EPAM/RS School) and continue enriching my Golang skill. Have a knowledge of OOP and widely used design patterns.

Eager to solve real business problems and thus increase the value of a
product. Motivated to learn from others and strive to be a good team
member. Detail-oriented and dedicated to delivering high-quality work.

## Skills

- **HTML&CSS**
- **JavaScript\TypeScript** [Basic]
- **C#** (Entity Framework, Dapper, ASP.NET Core, Blazor)
- **Java** [Basic]
- **C++** [Basic]
- **Golang** (Gorm, Gin)
- **Databases** (Oracle, MSSQL, PostgreSQL, Redis [Basic])
- **Git\GitHub** (GitHub Actions)
- **Docker** [Basic]

## Code Example

Given an array (arr) as an argument complete the function countSmileys that should return the total number of smiling faces.

Rules for a smiling face:

- Each smiley face must contain a valid pair of eyes. Eyes can be marked as : or ;
- A smiley face can have a nose but it does not have to. Valid characters for a nose are - or ~
- Every smiling face must have a smiling mouth that should be marked with either ) or D

No additional characters are allowed except for those mentioned.

```js
// return the total number of smiling faces in the array
function countSmileys(arr) {
  var eyes = [':', ';']
  var noses = ['-', '~']
  var mouth = [')', 'D']
  return arr.filter(s => (s.length === 2 || s.length === 3) &&
                    eyes.some(t => t === s[0]) && mouth.some(t => t === s.slice(-1)) &&
                   (s.length === 3 ? noses.some(t => t === s[1]) : true)).length
}
```

## Job Experience

<img src="img/content/belstu.png" height=12> **Web Developer**\
*Belarusian State Technological University*\
<sup>Aug 2022 - July 2024 - 2 years, Minsk</sup>

<img src="img/content/dzd.png" height=12> **Information Technology Instructor**\
*Children's Railway*\
<sup>Feb 2024 - Now, Minsk</sup>

## Educational Projects

**Miadok Chaladok** ([link](https://github.com/Thrapis/MiadokChaladok-Go))\
Web Application built with React.js, Golang, and PostgreSQL. The goal of the project is to gain knowledge in React (using Typescript, architecture based on Feature-Sliced Design), Golang libraries (Gin, Gorm), Redis storage, Postgres database and Docker.

## Education

<img src="img/content/belstu.png" height=12> **Bachelor’s degree in Information Systems
and Technologies**\
*Belarusian State Technological University*\
<sup>2018 - 2022, Minsk</sup>

## Courses

<img src="img/content/rs-school.png" height=12> **Learning the basics of Golang and
participating in team project development**\
*Rolling Scopes School (EPAM)*\
<sup>2022, Minsk</sup>

<img src="img/content/ulc.png" height=12> **Learning English - B1**\
*Underground Language Club*\
<sup>2023, Minsk</sup>

## Languages

- **Russian** - Native
- **Belarusian** - Native
- **English** - B1