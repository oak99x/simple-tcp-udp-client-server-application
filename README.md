# TCP and UDP Client/Server Applications  

#### Students:  
#### Gustavo Geyer Arrussul Winkler dos Santos  
#### Mateus de Carvalho de Freitas  

## Description  
This repository contains two example client/server applications implemented using the TCP and UDP protocols. The applications are designed to enable communication between a client and a server within a local network.  

## Features  

### TCP and UDP Client/Server Application  
- The client can connect to a server (TCP or UDP) on the network.  
- Clients can send chat messages to the server.  
- The server retransmits messages to connected clients, enabling group chat communication.  

## Requirements  
- Python 3.x  
- Python socket library  

## Running the Applications  
- Run the corresponding server (TCP or UDP) on a machine in the network.  
- Run the corresponding client (TCP or UDP) on another machine or the same local machine to test communication.  

Note: The default host for the client is set to `localhost`. To run it on a different machine, check the `IP` of the machine running the server and update it in the client configuration.  

## Usage Examples  
- Run `python servidor.py` on one machine as the TCP server.  
- Run `python cliente.py` on another machine or the same local machine to connect to the TCP server.  

