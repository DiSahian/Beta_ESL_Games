HOW TO ADD YOUR IMAGES — Pronoun Shooter
==========================================

1. Copy your photo files into THIS folder (images/).
   Supported formats: JPG, PNG, GIF, WebP

2. Open the file:
   games/pronoun-shooter/index.html

3. Find the QUESTIONS section at the top of the <script> tag.

4. Replace  null  with the path to your image. Example:

   BEFORE:
     { image: null, emoji: '??', label: 'Sofia', ... }

   AFTER:
     { image: 'images/sofia.jpg', label: 'Sofia', ... }

5. Save the file and refresh — your photo will appear!

NOTE: Images work on GitHub Pages. If you open the file 
directly (double-click), images may not load due to browser
security. Deploy to GitHub Pages to see them.
