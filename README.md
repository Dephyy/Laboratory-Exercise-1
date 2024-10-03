This project is a personal portfolio website designed to showcase various projects and skills as a developer. The website includes sections for projects, an about me page, and a contact form that connects to an API for submission. The site is built using HTML, CSS, and JavaScript, ensuring a responsive and visually appealing layout.


Design Choices
Layout and Responsiveness:
The website's layout was designed to be clean and minimalistic with a focus on clarity and user experience. The navigation bar is fixed at the top for easy access to different sections, and the overall design incorporates modern UI elements such as shadows, hover effects, and animations. Special attention was given to ensure that the website remains responsive across different screen sizes, from desktop to mobile.

Styling:
The Poppins font was selected for its modern and professional appearance, paired with a color scheme of white, black, violet, and orangered for a sleek yet vibrant look. Hover effects and button animations enhance the user experience, creating a sense of interactivity.

Interactivity:
A key feature of the project section includes a slideshow for project images, which dynamically showcases different screenshots or visuals of each project. This was implemented using basic JavaScript and CSS transitions. Additionally, a contact form is integrated with Web3Forms API to handle form submissions.



Challenges Faced
Navigation Bar Overlap:
One of the initial challenges was ensuring that the navbar remained fixed at the top while preventing other elements from sliding underneath it. This was resolved by using CSS properties such as position: fixed and adding appropriate padding to the page content.

Image Containment in Project Box:
Ensuring that project images fit well within the container, without stretching or distorting, was tricky. This was handled by using CSS's object-fit: cover property, which allowed the images to maintain their aspect ratio while filling the project box entirely.

Contact Form API Integration:
During form implementation, an error occurred regarding missing name attributes in the form fields. This was resolved by ensuring that every <input> element had a corresponding name attribute, which allowed successful form submissions via the Web3Forms API.

How These Challenges Were Resolved
Navbar Overlap: Applied padding and margin adjustments to sections beneath the navbar, so content wouldn't be hidden behind it.
Image Resizing: Leveraged object-fit: cover to maintain the integrity of images inside project boxes.
Form Errors: Fixed the contact form submission issue by adding required attributes such as name, allowing the form to be successfully submitted through the Web3Forms API.

Conclusion
This portfolio website serves as a professional representation of the developer's work, designed to be visually appealing and functionally robust. With features like interactive project showcases and a responsive design, it is a solid foundation for future projects and personal branding.