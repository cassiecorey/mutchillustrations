# Mutch Illustrations - Webpage

Hi Tashi. This is called the README file. It's usually where you put an explanation of what the project is about. Sometimes it also includes a few basic setup steps and stuff.

## Getting Started

1. Make a GitHub account: https://github.com/join
1. Install a text editor. I think [Sublime](https://www.sublimetext.com/3) is the easiest to use. It's like microsoft word but....for code.
1. Download the files here. To make things easy, just click the "Download ZIP" button above.
1. Unzip the download by double-clicking on it.
1. Right click on the file called 'index.html' and open it with Firefox or Chrome. Please, anything but Safari. I beg you.
1. You're in! You should see the webpage. Look at the URL, that points to where the 'index.html' file is on your computer.
1. Open the 'index.html' file in Sublime (or whatever text editor you want). Try to find your name (you can ctrl+F if that's easier).
1. Once you find it, change it to say: "Cassie Corey" or something. Save. Go back to the browser where you have the page open. Reload the page and you should see the change go through.
1. Have fun making changes and messing around with stuff!

*Note*: Really the only files you should mess with are the HTML and CSS. CSS controls the styling, like background colors, font styles, font size, etc. HTML has most of the content.

## Download and Installation

Have you mastered the steps in the basic 'Getting Started' section? Do that first.

If you want to get really involved and see your changes live on http://mutchillustration.github.io, follow these steps:

1. Request access to the repository. Only I can add you right now, by now I should have sent you an email invitation so just follow the directions in that.
1. Open a Terminal window on your laptop.
1. Navigate to where you want the folder to be saved. You can see where you are on the left side of the terminal window. If you type `pwd` and hit "Enter" it will print out the "Working Directory" which is where you are. You can move to a sub-folder by typing `cd Documents` or `cd Downloads` or `cd` whatever you want. `cd` means "Change Directory"
1. Clone the repository by typing this into the terminal and hitting "Enter"

`git clone https://github.com/cassiecorey/mutchillustration/`

*Note*: If that didn't work...you might need to activate developer tools on your mac. Open XCode, go to Preferences and Install "Command Line Tools" then try again.

1. After cloning, if you type `ls` to list the files and folders in the directory you're in, you should see 'mutchillustration' in there somewhere. Cool.
1. Make whatever changes you want to the files using the text editor you prefer.
1. In a Terminal window, make sure you `cd mutchillustrations` so that you're inside the mutchillustrations folder.
1. Type `git status` and hit "Enter" this will print out a list of the files you changed.
1. Type `git add -A` to add all of your changes.
1. Type `git commit -m "boobies"` to commit your changes. Your message doesn't have to say boobies. That's just what I like.
1. Type `git push` to push your changes up to the github website. It will probably ask for your github username and password which you hopefully remember.

*Note*: If you mess up typing the username or password the only thing you have to re-type is the `git push` part.


*IGNORE THE STUFF BELOW THIS IT'S FOR ME*

## Usage

### Basic Usage

After downloading, simply edit the HTML and CSS files included with the template in your favorite text editor to make changes. These are the only files you need to worry about, you can ignore everything else! To preview the changes you make to the code, you can open the `index.html` file in your web browser.

### Advanced Usage

After installation, run `npm install` and then run `gulp dev` which will open up a preview of the template in your default browser, watch for changes to core template files, and live reload the browser when changes are saved. You can view the `gulpfile.js` to see which tasks are included with the dev environment.

#### Gulp Tasks

- `gulp` the default task that builds everything
- `gulp dev` browserSync opens the project in your default browser and live reloads when changes are made
- `gulp css` compiles SCSS files into CSS and minifies the compiled CSS
- `gulp js` minifies the themes JS file
- `gulp vendor` copies dependencies from node_modules to the vendor directory

You must have npm and Gulp installed globally on your machine in order to use these features.
