# Code-Refactor
Horiseon homepage code refactor. Updates to improve semantic HTML & CSS elements for SEO and accessibility. 


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
     <li>
      <a href="https://fac-73.github.io/Code-Refactor/">View project</a></li>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

![Website screenshot](https://github.com/FAC-73/Code-Refactor/blob/main/assets/images/Horiseon-website.jpg?raw=true "Horiseon Website")

**Horiseon - SEO and Web Marketing Expert Website - requires updates to the to the structure of the HTML elements and semantic HTML mark up, Improved logical structure of CSS styling elements. Accessibility considerations including image alt tag attributes and sequential header ordering**


### Built With

* [HTML](https://www.w3schools.com/)
* [CSS](https://www.w3schools.com/)



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/fac-73/code-refactor.git
   ```

2. Pull the latest
   ```sh
   git pull
   ```


<!-- USAGE EXAMPLES -->
## Usage

#### Updating HTML content
HTML & CSS is structured using semantic HTML where possible. For accessibility and SEO requirements headers are ordered in hierarchical order, and layout follows established layout best practices. 


#### Dark Mode stylesheet
If you want to switch to a more accessible dark mode option you can comment out the first style sheet and use the style_v2.css 


1. Remove comments from link
   ```
   link rel="stylesheet" href="./assets/css/style_v2.css"
   ```

2. Comment this link out
   ```
   link rel="stylesheet" href="./assets/css/style.css"
   ```

3. Switch out the assets in the aside section for lighter icons. Add '_light' in the file name extension
   ```
   "./assets/images/cost-management.png" - Light mode
   "./assets/images/cost-management_light.png" - Dark mode
   ```

![Website screenshot](https://github.com/FAC-73/Code-Refactor/blob/main/assets/images/Horiseon-website-dark.jpg?raw=true "Horiseon Website dark")

## Contributing

#### Updating HTML content
Follow the semantic HTML element layout as defined in the index.html text. <br>
Add main content sections within main element - include a header, paragraph text, image and alt text descriptions for accessibility and SEO. <br>
Add complementary sections within aside element - include a header, paragraph text image and alt text descriptions for accessibility and SEO. 

#### Updating CSS
If changing styles for main or complementary elements replace or add properties within aside or main. <br>
Text styles are grouped together with H1, H2, H3, P. <br>
Links and psuedo selectors are grouped in the links section. <br>
Most CSS styles use semantic classes to limit the need to reference classes within tags.


#### Pushing to GitHub

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/FeatureName`)
3. Commit your Changes (`git commit -m 'Add some FeatureName`)
4. Push to the Branch (`git push origin feature/FeatureName`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. 

See [LICENSE](https://github.com/FAC-73/Code-Refactor/blob/main/LICENSE.txt) for more information.



<!-- CONTACT -->
## Contact

Kay Davis

Project repo link: [https://github.com/fac-73/code_refactor](https://github.com/fac-73/code_refactor/code_refactor)
<br>
Project website: [https://fac-73.github.io/Code-Refactor/](https://fac-73.github.io/Code-Refactor/)