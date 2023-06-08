<img align="center" src="https://www.helakuru.lk/assets/images/icon.png" height="100px" width="100px">
<h1 align="center"><b> Helakuru.lk | | එසැණ </b></h1>
<h3 align="center"><b>⭕️ API (Unofficial) ⭕️<br><br> <a href="https://sisula.ml/" target="_blank">SISULA WELGAMAGE</a> | | <a href="https://ravindumanoj.ml/" target="_blank">RAVINDU MANOJ</a></b></h3><br>

`⭕️ This project is for educational purposes only!⭕️ `  <br>
`⭕️ The user shall take full responsibility for the errors such as changing the information and changing the name of the company. ⭕️` <br>
`⭕️ "Fetch All" has been temporarily removed ⭕️`

`Base Site -:` https://helakuru.lk/esana

`NPM Link  -:` https://www.npmjs.com/package/esana-node-api

## Installation

```console
$ npm install esana-node-api
$ yarn add esana-node-api
```
<br>

> QUENSTIONS ?

<br>

- [x] <b>  </b>

<br>

## Usage - Fetch Latest News Esana / එසැණ News ලබා ගැනීමට.

```js
const {Esana} = require("esana-node-api")

async function esana_run(){

await Esana.verify('Enter Your Passcode') 
const esana_data = await Esana.fetch_news_data()
console.log(esana_data)

}
esana_run()
```

Output:

```js
{
  status: 200,
  latest: true,
  esana: {
    news_id: 98376,
    title: 'දූෂණ විරෝධී පනත් කෙටුම්පත ජුනි 21දා විවාදයට ගැනීමට තීරණය කෙරේ',
    description: 'දූෂණ විරෝධී පනත් කෙටුම්පත ජුනි 21දා විවාදයට ගැනීමට තීරණය කර තිබෙනවා.',
    thumbnail: 'https://helakuru.sgp1.cdn.digitaloceanspaces.com/esana/images/lib/parliment-new-01[1].jpg',
    url: 'https://www.helakuru.lk/esana/98376',
    date: '2023-06-08 16:03:06',
    media: []
  }
}
```

## License

[MIT](/LICENSE)

## Disclaimer
`esana - එසැණ ` name, we have nothing to do with the website officially. If any complains please contact via dev-a@sisula.ml
