DR. DAVID KORMOS — PERSONAL WEBSITE
===================================

DESIGN
------
Editorial website with charcoal and muted-pastel colours, reflecting a
senior legal, privacy and governance professional. This is a personal
site, not a marketing or law-firm website.

FILES
-----
index.html — self-contained responsive website.
david_kormos_landing_page.html — identical copy under the earlier filename.

VIEW / PUBLISH
--------------
Open index.html in any modern web browser. For publishing, upload it to
static hosting such as Netlify, Cloudflare Pages or GitHub Pages.
No build process, paid service, libraries or backend are needed.

SECTIONS
--------
- Personal profile and expertise
- Professional experience without dates or durations
- Education and continuing development
- Professional perspective and considered collaboration
- Personal Projects — explicitly separate from employer or client work
- Contact through LinkedIn: https://www.linkedin.com/in/dakorsite/

ADDING PERSONAL PROJECTS
------------------------
Open index.html in a text editor and find:

  const personalProjects = [
  ];

Add one object per PERSONAL project, separated by commas, for example:

  const personalProjects = [
    {
      title: 'Your personal project name',
      kind: 'Independent research',
      description: 'A short description of your project and its purpose.',
      contribution: 'What you personally created or investigated.',
      referenceUrl: 'https://your-public-project-link.com',
      referenceLabel: 'View project'
    }
  ];

Save and refresh the browser. The styled project entry appears automatically.
You can omit contribution, referenceUrl and referenceLabel. If no projects
are listed, the website shows an elegant, clearly labelled reserved space.
Only share materials you own or are authorized to make public, and avoid
confidential employer/client information. Entries in this section are
PERSONAL INITIATIVES, not professional work performed for employers.

BEFORE PUBLICATION
------------------
Review content for accuracy, confidentiality and any relevant professional
or employer obligations. If adding tracking or third-party embeds, review
privacy and disclosure requirements. No personal information is collected
by the current static website, and contact goes through LinkedIn.
