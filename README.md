<p align="center">
  <img
    src="https://cdn.jsdelivr.net/gh/Gob-Goblet/Gob-Goblet-assets/Logo/Goblet_logo.webp"
    alt="Gob Goblet"
    width="400">
</p>

<h1 align="center">
  <picture>
    <h1>Gob Goblet</h1>
  </picture>
</h1>




<br clear="all" />


<h3 align="center">Gob Goblet is an open-source, lightweight, web-based utility for securely encrypting and decrypting modern files.</h3>

<br>
<br>

<h2 align="center">Zero-Knowledge Architecture</h2>

<p align="center">
  Gob Goblet is built strictly as a local-first application. The actual encryption and decryption of your files happen entirely within your browser environment, ensuring that your raw data never leaves your device.
</p>

<p align="center">
  The utility operates on a few uncompromising principles:
</p>

<div align="center">
  <ul style="display: inline-block; text-align: left; max-width: 600px;">
    <li><b>The Blind Server:</b> The backend server exists for one reason only: to securely derive a cryptographic pepper. It receives a hashed representation, applies the pepper, and returns it. The server is completely blind—it never sees your plain-text password, and it never touches your files.</li>
    <li><b>Stateless by Design:</b> There are no user accounts, no login portals, and no databases hoarding your metadata. The utility functions flawlessly without tethering your identity to a cloud account.</li>
    <li><b>Client-Side Execution:</b> Because all file processing and structural wrapping into the <code>.gob</code> format happens locally, the system remains lightweight, fast, and immune to traditional server-side data breaches.</li>
  </ul>
</div>

<br>
<br>
