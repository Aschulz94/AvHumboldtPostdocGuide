# Formatting Conventions — Derived from the Template Files

This supplements the main [`README.md`](README.md). Rather than just linking the templates, it breaks down the **formatting patterns actually used** in the files in [`templates/`](templates/) — useful as a checklist while drafting your own.

---

## Two-Page CV

📄 [`templates/2pageCV_Example.pdf`](templates/2pageCV_Example.pdf)

**Section order used in the template:**

1. **Header** — name and degree, phone, email, city/country, plus one line of links (research website, Google Scholar, LinkedIn, courses)
2. **Education** — reverse chronological; degree + field, institution, location, year range
3. **Experience** — reverse chronological; role, organization, year range, and one bullet describing the work (for research positions, name the PI/advisor and thesis title)
4. **Awards**
5. **Teaching**
6. **Invited Talks**
7. **Leadership and Service Activities**

**Explicitly excluded:** publications. They live in the separate publication list and don't count toward the two pages.

**Formatting notes:**
- Role/degree on the left, **year range right-aligned** on the same line, institution on the next line
- Dates as **year ranges** (`2018–2022`, `2022–Present`) — unambiguous for reviewers anywhere
- One short bullet per position: what you did, not a list of duties

**Optional sections** you may want depending on your career stage: Grants & Fellowships (funder, title, role, amount, dates), Supervised Students, Reviewing.

---

## Complete Publication List

📄 [`templates/Humboldt_ListOfPubs_Example.docx`](templates/Humboldt_ListOfPubs_Example.docx) · [official sample](https://www.humboldt-foundation.de/fileadmin/Bewerben/Allgemein/sample_list_of_publications.pdf)

**Title line:** `Complete list of publications of <Name>, PhD`

**Sections, in order (as in the template):**

1. Journal Publications with peer review process
2. Submitted publications with peer review process (on pre-print servers)
3. Submitted publications with peer review process
4. Conference Publications with peer review process
5. Accepted Conference Publications
6. Book Chapters

**Formatting rules:**
- **Numbered, reverse chronological** within each section
- Full author list in `Lastname, I.` format, then `"Title"`, journal/venue, volume/issue, `(Year)`
- **Corresponding author marked with an asterisk (\*)**
- Submitted works show status in place of volume/pages: `Submitted (2023)`, `Under Review (2023)`
- Closing line: **`As of <Month Year>`** so reviewers know how current the list is

**Required by the Foundation but easy to forget:** a note at the bottom indicating which publications **derive from your dissertation**. Do **not** include unsubmitted work.

---

## List of Key Publications

📄 [`templates/ListOfKeyPublications_Example.docx`](templates/ListOfKeyPublications_Example.docx) · [official sample](https://www.humboldt-foundation.de/fileadmin/Bewerben/Allgemein/sample_list_of_key_publications.pdf)

Each entry has **two parts**:

1. **Full citation** — authors, title, journal, volume/issue/pages, year, DOI
2. **A paragraph (~6–10 sentences in the template)** covering:
   - The question and what the paper showed
   - The methods, and why they matter
   - **Your specific contribution** — especially if you're not first author
   - **How it connects to the project you're proposing** (the template closes each paragraph by linking the paper to the proposed research or partnership model)

The paragraph is doing real work: reviewers may not be specialists in your subfield, and this is where you show why *this* paper qualifies you for *this* project.

**Count:** postdocs 1–3, experienced researchers 3–5. Surplus entries are removed without notice — pick the papers that most directly build the case for your proposal.

---

## Research Statement (LaTeX)

📄 [`templates/research-statement-latex/main.tex`](templates/research-statement-latex/main.tex)

- 10 pt `article`, 6.5 in × 9 in text block, superscript numeric citations (`natbib`) with tight bibliography spacing to save room
- **Title page = online-form drafting space** (Title, Summary, Impact — each with its character limit in a comment). It is *not* part of the 5-page PDF.
- **Pages 1–5:** Introduction → Project Significance → What Questions Are to Be Examined? (with a brief timeline) → Proposed Project Methodology (subsections per research question) → References
- Built-in `\TODO{}` macro (red text) for drafting notes
- Wrap figures (`wrapfig`) to fit a figure without losing much text space

---

## Quick Checklist Before You Submit

- [ ] CV is exactly 2 pages, no publications
- [ ] CV dates are unambiguous (year ranges or written months)
- [ ] Full publication list is sectioned, reverse chronological, corresponding authors marked (\*)
- [ ] Publication list notes dissertation-derived papers and ends with "As of [Month Year]"
- [ ] Each key publication has a full citation **plus** a paragraph tying it to your proposed project
- [ ] Author order and completeness triple-checked (inaccuracies can cause formal rejection)
- [ ] Research outline is ~5 pages including references, with host contributions attributed
