This README provides an overview of the project, instructions for setup, customization, and usage, and relevant details about this website's features.

```markdown
Nannim David Dandam - Portfolio Website

This repository hosts a responsive Single Page Application (SPA) for Nannim David Dandam's professional CV/Resume/Portfolio. Built with HTML, CSS (via Tailwind CSS), and vanilla JavaScript, the website showcases my skills, education, work experience, and achievements as a PHP/Laravel Developer.

Features

- Responsive Design: Mobile-first layout that adapts seamlessly to all screen sizes using Tailwind CSS.
- SPA Navigation: Smooth section switching without page reloads, implemented with vanilla JavaScript.
- Sticky Footer: Footer remains at the bottom of the viewport, even with minimal content.
- Landing Page: The "Home" tab features a hero section with a profile photo placeholder, gradient background, and call-to-action buttons, followed by a summary of expertise, innovation, and collaboration.
- Sections: Organized into Home, Profile, Education, Experience, Skills, and Achievements.
- Animations: Subtle fade-in transitions enhance user experience.
- Lightweight: Single HTML file with no heavy dependencies, using Tailwind CSS via CDN.

Demo

You can view the live portfolio by opening `index.html` in a web browser or hosting it on a static file server like GitHub Pages, Netlify, or Vercel.

Setup

1. Clone the Repository:
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   ```
2. Navigate to the Project Directory:
   ```bash
   cd <your-repo-name>
   ```
3. Open the Website:
   - Open `index.html` directly in a web browser for local testing.
   - Alternatively, host the file on a static server (e.g., GitHub Pages, Netlify) for online access.

 Customization

- Profile Photo: Replace the placeholder image in `index.html` by updating the `<img src="https://placehold.co/150x150">` in the Home section with a URL to your profile photo.
- Content: Edit the text in the `<section>` elements to update your personal details, experience, or achievements.
- Styling: Modify Tailwind CSS classes or add custom styles in the `<style>` section to change colors, fonts, or layout.
- Additional Sections: Add new `<section>` elements and update the navigation JavaScript to include them in the SPA.

 File Structure

```
├── index.html       # Single HTML file containing the entire SPA
├── README.md        # This file
```

Hosting

To host the website:
1. Push `index.html` to a GitHub repository.
2. Enable GitHub Pages in the repository settings under the "Pages" section, selecting the `main` branch.
3. Alternatively, deploy to platforms like Netlify or Vercel by uploading or linking the repository.

Technologies Used

- HTML5: Structure of the website.
- CSS (Tailwind CSS): Styling and responsive design via CDN.
- JavaScript: SPA navigation and section transitions.
- Placehold.co: Placeholder image for the profile photo.

Contributing

This is a personal portfolio project. If you have suggestions or improvements, please open an issue or submit a pull request.

License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Contact

Nannim David Dandam  
Email: [dandamnannim125@gmail.com](mailto:dandamnannim125@gmail.com)  
Phone: +2348141232871


Last updated: August 13, 2025
```

How to Use the README:
1. Create the File:
   - Copy the above content into a file named `README.md` in the root of your GitHub repository.
   - Replace `<your-username>` and `<your-repo-name>` with your actual GitHub username and repository name.
2. Add a License (Optional):
   - If you want to include a license, create a `LICENSE` file in the repository with the MIT License text (or your preferred license). You can generate one using GitHub's license template feature.
3. Push to GitHub:
   ```bash
   git add README.md
   git commit -m "Add README for portfolio website"
   git push origin main
   ```
4. Hosting:
   - Follow the instructions in the README to set up GitHub Pages or another hosting platform.
   - Update the "Demo" section with the live URL once hosted.

