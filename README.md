# KnowDetecor
Detecting Smart Home Automation Application Interference with Domain Knowledge

We converted and anonymized some commercial automation data, and formed annotated Json format.
For example,

'''
{

    "id": "a753cd54-f010-4328-8c69-22a0d38bd1a1",
    "trigger": {
        "conditions": [],
        "events": [
            {
                "devType": "00A",
                "deviceId": "6b3cdd3a-5fa0-435f-a5ef-254783a46525",
                "eventId": "eff4cefc-9dc8-46c0-8e55-7bec9c0c82fe",
                "params": {
                    "capabilityId": "audioPlayState",
                    "command": "pause",
                    "value": "1"
                },
                "prodId": "001T"
            }
        ]
    },
    "actions": [
        {
            "actions": [
                {
                    "actionId": "469fbd2d-ad13-4cae-9486-c8b5a5e7056a",
                    "devType": "00A",
                    "deviceId": "6b3cdd3a-5fa0-435f-a5ef-254783a46525",
                    "params": {
                        "capabilityId": "playMusic",
                        "command": "play",
                        "value": "aiting:5373510"
                    },
                    "prodId": "001T"
                },
                {
                    "actionId": "fbf0e4aa-dd96-4930-ac04-29100ceb3c98",
                    "devType": "00A",
                    "deviceId": "6b3cdd3a-5fa0-435f-a5ef-254783a46525",
                    "params": {
                        "capabilityId": "audioPlayState",
                        "command": "pause",
                        "value": "1"
                    },
                    "prodId": "001T"
                }
            ],
            "delay": {
                "delaySync": false
            }
        }
    ]
}
'''
