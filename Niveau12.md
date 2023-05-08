ssh bandit12@bandit.labs.overthewire.org -p 2220

-ls -al

-scp -P 2220 bandit12@bandit.labs.overthewire.org:/tmp/data.tar.gz .

-tar xvf data.tar.gz

-cat data.txt
-cat data.txt | xxd -r > data.bin

-file data.bin

-./data.bin

Password :
wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw
