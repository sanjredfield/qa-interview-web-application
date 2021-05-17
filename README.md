## Setup

To run this application locally. 

1. `python3 -m venv env`
2. `. env/bin/activate`
2. `pip install -r requirements.txt`


## How to run the QA interview application

To start the application, run `python qa_interview.py` and visit `localhost:6464` in your browser.


## What the application does

The application calculates the factorial of a given number. We have exactly one page with:

* one text box 
* one submit button
* a page title 
* three hyperlinks 
* a copyright message

By keeping the application this simple, we are increasing the likelihood of the interviewer and the candidate agreeing upon what is important. You can also reasonably expect QA to be able to verbalize their testing for such limited functionality.


## Tips when interviewing QA engineers

Apart from technical skills, you can also pick up on several characteristics. Here are some tips:

* Verify if the QA is able to check functional correctness for 0,1 and a few more integers
* Watch the body language of the QA as they discover bugs - good QA are happy when they are discovering bugs
* Make sure the QA tries to reproduce any bug they discover!
* Are they keeping notes or screenshots of what they see?
* Are they continuously trying to discover bugs through the entire time allotted?
* Do they ask good questions about context (why am I even testing this? who is going to use this? etc.)

For general advice on interviewing QA engineers effectively, refer to [A better way to interview QA engineers](https://qxf2.com/a-better-way-to-interview-qa).

## Solutions

We haven't really documented our test strategy and the bugs anywhere. For now, just write to Arun (mak@qxf2.com) if you want a quick overview of all the bugs and how a typical interview will look like.