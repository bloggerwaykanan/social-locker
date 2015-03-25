/**
* Basic styles
*/

/* locker text */
.onp-sociallocker .onp-sociallocker-strong,
.onp-sociallocker .onp-sociallocker-message, 
.onp-sociallocker .onp-sociallocker-timer,
.onp-sociallocker .onp-sociallocker-error-title,
.onp-sociallocker-error-text {
    font: normal normal 400 13px/23px "Arial", "Helvetica", sans-serif;;
    color: #111;
}

.onp-sociallocker iframe {
   margin: 0px !important;
}

/* locker containers */
.onp-sociallocker, 
.onp-sociallocker .onp-sociallocker-outer-wrap, 
.onp-sociallocker .onp-sociallocker-inner-wrap {
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
}

/* Error that is rised when the locker is setup incorrect. */
.onp-sociallocker-error {
    display: block !important;
    padding: 20px !important;
    font: normal normal 400 12px/18px "PT Sans", sans-serif !important;
    background-color: #ffebe8 !important;
    border: 1px solid #dd3c10 !important;
    text-align: left !important;
    -webkit-text-shadow: none !important;
    -moz-text-shadow: none !important;
    text-shadow: none !important;
    margin: 20px 0 !important;
    color: #000 !important;
}

.onp-sociallocker {
    position: relative !important;
    background-color: #f9f9f9;
    padding: 25px;
    margin: 20px auto;
    max-width: 650px;
}
.onp-sociallocker p {
    margin: 0px;
}

/**
* Locker Messages
*/

.onp-sociallocker .onp-sociallocker-text {
    text-align: center;
}
.onp-sociallocker-text .onp-sociallocker-strong {
    font-size: 16px;
    font-weight: bold;
    display: inline-block;
}

/**
* Locker Errors
*/

.onp-sociallocker-state-error .onp-social-button {
    display: none;
}
.onp-sociallocker .onp-sociallocker-error-body {
    text-align: center;
}
.onp-sociallocker .onp-sociallocker-error-title, 
.onp-sociallocker .onp-sociallocker-error-text {
    text-shadow: none;
}
.onp-sociallocker .onp-sociallocker-error-title {
    text-align: center;
    display: inline-block;
    background-color: #cc0000;
    font-size: 14px;
    line-height: 100%;
    padding: 4px 10px;
    color: #fff;
    vertical-align: top;
}
.onp-sociallocker .onp-sociallocker-error-title:hover {
    background-color: #ee0000;
}
.onp-sociallocker .onp-sociallocker-error-text {
    background: #c00;
    color: #fff;
    padding: 10px;
    margin-top: 15px;
}
.onp-sociallocker .onp-sociallocker-error-body .onp-sociallocker-error-text {
    display: none;
}

/**
* Locker Buttons
*/

.onp-sociallocker-buttons {
    text-align: center;
}
.onp-sociallocker-text + .onp-sociallocker-buttons {
    margin-top: 5px;
}
.onp-sociallocker-button-inner-wrap {
    height: 40px;
    min-width: 120px;
    padding: 10px;
    
    -webkit-box-sizing: border-box; 
    -moz-box-sizing: border-box;  
    box-sizing: border-box;
}
.onp-sociallocker-state-loading .onp-sociallocker-button-inner-wrap { 
    background: url('http://1.bp.blogspot.com/-rmBq4v6cP4w/U5qZZdqHAfI/AAAAAAAAARo/UC6aC0QqIU8/s1600/button-loader-f2f2f2.gif') 50% 50% no-repeat;
}

.onp-social-button {
    min-width: 104px;
}
/* facebook buttons, google buttons and tweet button always has the fixed size */
.onp-facebook-button, 
.onp-google-button, 
.onp-twitter-tweet {
    width: 104px;
}
.onp-sociallocker-button-overlay {
    width: 100%;
    border-bottom: none;
}

.onp-sociallocker-button-inner-wrap {
    position: relative;
}
.onp-sociallocker-button {
    display: inline-block;
    vertical-align: top;
    text-align: left;
}
.onp-sociallocker.onp-sociallocker-no-counters .onp-sociallocker-button {
    text-align: center;
}
.onp-sociallocker-button-overlay {
    position: absolute;
    top: 0px; left: 0px;
}
.onp-sociallocker-button {
    margin: 10px 5px 0 5px;
    background-color: #f2f2f2;
}
.onp-social-button {
    overflow: hidden;
    padding: 1px;
    position: relative;
    top: -1px;
}

.onp-sociallocker-opera .fb-like {
    position: relative;
    top: -2px;
}
.onp-sociallocker-button-facebook-like .fb-like span {
    vertical-align: top !important;
    -moz-box-sizing: content-box;
    box-sizing: content-box;
}

/* facebook share button */
.onp-facebook-share-button {
    line-height: 1%;
}
.onp-sociallocker-vertical .onp-facebook-share-button span {
    top: 1px;
}
.onp-facebook-share-button-overlay {
    position: absolute;
    top: 0px;
    right: 0px;
    bottom: 0px;
    left: 0px;
    background-color: rgba(255,255,255,0); 
    cursor: pointer;
    z-index: 20;
}
.onp-facebook-share-button-overlay:hover {
    background-color: rgba(255,255,255,0.1);  
}

/* remove the popup comment box */
.onp-sociallocker-button .fb-like span,
.onp-sociallocker-button .fb-like iframe {
    height: 22px;
}
.onp-sociallocker-button .fb-like span {
    overflow: hidden;
    padding: 0 1px;
}
.onp-sociallocker-button-unsupported {
    font-size: 10px;
    text-align: center;
    line-height: 13px;
}
/**
* Overlay for buttons
*/

.onp-sociallocker-button-overlay * {
    position: absolute;
    width: 100%;
    top: 0px;
    left: 0px;
}
.onp-sociallocker-overlay-front,
.onp-sociallocker-overlay-back {
    height: 100%;
    top: 0px;
    left: 0px;
    -moz-box-sizing: content-box;  
    box-sizing: content-box;
}

/**
* Helper tools (timer, close icon)
*/

.onp-sociallocker .onp-sociallocker-cross {
    background: url('http://3.bp.blogspot.com/-u2TLiDrfJYU/U5qZaUeRbyI/AAAAAAAAAR8/DUTwy-FZ1SE/s1600/close.png') 50% 50% no-repeat;
    width: 16px;
    height: 16px;
    opacity: 0.1;
    filter:progid:DXImageTransform.Microsoft.Alpha(opacity=10);
    cursor: pointer;
    position: absolute;
    top: 4px;
    right: 4px;
    z-index: 2;
}
.onp-sociallocker:hover .onp-sociallocker-cross {
    opacity: 0.2;
    filter:progid:DXImageTransform.Microsoft.Alpha(opacity=20);
}
.onp-sociallocker .onp-sociallocker-cross:hover {
    opacity: 0.8;
    filter:progid:DXImageTransform.Microsoft.Alpha(opacity=80);
}
.onp-sociallocker .onp-sociallocker-timer {
    position: absolute;
    right: 5px;
    bottom: 5px;
    z-index: 10;
}
.onp-sociallocker .onp-sociallocker-timer,
.onp-sociallocker .onp-sociallocker-timer * {
    font: normal normal 400 12px/12px sans-serif;
    text-transform: lowercase;
}
.onp-sociallocker .onp-sociallocker-timer {
    color: #000;
    margin-left: 5px;
}
.onp-sociallocker .onp-sociallocker-timer-counter {
    font-weight: bold;
}
.onp-google-button {
    position: relative;
}

/**
* Base styles of the flip effect
*/
.onp-sociallocker-flip .onp-sociallocker-button-inner-wrap
{
    perspective: 500px;
    perspective-origin: 50% 0;
    -webkit-perspective: 500px;
    -webkit-perspective-origin: 50% 0;
    -moz-perspective: 500px;
    -moz-perspective-origin: 50% 0;
}
.onp-sociallocker-flip .onp-sociallocker-button-overlay {
    display: block;

    transform-origin: bottom;
    transform-style: preserve-3d;		
    transition: transform .3s ease;
    transform: translate(0);

    -webkit-transform-origin: bottom;
    -webkit-transform-style: preserve-3d;
    -webkit-transition: -webkit-transform .3s ease;
    -webkit-transform: translateY(0) rotateX(0);

    -moz-transform-origin: bottom;
    -moz-transform-style: preserve-3d;		
    -moz-transition: -moz-transform .3s ease;
    -moz-transform: translate(0);
    
    text-decoration: none !important;
}
.onp-sociallocker-flip .onp-sociallocker-overlay-back 
{
    transform: rotateX(-180deg) translateZ(4px);
    -webkit-transform: rotateX(-180deg) translateZ(4px);
    -moz-transform: rotateX(-180deg) translateZ(4px);
}
.onp-sociallocker-flip .onp-sociallocker-overlay-header {
    height: 4px;
    
    transform-origin: top;
    transform: rotateX(-90deg);
    -webkit-transform-origin: top;
    -webkit-transform: rotateX(-90deg);
    -moz-transform-origin: top;
    -moz-transform: rotateX(-90deg);
}
.onp-sociallocker-touch .onp-sociallocker-button-overlay {
    cursor: pointer;
}
.onp-sociallocker-no-touch .onp-sociallocker-flip:hover .onp-sociallocker-button-overlay,
.onp-sociallocker-flip-hover .onp-sociallocker-button-overlay
{
     display: block !important;
    transform: translateY(4px) rotateX(-105deg);
    -webkit-transform: translateY(4px) rotateX(-105deg);
    -moz-transform: translateY(4px) rotateX(-105deg);
}
.onp-sociallocker-flip:hover .onp-sociallocker-overlay-back {
    border-top: 2px solid #eee;
}
.onp-sociallocker .onp-sociallocker-state-error.onp-sociallocker-button .onp-sociallocker-overlay-text {
    text-decoration: line-through;
    color: #fff;
    text-shadow: none;
}

/**
* Secrets style
*
* Credits:
* http://dribbble.com/shots/457259-Twitter-Button-Concept
* http://dribbble.com/shots/363710-Fb-Btn-Concept
* http://dribbble.com/shots/363401-Facebook-button-concept
* http://dribbble.com/shots/777465-Social-Sharing-Buttons
* http://dribbble.com/shots/684822-Free-Social-Button-PSD
*/

.onp-sociallocker-secrets .fb-like span,
.onp-sociallocker-secrets .fb-like iframe {
    width: 118px !important;
}
.onp-sociallocker-secrets {
    padding: 20px;
    margin: 10px auto 15px auto;
    border: 0px;

    background-color: transparent;
}
.onp-sociallocker-secrets .onp-sociallocker-inner-wrap {
    border: 3px solid #fefefe;
    background-color: #f7f7f7;
    padding: 30px;
}
.onp-sociallocker-secrets .onp-sociallocker-outer-wrap {
    border: 1px solid #e6e6e6;
    
    -moz-box-shadow: 0px 0px 40px rgba(0,0,0,0.08); 
    -webkit-box-shadow: 0px 0px 40px rgba(0,0,0,0.08);     
    box-shadow: 0px 0px 40px rgba(0,0,0,0.08);  
}
.onp-sociallocker-secrets .onp-sociallocker-text,
.onp-sociallocker-secrets  .onp-sociallocker-timer, 
.onp-sociallocker-secrets .onp-sociallocker-timer * {
    -webkit-text-shadow: 1px 1px 2px #fff;
    -moz-text-shadow: 1px 1px 2px #fff;
    text-shadow: 1px 1px 2px #fff;  
}
.onp-sociallocker-secrets .onp-sociallocker-text .onp-sociallocker-strong:before,
.onp-sociallocker-secrets .onp-sociallocker-text .onp-sociallocker-strong:after 
{
    content: '';
    display: inline-block;
    width: 11px;
    height: 14px;
    margin: 0 9px;
    background: url('http://3.bp.blogspot.com/-zh68d9Qv_cQ/U5qZboEospI/AAAAAAAAASw/fX_SFK1bdno/s1600/lock-icon.png') 0px 2px no-repeat;
}
@media screen and (max-width: 500px) 
{
    .onp-sociallocker-secrets .onp-sociallocker-text .onp-sociallocker-strong:before,
    .onp-sociallocker-secrets .onp-sociallocker-text .onp-sociallocker-strong:after 
    {
        display: none;
    }
}
.onp-sociallocker-secrets .onp-sociallocker-text .onp-sociallocker-strong:after {
    margin-left: 10px;
}
.onp-sociallocker-secrets .onp-sociallocker-button {
    padding: 4px;
    background: rgba(0, 0, 0, 0.05);
}
.onp-sociallocker-secrets .onp-sociallocker-button-inner-wrap, 
.onp-sociallocker-secrets .onp-sociallocker-button-overlay {
    height: 34px;
    min-width: 118px;
}
.onp-sociallocker-secrets .onp-sociallocker-button-inner-wrap{
    padding: 7px;
    -moz-box-shadow: inset 0px 0px 6px rgba(0, 0, 0, 0.25);
    -webkit-box-shadow: inset 0px 0px 6px rgba(0, 0, 0, 0.25);
    box-shadow: inset 0px 0px 6px rgba(0, 0, 0, 0.25);
}
.onp-sociallocker-secrets .onp-sociallocker-button .onp-sociallocker-overlay-front {
    background: #eaeaea;
    background-image: url('http://1.bp.blogspot.com/-XeR66KwhG5I/U5qZbx2MtDI/AAAAAAAAASU/MPyjCwtGZ2I/s1600/secrets-bg.png');
    background-repeat: repeat-x;
    box-shadow: inset 0 2px 0 rgba(255,255,255,.25);
    -moz-box-shadow: inset 0 2px 0 rgba(255,255,255,.25);
    -webkit-box-shadow: inset 0 2px 0 rgba(255,255,255,.25);
    position: relative;
}
.onp-sociallocker-secrets .onp-sociallocker-button .onp-sociallocker-overlay-icon {
    height: 34px;
    width: 44px;
    background: url('http://1.bp.blogspot.com/-0XAzn5_MtDA/U5qZcIegt6I/AAAAAAAAASY/MkLnSkKpoz0/s1600/social-icons.png') 0 50% no-repeat;
    position: absolute;
}
.onp-sociallocker-secrets .onp-sociallocker-button .onp-sociallocker-overlay-line {
    position: absolute;
    left: 41px;
    top: 7px;
    height: 21px;
    width: 0px;
    border-left: 1px solid rgba(0,0,0,0.11);
    border-right: 1px solid rgba(255,255,255,0.16); 
}
.onp-sociallocker-secrets .onp-sociallocker-button .onp-sociallocker-overlay-text {
    font-size: 14px;
    font-family: "Arial", "Helvetica", sans-serif;
    line-height: 34px;
    color: #fff;
    text-align: center;
    position: static;
    padding-left: 42px;
    -moz-box-sizing: border-box; 
    box-sizing: border-box;
    text-shadow: 0 -1px 1px rgba(0,0,0,0.15);
}
.onp-sociallocker-secrets .onp-sociallocker-button .onp-sociallocker-overlay-back {
    background: #eaeaea;
}
.onp-sociallocker-secrets .onp-sociallocker-button .onp-sociallocker-overlay-header {
    background: #eaeaea;
}

.onp-sociallocker-secrets .onp-sociallocker-button-twitter .onp-sociallocker-overlay-front {    
    background: rgb(0,191,238); /* Old browsers */
    /* IE9 SVG, needs conditional override of 'filter' to 'none' */
    background: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/Pgo8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjEwMCUiIGhlaWdodD0iMTAwJSIgdmlld0JveD0iMCAwIDEgMSIgcHJlc2VydmVBc3BlY3RSYXRpbz0ibm9uZSI+CiAgPGxpbmVhckdyYWRpZW50IGlkPSJncmFkLXVjZ2ctZ2VuZXJhdGVkIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjAlIiB5MT0iMCUiIHgyPSIwJSIgeTI9IjEwMCUiPgogICAgPHN0b3Agb2Zmc2V0PSIwJSIgc3RvcC1jb2xvcj0iIzAwYmZlZSIgc3RvcC1vcGFjaXR5PSIxIi8+CiAgICA8c3RvcCBvZmZzZXQ9IjEwMCUiIHN0b3AtY29sb3I9IiMwMGExZTMiIHN0b3Atb3BhY2l0eT0iMSIvPgogIDwvbGluZWFyR3JhZGllbnQ+CiAgPHJlY3QgeD0iMCIgeT0iMCIgd2lkdGg9IjEiIGhlaWdodD0iMSIgZmlsbD0idXJsKCNncmFkLXVjZ2ctZ2VuZXJhdGVkKSIgLz4KPC9zdmc+);
    background: -moz-linear-gradient(top,  rgba(0,191,238,1) 0%, rgba(0,161,227,1) 100%); /* FF3.6+ */
    background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,rgba(0,191,238,1)), color-stop(100%,rgba(0,161,227,1))); /* Chrome,Safari4+ */
    background: -webkit-linear-gradient(top,  rgba(0,191,238,1) 0%,rgba(0,161,227,1) 100%); /* Chrome10+,Safari5.1+ */
    background: -o-linear-gradient(top,  rgba(0,191,238,1) 0%,rgba(0,161,227,1) 100%); /* Opera 11.10+ */
    background: -ms-linear-gradient(top,  rgba(0,191,238,1) 0%,rgba(0,161,227,1) 100%); /* IE10+ */
    background: linear-gradient(to bottom,  rgba(0,191,238,1) 0%,rgba(0,161,227,1) 100%); /* W3C */
    filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#00bfee', endColorstr='#00a1e3',GradientType=0 ); /* IE6-8 */
}
.onp-sociallocker-secrets .onp-sociallocker-button-twitter .onp-sociallocker-overlay-icon {
    background-position: -132px 8px;
}
.onp-sociallocker-secrets .onp-sociallocker-button-twitter .onp-sociallocker-overlay-back {
    background: #24b1e5;
}
.onp-sociallocker-secrets .onp-sociallocker-button-twitter .onp-sociallocker-overlay-header {
    background: #368acd;
}

.onp-sociallocker-secrets .onp-sociallocker-button-facebook .onp-sociallocker-overlay-front {    
    background: rgb(85,129,188); /* Old browsers */
    /* IE9 SVG, needs conditional override of 'filter' to 'none' */
    background: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/Pgo8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjEwMCUiIGhlaWdodD0iMTAwJSIgdmlld0JveD0iMCAwIDEgMSIgcHJlc2VydmVBc3BlY3RSYXRpbz0ibm9uZSI+CiAgPGxpbmVhckdyYWRpZW50IGlkPSJncmFkLXVjZ2ctZ2VuZXJhdGVkIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjAlIiB5MT0iMCUiIHgyPSIwJSIgeTI9IjEwMCUiPgogICAgPHN0b3Agb2Zmc2V0PSIwJSIgc3RvcC1jb2xvcj0iIzU1ODFiYyIgc3RvcC1vcGFjaXR5PSIxIi8+CiAgICA8c3RvcCBvZmZzZXQ9Ijk5JSIgc3RvcC1jb2xvcj0iIzI1NWI5ZCIgc3RvcC1vcGFjaXR5PSIxIi8+CiAgPC9saW5lYXJHcmFkaWVudD4KICA8cmVjdCB4PSIwIiB5PSIwIiB3aWR0aD0iMSIgaGVpZ2h0PSIxIiBmaWxsPSJ1cmwoI2dyYWQtdWNnZy1nZW5lcmF0ZWQpIiAvPgo8L3N2Zz4=);
    background: -moz-linear-gradient(top,  rgba(85,129,188,1) 0%, rgba(37,91,157,1) 99%); /* FF3.6+ */
    background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,rgba(85,129,188,1)), color-stop(99%,rgba(37,91,157,1))); /* Chrome,Safari4+ */
    background: -webkit-linear-gradient(top,  rgba(85,129,188,1) 0%,rgba(37,91,157,1) 99%); /* Chrome10+,Safari5.1+ */
    background: -o-linear-gradient(top,  rgba(85,129,188,1) 0%,rgba(37,91,157,1) 99%); /* Opera 11.10+ */
    background: -ms-linear-gradient(top,  rgba(85,129,188,1) 0%,rgba(37,91,157,1) 99%); /* IE10+ */
    background: linear-gradient(to bottom,  rgba(85,129,188,1) 0%,rgba(37,91,157,1) 99%); /* W3C */
    filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#5581bc', endColorstr='#255b9d',GradientType=0 ); /* IE6-8 */
}
.onp-sociallocker-secrets .onp-sociallocker-button-facebook .onp-sociallocker-overlay-icon {
    background-position: 15px 9px;
}
.onp-sociallocker-secrets .onp-sociallocker-button-facebook .onp-sociallocker-overlay-back {
    background: #46629e; 
}
.onp-sociallocker-secrets .onp-sociallocker-button-facebook .onp-sociallocker-overlay-header {
    background-color: #314775;
}

.onp-sociallocker-secrets .onp-sociallocker-button-google .onp-sociallocker-overlay-front {   
    background: #5c5c5c; /* Old browsers */
    /* IE9 SVG, needs conditional override of 'filter' to 'none' */
    background: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/Pgo8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjEwMCUiIGhlaWdodD0iMTAwJSIgdmlld0JveD0iMCAwIDEgMSIgcHJlc2VydmVBc3BlY3RSYXRpbz0ibm9uZSI+CiAgPGxpbmVhckdyYWRpZW50IGlkPSJncmFkLXVjZ2ctZ2VuZXJhdGVkIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjAlIiB5MT0iMCUiIHgyPSIwJSIgeTI9IjEwMCUiPgogICAgPHN0b3Agb2Zmc2V0PSIwJSIgc3RvcC1jb2xvcj0iIzVjNWM1YyIgc3RvcC1vcGFjaXR5PSIxIi8+CiAgICA8c3RvcCBvZmZzZXQ9IjEwMCUiIHN0b3AtY29sb3I9IiMxNTA5MGQiIHN0b3Atb3BhY2l0eT0iMSIvPgogIDwvbGluZWFyR3JhZGllbnQ+CiAgPHJlY3QgeD0iMCIgeT0iMCIgd2lkdGg9IjEiIGhlaWdodD0iMSIgZmlsbD0idXJsKCNncmFkLXVjZ2ctZ2VuZXJhdGVkKSIgLz4KPC9zdmc+);
    background: -moz-linear-gradient(top,  #5c5c5c 0%, #15090d 100%); /* FF3.6+ */
    background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,#5c5c5c), color-stop(100%,#15090d)); /* Chrome,Safari4+ */
    background: -webkit-linear-gradient(top,  #5c5c5c 0%,#15090d 100%); /* Chrome10+,Safari5.1+ */
    background: -o-linear-gradient(top,  #5c5c5c 0%,#15090d 100%); /* Opera 11.10+ */
    background: -ms-linear-gradient(top,  #5c5c5c 0%,#15090d 100%); /* IE10+ */
    background: linear-gradient(to bottom,  #5c5c5c 0%,#15090d 100%); /* W3C */
    filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#5c5c5c', endColorstr='#15090d',GradientType=0 ); /* IE6-8 */

}
.onp-sociallocker-secrets .onp-sociallocker-button-google .onp-sociallocker-overlay-icon {
    background-position: -18px 9px;
}
.onp-sociallocker-secrets .onp-sociallocker-button-google .onp-sociallocker-overlay-back {
    background: #494647; 
}
.onp-sociallocker-secrets .onp-sociallocker-button-google .onp-sociallocker-overlay-header {
    background-color: #111111;
}

.onp-sociallocker-secrets .onp-sociallocker-button-linkedin .onp-sociallocker-overlay-front {    
    background: #0076a3; /* Old browsers */
    /* IE9 SVG, needs conditional override of 'filter' to 'none' */
    background: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiA/Pgo8c3ZnIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgd2lkdGg9IjEwMCUiIGhlaWdodD0iMTAwJSIgdmlld0JveD0iMCAwIDEgMSIgcHJlc2VydmVBc3BlY3RSYXRpbz0ibm9uZSI+CiAgPGxpbmVhckdyYWRpZW50IGlkPSJncmFkLXVjZ2ctZ2VuZXJhdGVkIiBncmFkaWVudFVuaXRzPSJ1c2VyU3BhY2VPblVzZSIgeDE9IjAlIiB5MT0iMCUiIHgyPSIwJSIgeTI9IjEwMCUiPgogICAgPHN0b3Agb2Zmc2V0PSIwJSIgc3RvcC1jb2xvcj0iIzAwNzZhMyIgc3RvcC1vcGFjaXR5PSIxIi8+CiAgICA8c3RvcCBvZmZzZXQ9IjEwMCUiIHN0b3AtY29sb3I9IiMwMDU1NzUiIHN0b3Atb3BhY2l0eT0iMSIvPgogIDwvbGluZWFyR3JhZGllbnQ+CiAgPHJlY3QgeD0iMCIgeT0iMCIgd2lkdGg9IjEiIGhlaWdodD0iMSIgZmlsbD0idXJsKCNncmFkLXVjZ2ctZ2VuZXJhdGVkKSIgLz4KPC9zdmc+);
    background: -moz-linear-gradient(top,  #0076a3 0%, #005575 100%); /* FF3.6+ */
    background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,#0076a3), color-stop(100%,#005575)); /* Chrome,Safari4+ */
    background: -webkit-linear-gradient(top,  #0076a3 0%,#005575 100%); /* Chrome10+,Safari5.1+ */
    background: -o-linear-gradient(top,  #0076a3 0%,#005575 100%); /* Opera 11.10+ */
    background: -ms-linear-gradient(top,  #0076a3 0%,#005575 100%); /* IE10+ */
    background: linear-gradient(to bottom,  #0076a3 0%,#005575 100%); /* W3C */
    filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#0076a3', endColorstr='#005575',GradientType=0 ); /* IE6-8 */

}
.onp-sociallocker-secrets .onp-sociallocker-button-linkedin .onp-sociallocker-overlay-icon {
    background-position: -58px 8px;
}
.onp-sociallocker-secrets .onp-sociallocker-button-linkedin .onp-sociallocker-overlay-back {
    background: #286b8d; 
}
.onp-sociallocker-secrets .onp-sociallocker-button-linkedin .onp-sociallocker-overlay-header {
    background-color: #19465d;
}
.onp-sociallocker-secrets .onp-sociallocker-cross {
    top: 28px;
    right: 28px;
}
.onp-sociallocker-secrets .onp-sociallocker-timer {
    right: 30px;
    bottom: 28px;
    color: #777;
}
.onp-sociallocker-secrets .onp-sociallocker-state-loading .onp-sociallocker-button-inner-wrap { 
    background-image: url('http://2.bp.blogspot.com/-9OIqdswfNJY/U5qZZd6U3aI/AAAAAAAAARk/tDdmAeeC_Cc/s1600/button-loader-eaeaea.gif');
}

/**
* Dandyish style
*/

.onp-sociallocker-dandyish {
    padding: 7px;
    background: url('http://2.bp.blogspot.com/-Ew8vy6sdtDA/U5qZa2zEPNI/AAAAAAAAASE/2Qnmos4jbkc/s1600/dandysh-border.png');
    border-radius: 12px;
    -moz-box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.25);
    -webkit-box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.25);
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.25);
}
.onp-sociallocker-dandyish .onp-sociallocker-outer-wrap {
    padding: 5px;
    background-color: #fff;
    border-radius: 10px;
}
.onp-sociallocker-dandyish .onp-sociallocker-inner-wrap {
    padding: 10px;
    border-radius: 10px;
    background-color: f8f8f8;
    background: linear-gradient(top, #f9f9f9, #F5F5F5);
    background: -o-linear-gradient(top, #f9f9f9, #F5F5F5);
    background: -moz-linear-gradient(top, #f9f9f9, #F5F5F5);
    background: -webkit-linear-gradient(top, #f9f9f9, #F5F5F5);
    filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#f9f9f9', endColorstr='#F5F5F5',GradientType=0 );
    background: -ms-linear-gradient(top, #FFFFFF, #F5F5F5);   
    -moz-box-shadow: inset 0px 1px 6px rgba(0, 0, 0, 0.20);
    -webkit-box-shadow: inset 0px 1px 6px rgba(0, 0, 0, 0.20);
    box-shadow: inset 0px 1px 6px rgba(0, 0, 0, 0.20);
}
.onp-sociallocker-dandyish .onp-sociallocker-text {
    padding: 10px 10px 0 10px;
}
.onp-sociallocker-dandyish .onp-sociallocker-text,
.onp-sociallocker-dandyish  .onp-sociallocker-timer, 
.onp-sociallocker-dandyish .onp-sociallocker-timer * {
    -webkit-text-shadow: 1px 1px 2px #fff;
    -moz-text-shadow: 1px 1px 2px #fff;
    text-shadow: 1px 1px 2px #fff;
}
.onp-sociallocker-dandyish .onp-sociallocker-text .onp-sociallocker-strong:before,
.onp-sociallocker-dandyish .onp-sociallocker-text .onp-sociallocker-strong:after {
    content: '';
    display: inline-block;
    width: 11px;
    height: 14px;
    margin: 0 9px;
    background: url('http://3.bp.blogspot.com/-zh68d9Qv_cQ/U5qZboEospI/AAAAAAAAASw/fX_SFK1bdno/s1600/lock-icon.png') 0px 2px no-repeat;
}
@media screen and (max-width: 500px) 
{
    .onp-sociallocker-dandyish .onp-sociallocker-text .onp-sociallocker-strong:before,
    .onp-sociallocker-dandyish .onp-sociallocker-text .onp-sociallocker-strong:after 
    {
        display: none;
    }
}
.onp-sociallocker-dandyish .onp-sociallocker-text .onp-sociallocker-strong:after {
    margin-left: 10px;
}
.onp-sociallocker-dandyish .onp-sociallocker-buttons {
    margin: 0px;
    padding: 5px;
}
.onp-sociallocker-dandyish .onp-sociallocker-button {
    border-radius: 7px;
    background-color: rgba(255,255,255, 1);
    -moz-box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.15);
    -webkit-box-shadow: 0px 3px 1px rgba(0, 0, 0, 0.15);
    box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.15);
}
.onp-sociallocker-dandyish .onp-sociallocker-button .fb-like span,
.onp-sociallocker-dandyish .onp-sociallocker-button .fb-like iframe {
    height: 61px;
}
.onp-sociallocker-dandyish .onp-sociallocker-button {
    margin: 14px 7px 0 7px;
    width: 85px;
}
.onp-sociallocker.onp-sociallocker-dandyish .onp-social-button {
    min-width: 0px;
    width: auto;
}

.onp-sociallocker-dandyish .onp-linkedin-button {
    position: relative;
}
.onp-sociallocker-dandyish .onp-google-button {
    position: relative;
    top: 2px;
}
.onp-sociallocker-dandyish .onp-facebook-button, 
.onp-sociallocker-dandyish .onp-google-button, 
.onp-sociallocker-dandyish .onp-twitter-tweet {
    width: auto;
}
.onp-sociallocker-dandyish .fb-like {
    position: top;
    top: 1px;
}
.onp-sociallocker-dandyish .onp-sociallocker-button-inner-wrap {
    min-width: 85px;
    height: 84px;
    padding: 10px;
    text-align: center;
}
.onp-sociallocker-dandyish .onp-sociallocker-cross {
    top: 20px;
    right: 20px;
}
.onp-sociallocker-dandyish .onp-sociallocker-timer {
    right: 20px;
    bottom: 20px;
}
.onp-sociallocker-dandyish .onp-sociallocker-state-loading .onp-sociallocker-button-inner-wrap { 
    background-image: url('http://3.bp.blogspot.com/-kjieP0CoGsc/U5qZZrdYjRI/AAAAAAAAASA/UE8imLPctXM/s1600/button-loader-ffffff.gif');
}

/**
* Glass style
*/
.onp-sociallocker-glass {
    padding: 15px;
    border: 0px;
    
    -moz-box-shadow: 0px 1px 1px rgba(255, 255, 255, 0.7), inset 0px 1px 1px rgba(0, 0, 0, 0.1);    
    -webkit-box-shadow: 0px 1px 1px rgba(255, 255, 255, 0.7), inset 0px 1px 1px rgba(0, 0, 0, 0.1);
    box-shadow: 0px 1px 1px rgba(255, 255, 255, 0.7), inset 0px 1px 1px rgba(0, 0, 0, 0.1);
    
    -webkit-border-radius: 15px;
    -moz-border-radius: 15px;
    border-radius: 15px;
    
    text-shadow: 0px 1px 1px #fff;
    
    background: rgba(0,0,0,0.03);
}
.onp-sociallocker-glass .onp-sociallocker-outer-wrap {

    padding: 30px;
    -webkit-border-radius: 11px;
    -moz-border-radius: 11px;
    border-radius: 11px;
    
    -webkit-shadow: 0px 1px 5px rgba(0, 0, 0, 0.25), inset 0px 1px 1px rgba(255, 255, 255, 0.7);
    -moz-box-shadow: 0px 1px 5px rgba(0, 0, 0, 0.25), inset 0px 1px 1px rgba(255, 255, 255, 0.7);   
    box-shadow: 0px 1px 5px rgba(0, 0, 0, 0.25), inset 0px 1px 1px rgba(255, 255, 255, 0.7);
    
    background: rgb(247,247,247);

    background: -moz-linear-gradient(top,  rgba(255,255,255,0.5) 0%, rgba(240,240,240,0.5) 100%);
    background: -webkit-gradient(linear, left top, left bottom, color-stop(0%,rgba(255,255,255,0.5)), color-stop(100%,rgba(240,240,240,0.5)));
    background: -webkit-linear-gradient(top,  rgba(255,255,255,0.5) 0%,rgba(240,240,240,0.5) 100%);
    background: -o-linear-gradient(top,  rgba(255,255,255,0.5) 0%,rgba(240,240,240,0.5) 100%);
    background: -ms-linear-gradient(top,  rgba(255,255,255,0.5) 0%,rgba(240,240,240,0.5) 100%);
    background: linear-gradient(to bottom,  rgba(255,255,255,0.5) 0%,rgba(240,240,240,0.5) 100%);
}
.onp-sociallocker-glass .onp-sociallocker-text .onp-sociallocker-strong:before,
.onp-sociallocker-glass .onp-sociallocker-text .onp-sociallocker-strong:after {
    content: '';
    display: inline-block;
    width: 11px;
    height: 14px;
    margin: 0 9px;
    background: url('http://3.bp.blogspot.com/-zh68d9Qv_cQ/U5qZboEospI/AAAAAAAAASw/fX_SFK1bdno/s1600/lock-icon.png') 0px 2px no-repeat;
}
@media screen and (max-width: 500px) 
{
    .onp-sociallocker-glass .onp-sociallocker-text .onp-sociallocker-strong:before,
    .onp-sociallocker-glass .onp-sociallocker-text .onp-sociallocker-strong:after 
    {
        display: none;
    }
}
.onp-sociallocker-glass .onp-sociallocker-button {
    -moz-border-radius: 7px;
    -webkit-border-radius: 7px;
    border-radius: 7px;
    
    -webkit-box-shadow: inset 0px 0px 4px rgba(0,0,0,0.12), 0px 1px 1px rgba(255, 255, 255, 0.7);
    -moz-box-shadow: inset 0px 0px 4px rgba(0,0,0,0.12), 0px 1px 1px rgba(255, 255, 255, 0.7);
    box-shadow: inset 0px 0px 4px rgba(0,0,0,0.12), 0px 1px 1px rgba(255, 255, 255, 0.7);
}
.onp-sociallocker-glass .onp-sociallocker-cross {
    top: 20px;
    right: 20px;
}
.onp-sociallocker-glass .onp-sociallocker-timer {
    right: 23px;
    bottom: 21px;
}


/**
* Flat style
*/
.onp-sociallocker-flat .fb-like span,
.onp-sociallocker-flat .fb-like iframe {
    width: 118px !important;
}
.onp-sociallocker-flat {
    padding: 0px;
    background-color: transparent;
}
.onp-sociallocker-flat .onp-sociallocker-inner-wrap {
    background-color: #f9f9f9;
    padding: 30px;
}
.onp-sociallocker-flat .onp-sociallocker-outer-wrap {
    border-bottom: 4px solid #f1f1f1;
}
.onp-sociallocker-flat .onp-sociallocker-inner-wrap,
.onp-sociallocker-flat .onp-sociallocker-outer-wrap {
    border-radius: 5px;
}
.onp-sociallocker-flat .onp-sociallocker-text .onp-sociallocker-strong:before,
.onp-sociallocker-flat .onp-sociallocker-text .onp-sociallocker-strong:after 
{
    content: '';
    display: inline-block;
    width: 11px;
    height: 14px;
    margin: 0 9px;
    background: url('http://3.bp.blogspot.com/-zh68d9Qv_cQ/U5qZboEospI/AAAAAAAAASw/fX_SFK1bdno/s1600/lock-icon.png') 0px 2px no-repeat;
}
@media screen and (max-width: 500px) 
{
    .onp-sociallocker-flat .onp-sociallocker-text .onp-sociallocker-strong:before,
    .onp-sociallocker-flat .onp-sociallocker-text .onp-sociallocker-strong:after 
    {
        display: none;
    }
}
.onp-sociallocker-flat .onp-sociallocker-text .onp-sociallocker-strong:after {
    margin-left: 10px;
}
.onp-sociallocker-flat .onp-sociallocker-button {
    background: rgba(0, 0, 0, 0.03);
}
.onp-sociallocker-flat .onp-sociallocker-button-inner-wrap {
    padding: 7px 10px 10px 10px;
}
.onp-sociallocker-flat .onp-sociallocker-button-inner-wrap, 
.onp-sociallocker-flat .onp-sociallocker-button-overlay {
    height: 34px;
    min-width: 118px;
}
.onp-sociallocker-flat .onp-sociallocker-button .onp-sociallocker-overlay-front {
    background: #eaeaea;
    border-bottom: 3px solid #dadada;
}
.onp-sociallocker-flat .onp-sociallocker-button .onp-sociallocker-overlay-front,
.onp-sociallocker-flat .onp-sociallocker-button .onp-sociallocker-overlay-back {
    border-radius: 3px;
}

.onp-sociallocker-flat .onp-sociallocker-button .onp-sociallocker-overlay-icon {
    height: 34px;
    width: 44px;
    background-image: url('http://1.bp.blogspot.com/-0XAzn5_MtDA/U5qZcIegt6I/AAAAAAAAASY/MkLnSkKpoz0/s1600/social-icons.png');
    background-repeat: no-repeat;
    background-position-y: 50%;
    position: absolute;
}
.onp-sociallocker-flat .onp-sociallocker-button .onp-sociallocker-overlay-text {
    font-size: 14px;
    font-family: "Arial", "Helvetica", sans-serif;
    line-height: 34px;
    color: #fff;
    text-align: center;
    position: static;
    padding-left: 42px;
    -moz-box-sizing: border-box; 
    box-sizing: border-box;
    text-shadow: 0 -1px 1px rgba(0,0,0,0.15);
}

.onp-sociallocker-flat .onp-sociallocker-button-twitter .onp-sociallocker-overlay-front {
    background: #4086cc;
    border-bottom-color: #13579e;
}
.onp-sociallocker-flat .onp-sociallocker-button-twitter .onp-sociallocker-overlay-icon {
    background-position: -132px 8px;
}
.onp-sociallocker-flat .onp-sociallocker-button-twitter .onp-sociallocker-overlay-back {
    background: #4086cc;
}
.onp-sociallocker-flat .onp-sociallocker-button-twitter .onp-sociallocker-overlay-header {
    background: #13579e;
}

.onp-sociallocker-flat .onp-sociallocker-button-facebook .onp-sociallocker-overlay-front {
    background: #3c5a9a;
    border-bottom-color: #082b6f;
}
.onp-sociallocker-flat .onp-sociallocker-button-facebook .onp-sociallocker-overlay-icon {
    background-position: 15px 9px;
}
.onp-sociallocker-flat .onp-sociallocker-button-facebook .onp-sociallocker-overlay-back {
    background: #3c5a9a;
}
.onp-sociallocker-flat .onp-sociallocker-button-facebook .onp-sociallocker-overlay-header {
    background: #082b6f;
}

.onp-sociallocker-flat .onp-sociallocker-button-google .onp-sociallocker-overlay-front {
    background: #ca4639;
    border-bottom-color: #a52316;
}
.onp-sociallocker-flat .onp-sociallocker-button-google .onp-sociallocker-overlay-icon {
    background-position: -18px 9px;
}
.onp-sociallocker-flat .onp-sociallocker-button-google .onp-sociallocker-overlay-back {
    background: #ca4639;
}
.onp-sociallocker-flat .onp-sociallocker-button-google .onp-sociallocker-overlay-header {
    background: #a52316;
}

.onp-sociallocker-flat .onp-sociallocker-button-linkedin .onp-sociallocker-overlay-front {
    background-color: #286b8d;
    border-bottom-color: #4a6887;
}
.onp-sociallocker-flat .onp-sociallocker-button-linkedin .onp-sociallocker-overlay-icon {
    background-position: -58px 7px;
}
.onp-sociallocker-flat .onp-sociallocker-button-linkedin .onp-sociallocker-overlay-back {
    background: #286b8d; 
}
.onp-sociallocker-flat .onp-sociallocker-button-linkedin .onp-sociallocker-overlay-header {
    background-color: #19465d;
}
.onp-sociallocker-flat .onp-sociallocker-cross {
    top: 8px;
    right: 8px;
}
.onp-sociallocker-flat .onp-sociallocker-timer {
    right: 10px;
    bottom: 8px;
    color: #777;
}

/**
* Like Button Widget styles
*/

.onp-sociallocker-horizontal.onp-sociallocker-has-counters .onp-facebook-like-es_ES,
.onp-sociallocker-horizontal.onp-sociallocker-has-counters .onp-facebook-share-es_ES {
    width: 114px !important;
}
.onp-sociallocker-horizontal.onp-sociallocker-has-counters .onp-facebook-like-ru_RU,
.onp-sociallocker-horizontal.onp-sociallocker-has-counters .onp-facebook-share-ru_RU {
    width: 124px !important;
}
.onp-sociallocker-horizontal.onp-sociallocker-has-counters .onp-facebook-like-pl_PL,
.onp-sociallocker-horizontal.onp-sociallocker-has-counters .onp-facebook-share-pl_PL {
    width: 120px !important;
}
.onp-sociallocker-horizontal.onp-sociallocker-has-counters .onp-facebook-like-de_DE,
.onp-sociallocker-horizontal.onp-sociallocker-has-counters .onp-facebook-share-de_DE {
    width: 120px !important;
}
.onp-sociallocker-horizontal.onp-sociallocker-has-counters .onp-facebook-share-pt_BR {
    width: 130px !important;
}

/* See #SLJQ-14 */
.onp-sociallocker .onp-facebook-like-count-none .fb_iframe_widget {
    display: inline-block !important;
}
.onp-sociallocker .onp-facebook-like-count-none .fb-like {
    overflow: hidden;
    width: 50px !important;
}

.onp-sociallocker-horizontal.onp-sociallocker-no-counters .fb-share-button {
    overflow: hidden;
    width: 60px !important;
}
.onp-sociallocker-horizontal.onp-sociallocker-no-counters .onp-facebook-like-es_ES .fb-like {
    width: 78px !important;
}
.onp-sociallocker-horizontal.onp-sociallocker-no-counters .onp-facebook-share-es_ES .fb-share-button {
    width: 81px !important;
}
.onp-sociallocker-horizontal.onp-sociallocker-no-counters .onp-facebook-like-pt_PT .fb-like {
    width: 59px !important;
}
.onp-sociallocker-horizontal.onp-sociallocker-no-counters .onp-facebook-share-pt_PT .fb-share-button {
    width: 71px !important;
}
.onp-sociallocker-horizontal.onp-sociallocker-no-counters .onp-facebook-like-fr_FR .fb-like {
    width: 63px !important;
}
.onp-sociallocker-horizontal.onp-sociallocker-no-counters .onp-facebook-share-fr_FR .fb-share-button {
    width: 73px !important;
}
.onp-sociallocker-horizontal.onp-sociallocker-no-counters .onp-facebook-like-ru_RU .fb-like {
    width: 81px !important;
}
.onp-sociallocker-horizontal.onp-sociallocker-no-counters .onp-facebook-share-ru_RU .fb-share-button {
    width: 91px !important;
}
.onp-sociallocker-horizontal.onp-sociallocker-no-counters .onp-facebook-like-fi_FI .fb-like {
    width: 68px !important;
}
.onp-sociallocker-horizontal.onp-sociallocker-no-counters .onp-facebook-share-fi_FI .fb-share-button {
    width: 43px !important;
}
.onp-sociallocker-horizontal.onp-sociallocker-no-counters .onp-facebook-like-pl_PL .fb-like {
    width: 77px !important;
}
.onp-sociallocker-horizontal.onp-sociallocker-no-counters .onp-facebook-share-pl_PL .fb-share-button {
    width: 87px !important;
}
.onp-sociallocker-horizontal.onp-sociallocker-no-counters .onp-facebook-like-de_DE .fb-like {
    width: 85px !important;
}
.onp-sociallocker-horizontal.onp-sociallocker-no-counters .onp-facebook-like-pt_BR .fb-like {
    width: 59px !important;
}
.onp-sociallocker-horizontal.onp-sociallocker-no-counters .onp-facebook-share-pt_BR .fb-share-button {
    width: 98px !important;
}
