# PHP + Tailwind CSS

Start simple project with PHP + Tailwind CSS

[![Watch the video](https://i.imgur.com/8bmtu3p.png)](https://youtu.be/LT-gHhmM_6o)

### Instalation


##### Download
```sh
curl -L https://raw.githubusercontent.com/wezoalves/php-tailwindcss/main/project-init.sh | bash
```

##### Init Project
```sh
sh project-init.sh
```

##### Tailwind CSS Watch
```sh
sh project-watch.sh
```

##### PHP Server Local
```sh
sh project-server.sh
```


##### Project Structure
```code
- dist/
        input.css { file base tailwind css }
- lib/
        { yours class php where }
- public/
        index.php { file with logic to show files template}
        .htaccess
        asset/
            css/
                style.css
            img/
                { static files image }
            js/      
                { static files javascript }
- template/
        footer.html
        header.html
        module/
               home.html
               {NEW FILES HERE eg: pricing.html }
- .gitignore
- .htaccess
- package.json
- tailwind.config.js
                                 
```

### Edit Project

##### Add new Page

 To add a new page for example **pricing**
 create a pricing.html file in the **/template/module/** folder
 at the end it will be: **/template/module/pricing.html**
 in other html files you must add the call **?page=pricing** in links

##### Run this command in terminal
```sh
printf '<h1>My Page Pricing</h1>\n<p>Content Here</p>' > template/module/pricing.html
```
