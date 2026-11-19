# Calvary Life Tutors — website

The website of **Calvary Life Tutors**, which offers mentored ministry training through local-church Bible Schools. It covers short courses (Certificate in Christian Discipleship, Diploma in Leadership, Advanced Diploma in Ministry, Higher Diploma in Shepherding) and pathways to Bachelor, Master and Doctor of Ministry. The site serves Evangelical, Charismatic and Pentecostal churches.

**Live site:** https://hlaolil.github.io/cltw/

## What's on the site

| Section | Folder | Contents |
| --- | --- | --- |
| Introduction | `intro/` | Who we are, about Calvary, character, principles, statement of faith, philosophy, departments, history and accreditation |
| Bible Schools | `bible_schools/` | Starting and registering a centre, the dean's documents, courses, the academic tutor, the list of Bible Schools, newsletters and FAQs. The numbered folders (`0_NewCentre` to `7_Graduate`) hold the downloadable packs |
| Student info | `student_info/` | Course introduction, method of study, receiving credits and e-course learning |
| Calvary Academics | `cal_acad/` | Programme and Phase 1 pages and the course folders |
| Study resources | `study_resources/` | Writing and research help, critical thinking, dissertation FAQs and graduate documents |

The site has about 1,200 HTML pages and about 230 PDF and PowerPoint documents (roughly 59 MB).

## Structure

```
index.html        home page
css/              stylesheets (style_clt.css is the main one)
images/           layout and content images
SpryAssets/       Adobe Spry form-validation scripts used by the forms
robots.txt
```

## Run it locally

It is a static site:

```bash
python3 -m http.server 8000
# open http://localhost:8000/
```

GitHub Pages publishes the `main` branch.
