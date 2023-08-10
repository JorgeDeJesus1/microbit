# microbit
from microbit import *  while True:     nivel_de_luz = display.read_light_level()          if nivel_de_luz &lt; 80:         display.show(Image.ALL_ON, delay=0)     elif nivel_de_luz > 170:         display.show(Image.TARGET, delay=0)     else:         display.clear()
