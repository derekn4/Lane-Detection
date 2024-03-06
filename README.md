<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <!--<a href="https://github.com/derekn4/CurfewBot?tab=readme-ov-file">
    <img src="curfew.png" alt="Logo" width="300" height="300">
  </a>-->

<h3 align="center">Lane Detection</h3>

  <p align="center">
    Computer Vision to detect lane lines on a road
    <br />
    <a href="https://github.com/derekn4/PillClassification"><strong>Explore the docs »</strong></a>
    <br />
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
      <a href="#pipeline">Pipeline</a>
      <ul>
        <li><a href="#gray-scale">Grayscale</a></li>
        <li><a href="#guassian-blur">Guassian Blur</a></li>
        <li><a href="#canny-edge-detection">Canny Edge Detection</a></li>
        <li><a href="#region-of-interest">Region of Interest</a></li>
        <li><a href="#hough-transform">Hough Transform</a></li>
        <li><a href="#annotate-image">Annotate image</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
Lane line detection is crucial for self-driving cars. With Python and OpenCV, I was able to process video clips and identify lane lines.
The following techniques were used:
* Canny Edge Detection
* Region of Interest Selection
* Hough Transform Line Detection

With these techniques, I could process dash cam footage and annotate them highlighting lane lines

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With

* [![Python][Python.org]][Python-url]
* [![OpenCV][opencv.org]][opencv-url]


<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Pipeline
- Install all necessary libraries to run pillImageDownload.py
- NOTE: the  National Library of Medicine consisted of 4,000 high-quality reference pills and 133,000 pictures captured by digital cameras on mobile phones.
  - ~2-3TB of data which we could not store or processes in GoogleColab

### Grayscale



### Guassian Blur

### Canny Edge Detection


### Region of Interest

### Hough Transform


### Annotate Image


<!-- CONTACT -->
## Contact

Derek Nguyen 
- [LinkedIn](https://www.linkedin.com/in/derekhuynguyen/) 
- [Email](derek.nguyen99@gmail.com)
<br></br>
Project Link: [https://github.com/derekn4/PillClassification](https://github.com/derekn4/PillClassification)

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[Python.org]: https://www.python.org/static/img/python-logo.png
[Python-url]: https://www.python.org/about/website/
[opencv.org]: https://upload.wikimedia.org/wikipedia/commons/thumb/3/32/OpenCV_Logo_with_text_svg_version.svg/1200px-OpenCV_Logo_with_text_svg_version.svg.png
[opencv-url]: https://opencv.org/