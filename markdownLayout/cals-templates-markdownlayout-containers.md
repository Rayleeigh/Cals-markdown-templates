<!--
Thank you for using my markdown layout template
please dont forget to mention me in your sources, thank you! 😄

-->
<style>
.container {
  display: grid; 
  grid-template-columns: 1fr 1fr 1fr; 
  grid-template-rows: 1.1fr 1.1fr 1fr; 
  gap: 0px 0px; 
  grid-template-areas: 
    "Hello Hello Hello"
    "Test World World"
    "c1 c2 c3"; 
}
.Hello { grid-area: Hello; }
.World { grid-area: World; }
.Test { grid-area: Test; }
.c1 { grid-area: c1; }
.c2 { grid-area: c2; }
.c3 { grid-area: c3; }
<style>

<div class="container">
  <div class="Hello">d</div>
  <div class="World">d</div>
  <div class="Test">d</div>
  <div class="c1">d</div>
  <div class="c2">d</div>
  <div class="c3">d</div>
</div>