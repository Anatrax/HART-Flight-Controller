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
	<img src="./images/HARTlogo.jpg" width="200px" height="auto"/>
  </a>

  <!-- PROJECT TITLE -->
  <h1 align="center">OSU HART Flight Computer Documentation</h1>

  <p align="center">
    <!-- SHORT PROJECT DESCRIPTION -->
    Documentation for the OSU HART Flight Computer
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
This is the documentation for the OSU HART Flight Computer, the student-developed flight computer currently under development.

The documentation is currently under construction.

<a name="about-the-project-built-with"></a>
### Built with
<!-- This section should list any major frameworks that you built your project using. Leave any add-ons/plugins for the Acknowledgements section. Here are a few examples. -->

- [Sphinx][sphinx-install] documentation generator
- [TexLive][texlive-docs] typesetting system for formatting the PDF output

<a name="getting-started"></a>
Getting Started
---------------------
<!-- This is an example of how you may give instructions on setting up your project locally. To get a local copy up and running follow these simple example steps. -->
The documentation is built and deployed automatically using a GitHub Actions workflow. If you want to build the documentation locally, the easiest way is to use the [OSU HART Project Workspace][workspace], which comes with all the necessary dependencies pre-installed. Optionally, you can install the dependencies yourself with the following commands.

<a name="getting-started-prerequisites"></a>
### Prerequisites

- [Python PIP][pip-install]
  ```bash
  $ sudo apt-get install python3-pip
  ```
- [Sphinx][sphinx-install] documentation generator
  ```bash
  $ pip3 install -U sphinx
  ```
  > Make sure `~/.local/bin` is added to PATH
- [GNU Make][make-install]
  ```bash
  $ sudo apt-get install build-essential
  ```
- [recommonmark][recommonmark-install]
  ```bash
  $ pip3 install recommonmark
  ```

If you plan on building LaTeX PDF documentation, you'll also need the following packages:
```bash
$ sudo apt-get install texlive-latex-recommended texlive-fonts-recommended texlive-latex-extra latexmk
```

<a name="getting-started-installing"></a>
### Installing
1. Clone the official repository
    ```bash
    $ git clone https://github.com/HART-Avionics/OSU-HART-Flight-Controller.git
    ```

<a name="usage"></a>
Usage
--------
<!-- Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.<br> -->
The manual documentation is written mostly in Markdown, but Sphinx also has it's own default markup format called reStructuredText which can also be used for generating documentation from comments in source code.

The Sphinx configuration is set in [`docs/conf.py`][docs-config-file]. For the full list of available options, see [the official documentation][sphinx-config].

Once you're finished making changes, you can build the documentation.

```bash
$ cd docs
$ make build
```

Sphinx will generate both HTML & LaTeX PDF documentation in the `docs/build/` directory.

You can build the HTML and LaTeX PDF documentation individually with
```bash
$ make html
```
or
```bash
$ make latexpdf LATEXMKOPTS="-silent"
```

*For more examples, please refer to the official [Sphinx documentation][sphinx-docs]*

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
[workspace]: https://github.com/HART-Avionics/OSU-HART-Project-Workspace "Containerized Worspace for HART tools"
[texlive-docs]: https://www.tug.org/texlive/ "TexLive Documentation"
[pip-install]: https://pip.pypa.io/en/stable/installing/ "Install Python PIP"
[sphinx-install]: https://www.sphinx-doc.org/en/master/usage/installation.html "Install Sphinx"
[make-install]: https://www.gnu.org/software/make/manual/make.html "Instal GNU Make"
[recommonmark-install]: https://github.com/readthedocs/recommonmark "Install recommonmark"
[docs-config-file]: ./config.py "Documentation configuration file"
[sphinx-config]: https://www.sphinx-doc.org/en/master/usage/configuration.html "Configuring Sphinx"
[sphinx-docs]: https://www.sphinx-doc.org/en/master/index.html "Sphinx Documentation"
[license]:../LICENSE "GNU Public License"
[donate-url]: https://osuaiaa.com/donate "Donate"
