# Molly.github.io

## When change computer

1. Install git and set up ssh keys  

2. Install nodejs  
`$ sudo apt-get install nodejs`  
`$ sudo apt-get install npm`

3. Install hexo  
`$ sudo npm install hexo-cli -g`  

4. Clone repo and install deployer  
`$ git clone git@xxx.github.io.git`  
`$ cd xxx.github.io`  
`$ npm install`  
`$ npm install hexo-deployer-git --save`  

5. Generation and deployment  
`$ hexo g`  
`$ hexo d`

Now can start your new blog  
`$ hexo new newpage`

### TIPS
It is better to push source files when finish everytime  
`$ git add .`  
`$ git commit –m "xxxx"`  
`$ git push `
