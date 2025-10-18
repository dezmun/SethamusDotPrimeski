# Sethamus.Primeski

Howdy! I decided it would be fun to fork my bro-in-law's opensource website. 

## PokePeru

I've an interesting idea for this to take it in a similar but different direction.

# The rest of this info is from the original project. I'll update it when necessary.

This website is built with node v22.20.0. Please download the repo: https://github.com/jeffski13/jeffDotSki. Navigate to the downloaded repo in the terminal and install and start:

``` bash
npm install

npm start
```

NOTE: all folders inside of `app` should be camel cased starting with a lower case. Due to issues with casing and git and windows/unix file systems this might be a problem on install.

In the browser, go to http://localhost:5173/pokePeru/battle

For info on modifying the project with your students' monsters, please see http://localhost:5173/pokePeru/info.

## Deploying

I created a script that will run the build, copying into the local Firebase directory, and deploying to the firebase servers. It has made me want to update my site more! [deployski.sh](./deployski.sh)
