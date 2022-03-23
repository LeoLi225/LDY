---
layout: default
title: Leo
nav_order: 16
---

# heading

<span style="color:pink">background color </span>


<button class="btn js-toggle-dark-mode">Change to dark color scheme</button>

<script>
const toggleDarkMode = document.querySelector('.js-toggle-dark-mode');

jtd.addEvent(toggleDarkMode, 'click', function(){
  if (jtd.getTheme() === 'dark') {
    jtd.setTheme('light');
    toggleDarkMode.textContent = 'Change to dark color scheme';
  } else {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = 'Return to the light side';
  }
});
</script>