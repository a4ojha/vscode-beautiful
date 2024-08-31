<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
<h3 align="center">Minimal VS Code</h3>

  <p align="center">
    There's no replacing VS Code, but it can always look better...
    <br />
    <br />
    <br />
  </p>
</div>

<!-- ABOUT THE PROJECT -->
## Overview

<p align="center">
  <img src="https://github.com/user-attachments/assets/4f7162d5-cb53-4505-9b0d-789a5f75ef56" width="90%" />
</p>

Inspired by [Glen Raya](https://github.com/glennraya/vscode-settings-json), I customized my VS Code setup to be more minimalistic and reliant on keyboard shortcuts. 

So basically neovim but with VS Code extensions.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started
1. Install the **Custom CSS and JS Loader** VS Code extension  
    <br />
   <img src="https://github.com/user-attachments/assets/31ce2f93-063d-4d02-b995-5df2a7120ae6" width="400">     
   

2. Open the **command palette** (Ctrl+Shift+P) and run the following command to open your local settings:
     * **Preferences: Open User Settings (JSON)**

3. Copy the contents of [settings.json](https://github.com/a4ojha/vscode-beautiful/settings.json) and paste into your VS Code's **settings.json**
4. Clone the repo
    ```
    git clone https://github.com/a4ojha/vscode-beautiful.git
    ```
   >*Keep note of the file path of the created "vscode-beautiful" directory*
   
5. Replace the code block at line 189 of your **settings.json** as follows:
    ```
    "vscode_custom_css.imports": [
        "file:///absolute-path-to-cloned-project/vscode-beautiful/custom-vscode.css",
        "file:///absolute-path-to-cloned-project/vscode-beautiful/vscode-script.js"
    ],
    ```
6. Open the **command palette** (Ctrl+Shift+P) and run the following two commands in order:
     * **Reload Custom CSS and JS**
     * **Developer: Reload Window**

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/a4ojha/vscode-beautiful.svg?style=for-the-badge
[contributors-url]: https://github.com/a4ojha/vscode-beautiful/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/a4ojha/vscode-beautiful.svg?style=for-the-badge
[forks-url]: https://github.com/a4ojha/vscode-beautiful/network/members
[stars-shield]: https://img.shields.io/github/stars/a4ojha/vscode-beautiful.svg?style=for-the-badge
[stars-url]: https://github.com/a4ojha/vscode-beautiful/stargazers
[issues-shield]: https://img.shields.io/github/issues/a4ojha/vscode-beautiful.svg?style=for-the-badge
[issues-url]: https://github.com/a4ojha/vscode-beautiful/issues
[license-shield]: https://img.shields.io/github/license/a4ojha/vscode-beautiful.svg?style=for-the-badge
[license-url]: https://github.com/a4ojha/vscode-beautiful/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/adonojha/
[product-screenshot]: public/product-screenshot.png
[demo-screenshot]: public/demo.png
[demo-screenshot2]: public/demo2.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
[Tailwindcss]: https://img.shields.io/badge/tailwind-161D2D?style=for-the-badge&logo=tailwindcss&logoColor=16BECB
[Tailwind-url]: https://tailwindcss.com 
