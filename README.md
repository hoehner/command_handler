# CommandHandler
A LabVIEW Actor that builds on the Command Pattern to sequence through multiple steps/commands as part of sequence.

The Actor Framework is already based on the command pattern under the hood, but this library gives the user more control over when those commands are executed and uses an Actor as the "controller"

This Actor also leverages a broadcast template that allows the Actor caller (another actor, or a regular VI) to register/subscribe to the Command Handler Actors event data. 
