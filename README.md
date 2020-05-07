# Developer Mac Setup
:sunglasses:
I recently cleaned my Mac and decided to write down my steps for future reference. Some of these steps could change so take a look at some of the links to see if the commands are up to date. This is also for my indiviudal setup. Some of these packages you may not need and you may have others that you need that I don't have here. 

##Setup Command Line Tools
###Install Xcode Command Line
You can also install XCode from the app store later if you wish. But for now I just need the command line tool. 
```text
  xcode-select --install
```
###Install Homebrew
This command comes from [Homebrew](https://brew.sh)
Homebrew is a package manager that simiplifies installation of many things using terminal. Later we will use cask to install items such as Chrome, Firefox, Visual Studio Code, and Eclipse using "cask".
```text
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```
###Update Your Bash Version
By default MacOS comes with an outdated version of bash. (I was surprised myself. The installed version with the latest update is 3.2, but 5.0 is the latest available.  
These commands show you the version of bash that you have and then the second command uses brew and installs the latest version. 
```text
  bash -v
  brew install bash
```

##Setup You Applications for Development
Now we will use brew to install applications that we will need for development. The following commands will automatically install these applications and automatically move them into your Applications folder without you having to do anything. 
###Install Spectacle 
I like to use this tool to simiplify splitting my screen. After it installs you can set it up so that it runs on start up and also you can customize the commands. This command comes from [Spectacle](https://www.spectacleapp.com)
```text
  brew cask install spectacle
```
###Install Java
Currently the version is 14. 
```text
  brew cask install java
```
###Install Eclipse
Install the Eclipse IDE. [Eclipse](https://www.eclipse.org/downloads/)
```text
  brew cask install eclipse-java
```
###Install Visual Studio Code
Install Visual Studio Code editor. [Visual Studio Code](https://code.visualstudio.com) 
```text
  brew cask install visual-studio-code
```
###Install Google Chrome
Install Google Chrome browser. [Google Chrome](https://www.google.com/chrome/)
```text
  brew cask install google-chrome
```
###Install Firefox
[Firefox](https://www.mozilla.org/en-US/firefox/new/)
```text
  brew cask install google-chrome
```
###Install Postman
This is my favorite tool to test my API's. Insomnia is also a good one.[Postman](https://www.postman.com)
```text
  brew cask install postman
```

##Install Node and Node Packages 
###Install Node & NPM 
This command will install Node and NPM into your machine. 
```text
  brew install node
```
Install ESLint
```text
  npm install -g eslint
```
Install React
```text
  npm install -g create-react-app
```
Install Vue
Vue will eventually be replacing React. But I'm working with both Vue and React applications which is why I'm installing both.  
```text
  npm install -g @vue/cli
```
Install Path
```text
  npm install path
```
Install RESTful APi 
```text
  npm install http
```
Install Express
```text
  npm install express
```
Install Requests 
```text
  npm install request
```
Install MongoDB
```text
  npm install mongodb
```
Install Cheerio. This is a webscraper that I don't use often but still need. 
```text
  npm install cheerio
```
Install Nodemailer 
```text
  npm install nodemailer
```
Install GraphQL
```text
  npm install graphql
```
Install Express-GraphQL
```text
  npm install graphql
```

##Setup Git
We all use Git so this will need to be setup eventually. 
###Install Git
I believe Git is already installed on Mac but just to be safe.
```text
  brew cask install git
```
To setup git in your Mac you will also need to run the following commands. Replace the your@email with your email and replace git_username with your Git username.But keep the quotes. 
```text
  git config --global user.email "your@email.com"
  git config --global user.name "git_username"
 ```
:sunglasses:
