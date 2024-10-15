# ReimaginationApp
<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
[![Contributors](https://img.shields.io/github/contributors/SarthakB11/ReimaginationApp.svg?style=for-the-badge)](https://github.com/SarthakB11/ReimaginationApp/graphs/contributors)
[![Commits](https://img.shields.io/github/commit-activity/m/SarthakB11/ReimaginationApp.svg?style=for-the-badge)](https://github.com/SarthakB11/ReimaginationApp/commits/main)
[![Forks](https://img.shields.io/github/forks/SarthakB11/ReimaginationApp.svg?style=for-the-badge)](https://github.com/SarthakB11/ReimaginationApp/network/members)
[![Stargazers](https://img.shields.io/github/stars/SarthakB11/ReimaginationApp.svg?style=for-the-badge)](https://github.com/SarthakB11/ReimaginationApp/stargazers)
[![Issues](https://img.shields.io/github/issues/SarthakB11/ReimaginationApp.svg?style=for-the-badge)](https://github.com/SarthakB11/ReimaginationApp/issues)
[![MIT License](https://img.shields.io/github/license/SarthakB11/ReimaginationApp.svg?style=for-the-badge)](https://github.com/SarthakB11/ReimaginationApp/blob/master/LICENSE.txt)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555)](https://linkedin.com/in/sarthakbhardwaj1102)

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/SarthakB11/ReimaginationApp">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Reimagination App</h3>

  <p align="center">
    A functional prototype for text-to-image and text-to-video generation using generative AI models.
    <br />
    <a href="https://github.com/SarthakB11/ReimaginationApp"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/SarthakB11/ReimaginationApp">View Demo</a>
    ·
    <a href="https://github.com/SarthakB11/ReimaginationApp/issues/new?labels=bug&template=bug-report---.md">Report Bug</a>
    ·
    <a href="https://github.com/SarthakB11/ReimaginationApp/issues/new?labels=enhancement&template=feature-request---.md">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#project-video">Project Video</a></li>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
    <li><a href="#references">References</a></li>
  </ol>
</details>

## Project Video

Soon

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ABOUT THE PROJECT -->
## About The Project

![project-image-1](soon)
![project-image-2](soon)

The Reimagination App is a prototype designed for text-to-image, text-to-video generation and image captioning. It integrates advanced generative AI models to provide users with a seamless experience in generating visual content from textual input. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)](https://pytorch.org/)<br>
* [![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)<br>
* [![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FB3E3E?style=for-the-badge&logo=huggingface&logoColor=white)](https://huggingface.co/)<br>
* [![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)](https://opencv.org/)<br>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running, follow these steps:

### Prerequisites

* Python 3.8
* Pip (Python package installer)
* Streamlit
* ![Huggingface Token](https://huggingface.co/docs/hub/en/security-tokens)
  
### Ways to run the application
## Approach 1: Running on Local Machine
# Installation

1. Clone the repo
   ```sh
   git clone https://github.com/SarthakB11/ReimaginationApp.git
  ```
2. Navigate to the project directory
  ```sh
   cd ReimaginationApp
  ```
3. Install the required packages
  ```sh
  pip install -r requirements.txt
  ```
<p align="right">(<a href="#readme-top">back to top</a>)</p> <!-- USAGE EXAMPLES -->

# Usage

1. Run the Streamlit App
   ```sh
   streamlit run app.py
   ```
2. Open your browser and go to http://localhost:8501 to interact with the application.

3. For real-time demonstrations, follow the instructions in the README to expose your app using localtunnel or similar tools.

## Approach 2: Running on Colab

### Usage
1. Run the Jupyter Notebook
   Only run the Execution header!
2. Running the Streamlit App: Start the Streamlit application.
3. Copy the your external IP address using the wget command.
  ```sh
   !wget -q -O - ipv4.icanhazip.com
  ```
 It retrieves your external IP address.
 
4. 
   ```sh
   !streamlit run sm.py &
   ```
runs the Streamlit app in the background.
```sh
!npx localtunnel --port 8501
```
uses npx localtunnel to expose the locally running Streamlit app to the internet. 

The app is hosted on port 8501, and localtunnel provides a public URL through which the app can be accessed.

![image](https://github.com/user-attachments/assets/cdb95a07-03c6-484d-8783-794a5b746e0c)

5. Open the url link
   
![url-image)](https://github.com/user-attachments/assets/d2155717-1c15-4dde-8b8c-b926f41ca8e7)

Paste your IP address and submit.

<p align="right">(<a href="#readme-top">back to top</a>)</p> <!-- ROADMAP -->

### Roadmap

- Improve model efficiency and speed
- Integrate more advanced deep learning and generative AI models
- Enhance user interface and experience
- Expand the functionality to support more input types

See the open issues for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
### Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Top Contributors

<a href="https://github.com/SarthakB11/ReimaginationApp/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=SarthakB11/ReimaginationApp" alt="contrib.rocks image" />
</a>

<!-- LICENSE -->
### License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
### Contact

Sarthak Bhardwaj - [@Sarthak1102](https://x.com/Sarthak1102) - sarthak.bhardwaj21b@iiitg.ac.in

Project Link: [https://github.com/SarthakB11/ReimaginationApp](https://github.com/SarthakB11/ReimaginationApp)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
### Acknowledgments

* [Streamlit](https://streamlit.io/)
* [Hugging Face](https://huggingface.co/)
* [OpenCV](https://opencv.org/)
* [PyTorch](https://pytorch.org/)
