# Sass & scss

## Learning Objectives
- What Sass means
- How to write Sass & Scss file
- What is the difference between Sass and Scss
- What is the Sass preprocessing
- How to declare a variable
- How to use nested definition
- How to import a Sass file
- How to use mixins
- How to declare extend/inheritance styles
- How to manipulate operators

## Requirements
- General
- Allowed editors: vi, vim, emacs
- All your files will be executed on Ubuntu 20.04 LTS using Sass 1.82.0 (or higher)
- All your files should end with a new line
- All your Scss files should have a comment at the beginning (i.e. syntax above)
- All your files should start by a comment describing the task
- A README.md file, at the root of the folder of the project, is mandatory
- The length of your files will be tested using wc

## More Info
Comments for your Scss file:
All your Scss file must start with a comment block
```
$ cat my_styles.scss
/* My style */
body {
    .container {
        color: #3D3D3D;
    }
}
```

Install Sass/Scss on Ubuntu 20.04 LTS
```
$ curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
$ sudo apt-get install -y nodejs
$ sudo npm install -g npm@10
$ sudo npm install -g sass@^1.82.0
$ sass --version
1.82.0 compiled with dart2js 3.5.4
```