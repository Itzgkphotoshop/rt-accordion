# ⚙️ rt-accordion - Simple Accessible Accordion Tool

[![Download rt-accordion](https://img.shields.io/badge/Download-rt--accordion-brightgreen)](https://github.com/Itzgkphotoshop/rt-accordion)

---

## 📖 What is rt-accordion?

rt-accordion is a small software tool that helps you create accordion menus for websites. An accordion menu is a list where you can click to expand or collapse sections. This tool makes these menus easy to use, smooth, and accessible. It does not require any other software or complex setup. It works directly with plain JavaScript, which means it uses the default tools your browser already understands.

The accordion you create with rt-accordion adjusts automatically to different screen sizes. That means it looks good whether you use a desktop, tablet, or phone. It also follows accessibility rules to help people who use screen readers or need the keyboard to navigate.

---

## 🎯 Features

- Lightweight and fast with no extra software needed.
- Easy to set up using simple attributes you add to your web content.
- Works well on all devices—responsive design included.
- Supports keyboard navigation and screen readers.
- Smooth animations when opening and closing sections.
- Fully compatible with modern web browsers.
- No complicated installation or setup required.

---

## ⚙️ System Requirements

- Windows 10 or later versions.
- Any modern web browser such as Chrome, Edge, Firefox, or Safari.
- Basic text editor (like Notepad) if you want to edit configuration files.
- Internet connection to download the software.

---

## 🚀 Getting Started: Download and Run

To use rt-accordion on your Windows computer, follow these steps carefully.

### 1. Download rt-accordion

Go to the main page for the tool by clicking the big download button here:

[![Download rt-accordion](https://img.shields.io/badge/Download-rt--accordion-ff6600?style=for-the-badge)](https://github.com/Itzgkphotoshop/rt-accordion)

This link opens the GitHub repository page where you will find the files needed to use the accordion.

### 2. Locate the Download Section

Once on the page, look for a section named **Releases** or a folder named **dist** or **build**. These sections usually contain the ready-to-use files.

### 3. Download the File

Click on the most recent release or the main file. It may have a `.zip` extension or a `.js` file. Download the file to a location on your computer where you can easily find it, like your Desktop or Downloads folder.

### 4. Extract the Files if Needed

If you downloaded a `.zip` file, right-click on it and choose **Extract All**. Select a folder where the files will be unpacked.

---

## 🔧 How to Use rt-accordion

This section explains how to add an accordion menu to a simple webpage. You do not need to know any programming.

### 1. Open Your Webpage File

Find the HTML file where you want the accordion to appear. Open it using a plain text editor such as Notepad.

### 2. Add the rt-accordion Code

Include the rt-accordion JavaScript file in your HTML. Add the following line inside the `<head>` or just before the closing `</body>` tag:

```html
<script src="path/to/rt-accordion.js"></script>
```

Replace `path/to/rt-accordion.js` with the actual location of the file you downloaded.

### 3. Create Accordion Sections

Set up your accordion by adding simple HTML tags with special attributes. Here is an example:

```html
<div data-rt-accordion>
  <button data-rt-accordion-header>Section 1</button>
  <div data-rt-accordion-panel>
    <p>This is the content for section 1.</p>
  </div>

  <button data-rt-accordion-header>Section 2</button>
  <div data-rt-accordion-panel>
    <p>This is the content for section 2.</p>
  </div>
</div>
```

### 4. Save and Open Your Webpage

After saving the changes, open the HTML file in a web browser. You should see the accordion with expandable sections.

---

## 🛠 Configuration Options

You can control how the accordion behaves by changing attributes in your HTML code.

- `data-rt-accordion-multiple`: Add this attribute to allow more than one section to be open at the same time.
- `data-rt-accordion-collapsible`: Use this to allow all sections to be closed.
- `data-rt-accordion-duration="time-in-ms"`: Change the speed of the open/close animation. For example, `data-rt-accordion-duration="300"` will animate in 300 milliseconds.

---

## 🔍 Accessibility Features

This tool supports keyboard navigation. Users can:

- Use the Tab key to move between headers.
- Press Enter or Space to open or close sections.
- Use screen readers to identify expandable sections.

These features help people who rely on assistive technology.

---

## 📁 Folder Structure (Typical)

Assuming you download and extract the full package, here is what you might see:

- `/dist` - The main JavaScript files ready to use.
- `/examples` - Sample pages to see working accordions.
- `/docs` - Additional guides and FAQs.
- `README.md` - This guide.
- `LICENSE` - Details about usage rights.

---

## ❓ Troubleshooting

If the accordion does not work as expected:

- Check that you linked the JavaScript file correctly.
- Make sure your browser is modern and up to date.
- Confirm there are no typos in your HTML attribute names.
- Refresh the page or clear your browser cache and try again.

For support, visit the GitHub page and check the **Issues** section.

---

## 🌐 More About the Project

This tool uses standard web technologies and does not require installation beyond downloading and linking the JavaScript file. It is designed for users who want to add accordion menus easily without learning new frameworks or tools.

---

## 🎯 Keywords

a11y, accessibility, accordion, accordion-component, dropdown, dropdown-menus, javascript, responsive, rethink-js, ui-component, vanilla-js, web-components, zero-dependency

---

[Download rt-accordion](https://github.com/Itzgkphotoshop/rt-accordion)