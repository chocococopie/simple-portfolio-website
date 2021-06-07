# README_NOTES

## Project 6: Simple Portfolio Website

### 🧩 Focus
- **Layout**: Build a consistent structure across all pages using components like `Header`, `Footer`, and layout wrappers. Use CSS or frameworks like Flexbox/Grid for responsive design.
- **Reusable Components**: Break down UI into smaller parts (e.g., `ProjectCard`, `ContactForm`) and reuse them across pages to keep the code clean and DRY (Don't Repeat Yourself).

### 📄 Features
- **About Page**: Short personal bio, skills, or mission statement.
- **Projects Page**: List of your projects with title, description, and links. Use reusable `ProjectCard` components.
- **Contact Page**: Basic contact form or email link so people can reach out.

### 🔧 Key Concepts
- **Layout**: Create a consistent page skeleton with header, main content area, and footer.
- **Component Composition**: Build UIs by nesting smaller components. Example:  
  ```jsx
  <Layout>
    <AboutPage />
  </Layout>
