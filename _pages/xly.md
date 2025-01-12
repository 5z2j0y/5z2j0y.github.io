---
layout: archive
title: "Secret!"
permalink: /post/
author_profile: true 
redirect_from:
  - /resume
---
{% include base_path %}

<script>
  function checkPassword() {
    var password = prompt("Please enter the password:");
    if (password === "123") {
      console.log("Password correct");
      window.location.href = "https://5z2j0y.github.io/privateposts/";
    } else {
      console.log("Password incorrect");
      alert("Password incorrect");
    }
  }
</script>