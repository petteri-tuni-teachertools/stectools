# stectools
Tools for server technologies

## ray.sh

Tool for checking the config status of a server. Run the command (for example with SSH) in the target and run following command:
````
$ wget -O - https://homepages.tuni.fi/petteri.jekunen/stecray/ray.sh | bash
# RESULT: 1 - 2 - 2 - 3 #
````
Use exit status for OK/FAIL result.
````
$ echo $?
3
````
