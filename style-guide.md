# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Soft orange: hsl(35, 77%, 62%)
- Soft red: hsl(5, 85%, 63%)

### Neutral

Off-white: hsl(36, 100%, 99%)
Grayish blue: hsl(233, 8%, 79%)
Dark grayish blue: hsl(236, 13%, 42%)
Very dark blue: hsl(240, 100%, 5%)

## Typography

### Body Copy

- Font size (paragraph): 15px

### Font

- Family: [Inter](https://fonts.google.com/specimen/Inter)
- Weights: 400, 700, 800



/* Desktop version   */


body {
    font-family: Inter; src: url(https://fonts.google.com/specimen/Inter);

}   

main {
    display: flex;
}

.article-future {
    width: 1440px;
    height: 440px;
    background-color: hsl(36, 100%, 99%); 
    margin-top: 50px;
    margin-left: 50px;
    margin-right: 0px;
    padding-right: 1px;
   

 } 

 /* Image */   
.bright-img {
    width: 900px;
    height: 250px;
    object-fit: cover;
}

.bright-div {
    display: inline-block;
}

h1 {
    font-size: 40px;
    font-weight: 800;
    white-space: nowrap;
    display: inline;
    margin-top: 5px;
 }

 .bright-text {
    font-size: 400;

 }

 .btn {
    background-color: hsl(5, 85%, 63%);
    width: 200px;
    height: 40px;
    text-align: center;
    font-weight: bold;
    color: antiquewhite;
    letter-spacing: 0.5em;
    border-color:  hsl(36, 100%, 99%);
    align-content: flex-end;
    margin-top: 55px;
    cursor: pointer;

 } 
 
 


 .flex-box {
    display: flex;
    background-color: hsl(36, 100%, 99%);

  
 }

 .text-flex {
    align-content: end;
    margin-left: 300px;
 } 
   
.article-new {
    background-color: hsl(240, 100%, 5%);
    height: 440px;
    margin-left: 0px;
    margin-top: 50px;
    margin-left: 50px;
    margin-right: 50px;
    
    

}



h3 {
    color: hsl(35, 77%, 62%);
    font-size: 25px;
    margin-left: 10px;
    padding-top: 20px;
    
}

h4 {
    color: hsl(36, 100%, 99%);
    margin-left: 10px;

}

.new-text {
    color: hsl(36, 100%, 99%);
    margin-left: 10px;
    font-size: small;

}

.horizontal-line {
    border-top: 1px solid hsl(236, 13%, 42%);
}