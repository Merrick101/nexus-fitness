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

Nexus Fitness also aims to foster a supportive community for individuals at all stages of their fitness journey, from beginners to advanced athletes.
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
**ARIA Labels**
- ARIA labels were applied to buttons and links to improve screen reader compatibility.

## AI Tools Usage

### Midjourney
Midjourney was instrumental in creating high-quality visuals for Nexus Fitness, specifically images that represent the gym's facilities and classes in action. These visuals were designed to evoke a sense of motivation and inclusivity, aligning with the brand's goal to create an inviting and inspiring fitness environment.

**Images Created**
- Yoga Class Visuals: Generated calming and serene images featuring individuals practicing yoga in well-lit studio settings, reinforcing the class's focus on mindfulness and flexibility.
- Weightlifting Class Visuals: Depicted strength and determination by showcasing individuals performing lifts in professional gym environments.
- Boxing Class Visuals: Highlighted energy and intensity through dynamic action shots of boxing training sessions.

**Challenges and Iterations**
- The biggest challenge was crafting prompts that accurately reflected the intended mood and class environment without introducing elements that might confuse users (e.g., overly abstract or unrealistic visuals). After several iterations:

    - Adjusted prompts to include terms like "minimalistic," "modern gym," and "bright lighting" to ensure the images matched the site's clean and professional aesthetic.
    - Tested images for user feedback to confirm they complemented the site's content rather than overwhelming it.

**Impact on the Project**
These visuals enhanced user engagement by providing a professional and cohesive aesthetic that resonates with the target audience. The high-quality images helped establish Nexus Fitness as a credible and appealing fitness brand.

## Features Implementation

### Core Features (Must-Haves)
**Feature 1: Navigation Menu**
- Description: A fixed navigation bar available on all pages, providing quick access to key sections: Home, Classes, Contact, and Sign Up.
- Purpose: To ensure ease of navigation and enhance user experience, particularly for new visitors unfamiliar with the site layout.
- User Benefit: Allows users to locate information quickly, contributing to a seamless browsing experience.
- Development Note: The menu was designed to remain fixed at the top of the viewport, ensuring accessibility on longer pages. Responsive styling was applied to ensure usability on smaller screens.

**Feature 2: Class Information Page**
- Description: Dedicated pages for each fitness class (yoga, weightlifting, boxing) featuring detailed descriptions, benefits, and illustrative images.
- Purpose: To provide users with clear and compelling information to help them choose the best class for their fitness goals.
- User Benefit: Users can make informed decisions about class participation based on detailed descriptions and visuals.
- Development Note: Images were selected using Midjourney to align with the site’s modern aesthetic while maintaining clarity and accessibility.

**Feature 3: Contact Form**
- Description: A contact form on the "Contact" page, allowing users to submit inquiries. Submissions are directed to a centralized FormDump platform provided by the course educators.
- Purpose: To enable users to easily send inquiries or feedback.
- User Benefit: Simplifies communication with the gym, providing users with immediate confirmation of their submission.
- Development Note: The form uses the action attribute to direct users to the FormDump platform upon submission.
- Challenges: Initial alignment issues with the form fields were resolved during the responsive design testing phase.

### Advanced Features (Should-Haves)
**Feature 1: Testimonial Section**
- Description: A testimonial section on the homepage, featuring rotating feedback from gym members to build trust and credibility.
- Purpose: To showcase user satisfaction and encourage new users to engage with the gym.
- User Benefit: Adds a personal touch by sharing real user experiences, which can inspire confidence in potential members.
- Development Note: A simple testimonial carousel could be implemented using JavaScript for smooth transitions.

**Feature 2: Dynamic Class Schedule**
- Description: A dynamic schedule displaying available classes for each day, with time slots automatically updated to reflect the current week.
- Purpose: Allows users to quickly view up-to-date class times and availability without navigating away.
- User Benefit: Users can plan their attendance easily, improving their experience and encouraging consistent participation.
- Implementation Note: This feature could use JavaScript to dynamically update the schedule based on the current day of the week.

### Optional Features (Could-Haves)
**Feature 1: Blog Section**
- Description: A planned section for future enhancements, featuring articles on fitness, wellness tips, and healthy lifestyle guidance.
- Purpose: To provide users with additional resources and encourage repeat visits to the website.
- User Benefit: Users can access expert advice and tips to complement their fitness journey.
- Development Note: Considered for future versions, with a content management system (CMS) integration for seamless updates.

**Feature 2: Online Class Booking**
- Description: A proposed feature for users to directly book classes through the website, integrating with an external booking platform.
- Purpose: To enhance convenience for users and streamline the booking process.
- Development Note: Future iterations would explore API integrations with popular booking systems.

## AI Tools Usage

### GitHub Copilot
GitHub Copilot assisted in streamlining code by suggesting HTML and CSS structures for common elements, such as the navigation bar and form structure. Copilot provided helpful initial code suggestions, though adjustments were sometimes needed to align with accessibility standards.

## Testing and Validation
Testing was conducted across various devices (desktop, tablet, mobile) and browsers (Chrome, Firefox, Safari). The layout remained consistent across screen sizes, confirming that responsive design was implemented effectively.

### Testing Results
**Issues Found and Resolved:**
**Home Page**

![Home Page Initial Test 01](/assets/images/testing/index-before-01.PNG)

![Home Page Initial Test 02](/assets/images/testing/index-before-02.PNG)

![Home Page Initial Test 03](/assets/images/testing/index-before-03.PNG)

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

![Classes Page Initial Test 01](/assets/images/testing/classes-before-01.PNG)

![Classes Page Initial Test 02](/assets/images/testing/classes-before-02.PNG)

- Error: The button element must not appear as a descendant of the anchor element
- Cause: A button element was incorrectly nested within an anchor element, violating HTML specifications.
- Resolution: The button was replaced with a styled anchor element to maintain functionality while adhering to HTML standards.

**Contact Page**

![Contact Page Initial Test](/assets/images/testing/contact-before.PNG)

- Warning: Section lacks heading (contact-details)
- Cause: The contact-details section did not have a heading, reducing semantic clarity.
- Resolution: A descriptive h2 heading was added to the contact-details section to improve accessibility and structure.

**Sign-Up Page**

![Sign-Up Page Initial Test 01](/assets/images/testing/signup-before-01.PNG)

![Sign-Up Page Initial Test 02](/assets/images/testing/signup-before-02.PNG)

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
AI tools played a significant role in streamlining various stages of the development process, particularly in deployment, debugging, and design. Each tool contributed unique benefits and posed some challenges, as detailed below:

**GitHub Copilot**
- Role: GitHub Copilot was instrumental in suggesting optimized code snippets during deployment preparation. For example, it provided solutions for creating responsive layouts and managing file paths for deployment on GitHub Pages.
- Benefits: It saved significant time by reducing the need to manually write boilerplate code and offering accurate predictions for repetitive tasks, such as ensuring file paths were consistent across the project.
- Challenges: Occasionally, Copilot suggested solutions that were not compatible with GitHub Pages deployment, requiring additional validation to ensure proper functionality. This highlighted the need to cross-check AI-generated code with project requirements.

**ChatGPT Code Co-Pilot**
- Role: ChatGPT Code Co-Pilot assisted with debugging, code reviews, and resolving errors that occurred during deployment. It helped explain error messages and suggest fixes, particularly for issues like stray HTML tags and CSS validation errors.
- Benefits: The ability to receive instant, detailed explanations of errors and implementation suggestions allowed for faster problem resolution. ChatGPT also provided tailored insights into improving website accessibility and responsiveness.
- Challenges: While ChatGPT provided comprehensive answers, some suggestions needed to be adjusted to align with project-specific requirements. For example, a proposed solution for centering form elements required additional customization to ensure it fit the overall design.

**Midjourney**
- Role: Midjourney was used to generate high-quality visuals for the site, including representations of gym facilities and fitness classes. These images helped create an engaging and professional aesthetic.
- Benefits: The ability to quickly generate custom visuals reduced dependency on stock images and allowed for unique branding. The flexibility in generating tailored images improved the visual appeal of the website.
- Challenges: Using the correct prompts to produce appropriate and cohesive images was initially challenging. Some generated images required refinement to align with the site's color scheme and overall tone.

**Overall Impact**
AI tools enhanced the development process by improving efficiency and reducing manual effort. They enabled faster identification and resolution of issues, streamlined the deployment process, and elevated the site's visual design. While minor adjustments and validations were needed, the tools collectively contributed to delivering a polished and user-friendly project.

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
This project provided valuable experience in developing an accessible, responsive website, from design to deployment. Working with tools like GitHub Copilot for coding assistance and Midjourney for visuals added efficiency and creativity to the development process.

## Code Attribution
**CSS Flexbox & CSS Grid Guides:** 
- Flexbox layout patterns referenced from CSS-Tricks.

**Responsive Design:**
- Basic responsive design concepts referenced from W3Schools.

## Future Improvements
**Blog Section** 
- A dedicated blog section with regularly updated articles on fitness, nutrition, and wellness tips to engage users and support SEO efforts.
- Additional Features for the Blog Section:
    - Categories and Tags: Allow users to browse articles by categories (e.g., "Strength Training," "Yoga Tips," "Nutrition Advice") or search for topics using tags.
    - User Comments: Enable users to comment on articles to foster a sense of community and engagement.
    - Author Profiles: Include profiles of the contributors or fitness experts writing the articles to add credibility and personalization.
    - Social Media Integration: Add share buttons for articles so users can easily share content on platforms like Facebook, Instagram, or Twitter, increasing the site's reach.
    - Personalized Recommendations: Implement a feature that recommends classes or blog articles based on user preferences, such as previously booked classes or frequently viewed articles.

**Membership Portal**
- Develop a members-only section where users can:
    - Access exclusive content like advanced workout plans or videos.
    - Manage their membership, including upgrading or canceling plans directly through the website.

**Advanced Class Booking**
- Add an integrated booking calendar for users to select available dates and times for specific classes.
- Include a notification system that sends email or SMS reminders for upcoming bookings.

**Progress Tracking**
- Create a feature where users can log workouts and track their fitness progress over time. This could include:
    - A visual dashboard displaying progress charts.
    - Achievements or milestones to encourage users to reach fitness goals.

**Multilingual Support**
- Introduce language options to cater to a broader audience, ensuring accessibility for non-English speakers.