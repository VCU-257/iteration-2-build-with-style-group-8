# Student Name: Rayan Maazouz

## 1. My Assigned Work

My assigned work for Iteration 2 was to clean up the Login page and create a project presentation.

- **loginPage.html** – Resolved unresolved git merge conflicts that left two competing form implementations in the file (a bare-bones HTML form vs. a fully featured one). Kept the modern version and removed all conflict markers. Reworked the page to match the site's consistent look: replaced the standalone dark-gradient design with the same Bootstrap 5.3 Lux theme and Bootstrap Icons used across every other page, added the identical navbar (brand link, search bar, Seller button, cart icon, person icon), switched the background to the site's standard light gray (`#f8f9fa`), converted all form inputs to Bootstrap `input-group` components with icon prefixes, replaced the custom red submit button with Bootstrap `btn btn-primary`, and wired up Bootstrap's built-in `is-invalid`/`invalid-feedback` classes for real-time form validation. Also replaced the hand-rolled toast with Bootstrap's `Toast` component and added a post-login redirect to the home page.

- **presentation.html** – Built a 9-slide interactive HTML presentation for the full project. Slides cover: project hero/title, the problem being solved, the solution flow, a dedicated page for each of the 5 site pages (Home, Search, Product, Checkout, Login) with feature lists and browser window mockups, and a tech stack overview. Navigation works via on-screen arrow buttons, dot indicators, or keyboard arrow keys.

- **BudgetBuilds_Presentation.pptx** – Converted the HTML presentation into a PowerPoint file using python-pptx. Each slide was hand-built with positioned shapes, gradient-approximated backgrounds, browser chrome mockups, and consistent BudgetBuilds branding (dark navy background, blue and red accents) so it can be opened and presented directly in PowerPoint or Google Slides.

## 2. AI / LLM Usage

* **What I asked the AI:** I used Claude Code to identify and resolve the merge conflicts in `loginPage.html`, restyle the login page to match the rest of the site, build the HTML slide deck, and generate the PowerPoint file programmatically.

* **How it helped & What I learned:** The AI helped me understand how Bootstrap's `input-group` pattern works for combining icons with form fields, and how `is-invalid` and `invalid-feedback` interact to show validation errors without writing custom CSS. For the PowerPoint generation I learned how python-pptx positions shapes using EMU units (English Metric Units) and how to layer rectangles, text boxes, and ovals to recreate a styled UI without image assets. I reviewed all generated code to understand each component before accepting it.

## 3. Live Site Link

* **Live URL:** https://vcu-257.github.io/iteration-2-build-with-style-group-8/
