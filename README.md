<div id="top">

<!-- HEADER STYLE: CLASSIC -->
<div align="center">


# BYTEBUDDY

<em>Empower your coding journey with seamless collaboration.</em>

<!-- BADGES -->
<img src="https://img.shields.io/github/last-commit/pbrar17/byteBuddy?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
<img src="https://img.shields.io/github/languages/top/pbrar17/byteBuddy?style=flat&color=0080ff" alt="repo-top-language">
<img src="https://img.shields.io/github/languages/count/pbrar17/byteBuddy?style=flat&color=0080ff" alt="repo-language-count">

<em>Built with the tools and technologies:</em>

<img src="https://img.shields.io/badge/Express-000000.svg?style=flat&logo=Express&logoColor=white" alt="Express">
<img src="https://img.shields.io/badge/JSON-000000.svg?style=flat&logo=JSON&logoColor=white" alt="JSON">
<img src="https://img.shields.io/badge/npm-CB3837.svg?style=flat&logo=npm&logoColor=white" alt="npm">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat&logo=JavaScript&logoColor=black" alt="JavaScript">
<img src="https://img.shields.io/badge/Nodemon-76D04B.svg?style=flat&logo=Nodemon&logoColor=white" alt="Nodemon">
<img src="https://img.shields.io/badge/React-61DAFB.svg?style=flat&logo=React&logoColor=black" alt="React">
<img src="https://img.shields.io/badge/Axios-5A29E4.svg?style=flat&logo=Axios&logoColor=white" alt="Axios">
<img src="https://img.shields.io/badge/CSS-663399.svg?style=flat&logo=CSS&logoColor=white" alt="CSS">

</div>
<br>

---

## Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
    - [Usage](#usage)
    - [Testing](#testing)

---

## Overview

ByteBuddy is an innovative platform designed to empower developers with an interactive environment for coding challenges in Python. 

**Why ByteBuddy?**

This project aims to enhance the coding experience by providing a seamless interface for users to engage with Python programming challenges. The core features include:

- 🎨 **User Authentication:** Streamlined login and registration processes enhance security and user experience.
- 🛠️ **Interactive Code Editor:** Allows users to write, run, and submit Python code, fostering engagement and learning.
- 📚 **Dynamic Problem List:** Displays coding challenges categorized by difficulty, making it easy for users to find suitable tasks.
- ⚙️ **Robust Backend Architecture:** Manages user data and code execution efficiently, ensuring a seamless experience.
- 📱 **Responsive Design:** Ensures accessibility and usability across devices, enhancing the overall user experience.

---

## Getting Started

### Prerequisites

This project requires the following dependencies:

- **Programming Language:** JavaScript
- **Package Manager:** Npm

### Installation

Build byteBuddy from the source and intsall dependencies:

1. **Clone the repository:**

    ```sh
    ❯ git clone https://github.com/pbrar17/byteBuddy
    ```

2. **Navigate to the project directory:**

    ```sh
    ❯ cd byteBuddy
    ```
3. **Navigate to the Backend directory:**

    ```sh
    ❯ cd Backend
    ```

4. **Install the dependencies:**

**Using [npm](https://www.npmjs.com/):**

```sh
❯ npm install
```

5. **Navigate Back to project directory:**

    ```sh
    ❯ cd ..
    ```

3. **Navigate to the Frontend directory:**

    ```sh
    ❯ cd Frontend
    ```

4. **Install the dependencies:**

**Using [npm](https://www.npmjs.com/):**

```sh
❯ npm install
```

### Usage

To run the project, follow these steps:

1. Navigate to the Backend directory and run the following command using [npm](https://www.npmjs.com/):

    ```sh
    npm start
    ```

2. After that, navigate to the Frontend directory and run the same command:

    ```sh
    npm start
    ```

This will start both the backend and frontend of the project.

### Running Ollama for the AI Coach

To test the project, you need to set up Ollama and the Gemma3 model. Follow these instructions:

1. **Download Ollama** from [here](https://ollama.com/download) and install it on your machine.

2. **Pull the Gemma3 model** using the following command in your terminal or PowerShell:

    ```sh
    ollama pull gemma3
    ```

3. Once the Gemma3 model is downloaded, **serve the model** with this command:

    ```sh
    ollama serve
    ```

### Ollama Serve Error Fix

If you encounter an error when running the `serve` command due to the socket/port already being used, you can fix it by following these steps:

#### For Windows:

1. **End the process** that's using the port by running this command in your PowerShell or Command Prompt:

    ```sh
    netstat -aon | findstr :11434
    ```

2. Once the command returns the process ID, **kill the task** using:

    ```sh
    taskkill /PID <task> /F
    ```

    (Replace `<task>` with the actual task ID from the `netstat` output.)

#### For macOS:

1. **Find the process** that's using the port by running the following command in your terminal:

    ```sh
    lsof -i :11434
    ```

2. After identifying the process ID (PID) from the output, **kill the process** using:

    ```sh
    kill -9 <PID>
    ```

    (Replace `<PID>` with the actual process ID from the `lsof` output.)

After ending the conflicting process, you should be able to run the `ollama serve` command successfully.


---

<div align="left"><a href="#top">⬆ Return</a></div>

---
