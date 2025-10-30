# Lexchat 🤖💬
Welcome to the first ever publicly announced version of Lexchat this is a beginning of a great journey in AI this begins with a small but fun AI that does sorts of stuff like:
Features:
- Code small demos in Python, HTML, and JavaScript with explanations
- Make fun stories
- Tell jokes
- Different voice modes
- Tell the current time
- Search the web (DuckDuckGo)
- Show last search history
- Draw shapes using Turtle
- Play games (e.g., Rock, Paper, Scissors)
- Show recent actions (history)
- To discover more you can use the help function

Communication:
- Text input
- Voice input (4–5 second recordings converted to text)
- Type 'exit' to stop the AI

⚠️ Caution: This AI is not trained on external datasets yet. It's a beginner-friendly creative AI project.
⚠️ Caution: Do not feed it with personal data like passwords,contact information and so forth, for it saves it.


A start toward something greater, I want to introduce you all to Lexchat or LEX 0.5
The great future for AI, This is just the beginning of something great.

Re-create it.
import os
import sys
import re
import time
import json
import math
import random
import turtle
import difflib
import logging
import threading
from datetime import datetime

    import pyttsx3
    import sounddevice as sd
    import soundfile as sf
    import speech_recognition as sr
    from duckduckgo_search import DDGS
