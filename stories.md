## happy path greet 
* greet
  - utter_greet

## happy path with 4g sim

* network_issue
  - utter_name
* my_name_is
  - utter_num_confirm
* affirm
  - action_your_num
* affirm
  - utter_tell_issue
* facing_issue
  - utter_what_handset
* headset
  - utter_change_settings
* guide_me
  - utter_solution
* have_to_do
  - utter_solution_4G
* thanks
  - utter_goodbye

## happy path without 4g sim

* thanks
  - utter_goodbye


## say goodbye
* goodbye
  - utter_goodbye

## bot challenge
* bot_challenge
  - utter_iamabot

## interactive_story_1
* greet
    - utter_greet
* network_issue
    - utter_name
* my_name_is{"NAME": "Ashish"}
    - slot{"NAME": "Ashish"}
    - utter_num_confirm
* affirm
    - action_your_num
* affirm
    - utter_tell_issue
* facing_issue{"NETWORK": "network issues"}
    - utter_what_handset
* headset{"BRAND": "One plus"}
    - slot{"BRAND": "One plus"}
    - utter_change_settings
* guide_me
    - utter_solution
* thanks
    - utter_goodbye
