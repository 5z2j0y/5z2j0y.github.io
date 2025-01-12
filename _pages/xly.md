---
layout: default
title: "XLY Page"
permalink: /xly/
nav_exclude: true
---

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

<button onclick="checkPassword()">Load Private Posts</button>