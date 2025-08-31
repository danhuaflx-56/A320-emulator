---
hide:
  toc: true
---
<!-- Hero Section (Full Width) -->
<div class="hero-section" style="width:100vw; position:relative; left:50%; margin-left:-50vw; background-image: url('assets/banner.jpg'); background-position: center; background-repeat: no-repeat; background-size: cover; background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('assets/banner.jpg'); background-color:#004080; color:white; text-align:center; padding:30px 20px;">
  <h1 style="font-size:3.5em; font-weight:bold; margin-bottom:15px;">A320 Emulator</h1>
  <h3 style="font-size:1.8em; font-style:italic; color:#ccc; margin-bottom:40px;">
    Learning to fly has never been easier
  </h3>
  <p style="font-size:1.3em; max-width:700px; margin:0 auto 50px auto; line-height:1.8;">
    Explore the systems of the beautiful Airbus A320, the bestselling and most advanced passenger jet in history. This site provides step-by-step documentation to help you master everything from cockpit familiarization to advanced procedures.
  </p>
  <a href="getting-started/" style="
    display:inline-block;
    background-color:#005bbb;
    color:white;
    padding:14px 28px;
    border-radius:8px;
    font-size:1.3em;
    font-weight:bold;
    text-decoration:none;
    transition: background-color 0.2s ease;">
    Get Started →
  </a>
</div>

<script>
function updateHeroBackground() {
  const hero = document.querySelector('.hero-section');
  const scrollY = window.scrollY;
  hero.style.backgroundPosition = `center ${scrollY * 0.5}px`;
}

// Run on scroll
window.addEventListener('scroll', updateHeroBackground);

// Run once on page load
window.addEventListener('load', updateHeroBackground);
</script>

<!-- Section 1 -->
<div class="section rectangle-1" style="width:100vw; position:relative; left:50%; margin-left:-50vw; background-color:#111; color:white; text-align:center; padding:100px 20px;">
  <h2  class="animated-text" style="font-size:2.5em; margin-bottom:20px;">Getting Started</h2>
  <p   class="animated-text" style="font-size:1.2em; max-width:700px; margin:0 auto;">
    Learn about cockpit layout, controls, and basic startup procedures.
  </p>
</div>

<script>
function animateOnScroll() {
  const elements = document.querySelectorAll('.animated-text');
  
  elements.forEach(el => {
    const rect = el.getBoundingClientRect();
    const windowHeight = window.innerHeight;
    
    // Trigger when element is in the bottom half of the screen
    if(rect.top < windowHeight * 0.8) {
      el.classList.add('in-view');
    }
  });
}

// Run on scroll
window.addEventListener('scroll', animateOnScroll);
// Run on load
window.addEventListener('load', animateOnScroll);
</script>


<!-- Section 2 -->
<div class="section rectangle-2" style="width:100vw; position:relative; left:50%; margin-left:-50vw; background-color:#1a1a1a; color:white; text-align:center; padding:100px 20px;">
  <h2 class="animated-text" style="font-size:2.5em; margin-bottom:20px;">Systems Overview</h2>
  <p class="animated-text" style="font-size:1.2em; max-width:700px; margin:0 auto;">
    Electrical, hydraulics, fuel, and other systems are explained in detail.
  </p>
</div>

<!-- Section 3 -->
<div class="section rectangle-3" style="width:100vw; position:relative; left:50%; margin-left:-50vw; background-color:#111; color:white; text-align:center; padding:100px 20px;">
  <h2 class="animated-text" style="font-size:2.5em; margin-bottom:20px;">Procedures</h2>
  <p class="animated-text" style="font-size:1.2em; max-width:700px; margin:0 auto;">
    Step-by-step normal, abnormal, and emergency procedures.
  </p>
</div>

<!-- Section 4 -->
<div class="section rectangle-4" style="width:100vw; position:relative; left:50%; margin-left:-50vw; background-color:#1a1a1a; color:white; text-align:center; padding:100px 20px;">
  <h2 class="animated-text" style="font-size:2.5em; margin-bottom:20px;">Tips & Tricks</h2>
  <p class="animated-text" style="font-size:1.2em; max-width:700px; margin:0 auto;">
    Learn how to operate the A320 like a pro with efficiency and realism in mind.
  </p>
</div>

<!-- Footer Banner -->
<div class="footer-banner" style="width: 100%; position: relative;">
  <div class="footer-content" style="max-width:1000px; margin:0 auto; padding:10px 20px;">
    <p>© 2025 A320 Emulator. All rights reserved.</p>
    <p>Contact: <a href="mailto:daniel56huang@gmail.com">daniel56huang@gmail.com</a></p>
  </div>
</div>

