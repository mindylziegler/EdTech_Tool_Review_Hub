EdTech Tool Review

A standards-based scoring tool for evaluating classroom technology — designed and built by future educators.

Teachers face thousands of tech tools, all promising to transform learning, with no time to test them and no shared way to judge which are worth adopting. This tool fixes that: pick a tool, score it against eight research-based criteria, and get an instant, weighted recommendation — so a teacher knows in minutes whether a tool is worth their time.

Live tool: (add your GitHub Pages URL here once it's published)

Who built it

This tool was created by students in EDUC 201 · Technology in Education at Perry Meridian High School — a dual-credit course (through Ivy Tech Community College) in the Education Professions pathway, where high schoolers preparing to become teachers do the real work of the profession.

The evaluation rubric behind this tool wasn't handed to students — they built it themselves, translating the ISTE and InTASC professional standards into criteria a working teacher would actually use. This tool puts that rubric to work.

What it does
Scores a tech tool on eight weighted criteria using a 1–4 scale.
Handles "Not applicable" — when a criterion genuinely doesn't fit a tool (a name-picker has no academic-integrity stakes), it's dropped from the total so the score stays fair.
Shows a live weighted score (points + percentage) and a recommendation as you go.
Lets reviewers copy their full review to paste elsewhere, and optionally record evidence for each score.
The criteria
Criterion	Weight (max points)
Learning Value & Effectiveness	×3 (12)
Accessibility & Equity	×2 (8)
Engagement	×2 (8)
Teacher Workload / Cost / Sustainability	×2 (8)
Academic Integrity	×2 (8)
Collaboration	×1 (4)
Ownership	×1 (4)
Data & Privacy / Safety	×1 (4)

56 points possible when every criterion applies. Collaboration, Engagement, and Academic Integrity can be marked N/A.

Recommendation bands
Highly recommend — 80%+
Recommend — 70–79%
Consider — 60–69%
Avoid — below 60%
Using the tool
Open the tool (the live URL above).
Enter the tool's name; add your own name or stay anonymous.
Score each criterion — or mark it N/A where it doesn't apply.
Watch the score and recommendation update live at the bottom.
Copy my review to grab your full review as text, or Submit review if data capture is set up (below).
How it's built

A single, self-contained HTML file — no build step, no dependencies, no accounts. The school logo, all criteria and descriptors, and the scoring logic are built in. Open the file in any browser and it works.

Hosting: it's served as a static page via GitHub Pages. To run it yourself, download edtech-review-tool.html and open it, or fork this repo and enable Pages under Settings → Pages.

Optional data capture: the Submit review button can post each review to a Google Sheet via a Google Apps Script Web App, so contributed reviews collect automatically. Setup instructions are in the project's setup guide.

About the larger project

This scoring tool is one piece of the EdTech Review Hub — a published, student-built resource of classroom-technology reviews, created for teachers in the building (and eventually the district) to use, and for future Education Professions students to inherit and extend.

License

The code in this repository is released under the MIT License — use it, adapt it, build on it freely; just keep the credit.

The Perry Meridian High School name and Falcon logo are school trademarks and are not covered by the MIT License. Please replace the logo with your own if you fork this tool for another school.
