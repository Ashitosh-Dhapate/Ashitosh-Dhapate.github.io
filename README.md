#Peer to Peer File Sharing Protocol

##Team Members: Aman Chaudhari, Akarsh Bolar, Ashitosh Dhapate, Kishan Kanyar, Mohit Mayank, Vignesh Somasundaram

##Problem Statement:

Implement BitTorrent protocol based on the whitepaper published by Bram Cohen[1].
Implement this P2P file sharing protocol from scratch with seeding and leeching in python with performance as a priority (using asynchronous library asyncio).
Integrating using publicly hosted trackers for .torrent file sharing.
Testing and validating file hashes in virtual environment.
Motivation:

To explore and understand the internals of a peer-to-peer protocol: BitTorrent
Run our implementation of the protocol using virtual peers in Mininet
Learn in depth about P2P file sharing.
Challenges:

Implementing leeching and seeding in the same client.
Adding priority queue for connecting with peers.
Deploying our application in mininet environment.
Testing against other clients such as qbit-torrent & utorrent in different envirnoments and with different bandwidths.
Results:

After successful deployment of our P2P client on mininet we tested for downloading speed of our client against popular client utorrent and the most used open source client qbit-torrent and we observed that results were in par with the other clients with respect to the downloading speed.The qbit-torrent turned out to be superior in our experiment. The following figure shows the above mentioned results:

