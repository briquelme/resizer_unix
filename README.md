# resizer_unix
Fork of twitter/whuppo's little script for resizing twitch emotes. Tested on Manjaro 18.1.5, Python 3.8.1

This is a python script currently, I have no knowledge of how to build an actual standalone executable that doesn't conflict with the used libraries( [TkDND](https://github.com/petasis/tkdnd) and [TkinterDnD2](http://tkinterdnd.sourceforge.net/)), because they nedeed to be installed in a funky way. If anyone can help with it, I'd be grateful.

#Installation
Just clone the repo.

#Usage

You need to activate the included virutal environment and run the script:
~~~~
source venv/bin/activate
python resize_source.py
~~~~
Just drag and drop the emotes to be resized. The results will be stored on the directory of the original files.

