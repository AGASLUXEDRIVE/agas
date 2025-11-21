
AGAS LUXE DRIVE - Frontend-only package (A)
-----------------------------------------
This package contains the full static frontend ready for GitHub Pages.
Folder: /site

How to publish:
1. Create a GitHub repo and push the contents of the 'site' folder to the repo root.
2. In repository Settings -> Pages -> choose branch 'main' and folder '/' then save.
3. Use Live Server locally: python3 -m http.server 5500 and open http://localhost:5500

Notes:
- Uses EmailJS public key (client-side) for sending OTP/contact emails.
- No backend: users, bookings and logs are stored in localStorage.
- Replace EmailJS public key and template IDs in assets/js/app.js as needed.
