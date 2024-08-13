The on_press function is called whenever a key is pressed. It writes the key to a file named "keylog.txt" in append mode.
The on_release function is called whenever a key is released. If the key is the 'esc' key, it stops the listener.
The Listener object is created with the on_press and on_release functions. It starts listening for keyboard events until the 'esc' key is pressed.
Note: This program uses the pynput library, which is not a built-in Python library. You can install it using pip install pynput.

Important: Keyloggers can be used for malicious purposes, such as spying on users without their consent. It is essential to use this program responsibly and only with the explicit permission of the user. Additionally, be aware of the legal and ethical implications of using keyloggers in your jurisdiction.

Disclaimer: This program is for educational purposes only, and I do not condone or encourage the use of keyloggers for malicious purposes.

To run the program ,execute it using Python (e.g., python keylogger.py). The program will start logging keystrokes to a file named "keylog.txt" in the same directory. Press the 'esc' key to stop the program.
