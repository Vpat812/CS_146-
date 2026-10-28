# Stevens Campus Guide

CS 146 group project: help new Stevens students explore campus and academic resources.

## Departments page (issue #2)

Open `departments.html` directly in a browser. No installation, build step, account, or server is required. CSS and JavaScript are included in the file so the page is easy to integrate with the rest of the group project.

Features:
- School tabs with Arrow Left/Right, Home, and End keyboard navigation.
- Search across names, descriptions, schools, and areas of study.
- Expandable department/program details and official Stevens links.
- Reset and no-results states, live result counts, and responsive layouts.

The directory includes all nine Schaefer departments, the three undergraduate computing programs, eight business majors, seven HASS majors, and five featured professional education master's programs. Other schools' programs are labeled as programs rather than formal departments. Graduate/minor/certificate coverage is intentionally summarized with links to complete official listings.

## Integration

Link to `departments.html` from the team's navigation. This page currently links to official campus resources, avoiding broken links to teammates' pages that do not yet exist. Replace those navigation links with the team's agreed filenames when available. No other project pages are implemented by this task.

## Content sources

Reviewed October 28, 2026:
- https://www.stevens.edu/academics/our-schools
- https://www.stevens.edu/school-engineering-science/departments
- https://www.stevens.edu/school-computing
- https://www.stevens.edu/school-business/undergraduate-programs
- https://www.stevens.edu/hass
- https://online.stevens.edu/

Descriptions are short student-written summaries. Department cards list areas of study, not a complete degree inventory. Confirm degree requirements and contact information with Stevens. Classroom locations are not inferred from departments.

## Manual verification

1. Open the page and confirm 32 total results.
2. Select each school and confirm 9 engineering, 3 computing, 8 business, 7 HASS, and 5 professional education entries.
3. In Computing, search `cyber`; confirm one result and expand its B.S. information.
4. Search a nonexistent term; confirm the no-results message.
5. Reset; confirm all 32 entries return and the search receives focus.
6. Focus a tab and use Arrow Left/Right, Home, and End. Confirm selection, focus and panel content stay synchronized.
7. At phone widths, confirm tabs wrap, cards stack, and controls remain usable.

The page has no remote fonts, images, libraries, or API requests. The under-two-second requirement should be measured on the final team's hosting and target devices; local verification alone does not guarantee production performance.
