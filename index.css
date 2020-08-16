/* --------------------------------------- */
/* ----- Basic Setup ----- */
/* --------------------------------------- */

@font-face {
    font-family: 'Hk Grotesk';
    font-style: normal;
    font-weight: 400;
    src: url('./fonts/HKGrotesk-Regular.woff') format('woff');
}

@font-face {
    font-family: 'Jost';
    font-style: normal;
    font-weight: 400;
    src: url('./fonts/Jost-Regular.ttf') format('woff');
}

* {
    margin: 0;
    padding: 0;
    box-sizing: inherit;
}

:root {
    --font-size-small: 1.8rem;
    --font-size-normal: 2.2rem;
    --font-size-medium: 2.8rem;
    --font-size-medium-1: 3.6rem;
    --font-size-large: 5.5rem;
    --font-size-huge: 7.5rem;
    --font-stack: 'Hk Grotesk', sans-serif;

    --line-height-normal: 1.7;
    --line-height-small: 1.2;

    --black: #000;
    --pink: #ff3258;
    --white: #f0e9f2;
    --white-1: #e5e5e6da;


    --container-max-width: 1180px;
    --container-normal-width: 800px;
    --container-medium-width: 700px; 
    --container-small-width: 500px;

    --gutter-huge: 12rem;
    --gutter-medium: 6rem;
    --gutter-normal: 3rem;
    --gutter-small-1: 2.5rem;
    --gutter-small: 2rem;

    --border-light: 1px solid rgb(36, 35, 35);
}

html {
    font-size: 62.5%; /* (16/10)*100 = 62.5% => 1rem = 10px */
    box-sizing: border-box;
    scroll-behavior: smooth;
}

@media(max-width: 1000px) {
    html {
        font-size: 52%;
    }
}

body {
    font-size: var(--font-size-small);
    font-family: var(--font-stack);
    font-weight: 400;
    color: var(--white-1);
    line-height: var(--line-height-normal);
    background: var(--black);
    overflow-x: hidden;
}

.row {
    max-width: var(--container-max-width);
    margin: 0 auto;
}

@media(max-width: 1340px) {
    .row {
        max-width: 1100px;
    }
}

@media(max-width: 1240px) {
    .row {
        padding: 0 var(--gutter-medium);
    }
}

@media(max-width: 600px) {
    .row {
        padding: 0 var(--gutter-normal);
    }
}

@media(max-width: 600px) {
    .row {
        padding: 0 var(--gutter-small);
    }
}

section {
    padding: var(--gutter-huge) 0;
    border-bottom: var(--border-light);
}

img {
    object-fit: contain;
    max-width: 100%;
}

/* --------------------------------------- */
/* ----- Headlines and Paragraphs ----- */
/* --------------------------------------- */

h1,
h2,
h3 {
    font-family: 'Jost', sans-serif;
    font-weight: 400;
    line-height: var(--line-height-small);
    color: var(--white);
}

.heading-primary {
    line-height: 1;
    font-size: var(--font-size-huge);
    font-weight: 400;
}

@media(max-width: 900px) {
    .heading-primary {
        font-size: 6.5rem;
    }
}

h2 {
    font-size: var(--font-size-large);
    margin-bottom: var(--gutter-medium);
}

h2::after {
    content: '';
    display: block;
    height: 2px;
    width: 10rem;
    background: var(--pink);
    margin: var(--gutter-small) 0;
}

h3 {
    font-size: var(--font-size-medium-1);
    margin-bottom: var(--gutter-small);
}

@media(max-width: 500px) {
    .heading-primary {
        font-size: var(--font-size-large);
    }

    h2 {
        font-size: var(--font-size-medium-1);
    }

    h3 {
        font-size: var(--font-size-medium);
    }
}

p {
    margin: var(--gutter-small-1) 0;
}

@media(max-width: 900px) {
    p { 
        max-width: var(--container-small-width);
    }
}

/* --------------------------------------- */
/* ----- Buttons and Links ----- */
/* --------------------------------------- */

a {
    color: var(--white);
    font-weight: 400;
    font-family: 'Jost', sans-serif;
    transition: all .2s;
    outline: 2px solid transparent;
}

::-moz-focus-inner {
    border: 0;
}

button:focus,
a:focus {
    outline: 2px solid var(--pink);
}

body:not(.user-is-tabbing) button:focus,
body:not(.user-is-tabbing) a:focus {
    outline: none;
}

.link:hover {
    color: var(--pink);
}

.btn {
    position: relative;
    display: inline-block;
    padding: 1rem 4.2rem;
    text-decoration: none;
    color: inherit;
    border: 1px solid  var(--pink);
    font-weight: 400;
}

.btn:focus {
    outline: none;
}

.btn::after {
    content: '';
    display: block;
    position: absolute;
    top: 0;
    left: 0;
    right: 100%;
    background: var(--white);
    height: 100%;
    z-index: -1;
    transition: all 0.2s cubic-bezier(1, 0.68, 0.16, 0.9);
}

.btn:hover::after,
.btn:focus::after {
    right: 0;
    background: var(--pink);
}

.btn--pink {
    background: var(--pink);
    transition: all 0.2s;
}

.btn--pink::after {
    display: none;
}

.btn--pink:hover,
.btn--pink:focus {
    background: transparent;
}

.link__text {
    position: relative;
    display: inline-block;
    padding: .6rem;
    color: inherit;
    text-decoration: none;
    border-bottom: 1px solid var(--pink);
}

.link__text::after {
    content: '';
    display: block;
    position: absolute;
    top: 0;
    left: 0;
    right: 100%;
    background: var(--white);
    height: 100%;
    z-index: -1;
    transition: all 0.2s cubic-bezier(1, 0.68, 0.16, 0.9);
}

.link__text:focus {
    outline: none;
}

.link__text:hover::after,
.link__text:focus:after {
    right: 0;
    background: var(--pink);
}

.link__text span {
    padding-left: 1rem;
    font-family: sans-serif;
}

/* ----- Back to Top ----- */

.back-to-top {
    position: fixed;
    bottom: 4rem;
    right: 4rem;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 5.5rem;
    width: 5.5rem;
    background-color: var(--pink);
    border-radius: 50%;
    z-index: 10;
    visibility: hidden;
    transition: all .4s;
}

.back-to-top__image {
    height: 70%;
}

@media(max-width: 900px) {
    .back-to-top {
        right: 2rem;
    }
}

@media(max-width: 500px) {
    .back-to-top {
        right: 1rem;
    }
}

/* --------------------------------------- */
/* ----- Navigation ----- */
/* --------------------------------------- */

.nav {
    display: flex;
    justify-content: flex-end;
    padding: var(--gutter-normal) 0;
}

.nav__items {
    display: flex;
    list-style: none;
}

.nav__item:not(:last-child) {
    margin-right: var(--gutter-medium);
}

@media(max-width: 500px) {
    .nav {
        justify-content: center;
    }
}

@media(max-width: 400px) {
    .nav__item:not(:last-child) {
        margin-right: var(--gutter-normal);
    }
}

@media(max-width: 300px) {
    .nav {
        font-size: var(--font-size-small);
    }
}

.nav__link {
    position: relative;
    display: inline-block;
    padding: 1rem 0;
    text-decoration: none;
    color: inherit;
    transition: all .2s;
}

.nav__link::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    right: 100%;
    display: inline-block;
    height: 1rem;
    background: var(--white);
    transition: all 0.25s cubic-bezier(1, 0.68, 0.16, 0.9);
}

.nav__link:hover {
    color: var(--pink);
}

.nav__link:hover::after {
    right: 0;
    height: 2px;
    background: var(--pink);
}

/* --------------------------------------- */
/* ----- Header ----- */
/* --------------------------------------- */

.header {
    background: linear-gradient(rgba(0,0,0, .1), rgba(0,0,0, .4)), 
        url('./images/header.jpg');
    height: 100vh;
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    font-size: var(--font-size-normal);
}

.header__text {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
}

.header__text p {
    margin: 1.5rem 0 3.5rem;
    max-width: var(--container-medium-width);
    font-family: 'Jost', sans-serif;
    font-size: var(--font-size-medium);
}

@media(max-width: 500px) {
    .header {
        text-align: center;
    }

    .header__text p {
        transform: scale(.8);
    }
}

/* --------------------------------------- */
/* ----- Work ----- */
/* --------------------------------------- */

.work__box {
    display: flex;
    align-items: center;
}

@media(max-width: 900px) {
    .work__box {
        align-items: initial;
        flex-direction: column-reverse;
    }
}

.work__box:not(:last-child) {
    margin-bottom: 25rem;
}

@media(max-width: 500px) {
    .work__box:not(:last-child) {
        margin-bottom: 20rem;
    }
}

.work__links {
    display: flex;
    align-items: center;
}

.work__text {
    flex: 0 0 30%;
}

.work__list {
    /* list-style-type: square; */
    list-style-position: inside;
    margin-bottom: var(--gutter-normal);
}

.work__code {
    display: block;
    height: 3rem;
    margin-left: var(--gutter-normal);
    transition: all .3s;
}

.work__code:hover {
    transform: scale(1.2);
}

.work__image-box {
    margin-bottom: var(--gutter-normal);
}

@media(min-width: 901px) {
    .work__image-box {
        flex: 1;
        margin: 0 0 0 10rem;
    }
}

@media(max-width: 900px) {
    .work__code {
        height: 4rem;
    }
}

/* --------------------------------------- */
/* ----- Clients ----- */
/* --------------------------------------- */

.client__logos {
    display: flex;
    justify-content: space-between;
    filter: invert(100%) grayscale(100%) opacity(.8);
}

.client__logo {
    height: 6.5rem;
    max-width: 18rem;
}

@media(max-width: 1240px) {
    .client__logos {
        overflow-x: scroll;
        padding: var(--gutter-normal);
    }

    .client__logo:not(:last-of-type) {
        margin-right: var(--gutter-medium);
    }
}

/* --------------------------------------- */
/* ----- About ----- */
/* --------------------------------------- */

.about__content {
    display: flex;
    flex-direction: row-reverse;
    align-items: center;
}

@media(max-width: 900px) {
    .about__content {
        flex-direction: column-reverse;
        align-items: initial;
    }
}

.about__photo-container {
    margin-bottom: var(--gutter-normal);
}

@media(min-width: 901px) {
    .about__text {
        flex: 0 0 35%;
    }
    
    .about__photo-container {
        flex: 1;
        margin: 0 var(--gutter-huge) 0 0;
    }
}

/* --------------------------------------- */
/* ----- Contact ----- */
/* --------------------------------------- */

.contact__info {
    max-width: var(--container-medium-width);
}

/* --------------------------------------- */
/* ----- Footer ----- */
/* --------------------------------------- */

.footer {
    text-align: center;
    padding: var(--gutter-medium) 0 var(--gutter-normal);
}

.footer__social-links {
    display: flex;
    justify-content: center;
    padding: var(--gutter-normal) 0;
    list-style: none;
}

.footer__social-link-item:not(:last-of-type) {
    margin-right: var(--gutter-small);
}

.footer__social-image {
    height: 4rem;
}

.footer__github-buttons {
    display: flex;
    justify-content: center;
}

.footer__github-buttons iframe {
    height: 2.5rem;
    width: 84px;
    transform: translateY(3px);
}

@media(max-width: 500px) {
    .footer {
        padding: var(--gutter-medium) 0;
    } 
}
