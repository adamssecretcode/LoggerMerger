# LoggerMerger

Bash scripts to combine 15 minute records from B.U.T.T. encoder into hour long files between 6am and midnight. 

Launching the script will ask you to enter two pieces of information:
1. Working Directory : the directory where the files to join are stored
2. Logger Date : the date 

Those 2 pieces of information are used to form the path:
{Working Directory}/rec_{Logger Date}-{Hour}{Minute}00.aac 

(e.g. /media/LOGGER/audio/rec_20220814-221500.aac)
