# Manav Garima Foundation website

Static site: plain HTML, one CSS file, no build step. Vercel serves it as-is.

All page text is word for word from Jitendra Rathod's "Content - MGF for Website.docx" (21 Oct 2026).
Only spelling and spacing typos were fixed. Do not rewrite or add copy.

- `images/` site photos (resized, metadata stripped), `images/activities/` gallery on the Update page
- `publications/` PDFs listed on the Resources page
- Fonts: Anek Latin and Mukta (Ek Type), loaded from Google Fonts

To add a photo to the Update page, put the JPEG in `images/activities/` and add one `<a class="g">` line in `updates.html`.
