# Final-peer-graded-project
Peer graded final project
<nav>
  <ul>
    <li><a href="index.html">Home</a></li>
    <li><a href="about.html">About Us</a></li>
    <li><a href="contact.html">Contact Us</a></li>
  </ul>
</nav>
<section id="intro">
  <h1>Discover Your Dream Destination</h1>
  <p>Use our travel recommendation engine to explore beaches, temples, and iconic places around the world based on your preferences.</p>
</section>
<h2>Our Mission</h2>
<p>We aim to make travel planning easy and fun by offering curated destination suggestions with images, tips, and cultural highlights.</p>

<h3>Meet the Team</h3>
<ul>
  <li>Jane Doe – Travel Expert</li>
  <li>John Smith – Web Developer</li>
</ul>
<form id="contact-form">
  <label>Name:</label>
  <input type="text" required>
  
  <label>Email:</label>
  <input type="email" required>
  
  <label>Message:</label>
  <textarea required></textarea>
  
  <button type="submit">Send</button>
</form>
<h2>Top Beach Destinations</h2>
<div class="destination">
  <h3>Bondi Beach, Australia</h3>
  <img src="images/bondi.jpg" alt="Bondi Beach">
  <p>A stunning beach perfect for surfing and relaxing under the sun.</p>
</div>
<h2>Must-See Temples</h2>
<div class="destination">
  <h3>Angkor Wat, Cambodia</h3>
  <img src="images/angkor.jpg" alt="Angkor Wat Temple">
  <p>A breathtaking ancient temple complex rich in history and architecture.</p>
</div>
document.getElementById('contact-form')?.addEventListener('submit', function (e) {
  e.preventDefault();
  alert('Thank you for contacting us! We will get back to you soon.');
});
