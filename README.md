# wellness-check-bot
This is a simple Rasa bot that uses a form to create a daily log of health information.

All the trained model is store in the model folder, if there has no model folder please mkdir one. 
And train follow commods

Note, all new added samples also re-train the RASA model. 

## Running the assistant
1. Install Rasa Open Source: https://rasa.com/docs/rasa/user-guide/installation/
2. Train the model:

``rasa train``

3. Open a second terminal window and start the action server:

``rasa run actions``

4. Return to telegram and start the assistant on the command line:

``rasa run --por5005 --credentials credentials.yml``
