
# Dockerfile Generator

  

## Overview

  

The Dockerfile Generator is a Yeoman generator that helps you quickly generate Dockerfiles for your projects. It provides the following features:

  

- **Prompt-based Configuration**: Easily configure your Dockerfile by answering a series of prompts for options such as base image, source path for COPY, destination path for COPY, expose ports, and environment variables.

- **Input Validation**: Ensures that user inputs meet specific criteria or formats, such as validating port numbers, directory paths, and environment variable formats.

- **Fallback Options**: Provides default values for prompts and allows users to skip optional prompts if desired, providing fallback options and alternative paths if certain inputs are missing or invalid.

- **User-friendly Usage**: Simple and intuitive command-line interface makes it easy to generate Dockerfiles in any project directory.

- **Comprehensive Options**: Offers a range of options to customize Dockerfile generation, including base image, COPY paths, exposed ports, environment variables, and more.

  

## Requirements

  

- Node.js installed on your system

- Yeoman installed globally (`npm install -g yo`)

  

## Installation

  

1. Install Yeoman globally if you haven't already:

  

```bash

sudo npm install -g yo

```

  

2. Install the Dockerfile Generator:

  

```bash

npm install -g generator-dockerfile

```

  

## Usage

  

To use the Dockerfile Generator, follow these steps:

  

1. Open your terminal or command prompt.

  

2. Navigate to the directory where you want to generate the Dockerfile. You can use the `cd` command to change directories. For example:

  

```bash

cd path/to/your/project/directory

```

  

Replace `path/to/your/project/directory` with the actual path to your project directory.

  

3. Run the generator:

  

```bash

yo dockerfile

```

  

4. Follow the prompts to configure your Dockerfile. You'll be prompted to provide information such as the base image, source path for COPY, destination path for COPY, and more.

  

5. Once you've provided all the necessary inputs, the generator will generate a Dockerfile in the current directory based on your configuration.

  

6. You can then use the generated Dockerfile in your projects as needed.

  

## Options

  

- **Base Image**: Specify the base image for your Dockerfile. Default is "node:14".

- **Source Path for COPY**: Specify the source path for the COPY instruction in your Dockerfile. Default is "." (current directory).

- **Destination Path for COPY**: Specify the destination path for the COPY instruction in your Dockerfile. Default is "." (current directory).

- **Expose Ports**: Specify the ports to expose from the container to the host. Enter port numbers separated by commas. Default is empty.

- **Environment Variables**: Specify environment variables for the container in key=value format, separated by commas. Default is empty.

- **Skip Optional Prompts**: Skip optional prompts if desired. Default is false.

  

## Additional Information

  

- For more information on Yeoman generators, refer to the [Yeoman documentation](https://yeoman.io/).

- If you encounter any issues or have suggestions for improvements, please report them on the [GitHub repository](https://github.com/DiogoAngelim/generator-dockerfile).
