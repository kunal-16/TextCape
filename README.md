<h1 align="center">
  <br>
  <img src="assets/stegCloakIcon.svg" alt="StegCloak" width="100">
  <br>
  <br>
  <span>TextCape</span>
  <br>
  <img src="https://img.shields.io/npm/l/stegcloak?style=plastic" />
  <a href="https://www.npmjs.com/package/stegcloak"> <img src="https://img.shields.io/npm/v/stegcloak?style=plastic" /> </a>
   <a href="https://github.com/sindresorhus/awesome-nodejs">
  <img src="https://raw.githubusercontent.com/sindresorhus/awesome/main/media/badge.svg" />
  </a>
  <img src="https://img.shields.io/badge/code_style-standard-brightgreen.svg" />
  <br>
</h1>
<h4 align="center">The Cloak of Invisibility for your texts</h4>

<p align="justify">
StegCloak is a pure JavaScript steganography module designed in functional programming style, to hide secrets inside text by compressing and encrypting the secret before cloaking it with special unicode invisible characters. It can be used to safely watermark strings, invisible scripts on webpages, texts on social media or for any other covert communication. Completely invisible! See how it works in-depth in this Medium <a href="https://blog.bitsrc.io/how-to-hide-secrets-in-strings-modern-text-hiding-in-javascript-613a9faa5787">article</a> or watch our <a href="https://www.youtube.com/watch?v=RBDqZwcGvQk">demo</a> to know what it does.
<p>

<a href="https://standardjs.com" style="position: absolute; top: 100px; right: 20px; padding: 0 0 20px 20px;"><img src="https://cdn.rawgit.com/feross/standard/master/sticker.svg" alt="JavaScript Standard Style" width="80" align="right"></a>

## Features
- Protect your invisible secret using passwords and HMAC integrity
- Cryptographically secure by encrypting the invisible secret using AES-256-CTR.
- Uses 6 Invisible characters in unicode characters that works everywhere in the web - Tweets, Gmail, WhatsApp, Telegram, Instagram, Facebook, and many more!
- Maximum Compression to reduce the payload (LZ, Huffman).
- Completely invisible, uses Zero Width Characters instead of white spaces or tabs.
- Super fast! Hides the Wikipedia page-source for steganography (800 lines and 205362 characters) within a covertext of 3 words in under one second.
- Hiding files in strings can be achieved by uploading the file to cloud and stegcloaking the link in the string
- Written in pure functional style.
- Usage - Available as an API module, a CLI and also a <a href='https://stegcloak.surge.sh'>Web Interface</a> (optimized with web workers). 

<br>

![StegCloak Demo](assets/stegcloak.gif)



## How it works

<img src='assets/FlowDiagram.PNG'>


