# PorfolioWebsite
 HTML/CSS based CV website

# My Portfolio Website

This is a static developer portfolio website built with **HTML5** and **CSS3** (no JavaScript). It showcases my projects, experience, and contact information in a multi-page format. The design is inspired by Yashita Namdeo's portfolio site and uses a dark theme with accent colors.

## 📁 Project Structure

- **index.html** – Landing page (introduction and home).  
- **about.html** – About Me page (personal bio and skills).  
- **experience.html** – Experience page (work and education history).  
- **projects.html** – Projects page (portfolio of projects with descriptions).  
- **contact.html** – Contact page (invitation to connect, with email link).  
- **assets/** – Static assets: CSS, images, and icons.  
  - **css/style.css** – Stylesheet for the site.  
  - **images/** – Folder for images (e.g., profile picture, project screenshots).  
  - **icons/** – Folder for social icons (GitHub, LinkedIn, etc.).  
  - **resume.pdf** – My resume file (downloadable via the "Resume" link in nav).

Each HTML page includes the same header (navigation menu) and footer (social links and contact info) for consistency. The site is styled with a single CSS file for simplicity.

## 🚀 How to Run Locally

1. **Clone or download** this repository to your local machine.  
2. Open the `index.html` file in your web browser. You can navigate to other pages via the top menu.  
3. (Optional) You can also serve the files using a simple HTTP server (like using VSCode Live Server or Python's `http.server`) to test as if it were on a web server, but it's not required.

## 🎨 Customization

- **Content:** Replace the placeholder text (name, bio, job titles, project descriptions, etc.) in the HTML files with your information. Each section in the HTML is marked by comments to help you identify where to put your content.
- **Images:** Add your own images in the `assets/images` folder and update the `<img>` `src` attributes in HTML. For example, replace `profile.jpg` with your profile picture file name. Similarly, add screenshots for your projects.
- **Icons & Links:** Update the social media links in the footer (the `href` for GitHub and LinkedIn) with your profiles. Ensure you have corresponding icon images (or you can use an icon font/CDN). Also update the email in the footer and contact page to your email. Update the Resume link to point to your actual resume PDF (replace the placeholder file if needed).
- **Colors:** The color theme is controlled by CSS variables in `style.css` (at the top). If you want to adjust the theme, you can change these hex values. For example, `--color-accent` and `--color-accent-alt` control the primary accent colors (red-orange and gold in this design).

## 🌐 Deployment to GitHub Pages

You can host this portfolio using **GitHub Pages** in either of two ways:

**Option 1: GitHub User/Organization Page** (personal portfolio at `username.github.io`):  
- Rename your repository to `<your-github-username>.github.io`.  
- Push all the files to the `main` branch of this repo.  
- In your repository settings, enable GitHub Pages if not automatically enabled. (For a user site, GitHub Pages uses the root of the repo by default.)  
- Your site should be live at `https://<your-github-username>.github.io` within a minute or two.

**Option 2: GitHub Project Page** (if you want to use a custom repo name):  
- Push the code to the `main` branch (or `gh-pages` branch) of your repository.  
- In the repository settings, under "Pages", set the source to the branch you pushed to (e.g., `main` branch). If using `main`, you can select `/ (root)` as the folder.  
- After saving, GitHub Pages will provide a URL like `https://<your-username>.github.io/<repository-name>/`. Use that to access your site.

After deployment, test the live site to ensure all links and images are loading correctly. All the links are relative (e.g., `about.html`), so they should work on GitHub Pages as long as the files are in the root or the correct published folder.

**Note:** If you add new files or make changes, just commit and push them to GitHub. GitHub Pages will update the website automatically on each push (there may be a minute or so delay). If you don't want Jekyll processing (not needed here), you can add an empty `.nojekyll` file to the root just to be safe.

## 💡 Additional Tips

- You can use a custom domain with GitHub Pages if you have one, by adding a `CNAME` file with your domain and configuring DNS (see GitHub Pages documentation for details).  
- Since this site uses no framework, maintenance is simple – just edit the HTML/CSS. If you want to add dynamic features (like a contact form that sends emails), you'd need to include a third-party service or backend since GitHub Pages doesn't support server-side code.  
- Keep your repository updated with your latest projects and experience to ensure your portfolio stays current!

