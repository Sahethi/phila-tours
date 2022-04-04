# Phila Tours

This is a personal project based on a touring website.
The main aim of this project was to get more hands on experience with module bundling, automation of workflows, jQuery and dealing with packages which make the project more sophisticated. 

- Installation

```bash
  git clone https://github.com/Sahethi/phila-tours.git
  cd phila-tours
 ```
 
The project uses **gulp task runner** for several tasks, one can check them out with the following command: 
`gulp --tasks`

To name a few examples,
  1. Creating CSS Image Sprites (image sprite is a collection of images put into a single image)
  2. Minifying JavaScript & CSS
  3. Watching Files
  4. Autoprefixing the CSS files (a PostCSS plugin which parses your CSS and adds vendor prefixes)

- To Run

```bash
  gulp build
  gulp watch 
 ```

Here the build task will automatically create the destination folder and the watch task will constantly watch the files for any changes. 