Mowbray Cemetery Board Election — Candidate Information Hub
An accessible, lightweight, single-page web application designed for the Mowbray community in Cape Town. The platform houses comprehensive profile data, platform statements, and comparison tools for all 24 shortlisted candidates contesting the 11 available seats on the Mowbray Cemetery Board.

Built as a zero-dependency, pure client-side web app (HTML5, CSS3, vanilla ES6+ JavaScript), it can be served directly via GitHub Pages or any static web web server.

Key Features
Interactive Candidate Directory: Displays all 24 shortlisted candidates with status badges, focus tags, key platform statements, and experience summaries.

Dynamic Category Filtering: Filter candidates in real time across five core operational priorities:

Heritage preservation

Financial transparency

Grounds & maintenance

Community engagement

Records digitisation

Side-by-Side Comparison Matrix: Compare up to 4 candidates simultaneously in a side-by-side breakdown of their focus areas, statements, and background experience.

Priority Matching Tool: A 4-question interactive matcher that ranks candidates based on user-selected governance priorities without collecting or storing personal data.

Accessible Biography Modal: Detailed candidate overlay panel equipped with focus trapping (Tab cycling), keyboard ESC handling, and focus restoration for accessibility standards (WCAG compliance).

Deterministic Vector Avatars: Generates unique, lightweight SVG portraits on-the-fly using candidate IDs, eliminating external image asset dependencies while allowing seamless fallback to real photography.

URL State Persistence: Synchronizes active filter tags and candidate comparisons directly to URL parameters (?filter=...&compare=1,2,3), enabling community members to share specific candidate views across messaging platforms.

File Structure
Plaintext
├── index.html          # Entire web application (HTML structure, CSS styles, & JS logic)
└── README.md           # Project documentation and deployment guide
Local Development & Setup
Since the application runs entirely in the browser without build steps or external package dependencies:
