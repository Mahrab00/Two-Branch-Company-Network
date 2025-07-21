# Two-Branch Company Network with Centralized Services

Hi, I am Mahrab Hossain.

This project, created in Cisco Packet Tracer, demonstrates the network architecture of a company with two separate branches. The network is managed by centralized DHCP and HTTP servers.

## Network Topology Overview

Here is an overview of the network topology:

[Network Diagram](network-topology.png)

## Key Features

*   **Two Separate Branches:** The network is divided into two main branches, Branch 1 (B1) and Branch 2 (B2), connected via routers.
*   **Centralized Servers:** Both branches are served by a central server location that provides:
    *   **DHCP Services:** Dynamically assigns IP addresses to devices within each department's subnet.
    *   **HTTP Services:** Hosts a central web server accessible from both branches.
*   **Departmental Subnets:** Each branch is further segmented into departments (e.g., Employ, Security, IT, Marketing), each on its own subnet. This improves security and network management.
*   **Wireless Access:** The Marketing departments in both branches are equipped with wireless access points for laptop connectivity.

## Branch 1 (B1) Structure

*   **Employ Department B1:** Gateway `192.168.2.33/27`, DNS `192.168.1.10/24`
*   **Security Department B1:** Gateway `192.168.2.65/27`, DNS `192.168.1.10/24`
*   **IT Department B1 Group1:** Gateway `192.168.2.97/27`, DNS `192.168.1.10/24`
*   **Marketing Department B1 (Wireless):** Gateway `192.168.2.129/27`, DNS `192.168.1.10/24`

## Branch 2 (B2) Structure

*   **Employ Department B2:** Gateway `192.168.3.33/27`, DNS `192.168.1.10/24`
*   **Security Department B2:** Gateway `192.168.3.65/27`, DNS `192.168.1.10/24`
*   **IT Department B2:** Gateway `192.168.3.97/27`, DNS `192.168.1.10/24`
*   **Marketing Department B2 (Wireless):** Gateway `192.168.3.129/27`, DNS `192.168.1.10/24`

## Server Configuration

*   **Server-PT (DHCP and HTTP):** IP `191.168.1.2/24`, Gateway `192.168.1.1/24`
*   **Server-PT (DNS):** IP `191.168.1.10/24`, Gateway `192.168.1.1/24`

## How to Use This Project

1.  Download and install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer).
2.  Clone this repository or download the `.pkt` file.
3.  Open the `.pkt` file in Cisco Packet Tracer to explore the network configuration and run simulations.

### Fun Tips for Students

Here are some ideas to explore and expand upon this project:
*   Go to the HTTP server in the project. Use the "HTML" tab to edit the web page with some basic HTML.
*   After editing, try to access your custom web page from a PC in any of the departments in either branch.
*   Think of other services you could add to the central servers!

This project is a great starting point for exploring new ideas and improving its capabilities.

## Contribution

Feel free to use this project and suggest improvements by creating a pull request.