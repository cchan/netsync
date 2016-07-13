Netsync
=======

The idea is to create a networked game setup where I can plug in user input 
and have it sent across in an efficient way, where lag, cheating, etc. are 
taken into account, with queueing and server authoritative simulation and 
all of that.

Some potential sources:
- https://developer.valvesoftware.com/wiki/Source_Multiplayer_Networking
- https://www.codeofhonor.com/blog/choosing-a-game-network-lib
- https://www.reddit.com/r/gamedev/comments/1tvbe0/is_it_just_me_or_is_networking_really_hard/

In the end this is more of a side project than an actual push to make some 
massively scalable network system, but hey, Open Source is awesome.

General timeline
----------------

- [ ] Design a really basic dumb client thing where you just have the server 
      take input from the dumb client and send data right back to be rendered
      (this will be the first of multiple networking modes available here)
- [ ] Make some basic moba or something on this
- [ ] Start making some more complex client-server setups

