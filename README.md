# Network Topology Server-Client Project

## Project Description

This project demonstrates a simple client-server network topology created using GNS3.
The goal of the project is to configure a server and a client so the client can access a website hosted on the server.

The server was first connected to a NAT network to download the required packages. After installing the packages, the NAT connection was removed and the server was connected directly to the client.

---

## Network Topology

![Network Topology](<the project \&Screenshot for it/Network Topology.png>)

This image shows the network topology created in GNS3 and how the server and client are connected.

---

## Server and Client Connection

![Server and Client](<the project \&Screenshot for it/server & client.png>)

This screenshot shows the connection between the server and the client after configuring the network.

---

## Server Terminal

![Server Terminal](<the project \&Screenshot for it/Server Terminal.png>)

This image shows the server terminal after installing the required packages and running the web server.

---

## Website on the Server

![Website on Server](<the project \&Screenshot for it/the website on server.png>)

This screenshot shows the website running locally on the server.

---

## Website on the Client

![Website on Client](<the project \&Screenshot for it/the website on client.png>)

This image shows that the client can successfully access the website hosted on the server.

---

## GNS3 Project File

`web_test.gns3`

This file contains the full network topology used in the project.

---

## Steps Summary

1. Create the network topology in GNS3.
2. Connect the server to NAT to install required packages.
3. Disconnect the NAT network.
4. Connect the server directly to the client.
5. Run the web service on the server.
6. Access the website from the client.

---

## Result

The client successfully accessed the website hosted on the server, confirming that the client-server communication works correctly.
