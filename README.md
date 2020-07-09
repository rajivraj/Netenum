<h1 align="center"> Netenum </h1> <br>

<p align="center">
  <a>
    <img alt="Netenum" title="Netenum" src="logo.png">
  </a>
</p>

<p align="center">
  Network reconnaisance tool that sniffs for active hosts
</p>

![Language](https://img.shields.io/badge/Language-Python-blue.svg?longCache=true&style=flat-square)   ![License](https://img.shields.io/badge/License-MIT-purple.svg?longCache=true&style=flat-square)   

## Introduction
Netenum passively monitors the ARP traffic on the network. It extracts basic data about each active host, such as IP address, MAC address and manufacturer. The main objective of this tool is to find active machines without generating too much noise.


## Features

* Provides basic information about the network, such as ESSID and current signal strength.
* Found hosts can be written to a file (next we can use Nmap's `-iL <hosts_file>` option to scan detected hosts).
* Shows a signature next to the IP address indicating that the host is a local gateway:`(G)`.


## Screenshot
<p align="center">
  <a>
    <img src="screen.png">
  </a>
</p>


## License
This software is under [MIT License](https://en.wikipedia.org/wiki/MIT_License)


