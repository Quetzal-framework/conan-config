# Conan Configuration Repository

This repository contains configuration files for Conan, the C++ package manager. 
The configuration files control Conan's behavior, allowing you to customize various aspects of the package management process.

## Contents
The repository includes the following directories and configuration files:

- `remotes/`: This directory contains configuration files for remote repositories. You can define and customize remote repositories for Conan to fetch packages from.

- `profiles/`: This directory contains build profile configuration files. Build profiles allow you to define specific settings and options for different build environments or target platforms.

- `conan.conf`: This file is the main configuration file for Conan. It contains global settings and options that influence Conan's behavior.

## Usage

It is meant to be used with `conan config install https://github.com/Quetzal-framework/conan-config.git` in a Dockerfile, specifically for the Visual Studio Code DevContainer extension working with the [Quetzal starter project](https://github.com/Quetzal-framework/starter-template)

## License

This repository is provided under the GNU General Public License v3.0. Feel free to use and modify the configuration files as needed, but keep in mind the requirements and obligations imposed by the GPL v3.0 license.

## Disclaimer

The configuration files in this repository are provided as a starting point and a reference. It is important to review and adjust the settings according to your specific needs and requirements. Use them at your own discretion and ensure compatibility with your development environment.




