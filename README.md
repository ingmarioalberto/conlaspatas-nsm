# conlaspatas-nsm
"Con las patas", is a mexican which is literally translated to "with the legs", and makes reference to something that has been build, and is working, but maybe it will fail soon, or maybe will break tomorrow, or maybe is not working correctly, but appears to be working, said so, "conlaspatas", will be a series of projects that I hope, somebody could help them to be (re)programmed right from the beginning, that is, to have a nice GUI, to improve performance, presentation, or being programmed following good practices.  
NSM, i don't even remember what the term NSM was meant, but it was something like "network map or something"
Description: 
  A program to be able to view a map for incoming, outgoing and local connections to and from an specific server.
What we have now: 
  1. script to map the connections: currently via netstat command (maybe this is not the correct way, and we should modify to use pcap files or somenthing), it's basically a loop for the netstat commands and output information with certain soon to be documented format which contains: source,dest, protocol, source port, dest port, program/app, type of connection (incoming, outgoing, local), reference and stamp.
  2. php script to receive the data and discard repeated infrmation and save to mysql database, script to gather data, installation  and run: (boring...)
     
    https://youtu.be/wVD19tOETtM
  3. php webapp to show the map in the simplest form using the js library: 3d-force-graph which in turn uses three.js

    https://youtu.be/de0-ABQLiik
    
Do you think is worth to be re made?
  
  
