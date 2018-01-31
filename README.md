# sass-starter

make an index.html and connect to css 

    IN SASS
    we created some body styles, in this case, font-stack and primary-color
    
    IN TERMINAL
    now we connected our main.scss to the css in the terminal see sassTerminalNotes.png

    each time you update your scss, you must recompile via terminal <<sass scss/main.scss css/main.css>> (you'll notice the update in your css file)

    http://sass-lang.com/guide this is a good place to look at what you can do with sass

        we copied the nesting section and included it

    MAKE A NEW PARTIAL FILE
    use an _ in front of your file name to denote a partial file 
        ex) "_reset.scss" 
    The underscore lets Sass know that the file is only a partial file and that it should not be generated into a CSS file.

    We created a partial file that resets the browser (see "_reset.scss")
        link to the main.scss file by including @import: 'reset' (extension not needed)
    
    IN SASS 
    we copied and pasted the @mixin example (http://sass-lang.com/guide)
        
        this is a good way to include a few css values almost as a function. 
        Look at the difference between @mixin border-radius in the sass and the css

    we copied and pasted the extend/inheritance example (http://sass-lang.com/guide)

*********************BEFORE YOU PUSH TO GITHUB****************
 
 make sure your .gitigore includes: 
    .DS_Store
    css/
    .sass-cache/

when you git add **DO NOT** include .sass-cache/


