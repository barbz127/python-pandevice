# python-pandevice

A python3 container based on the official with pandevice and requests installed.

## How to run
`docker run -it --rm -v $PWD:/scripts barbz127/python-pandevice python /scripts/pythonscript.py` - where pythonscript.py is your file to run

`docker run -it --rm -v $PWD:/scripts -v $PWD:/output barbz127/python-pandevice python /scripts/pythonscript.py` - use /output in your script if you need to write files outside the container

 ## Sample backup script for PAN devices
 coming soon.


