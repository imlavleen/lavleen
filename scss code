
@import "compass/reset";
@import "compass/css3";
@import url(http://fonts.googleapis.com/css?family=Open+Sans:400,400italic,800,300);

 /***** Colors *****/

$black:#222;
$lessblack:#333;
$lesserblack:#444;
$darkblue:#06A2CB;
$blue:#52ADDA;
$lessblue:#68B8DF;
$grey:#C9C9C9;
$lessgrey:#DBDBDB;
$white:#fafafa;
$darkpink:#cb2c54;
$pink:#d42a5c;
$lesserpink:#ec4c64;
$redpink: #E96D63;

/***** Mixins ******/

@mixin breakpoint($point) {
  @if $point == small {
    @media  only screen
            and (max-width: 600px)  {@content;}
  }
    @else if $point == medium {
      @media only screen
            and (max-width: 820px) { @content; }
    }
      @else if $point == larger {
        @media only screen 
            and (max-width: 1100px)  { @content; }
        }
}

/*****main*****/

.container {
    height:100%;
    width:100%;
}

/****body****/

body {
    background:url("img/___incredible_india___-wallpaper-2400x1350.jpg") no-repeat ;
    background-size:100% 100%;
}

/***sass begins***/

.slide {
   
    width:100%;
    height:100%;
    @include breakpoint(small) {min-height:400px;}
    a{
   text-decoration:none;
    color:white;
    &:hover{@include single-text-shadow(1px,1px);}
}
}
.slide1 {
    @extend .slide;
    width:100%;
    height:100%;
   
    .text {
        color:black;
        padding-top: 460px;
       
        padding-right:50px;
        
        text-shadow: 5px 5px 5px #CCFF66;
        font-family:serif;
        text-align:right;
     font-size: 70px;
     @include breakpoint(small) {
            font-size:15px; } 
            @include breakpoint(medium) {
            font-size:20px; } 
 }      
}



.slide2 {
    @extend .slide;
    width:100%;
    height:100%;
    background-color:black;
  .photobanner {
   z-index:1000;
        height: 233px;
        width: 2000px;
        margin-bottom: 80px;
    }
.first {
    -webkit-animation: bannermove 30s linear infinite;
       -moz-animation: bannermove 30s linear infinite;
        -ms-animation: bannermove 30s linear infinite;
         -o-animation: bannermove 30s linear infinite;
            animation: bannermove 30s linear infinite;
}
 
@keyframes "bannermove" {
 0% {
    margin-left: 0px;
 }
 100% {
    margin-left: -2125px;
 }
 
}
 
@-moz-keyframes bannermove {
 0% {
   margin-left: 0px;
 }
 100% {
   margin-left: -2125px;
 }
 
}
 
@-webkit-keyframes "bannermove" {
 0% {
   margin-left: 0px;
 }
 100% {
   margin-left: -2125px;
 }
 
}
 
@-ms-keyframes "bannermove" {
 0% {
   margin-left: 0px;
 }
 100% {
   margin-left: -2125px;
 }
 
}
 
@-o-keyframes "bannermove" {
 0% {
   margin-left: 0px;
 }
 100% {
   margin-left: -2125px;
 }
 
}
.photobanner img {
    -webkit-transition: all 0.5s ease;
    -moz-transition: all 0.5s ease;
    -o-transition: all 0.5s ease;
    -ms-transition: all 0.5s ease;
    transition: all 0.5s ease;
}
 
.photobanner img:hover {
    -webkit-transform: scale(1.1);
    -moz-transform: scale(1.1);
    -o-transform: scale(1.1);
    -ms-transform: scale(1.1);
    transform: scale(1.1);
    cursor: pointer;
 
    -webkit-box-shadow: 0px 3px 5px rgba(0,0,0,0.2);
    -moz-box-shadow: 0px 3px 5px rgba(0,0,0,0.2);
    box-shadow: 0px 3px 5px rgba(0,0,0,0.2);
}
 }   
