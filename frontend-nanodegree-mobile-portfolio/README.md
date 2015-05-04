P4 README by Ina Semionova

TESTING INSTRUCTIONS

- Clone https://github.com/innac/frontend-nanodegree-mobile-portfolio
- for testing index.html on PageSpeed Insights I have used webserver 'python -m SimpleHTTPServer 8080' and
	'./ngrok html 8080'
- for pizza.html - loaded page on the browser from the local repository;
- Original files with comments can be found in 'Original Files' folder for Part II;

NOTES

PART I

- Minified CSS file and inlcuded it inside HTML;
- minified perfmatters.js;
- added async attributes to javascript file links;
- moved Google Analytics script to the bottom of the <body>;
- replaced GOOGLE font with basic web safe font;
- compressed images with www.tinypng.com;
- created pizzeria-thumb.jpg file; 
- last PSI results were: Mobile - 91 and Desktop - 93;


PART II

- First I replaced 'querySelector' to 'getElementById' and 'querySelectorAll' to 'getElementsByClassName';
- Optimized 'for' loops: moved some variables to the global scope which helped speed up loading process, optimized variable names a bit (e.g. cols => c);
- Optimized images on www.tinypng.com. Resized pizza.png and cropped unnecessary transperancy which reduced file size even more. Resized pizzaria.jpg too. All these changes lowered paint time;
- Used some CSS properties (backface-visibility and transfrom) to add images into composite layers;
- Removed comments and minified javascript;


REFERENCES

- Google Developers documentation;
- Udacity Forums, Office Hours
- https://github.com/udacity/fend-office-hours/tree/master/Web%20Optimization/Effective%20Optimizations%20for%2060%20FPS
- http://www.w3schools.com/css/css3_2dtransforms.asp
-https://msdn.microsoft.com/library/bzt2dkta(v=vs.94).aspx
 






