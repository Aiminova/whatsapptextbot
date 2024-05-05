# WhatsappTextBOT :robot:
 - Send messages to any person in any time.
 - Just change the chromedriver or geckodriver location in WhatsappTextBot.py and enjoy it.
 


# How to run the project? :thinking:
 - Clone github repository in your local system  `git clone https://github.com/Aiminova/whatsapptextbot.git`
 - Move in WhatsappTextBOT repository  `cd WhatsappTextBOT`
 - Create new virtual python environment  `python3 -m venv venv`
 - Activate virtual python environment  `source venv/bin/activate`
 - Install all the libraries mentioned in [requirements.txt](https://github.com/Aiminova/whatsapptextbot/blob/master/requirements.txt) using  `pip install -r requirements.txt`
 - Run Python file  `python WhatsappTextBot.py`
 
# Directory Tree :cactus:
```bash
.
├── birthdays.json
├── chromedriver
├── executable
│   ├── 9022c3da331305796ded3dda4c619df0.png
│   ├── GZd3Pv.png
│   └── test
├── geckodriver
├── images
│   ├── GZd3Pv.png
│   ├── Main.jpeg
│   ├── Option1.jpeg
│   ├── Option1R.jpeg
│   ├── Option2.jpeg
│   ├── Option3.jpeg
│   └── Option4.jpeg
├── README.md
├── requirements.txt
└── WhatsappTextBot.py

2 directories, 16 files
```
 
## ScreenShot :camera_flash:

**1).** This is the Main Page of the application. First Option provides send as many messages as you want to a person. <br><br>
![github-small](images/Main.jpeg)

 - This is the input part. You enter Phone Number with country code, Message and Number of Messages. I don't try the maximum message capacity but you can try.  <br><br>
![github-small](images/Option1.jpeg)

 - Result of the First Option. I tried send to 'Merhaba' ten times. <br><br>
![github-small](images/Option1R.jpeg)

**2).** This is the Second Option. This provides send message in specific month and day. You can add all of your relationships in the input part. Input part saves input in the [birthday.json](https://github.com/Aiminova/whatsapptextbot/blob/master/birthdays.json) and you run the program it's control the dates and if it matches, bot send it.  <br><br>
![github-small](images/Option2.jpeg)

**3).** Third Option: If you want send one message many person, you should choice this option. **Example:** In important days like holidays and feasts. You need to enter message and phone number here.  <br><br>
![github-small](images/Option3.jpeg)

**4).** Fourth Option: This option provides if you busy with your job and forget send important message to anyone. Just use it set hour and seconds just like `12:00`.   <br><br>
![github-small](images/Option4.jpeg)

## Bug / Feature Request :man_technologist:
If you find a bug (the application couldn't handle the query and / or gave undesired results), kindly open an issue [here](https://github.com/Aiminova/whatsapptextbot/issues/new) by including your search query and the expected result.

If you'd like to request a new function, feel free to do so by opening an issue [here](https://github.com/Aiminova/whatsapptextbot/issues/new). Please include sample queries and their corresponding results.






