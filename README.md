# nginx-loadbalancer

<!-- ABOUT THE PROJECT -->
## About The Project

This is a demonstration of load-balancing using nginx, done on one of my previous projects [NodeMailer](https://github.com/RishabhKodes/NodeMailer). In this I have 3 secondary ports to run the server for the webapp, defined in the nginx.conf file. <br>If we have excess load on the primary port the traffic will be directed to any of the load-balancing ports with the help of nginx. Finally, the webapp and the nginx have been integrated on a single server using Docker, specifically Docker-Compose.

### Built With
This is a list of the major frameworks that were used in this project using:-

* [Nginx](https://www.nginx.com/)
* [Docker](https://www.docker.com/get-started)

<!-- GETTING STARTED -->
## Getting Started

### Installation
 
#### Using Docker-Compose
1. Clone the repo
```sh
git clone https://github.com/RishabhKodes/nginx-loadbalancer.git
```
3. Run using docker-compose:
```JS
docker-compose up -d
```

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- CONTACT -->
## Contact Me

**Rishabh Bhandari -** 

[LinkedIn](https://www.linkedin.com/in/rishabh-bhandari-ba5778168/)

[Email](rishabhbhandari6@gmail.com)

[My Website](http://www.rishabhbhandari.me/)

<p align="center">
Made with :heart: <br>
by e33or_assasin
</p>

