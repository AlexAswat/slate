```shell
curl --request POST \
  --url https://mule.aswat.co/call \
  --header 'api_key: YOUR-API-KEY-HERE' \
  --header 'cache-control: no-cache' \
  --header 'content-type: application/json'
  --data '{"call":{"name": "basic test","destination": "SIP/ziwo/1234","duration": 120,"dtmf_attented": true,"Language": "EN","mail":"notification@aswat-telecom.com","callerid":"0642424242","scenarios": [{"step": 1,"action": "wait","time": 8,"argument": null},{"step": 2,"action": "dtmf","time": null,"argument": 1},{"step": 3,"action": "wait","time": 6,"argument": 1},{"step": 4,"action": "playaudiofile","argument": "audiofile-testing","time": 110}]}}'
}
```