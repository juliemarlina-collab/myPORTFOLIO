# Julie Marlina Hasan — Portfolio

Static HTML, CSS, JavaScript and assets for GitHub Pages. Upload the **contents of this folder** to the repository root, then enable GitHub Pages for the chosen branch and root directory. Open `index.html` locally to review.

## Landing pages

`index.html` is English and `index-ms.html` is Bahasa Melayu. The EN/BM button switches between them; each project card links to its corresponding language story page. The featured Smart MUET Guide V2 section and the four Ideas in Action cards use the shared `styles.css` and `scripts.js`. The cards name Smart MUET Guide V2, Smart DT, Gemini Notebook Web Kit and CAMP21 explicitly. Small screens show section jump links below the header.

The contact buttons currently use a LinkedIn name search until a direct profile URL and preferred public email are supplied. Update both landing pages when those details are confirmed.

## Professional Sharing

The homepage Sharing section links to `stories/gemini-webinar.html` for the 26 August 2026 POLYCC Future-Ready AI Series. Its poster and livestream image sit in `stories/`; the panel appointment and report sit in `evidence/`. The story also links to the live recording and learning kit.

Other sharing pages and the DH13 folio remain included. Keep the folder structure intact so relative links work.

## Chapter image layout

The Innovative Learning Models presentation slide is beneath “The ideas I shared” on the right. The Gemini webinar poster and live screenshot sit beneath “The invitation” and “Shared live” headings on the left. On smaller screens, each heading and image stack before its chapter text. The shared layout is defined in `stories/story.css`.

`stories/uin-sharing.html` also contains a scoped layout rule for its ISIP presentation chapter and requests a versioned `story.css` URL. Upload that HTML file and `stories/story.css` together; the scoped rule prevents the chapter title, slide and narrative from overlapping when a previous stylesheet is cached.
