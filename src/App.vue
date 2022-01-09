<template>
<div>
  <!--<header>
    <img src="" alt="">
    <nav>
      <ul>
        <li>Pricing</li>
        <li>Product</li>
        <li>About Us</li>
        <li>Careers</li>
        <li>Community</li>
      </ul>
    </nav>
    <button>Get Started</button>
  </header>-->
  <main>
    <section class="section-bring flow container">
      <img src="@/assets/images/illustration-intro.svg" alt="image that illustrate numbers and graphs">
      <article class="article-bring flow">
        <h1 class="text-blue fs-600 fw-bold">Bring everyone together to build better products.</h1>
        <p class="text-grey">Manage makes it simple for software teams to plan day-to-day 
          tasks while keeping the larger team goals in view.
        </p>
        <Button />
      </article>
    </section>
    <section class="manage flow">
      <header class="header-section-different">
        <h2 class="text-blue fw-bold fs-500">What’s different about Manage?</h2>
        <p class="text-grey">Manage provides all the functionality your team needs, without 
          the complexity. Our software is tailor-made for modern digital 
          product teams.
        </p>
      </header>
      <article class="numbered-article flow">
        <h3 class="numbered-title text-blue fw-bold"><span class="number-in-title text-white fw-medium bg-orange">01</span> Track company-wide progress</h3>
        <p class="text-grey">See how your day-to-day tasks fit into the wider vision. Go from 
          tracking progress at the milestone level all the way done to the 
          smallest of details. Never lose sight of the bigger picture again.
        </p>
      </article>
      <article class="numbered-article flow">
        <h3 class="numbered-title text-blue fw-bold"><span class="number-in-title text-white fw-medium bg-orange">02</span> Advanced built-in reports</h3>
        <p class="text-grey">Set internal delivery estimates and track progress toward company 
          goals. Our customisable dashboard helps you build out the reports 
          you need to keep key stakeholders informed.
        </p>
      </article>
      <article class="numbered-article flow">
        <h3 class="numbered-title text-blue fw-bold"><span class="number-in-title text-white fw-medium bg-orange">03</span> Everything you need in place</h3>
        <p class="text-grey">Stop jumping from one service to another to communicate, store files, 
          track tasks and share documents. Manage offers an all-in-one team 
          productivity solution.
        </p>
      </article>
    </section>
    <section>
      <h2 class="text-blue fw-bold fs-600">What they’ve said</h2>
      <article class="article-testimony flow">
        <img src="@/assets/images/avatar-anisha.png" class="image-avatar" alt="">
        <h3 class="text-blue fw-bold testimoner-name ">Anisha Li</h3>
        <p class="text-grey">“Manage has supercharged our team’s workflow. The ability to maintain 
          visibility on larger milestones at all times keeps everyone motivated.”
        </p>
      </article>
      <!--<article>
        <img src="@/assets/images/avatar-anisha.png" class="image-avatar" alt="">
        <h3 class="text-blue fw-bold testimoner-name ">Ali Bravo</h3>
        <p class="text-grey">“We have been able to cancel so many other subscriptions since using 
          Manage. There is no more cross-channel confusion and everyone is much 
          more focused.”
        </p>
      </article>
      <article>
        <img src="@/assets/images/avatar-anisha.png" class="image-avatar" alt="">
        <h3 class="text-blue fw-bold testimoner-name ">Richard Watts</h3>
        <p class="text-grey">“Manage allows us to provide structure and process. It keeps us organized 
          and focused. I can’t stop recommending them to everyone I talk to!”
        </p>
      </article>
      <article>
        <img src="@/assets/images/avatar-anisha.png" class="image-avatar" alt="">
        <h3 class="text-blue fw-bold">Shanai Gough</h3>
        <p class="text-grey">“Their software allows us to track, manage and collaborate on our projects 
          from anywhere. It keeps the whole team in-sync without being intrusive.”
        </p>
      </article> -->
      <div>
        <button class="select-testimoner"><span class="sr-only">Anisha Li</span></button>
        <button class="select-testimoner"><span class="sr-only">Ali Bravo</span></button>
        <button class="select-testimoner"><span class="sr-only">Richard Watts</span></button>
        <button class="select-testimoner"><span class="sr-only">Shanai Gough</span></button>
      </div>
      <Button />
    </section>
    <div class="section-simplify bg-orange flow">
      <p class="text-white fs-700">Simplify how your team works today.</p>
      <button class="button-simplify fw-medium">Get Started</button>
    </div>
    <footer class="bg-dark-blue flow">
      <div>
        <input class="text-grey" type="text" value="Updates in your inbox…">
        <button class="button-go-input orange-button bo fw-medium">GO</button>
      </div>
      <div class="footer-links text-white flex">
        <div class="flow">
          <p>Home</p>
          <p>Pricing</p>
          <p>Products</p>
          <p>About Us</p>
        </div>
        <div class="flow">
          <p>Careers</p>
          <p>Community</p>
          <p>Privacy policy</p>       
        </div>
      </div>
      <div>
        <img src="" alt="">
        <img src="" alt="">
        <img src="" alt="">
        <img src="" alt="">
        <img src="" alt="">
      </div>
      <img src="@/assets/images/logo.svg" alt="" class="logo-footer">
      <p class="copyrights text-grey">Copyright 2020. All Rights Reserved</p>      
    </footer>
  </main>
</div>
</template>

<script>
import Button  from "@/components/Button.vue";

export default {
  name: 'App',
  components: {
    Button
  }
}
</script>

<style>
@font-face {
  font-family: 'be-vietnam';
  src:url('./assets/font/BeVietnamPro-Regular.ttf');
}

/* ---------- */
/* reset      */
/* ---------- */
*, 
::before,
::after {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

:root {
  /* colors */
  --bright-red: 12, 88%, 59%;
  --dark-blue: 228, 39%, 23%;
  --grey-blue: 227, 12%, 61%;
  --verydark-blue: 233, 12%, 13%;
  --light-red: 13, 100%, 96%;
  --clr-white: 0, 0%, 98%;

  /* font-sizes */
  --fs-800: 6.25rem;
  --fs-700: 3rem;
  --fs-600: 2.2rem;
  --fs-500: 1.7rem;
  --fs-400: 1.125rem;
  --fs-300: 1rem;
  --fs-200: 0.875rem;
}

/*@media (min-width: 35em) {
    :root {
        --fs-800: 5rem;
        --fs-700: 2.5rem;
        --fs-600: 1.5rem;
        --fs-400: 1rem;
    }
}

@media (min-width: 45em) {
    :root {
        --fs-800: 6.25rem;
        --fs-700: 3.5rem;
        --fs-600: 2rem;
        --fs-400: 1.125rem;
    }
}*/

body {
  font-family: 'be-vietnam';
  font-size: var(--fs-300);
  text-align: center; 
}

/* make images easier to work with */
img,
picture {
  max-width: 100%;
  display: block;
}

/* make forms elements easier to work with */
input,
button,
textarea,
select {
  font: inherit;
}

h1,
h2,
h3,
h4,
h5,
h6,
p {
  font-weight: 400;
}

/* Screen reader */
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  white-space: nowrap; /* add line */
  border: 0;
}

/* --------------------  */
/* specials classes      */
/* --------------------  */
.flex {
  display: flex;
  gap: var(--gap, 1rem);
}

.grid {
  display: grid;
  gap: var(--gap, 1rem);
}

.d-block {
  display: block;
}

.flow > *:where(:not(:first-child)) {
  margin-top: var(--flow-space, 1rem);
}

.container {
  padding-inline: 2rem;
  margin-inline: auto;
}

/* Colors */
.text-orange {
  color: hsl(var(--bright-red));
}

.text-blue {
  color: hsl(var(--dark-blue));
}

.text-grey {
  color: hsl(var(--grey-blue));
}

.text-white {
  color: hsl(var(--clr-white));
}

.bg-orange {
  background-color: hsl(var(--bright-red));
}

.bg-orange {
  background-color: hsl(var(--bright-red));
}

.bg-dark-blue {
  background-color: hsl(var(--verydark-blue));
}

.bg-white {
  background-color: hsl(var(--clr-white));
}

/* typographie */
.fs-900 { font-size: var(--fs-900); }
.fs-800 { font-size: var(--fs-800); }
.fs-700 { font-size: var(--fs-700); }
.fs-600 { font-size: var(--fs-600); }
.fs-500 { font-size: var(--fs-500); }
.fs-400 { font-size: var(--fs-400); }
.fs-300 { font-size: var(--fs-300); }
.fs-200 { font-size: var(--fs-200); }

.fs-900,
.fs-800,
.fs-700,
.fs-600 {
    line-height: 1.1;
}


.fw-medium {
  font-weight: 550;
}
.fw-bold {
  font-weight: 700;
}

/* orange buttons */
.orange-button {
  cursor: pointer;
  border: none;
  background-color: hsl(var(--bright-red));
  color: hsl(var(--clr-white));
  padding: 1rem 2rem;
  border-radius: 30px;
  box-shadow:  0 10px 20px 1px hsl(var(--bright-red));
  margin: 1rem;
}

/* ---------------- layout ---------------- */
/* section bring */
.section-bring {
  margin-bottom: 4rem;
}

.header-section-different {
  margin-bottom: 4rem;
  padding-inline: 2rem;
}

/* section manage */
.manage {
  margin-bottom: 4rem;
}
/*numbered article */
.numbered-article {
  --flow-space: 1rem;
  text-align: left;
  padding-left: 0.5rem;
}
.number-in-title  {
  padding: 0.5rem 1.5rem;
  border-radius: 30px;
}
.numbered-title {
  background-color: hsl(var(--light-red));
  padding-block: 0.5rem;
}

/* section testimony */
.article-testimony {
  --flow-space: 2rem;
}
.image-avatar {
  margin: auto;
  margin-block: 4rem 2rem;
}

.select-testimoner {
  cursor: pointer;
  width: 0.5rem;
  margin-inline: 0.1rem;
  margin-block: 4rem 3rem;
  aspect-ratio: 1;
  border: solid 1px hsl(var(--bright-red));
  border-radius: 50%;
}

/* section simplify */
.section-simplify {
  --flow-space: 2rem;
  margin-top: 2rem;
  padding-block: 7rem;
  padding-inline: 1rem;
}

.button-simplify {
  cursor: pointer;
  border: none;
  color: hsl(var(--bright-red));
  background-color: hsl(var(--clr-white));
  padding: 1rem 2rem;
  border-radius: 30px;
}

.button-go-input {
  box-shadow: none;
  letter-spacing: 0.1rem;
}

input {
  margin-top: 2rem;
  padding: 1rem 2rem;
  border-radius: 30px;
  border: none;
}

/* footer */
.footer-links {
  justify-content: space-between;
  padding-inline: 2rem;
  text-align: left;
}

.copyrights,
.logo-footer {
  margin: auto;
  padding-block: 1rem;
}
</style>
