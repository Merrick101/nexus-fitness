# Nexus Fitness

![Nexus Fitness Multi-View](/assets/images/testing/home-multi-viewport.PNG)

Here's a link to the live version of my [project.](https://merrick101.github.io/nexus-fitness/index.html)

## Overview

### Purpose
The purpose of Nexus Fitness is to offer a user-friendly, informative, and accessible platform for individuals interested in improving their physical well-being. This website aims to promote different fitness classes (yoga, weightlifting, boxing), along with an overview of the gym facilities. The site helps users make informed decisions about the classes that best fit their fitness goals.

### Target Audience
The target audience for Nexus Fitness includes:

- Fitness Enthusiasts: Individuals seeking structured fitness classes in yoga, weightlifting, and boxing.
- Beginners: Those looking to explore gym facilities and understand available options in a welcoming and accessible format.
- Health-Conscious Individuals: People interested in integrating regular exercise into their lifestyle. 

## User Stories

### Must-Have User Stories
**User Story 1:**
- As a user, I want an intuitive navigation menu so I can easily find the information I need.
- Acceptance Criteria: A navigation bar is present on all pages, allowing users to access sections like "Home," "Classes," and "Contact" with ease.

**User Story 2:**
- As a user, I want clear information on available fitness classes so I can choose the best options for my fitness goals.
- Acceptance Criteria: Each class (e.g., yoga, weightlifting, boxing) has a dedicated page with descriptions and images.

### Should-Have User Stories
**User Story 1:**
- As a user, I want to receive confirmation after submitting a contact form to know my submission was successful.
- Acceptance Criteria: The contact form is set to submit via FormDump, which redirects users to a thank-you page upon submission.

**User Story 2:**
- As a user, I would like testimonials to see other users' experiences with the gym.
- Acceptance Criteria: A testimonial section featuring user feedback is present on the homepage.

### Could-Have User Stories
**User Story 1:** 
- As a user, I would like a blog section with fitness tips to support my fitness journey.
- Acceptance Criteria: A blog section includes regularly updated articles about fitness and wellness topics.

**User Story 2:**
- As a user, I would like the ability to book classes directly through the website.
- Acceptance Criteria: Each class page includes a "Book Now" button that connects to an external booking system or in-site form.

## Design Decisions

### Wireframes
Wireframes were created for key pages (e.g., homepage, classes page, contact page) to ensure a user-centered design approach. The homepage showcases an engaging layout, with a prominent navigation bar and easy access to class options.

**Home Page**
- Home Page: Large Devices Wireframe

![Home Page Large Devices](/assets/images/wireframes/home-page-large-screens.png)

- Home Page: Small Devices Wireframe

![Home Page Small Devices](/assets/images/wireframes/home-page-small-screens.png)

**Classes Page**
- Classes Page: Large Devices Wireframe

![Classes Page Large Devices](/assets/images/wireframes/classes-page-large-screens.png)

- Classes Page: Small Devices Wireframe

![Classes Page Small Devices](/assets/images/wireframes/classes-page-small-screens.png)

**Contact Page**
- Contact Page: Large Devices Wireframe

![Contact Page Large Devices](/assets/images/wireframes/contact-page-large-screens.png)

- Contact Page: Small Devices Wireframe

![Contact Page Small Devices](/assets/images/wireframes/contact-page-small-screens.png)

**Sign Up Page**
- Sign Up Page: Large Devices Wireframe

![Sign Up Page Large Devices](/assets/images/wireframes/sign-up-large-screens.png)

- Sign Up Page: Small Devices Wireframe

![Sign Up Page Small Devices](/assets/images/wireframes/sign-up-page-small-screens.png)

**Design Choices:**

- Layout: A clean, minimal layout is used to avoid overwhelming users and maintain focus on content.
- Color Scheme: High-contrast color schemes are used to enhance readability and accessibility.
- Fonts: A modern, sans-serif font was selected for readability and visual appeal.

### Accessibility Considerations
Accessibility guidelines were followed to ensure that Nexus Fitness is usable for a wide audience, including those with disabilities.

**Color Contrast:**
- Text and background colors meet WCAG guidelines for contrast.
**Alt Text:**
- All images contain descriptive alt text to assist visually impaired users.
**Semantic Markup:**
- HTML5 tags like header, nav, main, and footer provide structural meaning, aiding screen readers.

## AI Tools Usage

### Midjourney
Midjourney was used to create images for the project, including images displaying gym facilities, and classes in action, with the intention of promoting a positive environment aimed at group oriented and individual fitness needs. The biggest challenge was using correct prompts to create high quality images that would not distract the user.

## Features Implementation

### Core Features (Must-Haves)
**Feature 1:**
- Navigation Menu: A fixed navigation bar that is accessible on all pages, allowing users to easily access the main sections: "Home," "Classes," and "Contact."
**Feature 2:**
-Class Information Pages: Dedicated pages for each class (yoga, weightlifting, boxing) provide a description, benefits, and an image of the class environment.
**Feature 3:**
- Contact Form: A contact form on the "Contact" page allows users to submit inquiries, connected to FormDump for confirmation.

### Advanced Features (Should-Haves)
**Feature 1:**
- Testimonial Section: A carousel or fixed section on the homepage displaying user testimonials to build credibility and encourage engagement.
**Feature 2:**
- Thank-You Page for Form Submissions: After submitting the contact form, users are redirected to a thank-you page via FormDump, giving clear confirmation that their submission was received.

### Optional Features (Could-Haves)
**Feature 1:**
- Blog Section: A future enhancement planned to provide users with articles on fitness, wellness tips, and healthy lifestyle information.
**Feature 2:**

## AI Tools Usage

### GitHub Copilot
GitHub Copilot assisted in streamlining code by suggesting HTML and CSS structures for common elements, such as the navigation bar and form structure. Copilot provided helpful initial code suggestions, though adjustments were sometimes needed to align with accessibility standards.

## Testing and Validation
Testing was conducted across various devices (desktop, tablet, mobile) and browsers (Chrome, Firefox, Safari). The layout remained consistent across screen sizes, confirming that responsive design was implemented effectively.

### Testing Results
**Issues Found and Resolved:**
**Home Page**
- Error: Unclosed anchor element
- Cause: An anchor element was left unclosed, leading to rendering issues.
- Resolution: The missing closing anchor tag was added to properly close the anchor element.

- Error: Stray end tag button
- Cause: A stray button end tag was incorrectly placed.
- Resolution: The misplaced button was removed, and the structure was corrected.

- Error: End tag td seen, but there were open elements
- Cause: The td element had an unclosed child or sibling element.
- Resolution: All open elements within the td were properly closed.

**Classes Page**
- Error: The button element must not appear as a descendant of the anchor element
- Cause: A button element was incorrectly nested within an anchor element, violating HTML specifications.
- Resolution: The button was replaced with a styled anchor element to maintain functionality while adhering to HTML standards.

**Contact Page**
- Warning: Section lacks heading (contact-details)
- Cause: The contact-details section did not have a heading, reducing semantic clarity.
- Resolution: A descriptive h2 heading was added to the contact-details section to improve accessibility and structure.

**Sign-Up Page**
- Error: First child option of a select element must have an empty value
- Cause: The default option in the select element lacked an empty value attribute, which is required for accessibility and validation.
- Resolution: A placeholder option label was added with an empty value attribute, ensuring compatibility and proper behavior.

**CSS**
- Issue: Minor alignment issues in the navigation bar on smaller screens.
- Solution: Adjusted CSS flex properties to ensure elements aligned properly.

### Validation
- HTML: All HTML code passed the W3C Validator with no issues.

![Home Page Validation](/assets/images/testing/index-page-test.PNG)

![Classes Page Validation](/assets/images/testing/classes-page-test.PNG)

![Contact Page Validation](/assets/images/testing/contact-page-test.PNG)

![Sign Up Page Validation](/assets/images/testing/signup-page-test.PNG)

- CSS: CSS code was validated through Jigsaw with no errors.

![CSS Validation](/assets/images/testing/css-test.PNG)

## AI Tools Usage

### GitHub Copilot
Copilot was beneficial in identifying syntax issues and suggesting minor corrections, helping to speed up the validation and debugging process.

## Deployment

### Deployment Process
The site was deployed on GitHub Pages. Deployment steps included:

- Committing the final version to GitHub.
- Enabling GitHub Pages and selecting the main branch as the source.
- Testing the deployed site to ensure functionality matched the development environment.
- Challenges: Initial deployment issues with images not appearing on the website were resolved by double-checking the image file paths.

## AI Tools Usage

### Reflection
Describe the role AI tools played in the deployment process, including any benefits or challenges.  
**Guidance:** Reflect on how AI tools assisted with the deployment process, particularly how they streamlined any tasks or presented challenges.

## Reflection on Development Process

### Successes
**Responsiveness:**
- Achieved a consistent layout across devices.
**User Experience:**
- Positive feedback from initial testers on the site’s simplicity and ease of navigation.

### Challenges
**Commit Management:**
- Ensuring commit messages were detailed enough to reflect specific changes was challenging initially but improved over time.

### Final Thoughts
This project provided valuable experience in developing an accessible, responsive website, from design to deployment. Working with tools like GitHub Copilot for coding assistance and DALL-E for visuals added efficiency and creativity to the development process.

## Code Attribution
**CSS Flexbox & CSS Grid Guides:** 
- Flexbox layout patterns referenced from CSS-Tricks.

**Responsive Design:**
- Basic responsive design concepts referenced from W3Schools.

## Future Improvements
**Blog Section:** 
- A blog with articles on fitness and wellness tips to engage users and support SEO efforts.
