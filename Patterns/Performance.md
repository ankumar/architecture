Service that always responds in 100ms, except for 5 minutes of every hour where it stalls completely(TCP connection and HTTP request will be accepted, but the response will be provided at the end of the 5 minute stall). If a serial client (i.e. it sends a request, waits for it to finish, sends next) is monitoring latency, what 99th percentile does it measure? 

**- About 300s**

Same service, but with a client sending requests every 1s whether the last one has completed or not. What 99th percentile latency does it see? 

**- About 110ms**

Same service, serial client with a 1s request timeout. What 99th percentile latency does it measure? 

**- About 1s**
