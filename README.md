# ComShare

## About
This web app aims at building a community inside any local area network for sharing movies,music and other files along with books and other things that can be shared with people on or off wires. It is complete with chatting and posting functionality. A user can post his need on a forum which everybody can view. On creation, each user is given a starting point value of 1200 which can increase as the file sharing goes on. Posts are ordered according to the points of the user who posted his need, and so the need of an active sharer is put at the top. Points are distributed on the basis of Elo Rating system thus providing an incentive for people to share more (their needs are at the top of the posts section and lower rated people get greater benefits by sharing with them). They can also dicuss about movies and give suggestions to each other. Users can also chat with each other.

This app has been built on a Node.JS Server with a MongoDB Server mongodb://ds046267.mlab.com:46267/comshare. This page uses socket to transfer information and so it must not be refreshed while usage. WebRTC is used for establishing a peer to peer connection for transfer of files over the LAN or same wifi.
There are two dummy users on the system named- 
Ayush (username ayush password ayush)
Rajas (username rajas password rajas)

## Deployment
The app has been deployed at [https://comshare.herokuapp.com/]
-----------------------------------------------------------------------------------------
## Requirements
1. Need to have Node.js installed
2. npm


## Getting Started: 
1. Get a copy of the source by cloning it downloading a zip.
2. Navigate to the root.
3. Install the required packages and run the server.
4. ```bash
	npm install
	node server.js
   ```
5. Navigate to (http://localhost:7000/)

-------------------------------------------------------------------------------------------------------------------------------------------

