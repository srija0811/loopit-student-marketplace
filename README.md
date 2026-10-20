# LoopIt — Advanced Student Sharing Marketplace

A responsive front-end demo for a student marketplace to buy, rent, sell, and swap campus essentials.

## Features
- Blue / light-blue / beige / cream design and light/dark mode
- Demo login and registration UI
- Verified-student mock badges and campus filter label
- Search, category, type, area and price sorting filters
- Product quick-view slide-out drawer and Safe Exchange Points
- Three-block condition meters
- Post, edit and delete listings; image upload preview stored as Base64 in browser storage
- Rental booking, due-date status automation, late fee estimates, dashboard warnings
- Mock notification dropdown and exchange request flow
- Responsive layout and semantic HTML

## Run locally
1. Extract the ZIP.
2. Open this folder in VS Code.
3. Open `index.html` with Live Server, or open it directly in a browser.

## GitHub Pages
Upload `index.html`, `style.css`, `app.js`, and `README.md` to the root of a repository. Open Settings → Pages → Deploy from a branch → `main` → `/(root)`.

## Important demo limitations
- Authentication stores demo credentials in browser storage and is not secure. Never enter a real password.
- Listings, rentals, and notifications are local to this browser; there is no backend or cross-user synchronization.
- Student badges and notifications are simulated, not real identity verification or real messages.
- Purchases, payments, and rental agreements are not processed.
- Image uploads are limited to 1.5 MB per file and four images per selection; browser storage limits still apply.
- Overdue days are calculated from local calendar dates; late fee is overdue days × agreed daily late fee. This is a demo estimate.

## Expanded textbook catalogue
The demo now includes sample listings for school classes, Intermediate/PUC, degree, engineering, medical, pharmacy, and competitive exams (NEET, JEE, UPSC, GATE). Use the **Books** category and the **All education levels** selector to browse them. These are sample marketplace listings, not an exhaustive catalogue of every textbook, board, university, edition, or syllabus. Confirm the exact title, edition, board/university, and syllabus with the seller before buying or renting.


## Sports equipment catalogue
The demo includes sports listings such as cricket bats, badminton rackets (sometimes called shuttle bats), shuttlecocks, tennis rackets, footballs, basketballs, volleyballs, table-tennis bats, sports shoes, and cricket practice sets. Choose the Sports category to browse them. These are sample listings, not live inventory.
