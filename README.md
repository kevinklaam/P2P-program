# P2P-program

In this project, we build a P2P (Peer-to-Peer) application. The will consists of an index server
and multiple peers. An index server will host the ip addresses and filenames of individual items.
Peers can exchange content among themselves using the names and IPs the index server
provides. A peer can register a file to be available for download by other peers. A peer that
wants to download a file can contact the index server for information about another peer, a
transfer between peers can then be made. The communication between the index server and a
peer is based on UDP packets while the content download is based on TCP packets.

P2P server and client in C on Linux for computer networks course project

compile with gcc -o 
run on two linux platforms
