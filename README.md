# **AutomaticIPv4-Calculator**

> ![image](https://github.com/douglascybersec/AutomaticIPv4-Calculator/blob/new-main/static/repo.png)
> A sophisticated WINDOWS Python app for IPv4 subnetting that supports both Fixed Length Subnet Masking (FLSM) and Variable Length Subnet Masking (VLSM) scenarios. It is created with Customtkinter.

# **Installation & Usage Guide**
## Overview
This guide provides how to Install the full-featured WINDOWS-version pre-release app and reusing the code, all are explained below. The program is completely functional and ready for use in the [ZIP file](https://github.com/douglascybersec/AutomaticIPv4-Calculator/blob/new-main/exe-file-output.zip), and accessing and reusing the codebase—including the [ZIP file](https://github.com/douglascybersec/AutomaticIPv4-Calculator/blob/new-main/exe-file-output.zip) —is made possible by cloning the repository.

## Prerequisites
- [x] Windows 10/11
- [x] Python 3.x
- [x] Tkinter/Customtkinter

## Usage Methods
### Method I: Running (pre-release) from ZIP File
1. Clone the repository:
```
git clone https://github.com/douglascybersec/AutomaticIPv4-Calculator.git

```

2. Navigate to project directory:
```
cd AutomaticIPv4-Calculator

```

3. Unzip the pre-release file:
```
. locate the exe-file-output.zip
. extract and unzip it
. finally, open the files to autoipv4 and run

```
**_note:_** **_to avoid dependency concerns, do not execute the application outside of its directory_**


### Method II: Runnning/Reusing the cloned repository

1. Make a fresh file named **.env** and copy-paste the following in:
```
SENDER_EMAIL= "your_email@gmail.com"
RECEIVER_EMAIL = "your_email@gmail.com"
EMAIL_PASSWORD = "your_app_password"
SMTP_SERVER = "smtp.gmail.com"  
SMTP_PORT = 587

```
2. enter the necessary data -your_email_address, including [your_app_password](https://support.google.com/accounts/answer/185833?hl=en)

**_so, instead of hardcoding vital data in your code, this creates [environmental variables](https://en.wikipedia.org/wiki/Environment_variable) for security purposes (make the cybersec team proud!)_**

3. Install dependencies:
```
py -3 -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt

```

4. Run the Script:
```
python autoipv4.py

```


## License
The MIT License grants the use of this project. See the [LICENSE](https://github.com/douglascybersec/AutomaticIPv4-Calculator/blob/new-main/LICENSE) file for additional details.

## Feedback & Collabs
Got a feedback or want to collaborate? I'm all circuits! Pull requests? Yes, I love them! _If not h4ck1n9 or c0d1ng, you might catch me creating cybersecurity content mostly on YouTube._ Checkout the [YouTube Channel](https://www.youtube.com/@douglascybersec) for more..
