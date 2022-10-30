<div align="center">
  <h1>randomize-data</h1>
  <p>Generate massive amounts of fake data for testing and development.</p>
  
  [![npm version](https://badgen.net/npm/v/randomize-data)](https://www.npmjs.com/package/randomize-data)

</div>

## 🚀 Features

- 💌 Locations - Generate Countries!
- 🧍 Persons - Generate virtual persons name, id, age and country.
- 🔢 Numbers - Of course, we can also generate random numbers and words.
- 🌈 Colors - Generate hex colors.

## 📦 Install

```bash
npm install randomize-data
```

## 🪄 Usage

```ts
const randomizer = require('randomize-data')

console.log(randomizer.getRandomHexColor())
console.log(randomizer.getRandomPerson(['age', 'fullName', 'country', 'id']))
```

## 🔑 License

MIT