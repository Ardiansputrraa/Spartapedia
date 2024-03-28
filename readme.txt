settings.json dengan:
{
    "liveServer.settings.port": 5501,
    "terminal.integrated.profiles.windows": {
        "PowerShell": {
            "source": "PowerShell",
            "icon": "terminal-powershell",
            "args": [
                "-ExecutionPolicy",
                "Bypass"
            ]
        }
    },
    "terminal.integrated.defaultProfile.windows": "PowerShell"
}

virtual environment dengan cara
pyhon -m venv venv

activkan virtual environment
.\venv\Scripts\activate

install flask
pip install flask

install package request untuk dapat meminta req pada web
syntax = pip insstall request

install package beutifulsoup4
pip install beautifulsoup4

untuk mengubungkan ke database mangodb install dibagian enveronment
syntax = 
        pip install pymongo
        pip install dnspython
