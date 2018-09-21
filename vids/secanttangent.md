---
layout: page
title: "Slopes of Secants and Tangents"
meta_title: "secanttangent"
permalink: "/vids/secanttangent/"
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
    var vidchoice=getCookie("secanttangent");
    if (vidchoice==1){window.location.href = "https://ximera.osu.edu/fall18calcvids/o/secanttangent/name";}
    else if (vidchoice==2){window.location.href = "https://ximera.osu.edu/fall18calcvids/q/secanttangent/name";}
    else if (vidchoice==3){window.location.href = "https://ximera.osu.edu/fall18calcvids/v/secanttangent/name";}
    else if (vidchoice==4){window.location.href = "https://ximera.osu.edu/fall18calcvids/c/secanttangent/name";}
    else {
      var forwardchoice=Math.random();
      if (forwardchoice <= 0.25 ){
        setCookie("secanttangent", 1, 365);
        checkCookie();
        }
      else if (forwardchoice <= 0.5 ){
        setCookie("secanttangent", 2, 365);
        checkCookie();
        }
      else if (forwardchoice <= 0.75 ){
        setCookie("secanttangent", 3, 365);
        checkCookie();
        }
      else {
        setCookie("secanttangent", 4, 365);
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
