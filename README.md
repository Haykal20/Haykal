# Haykal
***WhatsApp OpenAI Create with NodeJS Using Library [Baileys](https://github.com/adiwajshing/Baileys)***
## Fitur
***Ketik /menu untuk melihat fitur OpenAI***

**ChatGPT:**
```bash
Cmd: /ai <query>
```
**DALL-E:**
```bash
Cmd: /img <query>
```
## Command In Termux
**Install Script OpenAI**
```bash
$ termux-storage-setup
$ pkg update && pkg upgrade
$ pkg install git nano nodejs 
$ git clone https://github.com/Haykal20/Haykal.git
$ cd Haykal
```
**Change OpenAI ApiKey**
- Silakan buat apikey [disini](https://beta.openai.com/account/api-keys)
- Ganti ApiKey OpenAI di file [key.json](https://github.com/Haykal20/Haykal/blob/main/key.json)
```bash
$ cd Haykal && ls
$ nano key.json
```
**Change No Owner**
- Ubah nomor owner di file [index.js](https://github.com/Haykal20/Haykal/blob/main/index.js)
```bash
$ cd Haykal && ls
$ nano index.js
```
**Run**
```bash
$ cd Haykal && node index.js
```
**How To Remove Session**
```bash
$ cd Haykal && ls
$ rm Haykal.json
```
## License
[MIT License](https://github.com/Haykal20/Haykal/blob/main/LICENSE)

Copyright (c) 2023 Haykal20