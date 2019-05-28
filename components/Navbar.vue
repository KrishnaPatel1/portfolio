<template>
    <nav>
    <ul>
        <li><h3><a href="#" style="color:inherit;text-decoration: none;">Krishna Patel</a></h3></li>
        <li><a href="#work">Work Experience</a></li>
        <li>
            <a href="#education">Education</a>
        </li>
        <li><a href="#extracurriculars">Extracurriculars</a></li>
        <li><a href="/">Hobbies and Interests</a></li>
        <li class="social">
            <a class="logo_github" href="https://github.com/KrishnaPatel1" target="_blank">Github</a>
        </li>
        <li class="social">
            <a class="logo_linkedin" href="https://www.linkedin.com/in/krishna-patel1/" target="_blank">LinkedIn</a>
        </li>
        <li class="social">
            <a class="logo_cv" href="https://www.linkedin.com/in/krishna-patel1/" target="_blank">Resume</a>
        </li>

    </ul>
</nav>
</template>

<style scoped>
    nav {
        background-color: #fff;
        /* border-bottom: 0.5vh solid rgba(0, 0, 0, 0.5); */
        border-radius: 4px;
        box-shadow: inset -5px -5px 5px -5px rgba(0, 0, 0, 1);
        color: #888;
        display: block;
        overflow: hidden;
        width: 100%;
        position: sticky;
        top: 0;
        z-index: 1000;
    }
    nav ul {
        margin-left: 0;
        padding: 0;
    }
    nav ul li {
        display: inline-flex;
        list-style-type: none;
        margin: 0%;

        -webkit-transition: all 0.2s;
        -moz-transition: all 0.2s;
        -ms-transition: all 0.2s;
        -o-transition: all 0.2s;
        transition: all 0.2s;
    }
    nav ul li.social {
        display: inline-flex;
        list-style-type: none;
        line-height: 56px;
        margin: 0%;
        float: right;

        -webkit-transition: all 0.2s;
        -moz-transition: all 0.2s;
        -ms-transition: all 0.2s;
        -o-transition: all 0.2s;
        transition: all 0.2s;
    }
    nav > ul > li > a {
        color: #aaa;
        display: block;
        line-height: 56px;
        padding: 0 1vw;
        text-align: right;
        list-style-position: inside;
        text-decoration: none;
    }
    nav > ul > li > a.logo_github {
        background: url("../assets/Github.png") 50% no-repeat;
        background-size: 40px 40px;
        color: #aaa;
        display: block;
        line-height: 56px;
        padding: 0 1vw;
        text-align: bottom;
        list-style-position: inside;
        font-weight: bold;
        text-decoration: none;
        color: rgba(0,0,0,0);
    }
    nav > ul > li > a.logo_linkedin {
        background: url("../assets/LinkedIn.png") 50% no-repeat;
        background-size: 45px 45px;
        color: #aaa;
        display: block;
        line-height: 56px;
        padding: 0 1vw;
        text-align: bottom;
        list-style-position: inside;
        font-weight: bold;
        text-decoration: none;
        color: rgba(0,0,0,0);    
}
    nav > ul > li > a.logo_cv {
        background: url("../assets/cv.svg") 50% no-repeat;
        background-size: 40px 40px;
        color: #aaa;
        display: block;
        line-height: 56px;
        padding: 0 1vw;
        text-align: bottom;
        list-style-position: inside;
        font-weight: bold;
        text-decoration: none;
        color: rgba(0,0,0,0);    
}
    nav > ul > li > h3 {
        display: block;
        font-size: 3vh;
        line-height: 56px;
        padding: 0 2vw;
        text-decoration: none;
    }
    nav > ul > li > a > .caret {
        border-top: 4px solid #aaa;
        border-right: 4px solid transparent;
        border-left: 4px solid transparent;
        content: "";
        display: inline-block;
        height: 0;
        width: 0;
        vertical-align: middle;
    
        -webkit-transition: color 0.1s linear;
        -moz-transition: color 0.1s linear;
        -o-transition: color 0.1s linear;
        transition: color 0.1s linear;
    }
    nav > ul > li:hover {
        background-color: rgb( 40, 44, 47 );
    }
    nav > ul > li:hover > a {
        color: rgb( 255, 255, 255 );
    }
    nav > ul > li:hover > h3 {
        color: rgb( 255, 255, 255 );
    }
    nav > ul > li:hover > a > .caret {
        border-top-color: rgb( 255, 255, 255 );
    }
    nav > ul > li:hover > div {
        display: block;
        opacity: 1;
        visibility: visible;
    }
    /* The sticky class is added to the navbar with JS when it reaches its scroll position */
    .sticky {
        position: fixed;
        top: 0;
        width: 100%;
    }
    /* Add some top padding to the page content to prevent sudden quick movement (as the navigation bar gets a new position at the top of the page (position:fixed and top:0) */
    .sticky + .content {
        padding-top: 60px;
    }
    img {
        display: block;
        margin: 0 auto;
    }
</style>
