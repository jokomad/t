// ==UserScript==
// @name         captchaskip
// @namespace    http://tampermonkey.net/
// @version      0.1
// @description  try to take over the world!
// @author       You
// @include      https://*freebitco.in*

// @run-at       document-idle
// @grant        None
// ==/UserScript==

function random(min,max){
        return min + (max - min) * Math.random();
    }

//////////////////////////////////////////////////////////////////////////////////////////////////////////
document.querySelector("#menu_drop > a").onclick= function() {window.location.replace("http://localhost/"); }
