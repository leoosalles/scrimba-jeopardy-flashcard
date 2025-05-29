# scrimba-jeopardy-flashcard
A <strong>CSS-only flashcard</strong> that flips to reveal the answer—just like in Jeopardy! This project demonstrates <strong>pure CSS techniques</strong> for an interactive card flip effect.
<h2>✨ Features</h2>
<ul>
  <li>
    <strong>Smooth card flip animation</strong> using CSS transitions
  </li>
  <li>
    <strong>No JavaScript required</strong>—entirely CSS-based
  </li>
  <li>
    <strong>Hover-triggered interaction</strong> for revealing the answer
  </li>
  <li>
    <strong>Minimalist design</strong>, inspired by the Jeopardy aesthetic
  </li>
</ul>
<h2>🔧 How It Works</h2>
<p>
  The HTML structure consists of a <code>.card</code> element containing:
</p>
<ul>
  <li>
    A <strong>front side</strong> with the question
  </li>
  <li>
    A <strong>back side</strong> with the answer
  </li>
</ul>
<h2>CSS Techniques Used</h2>
<ul>
  <li>
    <code>perspective</code> for 3D depth effect
  </li>
  <li>
    <code>backface-visibility: hidden</code> to properly hide flipped content
  </li>
  <li>
    <code>transform: rotateY(180deg)</code> to flip the card on hover
  </li>
  <li>
    <strong>CSS transitions</strong> for a smooth animation
  </li>
</ul>
