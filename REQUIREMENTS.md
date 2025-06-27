### **Requirement Document: Simple Portfolio Website**

**1. Overview**
The goal is to create a clean, professional, single-page personal portfolio website. This website will introduce you, showcase your projects, and provide a way for visitors to contact you.

**2. Key Features/Sections**
The website will consist of the following sections on a single scrolling page:
*   **Navigation Bar:** A sticky header with links that smoothly scroll to the corresponding sections (Home, About, Projects, Contact).
*   **Home/Hero Section:** A full-width section with a prominent headline (e.g., "Hello, I'm [Your Name]"), a brief tagline about what you do, and a call-to-action button (e.g., "View My Work").
*   **About Section:** A section with a photo and a short biography describing your skills and experience.
*   **Projects Section:** A grid-based layout to showcase 2-3 of your key projects. Each project will have an image, a title, a short description, and a link to view the project live or see the source code.
*   **Contact Section:** A simple form for visitors to send you a message. It will include fields for Name, Email, and Message.
*   **Footer:** A footer with links to your social/professional profiles (e.g., GitHub, LinkedIn) and a copyright notice.

**3. Proposed Technology**
*   **Backend:** Java (Spring Boot). We will use the existing `HelloController.java` to serve the main page.
*   **Frontend:**
    *   **HTML5 & Thymeleaf:** To create the structure and content, using the existing `src/main/resources/templates` directory.
    *   **CSS3 & Bootstrap 5:** To ensure a modern, responsive design that works on all devices. We will add a CSS file to `src/main/resources/static`.

**4. Implementation Plan**
1.  Modify `pom.xml` to include the `spring-boot-starter-thymeleaf` dependency.
2.  Create `index.html` in `src/main/resources/templates/`.
3.  Add HTML structure for all the sections described above.
4.  Create `style.css` in `src/main/resources/static/css/` for custom styling.
5.  Update `HelloController.java` to map the root URL ("/") to the `index.html` template.
