# ChattingAppInJava
Simple Text Chatting Application using Datagrams with Java Programming
Description of the project: - This project is a Simple GUI Based Chatting Application written in java using Java Datagrams. Datagrams are bundles of information passed between machines. Datagram Transmission is Unreliable Transmission. Java implements Datagrams on top of UDP (User Datagram Protocol) by using two classes:
⦁	DatagramPacket: - This Object is the data container. 
⦁	DatagramSocket: - This Object is the mechanism used to send or receive the DatagramPackets. It defines two standard methods:
⦁	Send(DatagramPacket packet): used to send DatagramPacket.
⦁	Receive(DatagramPacket packet): used to receive DatagramPacket.
These classes are under the package of java.net.* 
	In order to send data and receive data concurrently, two threads have been used:
⦁	Send(): Thread used to send a Datagram Packet to the intended destination.
⦁	Receive(): Thread used to receive a Datagram Packet.
