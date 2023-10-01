<!-- Create a GitHub Pages README -->

## Table of Contents
- [Home](#home)
- [Info](#info)
- [Rules](#rules)
- [Additionals](#additionals)

<div id="home"></div>

## Home
Welcome to my GitHub repository!

This is the Home section of the README. You can put an introduction or any content you like here.

[Back to Top](#table-of-contents)

<div id="info"></div>

## Info
This is the Info section of the README.

Here, you can provide information about your project, such as what it does, how to use it, or any other relevant details.

[Back to Top](#table-of-contents)

<div id="rules"></div>

## Rules
These are the Rules for my project.

You can specify any guidelines, coding conventions, or project-specific rules here.

[Back to Top](#table-of-contents)

<div id="additionals"></div>

## Additionals
This section contains Additional information about the project.

You can include any extra details, documentation, or resources related to your project.

[Back to Top](#table-of-contents)

<script>
// JavaScript for smooth scrolling to the sections
document.addEventListener("DOMContentLoaded", function () {
  const links = document.querySelectorAll("a[href^='#']");
  for (const link of links) {
    link.addEventListener("click", function (e) {
      e.preventDefault();
      const targetId = this.getAttribute("href").substring(1);
      const target = document.getElementById(targetId);
      target.scrollIntoView({ behavior: "smooth" });
    });
  }
});
</script>
