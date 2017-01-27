# mycroft-vision-service

run main.py from opticalnerve

will process vision, detect faces, smiles and emit to messagebus so some skill can use info

2017-01-26 22:07:16,661 - Skills - DEBUG - {"type": "context_update", "data": {"asctime": ["Thu Jan 26 22:07:16 2017"], "smile detected ": [false], "master": [false], "time": [1485490036.656631], "number of persons": [1], "movement": [false]}, "context": null}

Currently being used by me to have mycroft take actions by itself when there is no user present, decided to share but this isnt release quality code


known issues:
- incomplete
- paths to haar cascades are hardcoded and need to be edited in .py
