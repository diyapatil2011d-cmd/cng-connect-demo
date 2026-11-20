CNG CONNECT - UPDATED PWA PACKAGE

Files:
- index.html: updated multi-energy station finder and simulated owner portal
- manifest.webmanifest: installable app metadata
- service-worker.js: app-shell offline caching
- icons/: PWA icons

FEATURES
- Four energy categories: CNG, Petrol, Diesel and EV Charging Point
- 26 illustrative station records: 7 CNG, 7 Petrol, 7 Diesel and 5 EV charging
- Individual simulated station-owner IDs and passwords
- Each owner can access only their matching station dashboard in this browser prototype
- Owners can update station availability, estimated waiting time and active service-point counts
- User listings reflect owner updates on the same browser/device
- User observations and customer feedback
- Responsive mobile layout and installable PWA support

IMPORTANT
This is a presentation prototype. Station records are illustrative, not verified real businesses or live availability. Owner credentials are stored in client-side JavaScript and are NOT secure authentication. Browser-local changes do not synchronise between different devices. Do not use these credentials for real accounts or sensitive information. A production system requires a secure backend, verified station operators, and a shared database.

GITHUB PAGES
Upload the CONTENTS of this folder to the root of the public repository's main branch. Ensure index.html, manifest.webmanifest, service-worker.js and icons/ are directly visible in the repository root. Keep GitHub Pages set to Deploy from a branch -> main -> /(root). After deployment, open the project URL and refresh the page.
