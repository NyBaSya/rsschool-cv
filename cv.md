
# **Dzmitry** **Byk**
**23 years old**
**Minsk**

## **Contacts**
Phone number: +375(29) 818-53-08
Email: dmitry.byk.brz@gmail.com

## **Summary**
I want to become the front-end boss.

## **Skills**
* HTML/CSS
* Basic JavaScript
* Regular Expressions
* Bootstrap
* jQuery
* React
* SCSS
* Adobe Photoshop

## **Code examples
```sh
//HTML theyalow
<!DOCTYPE html>
  <html>
    <head>
      <title></title>
      <link rel="stylesheet" type="text/css" href="style.css">
    </head>
  <body> 
    <div class="layout-positioner">
      <header class="header">
        <div class="logo">
          <div class="logo_img_1"></div>
          <div class="logo_img_2"></div>
            <h1 class="header_title">
              THEYALOW
            </h1>
        </div>
        <nav class="header_nav">
          <ul class="header_menu">
            <li class="header_menu_item">ABOUT US</li>
            <li class="header_menu_item">SERVICES</li>
            <li class="header_menu_item">CONTACT</li>
          </ul>
        </nav>
      </header>

    <main class="main"> 
      <section class="section_one">
        <div class="section_one_image">
          <img src="image/player.png" alt="player">
        </div>
        <div class="section_one_title">
          <h2>THE COOL</h2>
          <h2>THE MINIMAL</h2>
        </div>
      </section>

      <section class="section_two">
        <div class="section_two_item">
          <img src="image/shape_two.svg" alt="better design">
          <div>BETTER DESIGN</div>
        </div>
        <div class="section_two_item">
          <img src="image/shape_three.svg" alt="better design">
          <div>CUSTOMISE</div>
        </div>
        <div class="section_two_item">
          <img src="image/shape_four.svg" alt="better design">
          <div>ITS FREE</div>
        </div>
      </section>

      <section class="section_three">
        <h2>LOREM ISPUM DOLOR SIT AMET</h2>
        <div class="section_three_content">
          <div class="section_three_content_video">
            <div class="section_three_content_video_desription">
              <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor inci-didunt ut</span>
            </div>
            <div class="section_three_content_video_movie">
              <img src="image/section-three-video.png" alt="video">
            </div>
          </div>
          <div class="section_three_logo">
            <span>22</span>
            <img src="image/twitter-logo.svg" alt="twitter">
          </div>
        </div>
        <div class="section_three_data">
          <span>25</span>
          <span>April</span>
        </div>
      </section>
      <section class="section_four">

      </section>
    </main>

    <footer class="footer">
    </footer>
    
    </div>
  </body> 
</html>
``` 
```sh
//CSS they
@font-face {
	font-family: "SegoeWP Light";
	src: url('fonts/SegoeWPLight.ttf');

}

@font-face {
	font-family: "Asap-Regular";
	src: url('fonts/Asap-Regular.ttf');

}

@font-face {
	font-family: "LucidaSans";
	src: url('fonts/LucidaSans.ttf');

}

body {
	width: 1300px;
	margin: 0 auto;
	border: 2px dashed;
	background-image: url('image/background-header.png');
	background-repeat: no-repeat;
	background-position: center;
	height: 566px;

}

.layout-positioner {
	width: 1020px;
	margin: 0 auto;
	border: 2px dashed green;

}

.header {
	display: block;
	overflow:	hidden;
	position: relative;
	top: 28px;
	height: 84px;
	border: 2px dashed red;
}

.header_nav {
	float: right;
	width: 462px;
}

.logo {
	float: left;
}

.logo_img_1 {
	float: left;
	position: absolute;
	margin: 0 0;
	width: 84px;
	height: 84px;
	background-image: url('image/logo_1.png');
	background-repeat: no-repeat;
	z-index: 0;
	
}

.logo_img_2 {
	float: left;
	position: absolute;
	margin: 0 0 0 3px;
	width: 84px;
	height: 84px;
	background-image: url('image/logo_2.png');
	background-repeat: no-repeat;
	z-index: 1;
}

.header_title {
	float: left;
	position: relative;
    left: 92px;
	margin: 0 0;
	font-family: LucidaSans;
	font-size: 41.05px;
	color: #ffffff;
	height: 84px;
	padding-top: 21px;
}

li {
	list-style-type: none;
}

.header_menu {
	border: 2px dashed grey;
}

.main {
	overflow:hidden;
	position: relative;
    top: 56px;
}

.section_one {
	display: grid;
	grid-template-columns: 1fr 1fr;
	border: 1px solid yellow;
}

.section_one_title, .section_one_image {
	margin: 0 auto;
	align-self: center;
	justify-content: center;
	
}

.section_one_image {
	width: 557px;
    height: 336px;
}

.section_one_title {
	text-align: center;
	width: 408px;
    height: 327px;
}

.section_one_title h2:first-child{
	color: #f5c506;
	text-align: center;
	font-size: 63.05px;
	font-family: Asap-Regular;
}

.section_one_title h2:last-child {
	color: #ffffff;
	font-size: 63.05px;
	font-family: Asap-Regular;
}

.section_two {
	display: grid;
	grid-template-columns: 1fr 1fr 1fr;
	position: relative;
	top: 83px;
	border: 1px solid yellow;
	height: 212px;
}

.section_two_item {
	height: 212px;
	display: grid;
	justify-content: center;
	align-self: center;
	text-align: center;
	margin-top: 30px;
}

.section_two_item * {
	align-self: center;
}

.section_two_item img {
	width:100%;
	height: 100%;
}

.section_two_item span {
	display: block;
}

.section_three {
	position: relative;
    top: 62px;
	background-image: url('image/background-section-three.png');
	background-size: cover;
	height: 510px;
}

.section_three h2 {
	color: white;
}

.section_three_content {
	justify-content: center;
	display: flex;
}

.section_three_content_video {
	display: flex;
}

.section_three_content_video_desription {
	width: 341px;
	font-size: 30px;
	background-color: #ec9e03;
	color: white;

}

.section_three_content_video_desription span {
	font-family: SegoeWP Light;
	padding: 32px;
	display: block;
}

.section_three_logo {
	margin-left: 30px;
	background-color: #ec9e03;
	width: 315px;
	display: flex;
    justify-content: center;
    align-items: center;
}

.section_three_logo img {

	margin-left: 25%;
    margin-top: 25%;
}

.section_three_content_video_movie img{
	width: 100%;
	height: 100%
}

.section_four {
	height: 498px;
}

.footer {
	height: 200px;
}
```

## **Experience**
1. https://www.codecademy.com/
2. https://htmlacademy.ru/
3. https://www.freecodecamp.org/
4. https://www.codewars.com/

## **Education**
* Belarusian State University — Mechanics and Mathematics faculty — Department of Theoretical and Applied Mechanics.
* Online courses: _codecademy, htmlacademy, freecodecamp, codewars_.
* Angular Minsk Meetup #4
* Facebook Developer Circles Meetup

## **English**
Pre-Intermediate English (during university)

