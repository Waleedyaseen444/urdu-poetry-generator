# Urdu Poetry Generator

![Urdu Poetry](https://github.com/Waleedyaseen444/urdu-poetry-generator/blob/main/assets/urdu_poetry_banner.png?raw=true)

A **Streamlit** application that generates beautiful **Urdu poetry** using a **Transformer-based** model. This project leverages advanced natural language processing techniques to create coherent and aesthetically pleasing verses in Urdu, offering various text generation methods to enhance creativity and customization.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
  - [Running Locally](#running-locally)
  - [Docker Deployment](#docker-deployment)
- [Generating Poetry](#generating-poetry)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Multiple Generation Methods:** Choose between Greedy Sampling, Temperature Sampling, Top-K Sampling, Top-P (Nucleus) Sampling, and Beam Search to generate diverse and creative poetry.
- **User-Friendly Interface:** Intuitive Streamlit interface for easy interaction and poetry generation.
- **Customizable Parameters:** Adjust sequence length, maximum generated tokens, temperature, top-K value, top-P value, and beam width to fine-tune the output.
- **Dockerized Deployment:** Seamlessly deploy the application using Docker for consistent and scalable environments.

## Demo

![Urdu Poetry Generator Demo](https://github.com/Waleedyaseen444/urdu-poetry-generator/blob/main/assets/demo.gif?raw=true)

Experience the beauty of Urdu poetry generation firsthand by trying out the [live demo](https://share.streamlit.io/Waleedyaseen444/urdu-poetry-generator/main/streamlit_app.py).

## Installation

Follow these steps to set up the Urdu Poetry Generator on your local machine.

### Prerequisites

- **Python 3.7 or higher** installed on your system. You can download it from [here](https://www.python.org/downloads/).
- **Git** installed. Download it from [here](https://git-scm.com/downloads).
- **Docker** installed (optional, for Docker deployment). Download it from [here](https://www.docker.com/get-started).

### Step 1: Clone the Repository

Open your terminal or PowerShell and clone the repository:

```bash
git clone https://github.com/Waleedyaseen444/urdu-poetry-generator.git
cd urdu-poetry-generator
