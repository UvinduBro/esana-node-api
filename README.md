<img align="center" src="https://www.helakuru.lk/assets/images/icon.png" height="100px" width="100px">
<h1 align="center"><b> Helakuru.lk | | එසැණ </b></h1>
<h3 align="center"><b>⭕️ API (Unofficial) ⭕️<br><br> <a href="https://sisula.ml/" target="_blank">SISULA WELGAMAGE</a> | | <a href="https://ravindumanoj.ml/" target="_blank">RAVINDU MANOJ</a></b></h3><br>

`⭕️ This project is for educational purposes only!⭕️ `  <br>
`⭕️ The user shall take full responsibility for the errors such as changing the information and changing the name of the company. ⭕️` <br>
`⭕️ "Fetch All" has been temporarily removed ⭕️`

`Base Site -:` https://helakuru.lk/esana

<br>

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

const esana =  new Esana()
await esana.verify('Enter Your Passcode') 
const esana_data = await esana.esana_latest()
console.log(esana_data)

}
esana_run()
```

Output:

```js
{
  news: {
    helakuru: {
      title: 'මුදල් රාජ්‍ය ඇමති සහ IMF නියෝජ්‍ය කළමනාකාර අධ්‍යක්‍ෂ අතර හමුවක්',
      description: 'මුදල් රාජ්‍ය අමාත්‍ය ෂෙහාන් සේමසිංහ සහ ජාත්‍යන්තර මූල්‍ය අරමුදලේ නියෝජ්‍ය කළමනාකාර අධ්‍යක්‍ෂ කෙන්ජි ඔකමුරා සමඟ සාකච්ඡාවක් පවත්වා තිබෙනව
ා.\n' +
        '\n' +
        'එහිදී  ආර්ථිකය ස්ථාවර කිරීම සඳහා ශ්‍රී ලංකාව විසින් ක්‍රියාත්මක කර ඇති ආර්ථික ප්‍රතිසංස්කරණවල ප්‍රගතිය පිළිබඳව සාකච්ඡා කළ බවයි Twitter පණිවිඩයක් න
ිකුත් කරමින් මුදල් රාජ්‍ය අමාත්‍ය ෂෙහාන් සේමසිංහ සඳහන් කළේ.\n' +
        '\n' +
        'ජාත්‍යන්තර මූල්‍ය අරමුදලේ සහ ලෝක බැංකුවේ වාර්ෂික සම්මේලනයට සහභාගී වී සිටින අතරතුර මෙම හමුව සිදුව තිබෙනවා.',
      thumb: 'https://news.bhashalanka.com/image-library/shehan-okamura.jpg',
      url: 'https://www.helakuru.lk/esana/news/93795',
      data: '2022-10-16 16:02:40',
      lang: 'Sinhala'
      media: ['http://example.jpg', 'http://example2.jpg', 'http://example3.jpg']]

      //If Media Empty

      media: [{status: false}]
    }
  }
}
```

## License

[MIT](/LICENSE)

## Disclaimer
`esana - එසැණ ` name, we have nothing to do with the website officially. If any complains please contact via dev-a@sisula.ml
