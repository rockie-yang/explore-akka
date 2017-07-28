# Hello World

A Hellow world example with AKKA

1. Main start an Actor HelloWorld
1. Hello.preStart send a message Greeter.Greet to Greeter
1. Greeter receive the Greeter.Greet message and send back Greeter.Done message
1. HelloWorld Reived Greeter.Done message and stop the context
