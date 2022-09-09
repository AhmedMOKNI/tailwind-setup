# Installation &amp; commissioning of Tailwind 
## Using PostCSS
Complete tutorial on how to install TailWind as PostCSS in VSCode. 
  
**Step-1 Install NodeJS**  
You need to install Node JS before starting TailWind CSS Download Node JS at nodejs.org/en/download. Then install it on your system.  
  
**Step-2 Make package.json file**
```
npm init
```
  
**Step-3 install tailwind and postcss**
```
npm install -D tailwindcss postcss-cli autoprefixer
```
  
**Step-4 make postcss.config.js**
```
touch postcss.config.js
```
  
**Step-5 add base config to postcss.config.js**
```
module.exports = {
    plugins: {
      tailwindcss: {},
      autoprefixer: {},
    }
  }
```


