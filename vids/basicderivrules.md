---
layout: page
title: "Basic Derivative Rules"
meta_title: "basicderivrules"
permalink: "/vids/basicderivrules/"
---


<html>
<head>
<script>

function setCookie(cname,cvalue,exdays) {
    var d = new Date();
    d.setTime(d.getTime() + (exdays*24*60*60*1000));
    var expires = "expires=" + d.toGMTString();
    document.cookie = cname + "=" + cvalue + ";" + expires + ";path=/";
}

function getCookie(cname) {
    var name = cname + "=";
    var decodedCookie = decodeURIComponent(document.cookie);
    var ca = decodedCookie.split(';');
    for(var i = 0; i < ca.length; i++) {
        var c = ca[i];
        while (c.charAt(0) == ' ') {
            c = c.substring(1);
        }
        if (c.indexOf(name) == 0) {
            return c.substring(name.length, c.length);
        }
    }
    return "";
}

function checkCookie() {
    var vidchoice=getCookie("basicderivrules");
    if (vidchoice==1){window.location.href = "https://ximera.osu.edu/fall18calcvids/o/basicderivrules/name";}
    else if (vidchoice==2){window.location.href = "https://ximera.osu.edu/fall18calcvids/v/basicderivrules/name";}
    else if (vidchoice==3){window.location.href = "https://ximera.osu.edu/fall18calcvids/c/basicderivrules/name";}
    else {
      var forwardchoice=Math.random();
      if (forwardchoice <= 0.33 ){
        setCookie("basicderivrules", 1, 365);
        checkCookie();
        }
      else if (forwardchoice <= 0.66 ){
        setCookie("basicderivrules", 2, 365);
        checkCookie();
        }
      else {
        setCookie("basicderivrules", 3, 365);
        checkCookie();
        }
      }
}


</script>
</head>
<body onload="checkCookie()">
Loading...
</body>
</html>
