In terms of intents there are two main security risks:

- When a trusted app is using intents, a malicious app may try and recieve an intent that was not intended for it.
This could mean passing crucial and private information to the malicious app such as bank account information, 
social security numbers, etc. This can also result in the malicious app being run in place of the intended app.
The malicious app is then free to start its functions without having to have the user open it. This will result in
the malicious app opening in place of the intended app, which could open the door to more malicious activites
such as making people sign in with other account information thinking that they are on the right intended app.

- There is also another main way intents can cause security risks. A malicious app can forge intents and make 
strange, undesired behaviors occur on the users system. This is called intent spoofing. From this project we learned 
how easy it was to start phone calls, so the malicious app could spoof these intents and make random calls at random 
times. There is a large number of insecurities that intent spoofinging attacks could target allowing a large window
of information they could obtain or change. 