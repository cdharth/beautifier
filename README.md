## About JS Beautifier

This little beautifier will reformat and reindent bookmarklets, ugly
JavaScript, unpack scripts packed by Dean Edward’s popular packer,
as well as deobfuscate scripts processed by
[javascriptobfuscator.com](http://javascriptobfuscator.com/).

## About this repo
This repo is maintained in github and is content of [beautify.hemshrestha.com.np](http://beautify.hemshrestha.com.np)

Here we will learn to build a repo that will be hosted in the custom domain such as [beautify.hemshrestha.com.np](http://beautify.hemshrestha.com.np)

### Steps for custom domain hosting in github
1. First of all signin to account in [github](https://github.com) and create a new repository.  
2. Now, goto the project folder and initialize a repo.
    ```
    $ git init
    ```
3. Add the remote url of created new repository 
    ````
    $ git remote add origin https://github.com/<username>/<repository>
    ````
4. Create a file named CNAME and write your custom domain name. For example "beautify.hemshrestha.com.np"
    ```
    $ echo git.yourdomain.com >> CNAME
    ```
5. Add files to repo
    ````
    $ git add .
    ````
6. Commit those addition
    ````
    $ git commit -m "first commit"
    ````
7. Push master branch
    ````
    $ git push origin master
    ````
8. Create a repo named gh-pages (github-pages)
    ````
    $ git checkout -b gh-pages
    ````
9. Push gh-pages branch to github
    ````
    $ git push origin gh-pages
    ````
10. Now the page will be live with the custom domain provided in CNAME file.


### Steps for CNAME pointing in your Nameserver
1. Login to your Nameserver Account. For example [afraid.org](https://afraid.org)
2. Click on Subdomain tab.
3. Click on add subdomain.
4. Add a CNAME record git.yourdomain.com to point github.io . For example beautify.hemshrestha.com.np CNAME github.io

    ````
    git.yourdomain.com 
    point CNAME record to 
    github.io
    
    ```` 
5. Save the record and wait for 10 minutes.
6. Browse git.yourdomain.com in the browser and you will see the data pushed in the repo.

#### Happy Browsing !!!