# EPUB-to-PDF

Telegram bot EPUB to PDF converter, this bot is available on Telegram with the following username: [@EPUB_to_PDF_Convertor_Bot](https://t.me/EPUB_to_PDF_Convertor_Bot)

![EPUB to PDF](icon.png)

### Usage

Just contact the Telegram bot [@EPUB_to_PDF_Convertor_Bot](https://t.me/EPUB_to_PDF_Convertor_Bot) and send a file.epub, you will receive back a file.pdf.

## Local installation (development)

### Requirements

- python3
- python-telegram-bot
- calibre (ebook-convert)

If you are using Linux as OS you could install the requirements using the package manager, for debian-based you could use the following command to install the main requirements:

```bash
sudo apt install python3 python3-pip calibre
```

To install the python-telegram-bot framework you can use `pip` the python package manager:

```bash
pip3 install python-telegram-bot
```

### Configure

Create a personal bot contacting [@Botfather](https://t.me/Botfather).
Created the bot you will receive an API token, so copy the file *token.conf.dist* into *token.conf*, delete the content and put inside the API token.

Well, now, you can run the script **main.py** and send to your bot the file.epub, you will get a file,pdf back.

## Docker installation (production)

```bash
docker build -t epub_to_pdf:latest .
docker run -d epub_to_pdf
```

## Support 

**If you're having any problem, Head to [@DevelopedBotz](https.//tx.me/DevelopedBotz)**

### Credits

- [Kunal-Diwan](https://github.com/Kunal-Diwan)
