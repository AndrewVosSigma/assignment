# Sigma - JS assignment

### Custom event emitter
You are one of the open source library maintainers. Your job is to add the new highly anticipated functionality - a custom event emitter. Below you will find the email you have received from the main contributor. He/she wants the code to be fully functional and tested properly. 

Please, treat the e-mail as acceptance criteria in scope of this task.

* From: @a.williams@gmail.com
* Topic: Custom event emitter
* Hey there! How are the things going? :) You've probably heard the community wants to have this simple event emitter available, so we should deliver. Nothing fancy for now, the following should do:
    * A user should be able to subscribe to a certain event, event name can be a string only
    * A user should be able to unsubscribe from an event
    * A user should be able to emit an event
    * When subscribing you should be able to specify a number of times the callback should be invoked
    * When removing the event, the calls counter from above should be reset, even if we subscribe to the very same event later
* I hope you have a lovely weekend ahead, talk to you soon, mate!

* P.S.: in case you won't be able to implement all of the functionality/tests in scope, leave a comment(s) with your next steps so that Robin can take over.

Please, have the following in mind:

* external libraries usage is not allowed - Jest should do in terms of tests and JavaScript has all the functionality required out of the box
* this is an open source library (utility oriented) where you are not aware of the exact context the code is being used in
* we suggest not spending time on using TypeScript here, since the class does not have a lot of functionality and the types are not yet an absolute necessity
* you can organize the tests the way you want. Remember - other contributors might not be familiar with this functionality and they should be able to understand what's going on, otherwise the library development can get hindered!

Good luck!



