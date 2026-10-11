# Chicken-road-bot
from flask import Flask, render_template_string import pyautogui import time import threading  app = Flask(__name__) bot_running = False  def bot_logic():     global bot_running     while bot_running:         # Yahan se screen check hoti hai         # Demo: Har 3 second me Spin button pe click         print("Bot clicked SPIN")         pyautogui.cli
