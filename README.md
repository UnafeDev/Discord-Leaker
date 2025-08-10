# Discord-Leaker
Simple python tool to steal passwords and send through a webhook.

# Disclaimer
This tool/script is provided for educational purposes only and is made with purely educational intent. I am not responsible for any damages or consequences that may come from its use.

I take no part in, nor do I endorse, any activities you choose to perform or add with this tool.

# Editing
make sure to change these attributes :

![screenshot](https://github.com/UnafeDev/Discord-Leaker/blob/main/image.png)

you need to get location finding you need to get an api key from https://ipinfo.io/
# Compiling
drag and drop the py file into "pyinstaller.exe" and it will give options "--noconsole" (hidden) or with console (shows up when run)
![screenshot](https://github.com/UnafeDev/Discord-Leaker/blob/main/drag.png)

or run the command : 
pyinstaller --clean --onefile --noconsole -i NONE {script} (hidden)
pyinstaller --clean --onefile -i NONE (shown)

# Dependencies

pip install requests pywin32 pycryptodome
