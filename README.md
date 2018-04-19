What does it do?

This downloads the BBC Sounds Effects library one wav file at a time.

You can run this script multiple times, and it will start where it left off!  You are definitely allowed to move / delete / alter the wav files (I imagine you'll want to delete a few), and it won't re-download them.  Please don't touch the `lastFileDownloaded.txt` file though.  If you do, the script will lose it's place and start over again.

Disclaimer: This shouldn't be parallelized cause the BBC wouldn't be very happy if we did.  I'm not sure they would be happy with this existing at all.

Instructions:

Installing Node: Before you are able to run this script, you need to be able to run the code.  To do that please follow the instructions here: https://nodejs.org/en/download/

1. Download files: Click on the  `Clone or Download` button and `Download zip`.
2. Unzip the contents and put in your favourite folder
3. Open the command line and change the directory to the one in step 2.
4. Run `npm install`.  This installs other dependencies in which this code needs to run
5. Run `node index.js`

This should start the process of downloading the wav files into the `sounds` directory.  You'll see if it's working by  
a. Seeing if files are showing up in `sounds`  
b. messages about which file is being downloaded and saved shows up on the command line

If by any chance, the process crashes or stops, you can re-run the program in step 5 and it should pick up where it left off.

If you need to stop the program for whatever reason, you can press `crtl+c` in the command line.