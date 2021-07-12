[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<br />

<p align="center">
  <a href="https://github.com/jjuarez/podman-on-macos">
    <img src="docs/images/vagrant-logo-hashicorp.svg" alt="Vagrant Logo" width="300" height="100">
  </a>

  <h3 align="center">Vagrant Ansible LAB</h3>

  <p align="center">
    An Quick lab using Vagrant and ansible local!
    <br />
    <a href="https://github.com/jjuarez/podman-on-macos/docs"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/jjuarez/podman-on-macos/issues">Report Bug</a>
    ·
    <a href="https://github.com/jjuarez/podman-on-macos/issues">Request Feature</a>
  </p>
</p>

<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## 📘 About The Project

This project is just a lab to be able to use [podman](https://podman.io/) in an easy way working over a macOS


### 🛠 Built With

The project in strongly based on these following tools:

  * [Vagrant](https://www.vagrantup.com)
  * [ansible](https://www.ansible.com/)
  * [Fedora](https://getfedora.org/)


## 🛫 Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.


### Prerequisites

To work with this project you need to have installed [Vagrant](https://vagrantup.com) an its default provider, as you might know this is [VirtualBox](https://www.virtualbox.org/) 


### Installation

  1. Install the software pre-requisites
  2. Clone the repo
     ```shell
     git clone https://github.com/jjuarez/podman-on-macos.git
     ```
     
## 🔌 Usage

The example of use for this lab is extremely easy, just run the Virtual Machine
  ```shell
  vagrant up
  ```
### Configuration & Customization

All the configuraiton in this project is located at the podman role, you can override the variables as you whish


## 🏘 Roadmap

See the [open issues](https://github.com/jjuarez/podman-on-macos/issues) for a list of proposed features (and known issues).


## 🥼Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

  1. Fork the Project
  2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
  3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
  4. Push to the Branch (`git push origin feature/AmazingFeature`)
  5. Open a Pull Request


## 🔖 License

Distributed under the MIT License. See [`LICENSE`](./LICENSE.txt) for more information.


## ✉️ Contact

Your Name - [@thejtoken](https://twitter.com/thejtoken) - javier.juarez@gmail.com
Project Link: [https://github.com/jjuarez/podman-on-macos](https://github.com/jjuarez/podman-on-macos)


[contributors-shield]: https://img.shields.io/github/contributors/jjuarez/podman-on-macos.svg?style=for-the-badge
[contributors-url]: https://github.com/jjuarez/podman-on-macos/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/jjuarez/podman-on-macos.svg?style=for-the-badge
[forks-url]: https://github.com/jjuarez/podman-on-macos/network/members
[stars-shield]: https://img.shields.io/github/stars/jjuarez/podman-on-macos.svg?style=for-the-badge
[stars-url]: https://github.com/jjuarez/podman-on-macos/stargazers
[issues-shield]: https://img.shields.io/github/issues/jjuarez/podman-on-macos.svg?style=for-the-badge
[issues-url]: https://github.com/jjuarez/podman-on-macos/issues
[license-shield]: https://img.shields.io/github/license/jjuarez/vagrant-ansible.lab.svg?style=for-the-badge
[license-url]: https://github.com/jjuarez/podman-on-macos/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/javierjuarez/
[product-screenshot]: docs/images/screenshot.png

