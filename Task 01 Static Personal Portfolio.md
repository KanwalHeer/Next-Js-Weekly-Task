
### Task: Build and Deploy a Personal Portfolio Website

**Objective:** Develop a simple personal portfolio website using Next.js with TypeScript and Tailwind CSS. Deploy the completed website to Vercel. The website should include a home page, an about page, and a contact page with a responsive navigation bar.

---

### **Task Details:**

1. **Project Setup:**
   - Initialize a new Next.js project with TypeScript.
   - Install and configure Tailwind CSS for styling.

2. **Navigation Bar:**
   - Create a `Navbar` component that includes links to "Home", "About", and "Contact" pages.
   - Ensure the navigation bar is responsive and adjusts correctly on different screen sizes (e.g., mobile, tablet, desktop).
   - Use Tailwind CSS classes for styling and responsiveness.

3. **Home Page (`pages/index.tsx`):**
   - Design a welcoming home page with a brief introduction about yourself.
   - Use Tailwind CSS for styling, ensuring a clean and attractive layout.

4. **About Page (`pages/about.tsx`):**
   - Create a detailed about page providing more information about your background, skills, and experience.
   - Apply consistent styling with Tailwind CSS to maintain the site’s visual coherence.

5. **Contact Page (`pages/contact.tsx`):**
   - Develop a contact page with your contact information, such as email or social media links.
   - Optionally, include a simple contact form for visitors to reach out to you.
   - Style the contact page using Tailwind CSS for a polished appearance.

6. **Responsive Design:**
   - Ensure that all pages and the navigation bar are fully responsive. The layout should adapt seamlessly to various screen sizes.
   - Use Tailwind's responsive design utilities, such as `md:`, `lg:`, and `xl:` prefixes.

7. **Deployment:**
   - Deploy your completed website to Vercel. Vercel provides a free and easy way to host your Next.js applications.
   - Follow the instructions on [Vercel's documentation](https://vercel.com/docs) for deployment.

---

### **Hints for Implementation:**

1. **Setting Up Tailwind CSS:**
   - Follow the [Tailwind CSS setup guide for Next.js](https://tailwindcss.com/docs/guides/nextjs).
   - Update the `tailwind.config.js` file to include paths to your content files for proper utility class generation.

2. **Creating the Responsive Navigation Bar:**
   - Use Tailwind classes such as `flex`, `justify-between`, `items-center`, `md:hidden`, and `block` to create a responsive navigation bar.
   - Consider using a hamburger menu for smaller screens. You can use [Headless UI](https://headlessui.dev/) or [React Icons](https://react-icons.github.io/react-icons/) for the menu icon.

3. **Home Page:**
   - Apply classes like `text-3xl`, `font-bold`, `p-4`, and `text-center` to style the content attractively.
   - Consider using Tailwind’s `container` class for centered alignment and responsive padding.

4. **About Page:**
   - Structure the page with headings (`text-2xl`, `font-semibold`), paragraphs, and lists.
   - Ensure the content is well-organized with adequate spacing and alignment.

5. **Contact Page:**
   - Use Tailwind classes for form elements (`border`, `p-2`, `rounded`, `mb-4`) if you choose to include a contact form.
   - Style contact information with Tailwind classes for clear presentation.

6. **Deploying to Vercel:**
   - Connect your GitHub repository to Vercel for continuous deployment.
   - Follow Vercel's [deployment guide](https://vercel.com/docs/concepts/git/deployments) to link your project and deploy it.

---

### **Submission Guidelines:**

1. **Code Repository:**
   - Push your code to a GitHub repository.
   - Ensure your repository includes the complete project with the `pages`, `components`, and `public` directories.

2. **Live Website:**
   - Provide a link to your live website hosted on Vercel.
   - Verify that all pages are functional and that the navigation links work correctly.

3. **Responsive Testing:**
   - Test the website on different devices and screen sizes to ensure responsiveness.
   - Make adjustments as needed to maintain usability across devices.

4. **Code Quality:**
   - Ensure clean and well-organized code.
   - Utilize TypeScript for type safety and clarity.

---

**Detailed Instructions for Vercel Deployment:**

1. **Push to GitHub:**
   - Ensure your Next.js project is pushed to a GitHub repository. If you haven't already, create a new repository on GitHub and push your project.

2. **Connect to Vercel:**
   - Go to [Vercel’s website](https://vercel.com/) and sign up or log in.
   - Click on “New Project” and import your GitHub repository.
   - Vercel will automatically detect that you’re using Next.js and configure the deployment settings.

3. **Deploy:**
   - After connecting your repository, click “Deploy” to start the deployment process.
   - Vercel will build and deploy your site. You’ll get a live URL once the deployment is complete.

4. **Preview and Adjust:**
   - Visit the URL provided by Vercel to preview your site.
   - Make any necessary adjustments and push changes to GitHub. Vercel will automatically redeploy your changes.

---
