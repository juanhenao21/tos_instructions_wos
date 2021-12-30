# Tree of Science (TOS) instructions

We have no instructions in the home page of [TOS](https://tos.coreofscience.com/). The only way
our users are going to be able to use our product is if they have had training on how to use it.
We currently have about 52 weekly users and they create about 40 trees in the same period. These
are users that need to know exactly what they're doing, if someone would stumble into our page
looking for Tree of Science they wouldn't know how to use the tool.

This repository creates the instructions to use
[Web of Science](https://access.clarivate.com/login?app=wos&alternative=true&shibShireURL=https:%2F%2Fwww.webofknowledge.com%2F%3Fauth%3DShibboleth&shibReturnURL=https:%2F%2Fwww.webofknowledge.com%2F%3Fmode%3DNextgen%26action%3Dtransfer%26path%3D%252Fwos%252Fwoscc%252Fbasic-search%26DestApp%3DUA&referrer=mode%3DNextgen%26path%3D%252Fwos%252Fwoscc%252Fbasic-search%26DestApp%3DUA%26action%3Dtransfer&roaming=true)
files in TOS.

## Table of Contents

- [General Info](#general-information)
- [Setup](#setup)
- [Usage](#usage)
- [Room for Improvement](#room-for-improvement)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)
<!-- * [License](#license) -->

## General Information

Tree of Science - ToS, is a tool to solve a common problem between students and researchers: the
need to find pertinent and relevant scientific journal papers in the corresponding researchers
topic, optimizing the search time.

## Setup

To run this project it is necessary to install [Zola](https://www.getzola.org/). Zola is a static
site generator (SSG), similar to Hugo, Pelican, and Jekyll. It is written in Rust and uses the
Tera template engine, which is similar to Jinja2, Django templates, Liquid, and Twig. Content is
written in CommonMark, a strongly defined, highly compatible specification of Markdown.
To install Zola in Ubuntu you can use

```bash
$ sudo apt update
$ sudo apt install snapd
$ sudo snap install zola --edge
```

Then, you need to clone this repository and to start the Zola development server you can use

```bash
$ zola serve
```

This command must be run in the base Zola directory, which contains `config.toml`. If you point
your web browser to http://127.0.0.1:1111, you should see the site.

## Usage

How does one go about using it?
Provide various use cases and code examples here.

`write-your-code-here`

## Room for Improvement

Include areas you believe need improvement / could be improved. Also add TODOs for future development.

Room for improvement:

- Improvement to be done 1
- Improvement to be done 2

To do:

- Feature to be added 1
- Feature to be added 2

## Acknowledgements

Give credit here.

- This project was inspired by...
- This project was based on [this tutorial](https://www.example.com).
- Many thanks to...

## Contact

Created by [@flynerdpl](https://www.flynerd.pl/) - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->
