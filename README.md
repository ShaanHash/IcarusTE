<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/shaanhash/IcarusTE">
    <img src="logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Icarus</h3>

  <p align="center">
    A simple terminal based text editor written in Rust
    <br />
    <a href="https://github.com/shaanhash/IcarusTE"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/shaanhash/IcarusTE/issues">Report Bug</a>
    ·
    <a href="https://github.com/shaanhash/IcarusTE/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
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
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](screenshot.png)

Icarus is a simple terminal based text editor similar to Nano or Vim, written in Rust. It's fast, performative, and lightweight. It lets you quickly edit text files directly from the command line with common vim-like shortcuts. Written entirely in Rust, Icarus requires no external dependencies and works on multiple Operating Systems.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

[![Rust][Rust]][Rust-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Icarus can be built from source or you can use one of the prebuilt binaries offered under the releases section.

### Prerequisites

If you are building Icarus from source you will need Cargo and Rust.

* Ubuntu
  ```sh
  curl https://sh.rustup.rs -sSf | sh
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/shaanhash/IcarusTE.git
   ```
2. Build the binary
   ```sh
   cargo build --release
   ```
3. Add the Binary to your $PATH or execute directly with
   ```sh
   cargo run
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

If Icarus is on your $PATH
```sh
icarus <file-name>
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [X] Initial Build
- [X] Performance Upgrades
- [X] Search
  - [ ] Advanced Searching
- [ ] Syntax Highlighting
    - [ ] Rust

See the [open issues](https://github.com/github_username/repo_name/issues) for a full list of proposed features (and known issues).

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Shaan H - [@ShaanHashmi.com](https://shaanhashmi.com)

Project Link: [https://github.com/shaanhash/IcarusTE](https://github.com/shaanhash/IcarusTE)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Phillip Flecker](https://www.flenker.blog/about/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/shaanhash/IcarusTE.svg?style=for-the-badge
[contributors-url]: https://github.com/shaanhash/IcarusTE/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/shaanhash/IcarusTE.svg?style=for-the-badge
[forks-url]: https://github.com/shaanhash/IcarusTE/network/members
[stars-shield]: https://img.shields.io/github/stars/shaanhash/IcarusTE.svg?style=for-the-badge
[stars-url]: https://github.com/shaanhash/IcarusTE/stargazers
[issues-shield]: https://img.shields.io/github/issues/shaanhash/IcarusTE.svg?style=for-the-badge
[issues-url]: https://github.com/shaanhash/IcarusTE/issues
[license-shield]: https://img.shields.io/github/license/shaanhash/IcarusTE.svg?style=for-the-badge
[license-url]: https://github.com/shaanhash/IcarusTE/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/shaanhashmi
[product-screenshot]: screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
[Rust]: https://img.shields.io/badge/rust-000000?style=for-the-badge&logo=rust&logoColor=white
[Rust-url]: https://www.rust-lang.org/
