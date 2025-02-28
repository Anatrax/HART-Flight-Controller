<!-- GitHub Badges/Shields -->
<!-- See https://shields.io/ for more options. -->
[![CI/CD][cicd-shield]][cicd-url]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![License][license-shield]][license-url]
-----
<br />
<p align="center">
  <!-- PROJECT LOGO -->
  <a href="https://osuaiaa.com/hart">
	<img src="https://images.squarespace-cdn.com/content/v1/5a19a459e5dd5b3614fc8595/1518733757123-JZ5199GBQVQOEJBC9VKR/ke17ZwdGBToddI8pDm48kOx9thYkxoPEJMHoJ7vUPbh7gQa3H78H3Y0txjaiv_0fDoOvxcdMmMKkDsyUqMSsMWxHk725yiiHCCLfrh8O1z5QHyNOqBUUEtDDsRWrJLTmS0k9nmfOWkBD2X4dgpGrpWVYQT8AbCbINUUJycgJH0K3YOIy-qewO29_jEB_UvA_/HARTlogo.jpg" width="200px" height="auto"/>
  </a>

  <!-- PROJECT TITLE -->
  <h1 align="center">OSU HART Flight Computer</h1>

  <p align="center">
    <!-- SHORT PROJECT DESCRIPTION -->
    The OSU HART Flight Computer is the student-developed flight computer currently under development
    <br />
    <!-- LINK TO DOCUMENTATION -->
    <a href="https://hart-avionics.github.io/OSU-HART-Flight-Controller/"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <!-- LINK TO DEMO
    <a href="INSERT LINK TO DEMO HERE">View Demo</a>
    · -->
    <!-- LINK TO ISSUES -->
    <a href="https://github.com/HART-Avionics/OSU-HART-Flight-Controller/issues">Report Bug</a>
    ·
    <!-- LINK TO ISSUES -->
    <a href="https://github.com/HART-Avionics/OSU-HART-Flight-Controller/issues">Request Feature</a>
  </p>
</p>

Table of Contents
---------------------
- [About the Project](#about-the-project)
  - [Built with](#about-the-project-built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#getting-started-prerequisites)
  - [Installing](#getting-started-installing)
- [Usage](#usage)
- [Roadmap](#roadmap)
<!--
- [FAQ](#faq)
-->
- [Contributing](#contributing)
- [License](#license)
- [Contacts](#contacts)
- [Support the Project](#donate)
<!--
- [Acknowledgements](#acknowledgements)
-->

<a name="about-the-project"></a>
About the Project
---------------------
<!-- Description of the project and it's intended purpose or origin story. -->
The OSU HART Flight Computer is the student-developed flight computer currently under development.

This project is currently under construction.

<a name="about-the-project-built-with"></a>
### Built with
<!--
This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the Acknowledgements section. Here are a few examples:
- [Sphinx](https://www.sphinx-doc.org/en/master/usage/installation.html) documentation generator
- [TexLive](https://www.tug.org/texlive/)
-->

- [EasyEDA][easyeda]
- 

<a name="getting-started"></a>
Getting Started
---------------------
<!-- This is an example of how you may give instructions on setting up your project locally. To get a local copy up and running follow these simple example steps. -->

<a name="getting-started-prerequisites"></a>
### Prerequisites

- [Bill of Materials (BOM)][bom]

<a name="getting-started-installing"></a>
### Installing
1. Clone the official repository
    ```bash
    $ git clone https://github.com/HART-Avionics/OSU-HART-Flight-Controller.git
    ```
2. Open [EasyEDA Designer][easyeda-designer]
3. Create an new schematic in EasyEDA: `File>New>Schematic`
4. Go to `File>FileSource` and copy & paste in the contents of [`Student_Flight_Board.json`][easyeda-file]
5. Click `Apply` to apply the changes
6. `File>Save` the EasyEDA project

<a name="usage"></a>
Usage
--------
<!-- Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.<br> -->
Once the PCB design has been completed, you can send parts lists and gerber files to JLCPCB by selecting `Fabrication>Parts Order` or `Fabrication>PCB Order` in EasyEDA.

![OSU HART Flight Controller Schematic][schematic]

<a name="roadmap"></a>
Roadmap
----------
See the [open issues][issues-url] for a list of proposed features (and known issues).

<!--
<a name="faq"></a>
FAQ
----
-->

<a name="contributing"></a>
Contributing
---------------
Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the project
2. Create your feature branch (`git checkout -b username/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin username/amazing-feature`)
5. Open a pull request onto the `develop` branch of the official repository

<a name="license"></a>
License
-----------
Distributed under the GNU Public License. See [`LICENSE`][license] for more information.

<a name="contacts"></a>
Contacts
-----------
<!-- Your Name - @your_twitter - example@example.com -->
**Maintainer**: Samuel D. Villegas - villegsa@oregonstate.edu

<a name="donate"></a>
Support the Project
--------------------
[Donate to HART][donate-url]
<!--
<a name="acknowledgements"></a>
Acknowledgements
-----------------
- [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
- [Img Shields](https://shields.io)
- [Choose an Open Source License](https://choosealicense.com)
- [GitHub Pages](https://pages.github.com)
- [Animate.css](https://daneden.github.io/animate.css)
- [Loaders.css](https://connoratherton.com/loaders)
- [Slick Carousel](https://kenwheeler.github.io/slick)
- [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
- [Sticky Kit](http://leafo.net/sticky-kit)
- [JVectorMap](http://jvectormap.com)
- [Font Awesome](https://fontawesome.com)
-->

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[cicd-shield]: https://github.com/HART-Avionics/OSU-HART-Flight-Controller/workflows/CI/CD/badge.svg?branch=develop
[cicd-url]: https://github.com/HART-Avionics/docs/actions "CI/CD"
[contributors-shield]: https://img.shields.io/github/contributors/HART-Avionics/OSU-HART-Flight-Controller
[contributors-url]: https://github.com/HART-Avionics/OSU-HART-Flight-Controller/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/HART-Avionics/OSU-HART-Flight-Controller
[forks-url]: https://github.com/HART-Avionics/OSU-HART-Flight-Controller/network/members
[stars-shield]: https://img.shields.io/github/stars/HART-Avionics/OSU-HART-Flight-Controller
[stars-url]: https://github.com/HART-Avionics/OSU-HART-Flight-Controller/stargazers
[issues-shield]: https://img.shields.io/github/issues/HART-Avionics/OSU-HART-Flight-Controller
[issues-url]: https://github.com/HART-Avionics/OSU-HART-Flight-Controller/issues
[license-shield]: https://img.shields.io/github/license/HART-Avionics/OSU-HART-Flight-Controller
[license-url]: https://github.com/HART-Avionics/OSU-HART-Flight-Controller/blob/main/LICENSE
[easyeda]: https://easyeda.com/ "EasyEDA"
[bom]: ./src/BOM_Student_Flight_Board.csv "Bill of Materials"
[easyeda-designer]: https://easyeda.com/editor# "EasyEDA Designer"
[easyeda-file]: ./src/Student_Flight_Board.json "EasyEDA file"
[schematic]: ./docs/images/Schematic_Student_Flight_Board.png "OSU HART Flight Controller Schematic"
[license]: ./LICENSE "GNU Public License"
[donate-url]: https://osuaiaa.com/donate
