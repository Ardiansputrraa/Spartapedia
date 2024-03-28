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

buat package static dan templates

file meta_prac.py berisikan script roller pendek untuk mengekstrak data tag meta seperti webscraping
lakukan import beberapa library
import requests
from bs4 import BeautifulSoup

buat file app.py
import bebrapa library termasuk flask didalam file app.py
from flask import Flask, render_templatem, request, jsonify 
from http import client
from pymongo import MongoClient

buat file index.html didalam package tamplates

file .gitignoer adalah file yang akan dibaca oleh git
berisi file-file yang akan disertakan dalam ke git untuk mengabaikan beberapa file yang berukuran besar
