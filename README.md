<div id="top"></div>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][https://www.linkedin.com/in/sebastiankleinschmidt/]

<br />
<div align="center">

<h3 align="center">Deep Reinforcement Learning Project: BananaHunter</h3>

  <p align="center">
    This projects demonstrates an agent learning to collect yellow simulatneously avoiding blue bananas using deep reinforcement learning.
    <br />
    <a href="https://github.com/sebastian-kleinschmidt/RL_BananaHunter"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/sebastian-kleinschmidt/RL_BananaHunter">View Demo</a>
    ·
    <a href="https://github.com/sebastian-kleinschmidt/RL_BananaHunter/issues">Report Bug</a>
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
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

This project teaches an agent to collect yellow bananas using **Deep Reinforcement Learning**.

### Environment Details

#### Reward
A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

#### State and Action Space
The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

#### Goal
The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

* [Jupyter Notebook](https://jupyter.org/)
* [Conda](https://docs.conda.io/)
* [PyTorch](https://pytorch.org/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites and Installation

This project needs Conda installed on your system to create the needed environment. To then create a conda environment including all dependencies, use the following commands:
1. Create and activate a conda environment:
  ```sh
  conda create --name drl python=3.6
  source activate drl
  ```
> :warning: **If you are on a Windows machine**: Use ```activate drl``` instead of ```source activate drl```

2. Install required dependencies:
  ```sh
  pip install -r requirements.txt
  ```

3. Create an IPython kernel for the drl environment:
  ```sh
  python -m ipykernel install --user --name drl --display-name "drl"
  ```


<!-- USAGE EXAMPLES -->
## Usage
You can start the Jupyter Notebook by executing ```jupyter notebook``` in an active drl Conda environment (see prerequisites section). Execute the documented cells to either train a new agent or use the preptrained one.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://github.com/sebastian-kleinschmidt/RL_BananaHunter.svg?style=for-the-badge
[contributors-url]: https://github.com/sebastian-kleinschmidt/RL_BananaHunter/graphs/contributors
[forks-shield]: https://github.com/sebastian-kleinschmidt/RL_BananaHunter.svg?style=for-the-badge
[forks-url]: https://github.com/sebastian-kleinschmidt/RL_BananaHunter/network/members
[stars-shield]: https://github.com/sebastian-kleinschmidt/RL_BananaHunter.svg?style=for-the-badge
[stars-url]: https://github.com/sebastian-kleinschmidt/RL_BananaHunter/stargazers
[issues-shield]: https://github.com/sebastian-kleinschmidt/RL_BananaHunter.svg?style=for-the-badge
[issues-url]: https://github.com/sebastian-kleinschmidt/RL_BananaHunter/issues
[license-shield]: https://github.com/sebastian-kleinschmidt/RL_BananaHunter.svg?style=for-the-badge
[license-url]: https://github.com/sebastian-kleinschmidt/RL_BananaHunter/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/sebastiankleinschmidt/
[product-screenshot]: images/BananaHunter.gif