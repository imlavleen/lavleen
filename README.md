lavleen
=======

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

/*****main*****/

.container {
  height:100%;
  width:100%;
}

/****body****/

body {
 background:url("img/1.jpg") no-repeat;
 background-size:100% 100%;
}


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

/***sass begins***/

.slide {
   
    border-bottom:1px dashed $black;
    width:100%;
    height:100%;
    @include breakpoint(small) {min-height:400px;}
}

.slide1 {
  @extend .slide;
  width:100%;
  height:100%;

}   

.slide2 {
  @extend .slide;
  width:100%;
  height:100%;
}

.slide3 {
  @extend .slide;
  width:100%;
  height:100%;
}

.slide4 {
  @extend .slide;
  width:100%;
  height:100%;
}

.slide5 {
  @extend .slide;
  width:100%;
  height:100%;
}


/**header**/

  .head {
    background:transparent;
    width:100%;
    min-height:40px;
    z-index:1100;
    position:fixed;
    @include breakpoint(small) { position:absolute;}
}

/**** Header End *****/

.navbar {
    width:90%;
    max-width:1100px;
    margin:auto;
        li {
            float:left;
            width:18%;
            text-align:center;
            line-height:50px;
            font-size:1.6rem;
            border-bottom:2px solid $black;
            &:hover{border-bottom:2px solid $pink;
            }
            @include breakpoint(large) {font-size:1.4rem; float:right; width:136px;}
            @include breakpoint(medium) {font-size:1.3rem; width:33%;}
            @include breakpoint(small) {display:none;}
        }
        }



