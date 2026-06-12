# BiggusShipus

<p align="center">
    <img src="images/BiggusShipusLogo.png" alt="image" />
    <br />
    <img src="https://img.shields.io/static/v1?label=Project&amp;message=Home%20Lab%20Cloud&amp;color=2E3440&amp;style=flat-square" alt="Project: Home Lab Cloud" />
    <img src="https://img.shields.io/static/v1?label=Hardware&amp;message=Raspberry%20Pi%204&amp;color=C51A4A&amp;logo=raspberrypi&amp;logoColor=white&amp;style=flat-square" alt="Hardware: Raspberry Pi 4" />
    <img src="https://img.shields.io/static/v1?label=RAM&amp;message=4%20GB&amp;color=2EA44F&amp;style=flat-square" alt="RAM: 4 GB" />
    <img src="https://img.shields.io/static/v1?label=OS&amp;message=Raspberry%20Pi%20OS%20%2864-bit%29&amp;color=FCC624&amp;logo=linux&amp;logoColor=white&amp;style=flat-square" alt="OS: Raspberry Pi OS (64-bit)" />
    <img src="https://img.shields.io/static/v1?label=Runtime&amp;message=Docker&amp;color=2496ED&amp;logo=docker&amp;logoColor=white&amp;style=flat-square" alt="Runtime: Docker" />
    <img src="https://img.shields.io/static/v1?label=Ingress&amp;message=Traefik&amp;color=24A1C1&amp;logo=traefikproxy&amp;logoColor=white&amp;style=flat-square" alt="Ingress: Traefik" />
    <img src="https://img.shields.io/static/v1?label=DNS&amp;message=Pi-hole&amp;color=96060C&amp;logo=pihole&amp;logoColor=white&amp;style=flat-square" alt="DNS: Pi-hole" />
    <img src="https://img.shields.io/static/v1?label=Services&amp;message=Network%20and%20Office&amp;color=6C5CE7&amp;style=flat-square" alt="Services: Network and Office" />
</p>

<h3 align="center">
    Self-hosted Raspberry Pi 4 home cloud with Docker, Traefik, Pi-hole, and office services.
</h3>

## Overview

> This repository is intended as portfolio documentation and does not contain any deployment files.

The project is called **BiggusShipus**, a lighthearted reference to [*Monty Python's Life of Brian*](https://en.wikipedia.org/wiki/Monty_Python's_Life_of_Brian). The name gives the home cloud a more personal identity, while the technical focus of the project remains on practical self-hosting, containerized services, and network infrastructure.

BiggusShipus is a Raspberry Pi 4 based self-hosted home cloud designed to provide private network and office services in a compact, low-power environment. It runs on headless Raspberry Pi OS 64-bit and uses Docker to isolate, deploy, and manage the individual services.

Traefik acts as the central ingress and reverse proxy for containerized web services, while Pi-hole provides DNS-based ad blocking and local name resolution. Additional applications such as Paperless and Stirling-PDF extend the setup with document management and PDF automation features.

The system is designed to be modular and maintainable, so services can be added, removed, or replaced without changing the overall infrastructure concept.
