# Chatbot

## Libraries needed to run this chatbot:

* rasa 2.2.9 (run ```pip install rasa==2.2.9``` in command prompt)
* rasa-x 0.38.1 (run ```pip3 install --use-deprecated=legacy-resolver rasa-x --extra-index-url https://pypi.rasa.com/simple``` in command prompt)

## How to run this chatbot in command prompt?

* Use ```rasa shell``` to interact with chatbot in command prompt.
* Use ```rasa shell nlu``` to inspect the intent classified by the bot.

## How to run this chatbot with rasa-x?

* Run ```rasa run actions``` in one terminal. Do not close this tab.
* Now, run ```rasa x``` in another terminal. This will open a tab in the browser.
