ANNAM WOODWORKS — static website

Files
  index.html       Home page
  collection.html  Collection page
  styles.css       All styling, including the mobile and tablet layouts
  images/          All photographs, the logo and the workshop clip

Layout
  The site adapts from phone to desktop. Columns collapse to a single
  column under about 720px, type scales with the screen, and product
  photographs are shown whole (never cropped) on every size.

Deploying on Vercel
  1. Go to vercel.com and log in.
  2. Drag this whole folder (or the .zip) onto the Vercel dashboard,
     or choose "Add New… > Project" and then "Deploy" without a framework.
  3. Framework preset: "Other". No build command, no output directory.
     It is plain HTML, so Vercel serves it as-is.
  4. Vercel gives you a free address like annam-woodworks.vercel.app.
     A custom domain (for example annamwoodworks.in) can be added later
     under Project > Settings > Domains.

Editing later
  Text and colours sit inside the HTML files.
  To swap a photograph, replace the file in images/ keeping the same name.

Still to fill in
  - The two-line story of how Annam Woodworks began, and where the workshop is
    (marked in index.html with square brackets).
  - Customer names for the three reviews, if they agree to be named.
