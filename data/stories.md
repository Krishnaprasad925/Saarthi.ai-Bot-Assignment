## Greet path 1
* greet
  - action_greet
* goodbye
  - utter_goodbye

## Greet path 2
* greet
  - action_greet

## GoodBye path 
* goodbye
  - utter_goodbye

## thanks
* thanks
    - utter_noworries
    - utter_anything_else

## New Story00

* greet
    - action_greet
    - slot{"shown_privacy":true}
* thanks
    - utter_noworries
    - utter_anything_else
* goodbye
    - utter_goodbye

## weather_details
* weather_details
    - utter_weather_details

## identity
* identity
    - utter_identity

## affirm 
* affirm
  - action_intent

## deny
* deny
  - action_intent

## customer_support
* customer_support
  - utter_customer_support

## registration_info
* registration_info
  - action_intent

## onboarding_info
* onboarding_info
  - action_intent

## email_id
* email_id
  - utter_email_id

## explain
* explain
  - action_intent

## diff_domains
* diff_domains
  - action_intent

## New Story
* greet
    - action_greet
* greet
    - action_greet
* thanks
    - utter_noworries
    - utter_anything_else
* goodbye
    - utter_goodbye

## restart
* restart
    - action_restart

## New Story

* greet
    - action_greet
* greet
    - action_greet
* greet
    - action_greet
* affirm
    - utter_default_fallback
* greet
    - action_greet

## New Story

* greet
    - action_greet
    - slot{"shown_privacy":true}

## New Story

* happy
    - utter_happy

## New Story

* greet
    - action_greet
    - slot{"shown_privacy":true}
* happy
    - utter_happy
* happy
    - utter_happy
* affirm
    - action_intent
* goodbye
    - utter_goodbye
* identity
    - utter_identity
* email_id
    - utter_email_id
* onboarding_info
    - action_intent
* onboarding_info
    - action_intent
* registration_info
    - action_intent
* customer_support
    - utter_customer_support
