# 📌 QRAlliymi B2B Service Landing Page

This repository contains the QRAlliymi B2B Service Landing Page, a static, fully responsive, and self-contained promotional page designed to attract corporate clients.

## 📁 Project Directory: QR/

This page is designed to be a part of the larger QR/ project structure.

```bash
QR/
├── ... (other project folders)
├── B2B_Page/
│   ├── B2B_Images/       # All image assets for the B2B page
│   └── index.html        # ✅ Main B2B landing page file
├── Community_Page/
├── ... (other project folders)
└── index.html
```
## 🎯 Key Features

✅ Single-File Static Page: All content, styling, and structure are contained within a single index.html file for maximum simplicity and portability.

✅ Fully Responsive Design: The layout fluidly adapts from large desktops to mobile devices using CSS media queries, ensuring a seamless experience on any screen.

✅ High-Impact Hero Section: Features a visually engaging hero section with a unique curved background, layered images, and clear messaging.

✅ Sticky Navigation Header: The main header remains fixed to the top of the page on scroll, providing persistent access to navigation links.

✅ Dual Call-to-Action (CTA) Buttons: Includes two distinctly styled buttons ("B2B Login" and "Contact Us") to guide users toward key actions.

✅ Structured and Semantic HTML: The page is organized into clear, logical sections like header, footer, and content divisions, making it easy to read and maintain.

✅ Self-Contained with Inline CSS: All CSS rules are embedded within a <style> tag in the <head>, eliminating the need for external stylesheets.

✅ Consistent Branding: Utilizes QRAlliymi's official fonts, logos, and color schemes to maintain brand identity.

## 🧪 How to Use

### Clone or Download the Repository

``` bash
git clone https://github.com/Saikumar1801/B2B_Page.git
```

### Place the Folder

Copy the entire B2B_Page/ directory into the QR/ directory of your main project.

### Run on Localhost or Server

Open the B2B landing page in your browser:

```bash
http://localhost/QR/B2B_Page/index.html
```


💡 Note: Ensure all required image assets are located inside the B2B_Page/B2B_Images/ folder for the page to render correctly.

## 📝 Additional Notes

### Technology Stack:
This page is built with pure HTML5 and CSS3. It contains no JavaScript, making it extremely lightweight and fast-loading.

### Styling Approach:
The design relies heavily on CSS Flexbox for creating the complex, responsive layouts in the header and hero section. All styles are scoped and embedded directly in the HTML file, making it a single, standalone asset.

### Content Updates:
To update the page, you can directly edit the index.html file:

Text: Modify the text within tags like <b>, <p>, or <div>.

Images: Replace image files in the B2B_Images/ folder and update the src attribute in the corresponding <img> tags in the HTML.

Links: Change the href attribute on the <a> tags for the CTA buttons or header navigation.

### Portability:
Because it has no external CSS or JS dependencies, this index.html file is highly portable. It can be dropped into any web server or opened locally without any build steps or configuration.

### Dependencies:
The project uses Google Fonts loaded from the internet (as specified in the <head> tag). Fonts may not render correctly in an offline environment.
