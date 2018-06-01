# Kyle Yasumiishi Portfolio Website

Welcome to the source code of my <a href="https://kyleyasumiishi.github.io/portfolio/" target="_blank">personal portfolio website</a>, currently hosted on GitHub Pages!

## Usage

Follow these instructions to use or modify my portfolio website:

Clone the repository
```
git clone https://github.com/kyleyasumiishi/portfolio.git
```

Install dependencies
```
# cd into root directory
npm i
```

After downloading, simply edit the HTML and CSS files. To preview changes, you can open the `index.html` file in your web browser.

#### Gulp Tasks

- `gulp` the default task that builds everything
- `gulp dev` browserSync opens the project in your default browser and live reloads when changes are made
- `gulp sass` compiles SCSS files into CSS
- `gulp minify-css` minifies the compiled CSS file
- `gulp minify-js` minifies the themes JS file
- `gulp copy` copies dependencies from node_modules to the vendor directory
- `gulp docs` updates the 'docs' directory with any changes made in the root directory. GitHub Pages sources files from './docs'.

## Technologies Used

* JavaScript & jQuery
* HTML5
* CSS3
* Bootstrap 4
* Formspree
* Gulp
* SCSS

## Authors

* **Kyle Yasumiishi** - https://github.com/kyleyasumiishi

