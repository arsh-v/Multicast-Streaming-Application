## Internet-Radio-Multicasting-Multimedia-Over-IP
This project will function as follows:

1. The client will initiate a join request to the server to join the multicast group.
2. Subsequently, the server will transmit the station list and site information to the client via TCP.
3. Subsequently, the client will connect to the selected station from the station list.
4. All stations will transmit data regardless of whether the client is connected or not. This functionality is incorporated to simulate real-life scenarios, such as television or radio broadcasting data even when there is no receiver connected.
5. When the receiver connects to a particular station, it will begin receiving live-streaming videos from that station.
6. The receiver can pause, resume, change station, or terminate at any given time from the GUI using a thread.
