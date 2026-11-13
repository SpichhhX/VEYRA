VEYRA WEBSITE — GitHub Pages + Jekyll

1. Create a PUBLIC GitHub repository named seo-practice.
2. Extract this ZIP and upload the CONTENTS of seo-practice into the repository root. _config.yml and index.md must be at the root, not inside an extra folder.
3. Edit _config.yml: replace SpichhhX with your GitHub username. Keep baseurl: "/seo-practice" if that is your repository name. If you choose another repository name, update baseurl too.
4. Open Settings > Pages > Build and deployment. Choose Deploy from a branch, then main and /(root), and Save. Your default branch may have another name; select the branch holding these files.
5. After the GitHub Pages build succeeds, visit https://SpichhhX.github.io/seo-practice/ . Check both pages, view page source for title/description/canonical, and open /seo-practice/sitemap.xml and /seo-practice/robots.txt.
6. Edit the site title, description, and page content to match your real learning topic. Add original examples before expecting meaningful search traffic.

Plugins already configured:
- jekyll-seo-tag: title, description, canonical, social metadata and structured metadata. The layout includes {% seo %}.
- jekyll-sitemap: generates sitemap.xml automatically at build time.
Do NOT add .nojekyll: this project needs Jekyll processing.
No database, npm, paid hosting, or paid domain is required.

GOOGLE SEARCH CONSOLE
Add a URL-prefix property for https://SpichhhX.github.io/seo-practice/ . Choose HTML file verification, upload Google's exact verification file to the repository root, wait for deployment, then click Verify. Keep the verification file afterwards. Submit the full URL https://SpichhhX.github.io/seo-practice/sitemap.xml and inspect the homepage URL. Indexing and ranking are not guaranteed.

LEARNING EXERCISES
- Choose one real topic; write a useful page answering a specific question.
- Give each page a unique title and description in its YAML front matter.
- Add a descriptive internal link from an existing page.
- Check mobile usability and speed using PageSpeed Insights.
- Record changes and later compare Search Console impressions and clicks.

GitHub Pages hosts generated static files; WordPress plugins such as Yoast and Rank Math cannot run here. The source in a public repository is visible to everyone. Never upload passwords, API keys, or private information.

LOCAL PREVIEW (optional, no Jekyll build verified in this package)
GitHub performs the Jekyll build after upload. Opening index.md directly is not a website preview. This package has been checked for required files and internal source references, but has not been deployed or built with Jekyll in this session.
