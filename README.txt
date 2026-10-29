AZEEM CONSTRUCTION WEBSITE — RESTRUCTURED STATIC FILES

STRUCTURE
- index.html — homepage
- about-us/index.html
- services/index.html and individual SEO service pages under services/<slug>/index.html
- projects/index.html and the available project detail page under projects/<slug>/index.html
- contact/index.html
- blog/index.html and blog/lda-map-approvals-lahore-guide/index.html
- our-process/index.html
- testimonials/index.html
- privacy-policy/index.html
- thank-you/index.html
- construction-company-dha-lahore/index.html
- turnkey-home-builders-bahria-town-lahore/index.html
- 404.html

IMPORTANT BEFORE LAUNCH
1. Replace the existing placeholders such as [domain], [Phone Number], [WhatsApp Number], [Email], [PEC License Number], [Facebook URL], [Instagram URL], [YouTube URL], [Google Business Profile URL], and [Google Maps Embed URL] with real values.
2. The commercial DHA project-detail page retains editorial placeholders such as [Project Name], [Number], [Month, Year], and [Brand]. Replace these with verified project information before publishing that page.
3. Open construction/index.html (or index.html if you moved the contents up one level) to start from the homepage. The homepage now contains an Explore Every Page directory with links to every HTML page. Internal page links use relative paths to support both local file browsing and static hosting.
4. The contact form currently posts to /thank-you/. A static host alone does not process POST form submissions; connect a form handler before relying on production enquiries.

DESCRIPTIVE HTML FILENAMES
All nested original index.html pages have been kept as lightweight redirects to the descriptive HTML page in the same folder. Root index.html remains the homepage. Canonical folder URLs still resolve via the redirect stubs. The contact form is a front-end preview only; POST needs a backend. On GitHub Pages deploy the contents of the construction/ directory at the configured publishing root, not the outer packaging folder. Replace [domain] canonical and other placeholders before launch.

RENAMES (original -> descriptive page)
about-us/index.html -> about-us/about-us.html
blog/index.html -> blog/blog.html
blog/lda-map-approvals-lahore-guide/index.html -> blog/lda-map-approvals-lahore-guide/lda-map-approvals-lahore-guide.html
construction-company-dha-lahore/index.html -> construction-company-dha-lahore/construction-company-dha-lahore.html
contact/index.html -> contact/contact.html
our-process/index.html -> our-process/our-process.html
privacy-policy/index.html -> privacy-policy/privacy-policy.html
projects/commercial-construction-dha-phase-6/index.html -> projects/commercial-construction-dha-phase-6/commercial-construction-dha-phase-6.html
projects/index.html -> projects/projects.html
services/architectural-design-lda-dha-approvals/index.html -> services/architectural-design-lda-dha-approvals/architectural-design-lda-dha-approvals.html
services/commercial-construction-lahore/index.html -> services/commercial-construction-lahore/commercial-construction-lahore.html
services/construction-project-management-lahore/index.html -> services/construction-project-management-lahore/construction-project-management-lahore.html
services/grey-structure-construction-lahore/index.html -> services/grey-structure-construction-lahore/grey-structure-construction-lahore.html
services/home-renovation-lahore/index.html -> services/home-renovation-lahore/home-renovation-lahore.html
services/index.html -> services/services.html
services/mep-firefighting-systems-lahore/index.html -> services/mep-firefighting-systems-lahore/mep-firefighting-systems-lahore.html
services/turnkey-home-construction-lahore/index.html -> services/turnkey-home-construction-lahore/turnkey-home-construction-lahore.html
testimonials/index.html -> testimonials/testimonials.html
thank-you/index.html -> thank-you/thank-you.html
turnkey-home-builders-bahria-town-lahore/index.html -> turnkey-home-builders-bahria-town-lahore/turnkey-home-builders-bahria-town-lahore.html
