### <u>Request</u>

`POST https://mule.aswat.co/call

### <u>Request Headers</u>

Parameter | Type | Mandatory | Description
--------- | ------- | ------- | -----------
api_key | string | true | The api_key assigned to access the platform

### <u>Request Body (JSON)</u>

Parameter | Type | Mandatory | Description
--------- | ------- | ------- | -----------
call.destination | string | true | Destination number or destination SIP `E.g.: 0033642424242 or SIP/ziwo/0033642424242`
call.language | string | true | Audio file and notification language `E.g. : FR / EN / AR`
call.scenario.step | number | true | Number of step
call.scenario.action | string | true | Type of action `['wait','playaudiofile','dtmf']`
call.scenario.time | string | true | time of the action
call.scenario.argument | number | true | argument of action
call.mail | string | false | Email notification
call.callerid | string | false | Email notification
