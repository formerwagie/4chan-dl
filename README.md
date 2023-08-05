# 4chan-dl
download media from 4chan threads. previously downloaded threads are saved to a log file. use 4chan-update to download new media.

compatibility:
linux

about:
this is by no means faster than other scripts to download 4chan threads. however, it suits my needs as it allows a user to specify unique output directories for each thread.

install:
place 4chan and 4chan-update in your .local/bin folder. call them from the cli.

usage:
  4chan -o "/output/directory" "thread_url"
    if you do not specify an output directory, the script will download media to the current working directory.
    if you pass a URL that is already present in the logs, the script will ignore your output directory argument and use the one in the log file instead.


  4chan-update
    running this command will search the log files (/home/user/.local/state/4chan) and update all of the threads in one go.

