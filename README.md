# AlexaNJTransit
Alexa skill that gets the departure time of an NJ Transit train from an NJ station to NY Penn.

Intents, custom slot type "list_of_stations", sample utterances, and lambda function code are in their respective files in the repo.

Note that a zipped package has to be loaded into the lambda management console with the python module "requests" installed (i.e. make a directory with lambda.py, type 'pip install requests -t /path/to/your/directory' into the command line, and zip the CONTENTS of this directory and upload it to the lambda management console).
