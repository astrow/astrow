#Astrow

We have forked the waterbug project thanks to @codefoster. 

We are using Azure Server for our cloud needs and the Intel Edison devkit for our hardware needs.

The following is legacy information from the waterbug project:


#project status
The bulk of the work is likely to be in the UI - that is the [waterbug-client project](http://github.com/codefoster/waterbug-client). It's written in Angular 2.0.
The server component ([waterbug-server](http://github.com/codefoster/waterbug-server)) is currently very simple and only acts as a socket server passing all messages to all other clients. It's essentially a passthru.
The device component is not well tested yet. Rowing strokes can be simulated in the UI, so there's no need to have actual rowers to work on the project.
