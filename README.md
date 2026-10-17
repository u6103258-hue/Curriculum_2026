# Curriculum Vitae Website - Harrison Vance

A modern, responsive, single-page CV website designed and developed for the **Hypermedia** course assignment. This website showcases my background, technical skills, language proficiencies, and work availability as a Computer Science student.

---

## 🔗 Project Links

* **Live Website:** [Curriculum 2027 Website](https://u6103258-hue.github.io/Curriculum_2027/)

* **Figma Design File:** [Curriculum 2027 Figma proyect](https://www.figma.com/design/lEVNehjW2TPk5OqSVS2zhG/Curriculum_2027?node-id=0-1&t=PAQYIOZaJDoebO59-1)

---

## 👤 User Profile (User Persona)

To build an effective personal website, the target end-user was defined prior to design and development.

### **User Persona: Sarah Jenkins (Tech Recruiter / Hiring Manager)**
* **Role:** Senior IT Recruiter at a Tech Consultancy / Software Studio.
* **Goal:** Quickly student candidates for part-time, weekend, or internship developer positions.
* **Needs & Expectations:**
  * **Immediate Visual Impact:** Wants to identify the candidate's name, field of study, and contact details.
  * **Scannability:** Needs to assess technical skill sets (languages, frameworks).
  * **Practical Information:** Seeks clear details regarding work availability, location, and language proficiencies.
  * **Contact:** Expects the contact information about the candidate (phone number, email and location).

---

## 🏗️ Information Architecture

The information architecture of this CV website is organized into a clean, two-column asymmetrical layout designed to optimize reading flow and prioritize key information for recruiters. The layout split follows a **40% (left) / 60% (right)** proportion across three horizontal rows, supported by a prominent header topbar at the top of the page.

1. **Header Section (`.topbar`):** Placed at the top part of the website, this section serves as the initial visual focal point. It contains a circular profile photo overhanging the left side and a bold header on the right displaying the candidate’s full name (*Harrison Vance*) and current status (*Computer Science student*).

2. **First Row (`.content1`):**
   * **Left Column:** Contains direct, interactive contact information (phone number, email address, and location) paired with icon indicators.
   * **Right Column:** Contains the "About Me" summary, giving a personal and professional introduction about career goals, personal traits, and specific weekend job search objectives.

3. **Second Row (`.content2`):**
   * **Left Column:** Divided vertically into two blocks: "More Information" (highlighting weekend work availability hours) and "Languages" (showing language proficiency levels paired with national flag icons for fast recognition).
   * **Right Column:** Dedicated to "Work Experience", presenting past roles, dates, and lists of technical responsibilities.

4. **Third Row (`.content3`):**
   * **Left Column:** Displays "Technical Skills" formatted as styled badge tags (JavaScript, Python, SQL, HTML5 & CSS3, Node.js) for instantaneous scanning.
   * **Right Column:** Contains "Academic Information", detailing university degree progress, specialization, and professional certifications.

This separation ensures that quick reference data remains structured on the left while detailed narratives and work history flow naturally down the right side.

---

## 🎨 Visual Design Decisions

The visual design strategy focuses on creating a distinctive and modern appearance while maintaining a high level of legibility and professional style.

* **Color Palette & Split Background:** The website utilizes an asymmetrical dual-tone background created by CSS linear gradients (`linear-gradient(to right, #8190c7 40%, #dedede 40%)`). The left 40% uses light blue color (`#8190c7`), providing contrast for icons and badges, while the right 60% uses white color (`#dedede`) to ensure high contrast and optimal readability for body text. Dark navy blue (`#293063`) is applied to header banners and section titles, accented by high-contrast black borders (`border: 3px solid black`) to create a clear, structured container.

* **Typography & Hierarchy:** The Google Font **'Roboto'** was selected for its modern sans-serif style, which fits well with a technology profile. Text hierarchy is established through strong contrast in font weight and size:
  * Name Title: 52px bold, uppercase, with 1px letter spacing.
  * Section Headers (`<h2>`): 20px bold uppercase text inside rounded dark blue banners.
  * Body Text: 15px with line-height 1.6 for comfortable reading.

* **Responsive Adaptation:** A media query (`@media (max-width: 850px)`) ensures full responsiveness. On mobile screens, the split background converts to a single solid neutral background, and all two-column structures collapse into a single stacked column layout with centered elements for ideal touch interaction.

---

## 🛠️ Technologies Used & Justification

* **HTML5:** Used for semantic structuring (`<meta>`, `<hr>`, `<a>`, `<ul>`, `<img>`). Interactive schemas (`mailto:`, `tel:`, and Google Maps links with `target="_blank"`) were implemented to give a better user experience.
* **CSS3:** Custom CSS was chosen to maintain full control over the two-column gradient layout, flexbox alignment, rounded styling, and custom media query breakpoints.

---

## 📁 Repository File Structure

```text
.
├── index.html        # Main HTML structure with semantic tags and links
├── CV.css            # Custom CSS stylesheet (organized by section)
├── README.md         # Documentation file
└── assets / images   # Image resources (Harrison.jpeg, Phone.png, Email.png, GPS.png, flags)
```
