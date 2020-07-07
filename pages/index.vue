<template>
<b-container fluid="xxl" class="p-0">
  <div class="container">
        <div class="notification">
            <div class="container">
                <div class="row grid-category">
                  <b-row >
                    <b-col sm="12" md="6" xl="6" offset-md="2" offset-xl="3" >
                      <p>
                            By accessing and using this website, you acknowledge that you have read and
                            understand our <a href="">Cookie Policy</a>, <a href="">Privacy Policy</a>, and our <a href="">Terms of Service</a>.
                        </p>
                    </b-col>
                    <b-col sm="3" offset-sm="1" md="2" xl="1" class="pl-0 ml-2" >
                      <b-button class="btn btn-notification btn-sm pb-1 pt-1 mt-1">Got it</b-button>
                    </b-col>
                  </b-row>
                </div>
            </div>
        </div>
        <div class="jumbotron">
            <div class="container">
                <div class="row grid-category">
                    <div class="logo">
                        <img src="~assets/y-logo-white.png" alt="Logo"/>
                    </div>
                </div>
                <div class="greeting row grid-category grid-align-center grid-jc-center">
                    <div class="">
                        <h1>Hello! I'm Abdullah Zaky</h1>
                        <h3>Consult, Design and Develop Websites</h3>

                        <p>Have something great in mind? Feel free to contact me.</p>
                        <p>I'll help you to make it happen.</p>

                        <button class="btn btn-bordered btn-transparent u-mt-20">
                            LET'S MAKE CONTACT
                        </button>
                    </div>
                </div>
            </div>
        </div>
    <section class="highlight u-py-28">
      <!-- <b-container fluid="lg" > -->
        <div class="container">
            <b-row>
              <b-col xl="6" offset-xl="3" class="p-5 u-tx-align-center highlight-header">
                    <h2 class="u-tx-300">How Can I Help You?</h2>
                    <p>Our work then targeted, best practices outcomes social innovation synergy.
                    Venture philanthropy, revolutionary inclusive policymaker relief. User-centered
                    program areas scale.</p>
                </b-col>
            </b-row>
            <div class="row u-mt-52 grid-category">
                <div class="highlight-wrapper col-12 col-sm-6 col-md-6 col-lg-4">
                    <div class="highlight-content">
                        <article>
                            <h4>Consult</h4>
                            <p>
                                Co-create, design thinking; strengthen infrastructure resist granular.
                                Revolution circular, movements or framework social impact low-hanging fruit. 
                                Save the world compelling revolutionary progress.    
                            </p>
                            
                            <font-awesome-icon :icon="['far', 'comments']" class="iconFa" />
                        </article>
                    </div>
                </div>
                
                <div class="highlight-wrapper col-12 col-sm-6 col-md-6 col-lg-4">
                    <div class="highlight-content">
                        <article>
                            <h4>Design</h4>
                            <p>
                                Policymaker collaborates collective impact humanitarian shared value
                                vocabulary inspire issue outcomes agile. Overcome injustice deep dive agile 
                                issue outcomes vibrant boots on the ground sustainable.                        
                            </p>
                            <font-awesome-icon :icon="['fas', 'paint-brush']" class="iconFa" />
                        </article>
                    </div>
                </div>

                <div class="highlight-wrapper col-12 col-sm-6 col-md-6 col-lg-4">
                    <div class="highlight-content">
                        <article>
                            <h4>Develop</h4>
                            <p>
                                Revolutionary circular, movements a or impact framework social impact low-
                                hanging. Save the compelling revolutionary inspire progress. Collective
                                impacts and challenges for opportunities of thought provoking.
                            </p>
                            <font-awesome-icon :icon="['fas', 'cubes']" class="iconFa" />
                        </article>
                    </div>
                </div>
                <div class="highlight-wrapper col-12 col-sm-6 col-md-6 col-lg-4">
                    <div class="highlight-content">
                        <article>
                            <h4>Marketing</h4>
                            <p>
                                Peaceful; vibrant paradigm, collaborative cities. Shared vocabulary agile,
                                replicable, effective altruism youth. Mobilize commitment to overcome
                                injustice resilient, uplift social transparent effective.
                            </p>
                            <font-awesome-icon :icon="['fas', 'bullhorn']" class="iconFa" />
                        </article>
                    </div>
                </div>
                
                <div class="highlight-wrapper col-12 col-sm-6 col-md-6 col-lg-4">
                    <div class="highlight-content">
                        <article>
                            <h4>Manage</h4>
                            <p>
                                Change-makers innovation or shared unit of analysis. Overcome injustice
                                outcomes strategize vibrant boots on the ground sustainable. Optimism,
                                effective altruism invest optimism corporate social.                            
                            </p>
                            <font-awesome-icon :icon="['fas', 'bars']" class="iconFa" />
                        </article>
                    </div>
                </div>
                
                <div class="highlight-wrapper col-12 col-sm-6 col-md-6 col-lg-4">
                    <div class="highlight-content">
                        <article>
                            <h4>Evolve</h4>
                            <p>
                                Activate catalyze and impact contextualize humanitarian. Unit of analysis
                                overcome injustice storytelling altruism. Thought leadership mass 
                                incarceration. Outcomes big data, fairness, social game-changer.                              
                            </p>
                            <font-awesome-icon :icon="['fas', 'chart-line']" class="iconFa" />
                        </article>
                    </div>
                </div>
                
                
            </div>
        </div>
      <!-- </b-container> -->
    </section>
    <div class="newsletter">
        <h4>Get latest updates in web technologies</h4>
        <p>
            I write articles related to web technologies, such as design trends, development
            tools, UI/UX case studies and reviews, and more. Sign up to my newsletter to get
            them all.                
        </p>
        <b-row>
          <b-col xl="9" class="px-2">
                <input type="text" name="email" placeholder="Email address" class="newsletter-input small u-full-width"/>
          </b-col>
          <b-col xl="3"  class="px-2">
                <b-button squared class="btn btn-small btn-orange u-full-width">Count me in!</b-button>
          </b-col>
        </b-row>
        <button
          type="button"
          class="newsletter1 btn-newsletter-close"
        >
          <i class="fas fa-times"></i>
        </button>
    </div>  
    <footer>
        <div class="footer">
            &copy; 2020 Abdullah Zaky. All rights reserved.
        </div>
    </footer>
  </div>
</b-container>
</template>

<script>
import $ from 'jquery'

export default {

  mounted: () => {
const notification = $('.notification')
const newsletter = $('.newsletter')
const btnNotification = $('.btn-notification')
const btnNewsletterClose = $('.btn-newsletter-close')
let showNewsletter = true

const handleNotificationOnWindowScroll = (evt) => {
    const notifHeight = notification.height()
    const scrollPosition = $(window).scrollTop()
    if(scrollPosition >= notifHeight){
        notification.addClass('fixed')
    }else{
        notification.removeClass('fixed')
    }
}
const handleNewsletterOnWindowScrooll = (evt) => {
    const windowHeight = $(window).height()
    const scrollPosition = $(window).scrollTop()
    const actionStart = windowHeight / 3

    if(scrollPosition >= actionStart && showNewsletter){
        newsletter.addClass('show')
    }
}
const handleCloseNotification = (evt) => {
    notification.slideUp()
}
const handleCloseNewsletter = (evt) => {
    newsletter.removeClass('show')
    showNewsletter = false
    setTimeout(() => {
        showNewsletter = true
    }, 1000 * 60 * 10)
}
$(document).ready(() => {
    $(window).on('scroll', () => {
        handleNotificationOnWindowScroll()
        handleNewsletterOnWindowScrooll()
    })
    btnNotification.click(handleCloseNotification)
    btnNewsletterClose.click(handleCloseNewsletter)
})
  }
}
</script>
<style lang="scss" scoped>
@import 'assets/scss/custom-vars.scss';
@import '../node_modules/bootstrap/scss/bootstrap';
@import '../node_modules/bootstrap-vue/src/index.scss';
*,:after,:before{-webkit-box-sizing:border-box;-moz-box-sizing:border-box;box-sizing:border-box}html{font-size:10px;-webkit-tap-highlight-color:rgba(0,0,0,0)}
html{
    line-height: 12px;
    font-size: 12px;
}body{
    margin: 0;
    padding: 0;
    color: #434755;
    font-family: 'Roboto', sans-serif;
    background-color: white;
    font-size: 12px;
    line-height: 14px;
}p{
    font-size: 1rem;
    line-height: 1.4rem;
    margin: 0;
    font-weight: 300;
}h1,h2,h3,h4,h5{
    line-height: 1;
}h1{
    font-size: 3rem;
}h2{
    font-size: 2.8rem;
}h3{
    font-size: 2.6rem;
}h4{
    font-size: 2;
    font-weight: 300;
}a{
    text-decoration: none;
    color: #007bc1;
    font-weight: 400;
}input{
     padding: 10px 16px;
    height: 35px;
    border-radius: 4px;
    border-style: solid;
    border-width: 1px;
    border-color: #DCDEE3;
    &.small{
        padding: 5px 8px;
        height: 25px;
    }
}.notification{
    height: auto;
    background-color: #F8FBFC;
    padding-top: 10px;
    padding-bottom: 10px;
    width: 100%;
    position: relative;
    &.fixed{
        position: fixed;
        top: 0;
        z-index: 5;
    }
}button{
    background-color: #007bc1;
    color: white;
    border-radius: 4px;
    padding: 10px 16px;
    font-size: 1rem;
    border: transparent;
    font-weight: 300;
    outline: none;
}.jumbotron{
    background: #004a75 url('~assets/work-desk__dustin-lee.jpg') center center no-repeat;
    background-blend-mode: multiply;
    background-size: cover;
    border-radius: 0;
    // width: 100%;
    height: calc(100vh - 50px);
    position: relative;
    & > .container{
        height: 100%;
    }.logo{
        padding-top: 15px;
        position: absolute;
        top: 0;
        img{
            height: 35px;
        }
    }h1{
        font-weight: 300;
        margin-bottom: 10px;
    }h3{
        font-weight: 400;
        margin-top: 10px;
    }p{
        font-size: 1.2rem;
        line-height: 1.3;
        font-weight: 100;
    }
}.greeting{
    height: calc(100% - 50px);
    color: white;
    text-align: center;
}.highlight{
    background-color: #EFF3F6;
}.newsletter-input {
  border-radius: 0;
}.highlight-header{
    padding-left: 72px;
    padding-right: 72px;
    p{
        line-height: 1.5;
        letter-spacing: .5px;
    }
}.highlight-wrapper{
    padding: 10px;
}.highlight-content{
    border: 1px solid #F8FBFC;
    outline: 1px solid #DCDEE3;
    padding: 15px;
    height: 100%;
    position: relative;
    h4{
        margin: 0;
        line-height: 2;
    }.iconFa{
        position: absolute;
        right: 20px;
        top: 20px;
        font-size: 2rem;
        color: #9C9DA6;
    }
}.newsletter1{
    position: absolute;
    right: 10px;
    top: 10px;
    cursor: pointer;
    background-color: transparent;
}.newsletter{
    max-width: 640px;
    position: fixed;
    bottom: -500px;
    // left: 0;
    background-color: rgba(0, 123, 193, .9);
    color: white;
    padding: 20px;
    transition: bottom ease .5s;
    &.show{
        bottom: 0;
        transition: bottom ease .5s;
    }h4{
        margin: 15px 0;
        font-size: 1.8rem;
    }p{
        margin-bottom: 15px;
    }
}.footer{
    background-color: #111c45;
    padding: 25px;
    color: #9C9DA6;
    text-align: center;
}
@media(max-width: 980px){
    .notification{
        button{
            margin-top: 7px;
            padding: 6px 7px;
            height: 25px;
        }
    }.jumbotron{
        padding: 10px 20px;
        // height: auto;
    }.greeting{
        margin-top: 20px;
        h1{
            font-size: 2rem;
            line-height: 1;
            margin-top: 5px;
            margin-bottom: 0;
        }h3{
            font-size: 2rem;
            line-height: 1;
            margin-top: 5px;
        }
    }.highlight{
        padding: 15px;
    }.highlight-header{
        padding-left: 0;
        padding-right: 0;
        h2{
            margin-bottom: 15px;
        }
    }.newsletter{
        &-input{
            padding-left: 0;
            margin-bottom: 10px;
        }
    }
}
.btn{
    background-color: #007bc1;
    color: white;
    border-radius: 4px;
    padding: 10px 16px;
    font-size: 1rem;
    border: transparent;
    font-weight: 400;
    transition: all ease .2s;
    &-transparent{
        background-color: transparent;
        &:hover{
            background-color: white;
            color: #007bc1;
            transition: all ease .2s;
        }
    }&-bordered{
        border: 1px solid white;
    }&.btn-small{
        padding: 0px;
        height: 25px;
    }&.btn-orange{
        background-color: #ff8000;
        color: white;
    }
}
.container{
    max-width: 100%;
    padding: 0;
    margin-left: auto;
    margin-right: auto;
    &::before,
    &::after{
        display: table;
        content: " ";
    }
    &::after{
        clear: both;
    }
}.row{
    margin-right: -12px;
    margin-left: -12px;
    &::before,
    &::after{
        display: table;
        content: " ";
    }
    &::after{
        clear: both;
    }   
}
@media(max-width: 1366px){
    .container{
        max-width: 1366px;
    }
}
@media (max-width: 1366px) and (min-width: 1200px)  {
  .container{
        width: 100%;
    }}

@media(max-width:1200px){
    .container{
        max-width: 1200px;
        width: 100%;
    }
}
@media(max-width: 960px){
    .container{
        width: 100%;
    }.row{
        margin-right: 0;
        margin-left: 0;
    }
}
@media(max-width: 480px){
    .container{
        width: 100%;
    }.row{
        margin-right: 0;
        margin-left: 0;
    }
}
/* =======================================================================*//* =======================================================================*/
/*! grid.css */
/* =======================================================================*//* =======================================================================*/
.grid-category{
    display: flex;
    flex-wrap: wrap;
}.grid-jc-center{
    justify-content: center;
}.grid-align-center{
    align-items: center
}
$sizes:  1,2,3,4,5,6,7,8,9,10,11,12;
@mixin make-col-lg($index: 1){
    @each $value in $sizes {
        .col-#{$value} {
            width: percentage(1 / (12 / $value));
            float: left;
            position: relative;
            padding-left: 12px;
            padding-right: 12px;
        }.col-offset-#{$value}{
            margin-left: percentage($number: 1 / (12 / $value) * $index);
        }
    }
}
@mixin make-col-lg($index: 1){
    @each $value in $sizes {
        .col-lg-#{$value} {
            width: percentage(1 / (12 / $value));
            float: left;
            position: relative;
            padding-left: 12px;
            padding-right: 12px;
        }.col-lg-offset-#{$value}{
            margin-left: percentage($number: 1 / (12 / $value) * $index);
        }
    }
}
@mixin make-col-md($index: 1){
    @each $value in $sizes {
        .col-md-#{$value} {
            width: percentage(1 / (12 / $value));
            float: left;
            position: relative;
            padding-left: 12px;
            padding-right: 12px;
        }.col-md-offset-#{$value}{
            margin-left: percentage($number: 1 / (12 / $value) * $index);
        }
    }
}
@mixin make-col-sm($index: 1){
    @each $value in $sizes {
        .col-sm-#{$value} {
            width: percentage(1 / (12 / $value));
            float: left;
            position: relative;
            padding-left: 12px;
            padding-right: 12px;
        }.col-sm-offset-#{$value}{
            margin-left: percentage($number: 1 / (12 / $value) * $index);
        }
    }
}
@media(max-width:1366px){
    .container{
        max-width: 1366px;
        width: 100%;
    }
    @include make-col-lg(0);
        @include make-col-md();
}
@media(max-width: 960px){
    .container{
        width: 100%;
    }
    @include make-col-lg(0);
        @include make-col-md();
}
@media(max-width: 480px){
    .container{
        width: 100%;
    }

    @include make-col-lg(0);
    @include make-col-sm(0);
}
@media(min-width:1360px){
    @include make-col-lg();
    @include make-col-sm();
}.u-tx-black{
    color: black;
}.u-tx-black-70{
    color: #151823;
}.u-tx-white{
    color: white;
}.u-tx-bold{
    font-weight: bold;
}.u-tx-300{
    font-weight: 300;
}.u-tx-400{
    font-weight: 400;
}.u-tx-100{
    font-weight: 100;
}.u-tx-align-right{
    text-align: right;
}.u-tx-align-center{
    text-align: center;
}
/* =======================================================================*/
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
/* =======================================================================*/
html {
  font-family: sans-serif; // 1
  -ms-text-size-adjust: 100%; // 2
  -webkit-text-size-adjust: 100%; // 2
}body {
  margin: 0;
}article,aside,details,figcaption,figure,footer,header,hgroup,main,menu,nav,section,summary {
  display: block;
}audio,canvas,progress,video {
  display: inline-block; // 1
  vertical-align: baseline; // 2
}audio:not([controls]) {
  display: none;
  height: 0;
}[hidden],template {
  display: none;
}a {
  background-color: transparent;
}a:active,
a:hover {
  outline: 0;
}abbr[title] {
  border-bottom: none; // 1
  text-decoration: underline; // 2
  text-decoration: underline dotted; // 2
}b,strong {
  font-weight: bold;
}dfn {
  font-style: italic;
}h1 {
  font-size: 2em;
  margin: 0.67em 0;
}mark {
  background: #ff0;
  color: #000;
}small {
  font-size: 80%;
}sub,sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}sup {
  top: -0.5em;
}sub {
  bottom: -0.25em;
}img {
  border: 0;
}svg:not(:root) {
  overflow: hidden;
}figure {
  margin: 1em 40px;
}hr {
  box-sizing: content-box;
  height: 0;
}pre {
  overflow: auto;
}code,kbd,pre,samp {
  font-family: monospace, monospace;
  font-size: 1em;
}
// ==========================================================================
// Forms
// ==========================================================================
button,input,optgroup,select,textarea {
  color: inherit; // 1
  font: inherit; // 2
  margin: 0; // 3
}button {
  overflow: visible;
}button,
select {
  text-transform: none;
}button,
html input[type="button"], // 1
input[type="reset"],
input[type="submit"] {
  -webkit-appearance: button; // 2
  cursor: pointer; // 3
}button[disabled],
html input[disabled] {
  cursor: default;
}button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}input {
  line-height: normal;
}input[type="checkbox"],
input[type="radio"] {
  box-sizing: border-box; // 1
  padding: 0; // 2
}input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  height: auto;
}input[type="search"] {
  -webkit-appearance: textfield; // 1
  box-sizing: content-box; //2
}input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em;
}legend {
  border: 0; // 1
  padding: 0; // 2
}textarea {
  overflow: auto;
}optgroup {
  font-weight: bold;
}table {
  border-collapse: collapse;
  border-spacing: 0;
}td,th {
  padding: 0;
}
//Spacing
$sizes:  0, 4, 8, 12, 16, 20, 24, 28, 32, 36, 40, 44, 48, 52, 56, 80;
@each $value in $sizes {
    .u-pt-#{$value} {
        padding-top: ($value*1px);
    }.u-pr-#{$value} {
        padding-right: ($value*1px);
    }.u-pb-#{$value} {
        padding-bottom: ($value*1px);
    }.u-pl-#{$value} {
        padding-left: ($value*1px);
    }.u-p-#{$value} {
        padding: ($value*1px)!important;
    }.u-px-#{$value} {
        padding-left: ($value*1px)!important;
        padding-right: ($value*1px)!important;
    }.u-py-#{$value} {
        padding-top: ($value*1px);
        padding-bottom: ($value*1px);
    }
};
@each $value in $sizes {
    .u-mt-#{$value} {
        margin-top: ($value*1px);
    }.u-mr-#{$value} {
        margin-right: ($value*1px);
    }.u-mb-#{$value} {
        margin-bottom: ($value*1px);
    }.u-ml-#{$value} {
        margin-left: ($value*1px);
    }.u-m-#{$value} {
        margin: ($value*1px);
    }.u-mx-#{$value} {
        margin-left: ($value*1px);
        margin-right: ($value*1px);
    }.u-my-#{$value} {
        margin-top: ($value*1px);
        margin-bottom: ($value*1px);
    }};.u-m-auto{
    margin: auto;
}.u-mx-auto{
    margin-left: auto!important;
    margin-right: auto!important;
}.u-my-auto{
    margin-top: auto;
    margin-bottom: auto;
}.u-full-width{
    width: 100%;
}
</style>
