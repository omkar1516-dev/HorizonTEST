<div align="center">

# 🎓 College Event Website

### Celebrate • Compete • Connect

A responsive college event website built with **HTML5, CSS3, Tailwind CSS, and JavaScript**.

<!-- Replace this image URL with your own event banner or repository image path -->
<img src="assets/highlight-images/event-banner.jpg" alt="College Event Website Banner" width="100%" />

<br />

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

<!-- Update these URLs with your actual project links -->
[🌐 Live Website](https://YOUR-LIVE-WEBSITE-LINK) ·
[📝 Registration](https://YOUR-GOOGLE-FORM-LINK) ·
[📂 Google Drive](https://drive.google.com/drive/folders/YOUR-FOLDER-ID)

</div>

---

## 📖 About the Project

The **College Event Website** is a web platform created to share information about a college event in an attractive and easy-to-use format. Visitors can explore event details, games, highlights, sponsors, downloadable documents, and important external resources.

The website uses HTML, CSS, Tailwind CSS, and JavaScript to provide a responsive layout and interactive user experience.

## ✨ Website Features

- **Event information:** Present event details, announcements, and important updates.
- **Game section:** Display games and related images.
- **Sponsor section:** Showcase event sponsors using sponsor images and branding.
- **Highlights gallery:** Display event highlights and memorable moments.
- **PDF downloads:** Provide downloadable event documents, brochures, schedules, or rules.
- **Quick links:** Add registration forms, Google Drive folders, and other useful resources.
- **Contact information:** Share organizer contact details and social media links.
- **Responsive design:** Support desktop, tablet, and mobile screens.
- **Interactive interface:** Use JavaScript for website interactions.

## 🧰 Technology Stack

| Technology | Usage |
|---|---|
| HTML5 | Page structure and content |
| CSS3 | Custom styles and visual design |
| Tailwind CSS | Utility classes and responsive styling |
| JavaScript | Interactive elements and functionality |

## 💻 Software Requirements

| Software | Requirement / Recommendation |
|---|---|
| Operating System | Windows 10/11, macOS, or Linux |
| Code Editor | Visual Studio Code (recommended) |
| Web Browser | Latest Google Chrome, Microsoft Edge, Firefox, or Safari |
| Local Server | VS Code Live Server extension (recommended) |
| Internet | Needed for CDN libraries, online fonts, and externally hosted resources |

### Recommended VS Code Extension

- **Live Server** – runs the website locally and refreshes the browser when you save changes.

## 📁 Project Folder Structure

The following is a suggested structure based on the four asset folders used by this project. Rename the example folder paths below if your actual folder names are different.

```text
college-event-website/
│
├── index.html
├── README.md
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── pdf/
│   ├── event-brochure.pdf
│   ├── event-schedule.pdf
│   └── rules-and-guidelines.pdf
│
├── game-images/
│   ├── game-1.jpg
│   ├── game-2.jpg
│   └── game-3.jpg
│
├── sponsor-images/
│   ├── sponsor-1.png
│   └── sponsor-2.png
│
└── highlight-images/
    ├── highlight-1.jpg
    ├── highlight-2.jpg
    └── event-banner.jpg
```

### 📂 What Each Folder Contains

| Folder | Purpose |
|---|---|
| `pdf/` | PDF files visitors can open or download |
| `game-images/` | Images used in the games section |
| `sponsor-images/` | Sponsor logos, banners, and sponsor images |
| `highlight-images/` | Event highlights, gallery images, and banner images |
| `css/` | Stylesheets and custom CSS |
| `js/` | JavaScript files |

> **Note:** Keep the folder names and file paths consistent with the paths used in your HTML and JavaScript. If your existing project uses different names, use those exact names in this README.

## 🚀 Getting Started

### 1. Download or clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### 2. Open the project

```bash
cd YOUR-REPOSITORY
```

Open the project folder in Visual Studio Code.

### 3. Run the website

1. Install the **Live Server** extension in VS Code.
2. Open `index.html`.
3. Right-click and select **Open with Live Server**.
4. The website will open in your default browser.

You can also open `index.html` directly in a browser if your project does not depend on server-side features.

## 🖼️ Website Preview

Add screenshots of your actual website to the `highlight-images/` folder and update the paths below.

<div align="center">

| Homepage | Games Section |
|---|---|
| ![Homepage](highlight-images/homepage.png) | ![Games](highlight-images/games-section.png) |

| Sponsors Section | Highlights Section |
|---|---|
| ![Sponsors](highlight-images/sponsors-section.png) | ![Highlights](highlight-images/highlights-section.png) |

</div>

If you use different screenshot filenames, replace the paths with the correct filenames. GitHub displays images when the paths point to existing image files in the repository.

## 🔗 Important Project Links

Update the sample links with your own URLs.

| Resource | Editable Link |
|---|---|
| Live Website | [Visit Website](https://YOUR-LIVE-WEBSITE-LINK) |
| Registration Form | [Register Here](https://YOUR-GOOGLE-FORM-LINK) |
| Main Google Drive Folder | [Open Google Drive](https://drive.google.com/drive/folders/YOUR-FOLDER-ID) |
| Event PDFs | [Download / View PDFs](https://YOUR-PDF-DRIVE-LINK) |
| Event Photos | [View Photos](https://YOUR-PHOTO-DRIVE-LINK) |
| Sponsor Details | [View Sponsor Resources](https://YOUR-SPONSOR-DRIVE-LINK) |

## ✏️ How to Customize the Website

### 1. Change event information

Open `index.html` and update the event name, description, date, venue, schedule, announcements, and other displayed text.

### 2. Add or replace PDF files

1. Put the new PDF inside the `pdf/` folder.
2. Find the corresponding download link in your HTML.
3. Update the link to the new PDF path.

Example:

```html
<a href="pdf/event-brochure.pdf" download>
    Download Event Brochure
</a>
```

### 3. Change game images

1. Add the new game images to `game-images/`.
2. Update the image paths in the relevant HTML section.

```html
<img src="game-images/game-1.jpg" alt="Game 1">
```

### 4. Change sponsor images

1. Add sponsor logos or images to `sponsor-images/`.
2. Update the image paths in the sponsor section.

```html
<img src="sponsor-images/sponsor-1.png" alt="Event Sponsor">
```

### 5. Change highlight images

1. Add event photographs to `highlight-images/`.
2. Update the corresponding image paths in the HTML or JavaScript gallery.

```html
<img src="highlight-images/highlight-1.jpg" alt="Event Highlight">
```

### 6. Change Google Drive and registration links

Find the relevant `<a>` element and replace its `href` value.

```html
<a href="https://drive.google.com/drive/folders/YOUR-FOLDER-ID"
   target="_blank"
   rel="noopener noreferrer">
    Open Event Drive
</a>
```

Make sure the Google Drive sharing permissions allow your intended visitors to access the files.

### 7. Change contact details

Update the contact section in `index.html`.

```html
<a href="mailto:your-email@example.com">
    your-email@example.com
</a>

<a href="tel:+910000000000">
    +91 00000 00000
</a>
```

Also update social media links wherever they appear.

## 📞 Contact & Organizer Details

Replace the sample information with your actual details.

- **College / Organization:** Your College Name
- **Event Name:** Your Event Name
- **Email:** your-email@example.com
- **Phone:** +91 00000 00000
- **Instagram:** https://www.instagram.com/YOUR-PAGE
- **LinkedIn:** https://www.linkedin.com/company/YOUR-PAGE
- **Google Drive:** https://drive.google.com/drive/folders/YOUR-FOLDER-ID

## 🤝 Contributing

Suggestions and improvements are welcome.

1. Fork this repository.
2. Create a new branch.
3. Make your changes.
4. Test the website on desktop and mobile.
5. Submit a pull request describing your changes.

## 📄 License

**License:** Not specified.

Add a `LICENSE` file if you want to publish the project under a particular open-source license.

---

<div align="center">

### Made with ❤️ for College Events

**Built using HTML • CSS • Tailwind CSS • JavaScript**

</div>
