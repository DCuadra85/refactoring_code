# Code Refactor

This repository is where I refactor existing code to get it up to date. There are no changes to the visual aesthetic of the original webpage that is generated from the HTML and CSS code provided. The following actions were performed:

* The code was set to meet accessibility standards. 
* Restructure the HTML.
* Add accessible alt attributes.
* Used semantic HTML tags instead of standard div tags.

## Usage

The HTML code needed significant adjustments. The first set of adjustments was to organize the code into a readily readable format with a reset.css file. After, all "div" tags were replaced with appropriate semantic tags, such as "header, nav, section, aside, and footer". All images had an alt attribute added to them.

![HTML-code](./develop/assets/images/htmlscreen.png)
<img src="https://github.com/DCuadra85/refactoring_code/blob/master/Develop/assets/images/htmlscreen.png">

Minor adjustments were made to the CSS code to make the HTML code properly load after the semantic tags were entered. One example of this is in the ".header nav {" line, which was originally ".header div {". Further re-organization of this code was also made.

![CSS-code](./develop/assets/images/css-screen.png)

## Credits

* https://github.com/coding-boot-camp
* https://www.w3schools.com/
* https://guides.github.com/features/mastering-markdown/

## Built With

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

## Deployed Link

* https://dcuadra85.github.io/refactoring_code/


## Authors

* **Daniel Cuadra** 

- [GitHub](https://github.com/DCuadra85)
- [LinkedIn](https://www.linkedin.com/in/daniel-cuadra-3705aa39/)


## License

MIT License

Copyright (c) [2020] [Daniel Cuadra]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.