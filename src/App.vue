<template>
  <div id="app" class="app">
    <router-view></router-view>
  </div>
</template>

<script>

export default {
  name: 'app'
}
</script>

<style>
@import url('https://rsms.me/inter/inter-ui.css');

/* * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    font-size: 100%;
    font-family: 'Inter UI', sans-serif;
}
*/


.app {
    /* width: 62em;
    margin: 0 auto;
    padding: 2em 6em 8em;
    background-color: #0074d9;
    border-top: 4px solid #0be6d7;
    color: white; */
}



/* @media screen and (max-width: 850px) {
    .app {
        max-width: 100%;
        padding: 0.5em 1.5em 2em;
        overflow-x: hidden;
    }
} */


h1 {
    font-size: 8em;
    font-weight: 100;
}

a {

}

a:hover {
    color: black;
}

h2 {
    font-size: 3em;
    font-weight: 100;
    margin-bottom: 1em;
}

p {
    font-size: 1.5em;
    font-weight: normal;
    margin-bottom: 0;
}

input {
    height: 2em;
    border-radius: 5px;
}

input[type=text],
input[type=email],
input[type=password] {
    width: 21em;
    margin-bottom: 2em;
}

input[type=number] {
    width: 7em;
    margin-bottom: 2em;
}

input[type=submit] {
    width: 7em;
    margin-bottom: 2em;
    color: #0074d9;
    background-color: white;
    cursor: pointer;
}

select {
    height: 2em;
    border-radius: 5px;
    width: 7em;
    cursor: pointer;
}

@media screen and (max-width: 650px) {
    input[type=text],
    input[type=password],
    input[type=email],
    input[type=submit] {
        width: 100%;
    }
    input[type=number],
    select {
        width: 33%;
    }
    input[type=submit] {
        font-size: 1em;
    }
}



.ittybittylabel {
    font-size: 0.7em;
    position: absolute;
    top: 2.3em;
    margin-left: 1em;
}

.ittybittylabel2 {
    font-size: 0.5em;
    display: inline-block;
    position: absolute;
    top: 45.7em;
    margin-left: 1em;
}

.form-group {
    position: relative;
    display: inline;
}



/* The navigation menu */
/* .navbar {
 overflow: hidden;
 background-color: #0074d9;
} */

/* Navigation links */
/* .navbar a {
 float: left;
 font-size: 16px;
 color: white;
 text-align: center;
 padding: 14px 16px;
 text-decoration: none;
} */

/* The subnavigation menu */
/* .subnav {
 float: left;
 overflow: hidden;
} */

/* Subnav button */
/* .subnav .subnavbtn {
 font-size: 16px;
 border: none;
 outline: none;
 color: white;
 padding: 14px 16px;
 background-color: inherit;
 font-family: inherit;
 margin: 0;
} */

/* Add a red background color to navigation links on hover */
/* .navbar a:hover, .subnav:hover .subnavbtn {
 background-color: white;
 color: #0074d9;
} */

/* Style the subnav content - positioned absolute */
/* .subnav-content {
 display: none;
 position: absolute;
 background-color: white;
 z-index: 1;
} */

/* Style the subnav links */
/* .subnav-content a {
 float: left;
 width: 8.6em;
 display: inline-block;
 color: #0074d9;
 text-decoration: none;
} */

/* Add a grey background color on hover */
/* .subnav-content a:hover {
 background-color: #eee;
 color: black;
} */

/* When you move the mouse over the subnav container, open the subnav content */
/* .subnav:hover .subnav-content {
 display: block;
} */

.wrapper {
    margin: 0 2em;
}


</style>
