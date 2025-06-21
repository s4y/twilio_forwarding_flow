## What is this?

This is a simple _Twilio flow_ that lets you set up a phone number to record a voicemail when someone calls it, and forwards any text messages to you. I initially made it to catch calls to my dad's old phone number, and his name remains in this flow (you'll want to change it!)

## Guide

1. [Make a new flow](https://console.twilio.com/us1/develop/studio/flows?frameUrl=/console/studio/flows) on Twilio and give it a name:

    ![](https://github.com/s4y/twilio_forwarding_flow/blob/docs/images/1_new_flow.png)

2. Leave _Start from scratch_ selected and click _Next_:

    ![](https://github.com/s4y/twilio_forwarding_flow/blob/docs/images/2_new_flow.png)

3. Click on the _Trigger_ box at the top of the flow to select it:

    ![](https://github.com/s4y/twilio_forwarding_flow/blob/docs/images/3_click_trigger.png)

4. Scroll down in the little panel on the right and click _Show Flow JSON_:

    ![](https://github.com/s4y/twilio_forwarding_flow/blob/docs/images/4_show_json.png)

5. Paste the contents of [this file](https://raw.githubusercontent.com/s4y/twilio_forwarding_flow/refs/heads/main/twilio_forwarding_flow.json) into the box and then click _Save_:

    ![](https://github.com/s4y/twilio_forwarding_flow/blob/docs/images/5_save_json.png)

6. One at a time, click each of the these two nodes and change the phone numbers in _Advanced configuration_ to your own:

    ![](https://github.com/s4y/twilio_forwarding_flow/blob/docs/images/6_nodes_to_change.png)

    ![](https://github.com/s4y/twilio_forwarding_flow/blob/docs/images/7_configuration_to_change.png)

7. Change anything else you'd like to (like the messages) and save the flow, then assign it to a phone number!
