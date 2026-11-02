# SPEC: Personal website for Dr Matthew Kang (v1)

## What this is
A one-page professional website for Dr Matthew Kang, consultant psychiatrist and clinician-researcher in Melbourne.

It shows who he is, what he's expert in, and what he's done, in a way colleagues, academics, and patients can all understand.

It is also a learning project, and a base that can later grow to host other ideas and projects.

## Who it's for
1. **Academics and researchers.** They want his research, publications, and a way to get in touch.
2. **Clinical colleagues.** They want his areas of expertise and where he works.
3. **Patients who look him up.** These are mostly public-clinic patients and people he sees for one-off assessments. They want to check his credentials and expertise. **He is not seeking new patients.**

All three read the same page. The About and Research sections are written in plain language.

## v1 must include
One page, in this order:

1. **Intro.** Name, "Consultant psychiatrist and clinician-researcher", one-line summary, and photo.
2. **About.** A short bio in plain language.
3. **Current roles.** Stated factually:
   - Consultant Psychiatrist, Neuropsychiatry Centre, The Royal Melbourne Hospital
   - Clinical Trials Fellow (young-onset dementia), RMH Neurosciences
   - Visiting Consultant Psychiatrist, Ramsay Clinic Albert Road (including the ketamine clinic, stated factually only)
   - Lecturer and Academic Coordinator, Department of Psychiatry, University of Melbourne; PhD candidate
4. **Clinical interests.** Neuropsychiatry, young-onset dementia, old age psychiatry, consultation-liaison psychiatry, treatment-resistant depression.
5. **Research.** Blood biomarkers (NfL, GFAP, p-tau217) in psychiatric and neurodegenerative disorders, the MiND study, and the PhD topic, explained for non-experts.
6. **Selected publications.** 5–6 highlights, plus links to Google Scholar and ORCID for the full list.
7. **Selected awards and leadership.** A short list of the strongest items only.
8. **Contact.** `matthew.kang1@unimelb.edu.au`, plus a clear statement: "I am not accepting new private patients."

Also required:
- Works well on phones as well as computers.
- Readable and accessible: good contrast, alt text on the photo, sensible headings.
- Loads fast. Plain and professional in look.

## Explicitly out of scope for v1
- Anything for recruiting patients: booking, fees, referral forms, patient education
- Blog, news, or "ideas and projects" section (later, maybe)
- Contact form (email address only)
- Multiple pages, full publication list, talks archive, downloadable CV
- Analytics, newsletter, comments, social media feeds
- Logos of RMH, Ramsay Health Care, or the University of Melbourne

## Rules the content must follow
- **AHPRA advertising rules.** No testimonials, no claims about outcomes, accurate titles only. Consider linking to his AHPRA register entry.
- **TGA rules.** No wording that promotes ketamine, or any prescription medicine, to the public. Roles are stated as facts.
- **Employer branding.** Workplaces are named as facts only, with no logos and nothing implying endorsement. Check whether RMH, Ramsay, or UoM have staff policies on public profiles.
- **Privacy.** The code is public on GitHub, so nothing private goes in this folder: no CVs, no notes. Source CVs stay outside the project.

## How it's built
- Plain HTML and CSS: one `index.html` and one stylesheet. No frameworks, no build tools, no dependencies.
- Hosted free on GitHub Pages at `<username>.github.io`. A custom domain can be added later without rebuilding.

## Still needed from Matthew
- [ ] GitHub account username (see open question below)
- [ ] Google Scholar profile URL
- [ ] ORCID iD / URL
- [ ] Professional photo
- [ ] Confirm which 5–6 publications and which awards to highlight (Claude can propose)
- [ ] Optional: AHPRA registration number, for a register link

## Done when
- The page is live on GitHub Pages and reads well on a phone and on a laptop.
- Matthew has reviewed every word, and it meets the content rules above.
- Each change is committed in git.
