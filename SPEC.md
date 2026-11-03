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
   - Research Fellow and Student Site Coordinator, Department of Psychiatry, University of Melbourne; PhD candidate
4. **Clinical interests.** Neuropsychiatry, young-onset dementia, old age psychiatry, consultation-liaison psychiatry, treatment-resistant depression.
5. **Research.** Blood biomarkers (NfL, GFAP, p-tau217) in psychiatric and neurodegenerative disorders, the MiND study, and the PhD topic, explained for non-experts.
6. **Selected publications.** These six, plus links to Google Scholar and ORCID for the full list:
   1. Kang et al. (2025) Plasma GFAP and NfL are elevated in bipolar disorder. *Bipolar Disorders*. (2025 Research Highlight)
   2. Kang et al. (2025) NfL and GFAP in mood and anxiety disorders: systematic review and meta-analysis. *Brain, Behavior, and Immunity*.
   3. Kang et al. (2025) Apathy and affective symptoms associated with elevated plasma NfL but not p-tau181 in Alzheimer's disease. *Alzheimer's & Dementia: DADM*.
   4. Eratne, Kang et al. (2024) Plasma and CSF NfL distinguish neurodegenerative from primary psychiatric conditions in a clinical setting. *Alzheimer's & Dementia*.
   5. Kang et al. (2023) Carer burden in early-onset Alzheimer's disease vs behavioural-variant FTD. *International Psychogeriatrics*.
   6. Kang et al. (2025) Beyond black-box AI: interpretable hybrid systems for dementia care. *Alzheimer's & Dementia: DADM*.
7. **Selected awards and leadership.** These six:
   1. Dean's Award for Excellence in Graduate Research, University of Melbourne (2026)
   2. Invited symposium speaker, biomarkers in psychiatry, World Congress of Psychiatry, Stockholm (2026)
   3. Executive Committee (Communications Chair), Neuropsychiatric Syndromes PIA, Alzheimer's Association ISTAART (2026–)
   4. AAIC ISTAART Ambassador (2025)
   5. CINP Early Career Committee; Chair, CINP Research Fellowship Program (2024–)
   6. RANZCP Faculty of Psychiatry of Old Age Trainee Prize (2023)
   
   No dollar figures for funding anywhere on the site.
8. **Contact.** `matthew.kang1@unimelb.edu.au`, plus a clear statement: "I am not accepting new private patients." Profile links:
   - LinkedIn: https://www.linkedin.com/in/matthew-kang-22a99162/
   - Google Scholar: https://scholar.google.com/citations?user=s7fMjfYAAAAJ
   - ORCID: https://orcid.org/0000-0001-9375-3762

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
- Hosted free on GitHub Pages at `https://drmattkang.github.io` (GitHub account: `drmattkang`; project name: `drmattkang.github.io`). A custom domain can be added later without rebuilding.

## Still needed from Matthew
- [x] GitHub account username: `drmattkang`
- [x] LinkedIn URL
- [x] Google Scholar profile URL
- [x] ORCID iD / URL
- [x] Professional photo: `images/matthew-kang.jpg` (560×560, hidden metadata removed)
- [x] Highlighted publications and awards confirmed
- [ ] Optional: AHPRA registration number, for a register link

## Done when
- The page is live on GitHub Pages and reads well on a phone and on a laptop.
- Matthew has reviewed every word, and it meets the content rules above.
- Each change is committed in git.
