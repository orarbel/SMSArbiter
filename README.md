# SMS Arbiter

### Why

  - SMS prices vary with different providers to different countries.
  - There is no reason to use just one provider rather than the cheapest for each indivdiual text message.

### What 

  - A web service that can send SMS by using the cheapest provider for the specific message destination.

### How

  - Extract, transform and load all providers prices into a single database.
  - On text message API request, compare all providers for the message destination.
  - Use the cheapest provider to send the message.
  - Aggregate the savings into a report.

### Where 

  - https://www.github.com/orarbel/SMSArbiter

### Who

  - Or Arbel (or@justyo.co)

