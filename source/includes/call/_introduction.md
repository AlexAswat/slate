## Launch call

This endpoint initiates a call on behalf of an agent. 
The platform will first automatically ring the agent's device and only when the agent picks up the call, outgoing call leg is connected.

A `callID` is returned from the request which can be used to follow the flow of the call and also get the CDR through it in the future.