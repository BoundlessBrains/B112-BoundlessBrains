## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot 

## ask periods 1
* greet 
  - utter_greet 
* ask_periods 
  - utter_periods 
  - utter_did_that_help 
* affirm
  - utter_happy 

## ask periods 2
* ask_periods 
  - utter_periods 

## ask periods 3
* greet 
  - utter_greet 
* ask_periods 
  - utter_periods 

## ask cramps 1 
* greet 
  - utter_greet 
* ask_stomach_pain
  - utter_cramps
  - utter_did_that_help 
* affirm
  - utter_happy 

## ask cramps 2  
* ask_stomach_pain
  - utter_cramps 

## ask back pain 1 
* greet 
  - utter_greet 
* ask_back_pain
  - utter_backpain
  - utter_did_that_help 
* affirm
  - utter_happy



