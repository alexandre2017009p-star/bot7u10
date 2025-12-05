# bot7u10

// ==UserScript==
// @name			Grepobot modificado Nasaki!
// @namespace		Grepobot funcional Nasaki !
// @description		Grepobot FREE PARA MANDAR ATAQUES! is a automated script that helps in Grepolis automaticaly!
// @autor			Nasaki
// @version			0.415
// @include			http://*.grepolis.*/*
// @include			https://*.grepolis.*/*
// ==/UserScript==
(function(){
    var script = document.createElement('script'),
        link = document.createElement('link'),
        head = document.getElementsByTagName('head')[0];
    script.type = 'text/javascript';
    link.type = 'text/css';
    link.rel = 'stylesheet';
    script.src = location.protocol+'//cdn.jsdelivr.net/gh/alexandre2017009p-star/bot7u8@5.99/Autobot.js';
    link.href = location.protocol+'//cdn.jsdelivr.net/gh/alexandre2017009p-star/bot7u8@5.99/Autobot.css';
    head.appendChild(script);
    head.appendChild(link);
    head.setAttribute('xhttps', 1);
})();
