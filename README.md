Project demonstrating that a `client.close()` command interrupt a `producer.sendAsync()`instruction.

Instructions:
- first run `./gradlew run` to launch consumer
- then run `./gradlew client` to produce a message

no message should be receive by the consumer. 

A message appears only if you use `producer.send` instead of `producer.sendAsync` in `Client`