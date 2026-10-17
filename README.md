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
* **Goal:** Quickly screen student candidates for part-time, weekend, or internship developer positions.
* **Needs & Expectations:**
  * **Immediate Visual Impact:** Wants to identify the candidate's name, field of study, and contact details within 3 seconds.
  * **Scannability:** Needs to assess technical skill sets (languages, frameworks) at a glance without reading long blocks of text.
  * **Practical Information:** Seeks clear details regarding work availability, location, and language proficiencies.
  * **Seamless Contact:** Expects interactive links to call, email, or view the candidate's location directly from desktop or mobile devices.

---

## 🏗️ Information Architecture

The information architecture of this single-page CV website is organized into a clean, two-column asymmetrical layout designed to optimize reading flow and prioritize key information for recruiters. The layout split follows a **40% (left) / 60% (right)** proportion across three major horizontal rows, anchored by a prominent header topbar at the top of the page.

1. **Header Section (`.topbar`):** Placed at the very top, this section serves as the initial visual focal point. It contains a high-resolution circular profile photo overlapping the left side and a bold header on the right displaying the candidate’s full name (*Harrison Vance*) and current status (*Computer Science student*).

2. **First Row (`.content1`):**
   * **Left Column (40%):** Contains direct, interactive contact information (phone number, email address, and physical location) paired with clean icon indicators.
   * **Right Column (60%):** Houses the "About Me" summary, giving a personal and professional introduction that outlines career goals, personal traits, and specific weekend job search objectives.

3. **Second Row (`.content2`):**
   * **Left Column (40%):** Divided vertically into two key blocks: "More Information" (highlighting exact weekend work availability hours) and "Languages" (showing language proficiency levels paired with national flag icons for fast recognition).
   * **Right Column (60%):** Dedicated to "Work Experience", presenting past roles, dates, and bulleted lists of technical responsibilities.

4. **Third Row (`.content3`):**
   * **Left Column (40%):** Displays "Technical Skills" formatted as styled badge tags (JavaScript, Python, SQL, HTML5 & CSS3, Node.js) for instantaneous scanning.
   * **Right Column (60%):** Contains "Academic Information", detailing university degree progress, specialization, and professional certifications.

This deliberate separation ensures that quick reference data remains structured on the left while detailed narratives and work history flow naturally down the right side.

---

## 🎨 Visual Design Decisions

The visual design strategy focuses on creating a distinctive, modern, and tech-oriented appearance while maintaining a high level of legibility and professional rigor.

* **Color Palette & Split Background:** The website utilizes an asymmetrical dual-tone background created via CSS linear gradients (`linear-gradient(to right, #8190c7 40%, #dedede 40%)`). The left 40% uses a calm slate blue (`#8190c7`), providing contrast for icons and badges, while the right 60% uses a soft neutral gray (`#dedede`) to ensure high contrast and optimal readability for body text. Dark navy blue (`#293063`) is applied to header banners and section titles, accented by high-contrast black borders (`border: 3px solid black`) to create a clear, structured container feel.

* **Typography & Hierarchy:** The Google Font **'Roboto'** was selected for its clean, modern sans-serif aesthetic, which fits well with a technology profile. Text hierarchy is established through strong contrast in font weight and size:
  * Name Title: 52px bold, uppercase, with 1px letter spacing.
  * Section Headers (`<h2>`): 20px bold uppercase text inside rounded dark blue pill banners.
  * Body Text: 15px with line-height 1.6 for comfortable reading.

* **UI Elements & Shape Language:** A consistent border-radius language is used throughout the interface. Section titles use 40px rounded corners, tech skill tags feature 20px pill shapes with vibrant purple-blue fills (`#5362CF`), and icons/profile images are styled with full 100% circular masks. The profile picture features an overlapping absolute positioning effect over the topbar banner, adding depth and visual interest.

* **Responsive Adaptation:** A media query (`@media (max-width: 850px)`) ensures full responsiveness. On mobile screens, the split background converts to a single solid neutral background, and all two-column structures collapse into a single stacked column layout with centered elements for ideal touch interaction.

---

## 🛠️ Technologies Used & Justification

* **HTML5:** Used for semantic structuring (`<meta>`, `<hr>`, `<a>`, `<ul>`, `<img>`). Interactive schemas (`mailto:`, `tel:`, and Google Maps links with `target="_blank"`) were implemented to enhance user experience.
* **CSS3 (Vanilla):** Custom CSS was chosen instead of heavy external frameworks (like Bootstrap) to maintain full control over the two-column gradient layout, flexbox alignment, rounded pill styling, and custom media query breakpoints.
* **Google Fonts:** Integrated 'Roboto' via external font linking.

---

## 📁 Repository File Structure

```text
.
├── index.html        # Main HTML structure with semantic tags and links
├── CV.css            # Custom CSS stylesheet (organized by section)
├── README.md         # Documentation file
└── assets / images   # Image resources (Harrison.jpeg, Phone.png, Email.png, GPS.png, flags)
```
