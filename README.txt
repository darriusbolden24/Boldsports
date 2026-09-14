BOLD SPORTS GROUP WEBSITE

FILES
- index.html
- styles.css
- script.js
- assets/

HOW TO OPEN
Double-click index.html.

HOW TO CHANGE THE CONTACT EMAIL
Search index.html for:
info@boldsportsgroup.com
and replace it with your real email.

HOW TO ADD ANOTHER ATHLETE PHOTO
1. Put the image into the assets folder.
2. Replace the placeholder card in the "ATHLETES" section with:
   <article class="athlete-card">
     <img src="assets/YOUR-FILE.jpg" alt="Athlete">
     <div class="athlete-card-overlay">
       <span>BASKETBALL</span>
       <h3>Athlete Name</h3>
     </div>
   </article>

DEPLOYMENT
This is a static site and works with GitHub Pages, Netlify, Vercel, or most website hosts.
