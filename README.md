# Network Topology Server-Client Project

## Project Description

This project demonstrates a simple client-server network topology created using GNS3.
The goal of the project is to allow client machines to access a website hosted on a server.

At the beginning, the server was connected to a **NAT network** in order to install the required packages.
After installing the packages, the NAT connection was removed and the server was connected directly to the clients in the network.

---

## Network Topology

![Network Topology](<the project \&Screenshot for it/Network Topology.png>)

This image shows the network topology created in GNS3 and how the server and the clients are connected.

---

## Clients Used in the Project

Two different clients were used to test the connection with the server:

* **Ubuntu Client**
  A Linux-based client with a **graphical interface (GUI)** used to access the website through a browser.

* **VPCS Client**
  A lightweight **command-line client** used to test network connectivity (such as ping and basic network configuration).

Both clients were used to verify that the server can communicate correctly with different types of machines.

---

## Server and Client Connection

![Server and Client](<the project \&Screenshot for it/server & client.png>)

This screenshot shows the configured connection between the server and the clients.

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

This image shows that the Ubuntu client successfully accessed the website hosted on the server.

---

## GNS3 Project File

`web_test.gns3`

This file contains the complete network topology used in the project.

---

## Steps Summary

1. Create the network topology in GNS3.
2. Connect the server to NAT to install required packages.
3. Disconnect the NAT network.
4. Connect the server to two clients (Ubuntu and VPCS).
5. Run the web service on the server.
6. Access the website from the Ubuntu client and test connectivity using VPCS.

---

## Result

The clients were able to successfully communicate with the server.
The Ubuntu client accessed the hosted website, while the VPCS client was used to verify network connectivity through command-line tools.

