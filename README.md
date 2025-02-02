# ![COMPUTER Logo](./assets/images/computer.svg)

[//]: # (cSpell: locale en)
[//]: # (cSpell: enableCompoundWords)
[//]: # (cSpell: ignore COMPUTER)

[![ci::status]][ci::github] [![documentation::badge]][documentation::web]

[ci::status]: https://img.shields.io/github/actions/workflow/status/georglauterbach/computer/TODO.yml?branch=master&color=green&label=CI&logo=github&logoColor=white&style=for-the-badge
[ci::github]: https://github.com/docker-mailserver/docker-mailserver/actions
[documentation::badge]: https://img.shields.io/badge/DOCUMENTATION-GH%20PAGES-0078D4?style=for-the-badge&logo=googledocs&logoColor=white
[documentation::web]: https://georglauterbach.github.io/computer

## :page_with_curl: About

>[!WARNING]
>
> This software is currently in development and should not be used in a production environment.

_COMPUTER_ is a supervisor daemon for Linux - written entirely in Rust&trade; - that conforms to the UNIX philosophy of doing one thing and doing it well[^1]. _COMPUTER_ supervises other processes, possibly as an init system (process with PID 1). Its main goals are:

1. **Stability**: The program is robust and reliable.
2. **Performance**: The program is efficient and fast.
3. **Integrity**: The code is well-documented, linted, tested, as well as easy to navigate and comprehend.
4. **Simplicity**: The code is easy to understand, and the program is easy to use.
6. **Fun**: Often overlooked, it should be seamless and fun to write code and to use the program.

_COMPUTER_ uses YAML configuration files to fully define the processes it supervises. The code aims to be simple in structure and easy to comprehend. Hence, you should be able to effortlessly navigate it to find out more about this project.

### :bookmark: Documentation

The dedicated documentation for _COMPUTER_ is hosted on _GitHub Pages_. The documentation is versioned - make sure to select a version that is compatible with the version of _COMPUTER_ that you are using. To view the latest version, [click here][documentation::web].

> [!NOTE]
>
> The name _COMPUTER_ is a reference to the computer of the _NCC-1701-D USS Enterprise_ from _Star Trek - The Next Generation_[^2]. It is a central system, from this project heavily draws inspiration, that manages the ship's operations. Engage!

[//]: # (Glossary)

[^1]: Doug McIlroy; E. N. Pinson; B. A. Tague (8 July 1978). "Unix Time-Sharing System: Foreword". The Bell System Technical Journal. Bell Laboratories: 1902-1903 (Style).
[^2]: Memory Alpha. Computer Technology. "[LCARS](https://memory-alpha.fandom.com/wiki/Library_Computer_Access_and_Retrieval_System)".
