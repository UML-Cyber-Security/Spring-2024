_**Modify/Download these files at your own risk. If you are to modify/download these files, you may want to consider doing it in a virtual machine.**_

For this activity, your goal is to be able to view the secret.jpg file and then find the secret message hidden utilizing steganography. You may find ExifTool or another one of the steganography decoder tools useful.

**Part 1:** Create a script (in any programming language) to decode the hidden message in the hiddenmessage.txt file using brute force. This message was encoded using a Caesar Cipher shift. Once you have decoded the message in various shift forms, find the shift message that has a three word phrase in it. Once you find this phrase, you can move on to part 2.
    **Hint: The shift amount is somewhere between +3 and +6, inclusive. **

**Part 2:** Now, it is time to run the decryptscript.py file (you may want to use a Virtual Machine). Once this has been run, you be prompted to input a "password." The "password" will be the phrase you found in the decoded message. Assuming you type in the correct password, the secret.jpg file will be decrypted. Now you can move on to the last and final part: Part 3

**Part 3:** It is now time to use your favorite steganography decoder tool, such as Exiftool, to inspect the meta information. If you have successfully inspected it, you will see a message. 

You have now finished investigating and found the hidden message!
