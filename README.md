# SciAIMed-P1
[Visit my webpage here](https://elisabethoelmann.github.io/SciAIMed-P1/index.html#home)

The  Website is intended for setting up my own medical consultancy business for small biotech companies and larger pharmaceutical companies. The main tasks of such a consultancy business is drug development, focused primarily on Oncology drug development from target identification until registration trials and final approval by health authorities. The intention is to include my coding expertise into this website in much more detail latest, when I have finished my CodeInstitute Course in Diploma in Full Stack Software Development (Common Curriculum). Currently this website mainly focuses on my medical education and the resulting services, I can offer at this moment in time.

This website is made up of the following sections:

1.	Home/Welcome/Introduction section with the header, logo and the navbar on the top

![](docs/images/homepage_introduction.png)

2.	Services

![](docs/images/services.png)

3.      Expertise 

![](docs/images/expertise.png)

4.      Footer, which also contains a link to my LinkedIn profile

![](docs/images/footer.png)

5.      A contact form, which people can fill in to send me an email. This contact form also contains my email address and mobile phone number, which at this moment in time is an invented number, as a business number does not yet exist.

![](docs/images/contactform.png)

The business goals for this website are:

1.	To give a precise overview of the services offered
2.	Background with my expertise to show the stages of my CV, education and previous work experience.
        This can only be finalized for programming, after I have finished my CI course

The user goals for this website are:

1. For first time users (mainly people in the Biotech- and Pharmaceutical Industry), who are looking for help with their projects and therefore search for medical consultancy companies, I want to give an easy understandable overview of the services I am offering, as well as my expertise to show, that I am able to conduct these services.

2. The services section is a summary of activities, which are required across the industry to sucessfully accomplish different parts   of drug develpment projects.

Data analysis is also mentioned here, as it is one of the key pillars for sucessful drug development in Medicine. AI has been incorporated already into the title, as it is a hot topic right now in Medicine and my intention is to be educated enough to further define specific tasks, when I have finished my CI course. A big lack for Medics is a thorough understanding of AI and data analysis and the requirements and methods behind, which is one of the reasons, for me why I have signed up to the full stack software developer course.

3. The Expertise section shows my complete education until now (except the full stack developer diploma), which serves as basis for my services, that I intend to offer.

4. The contact form is a simple from page for contacting me via email, mobile phone and LinkedIn.

## UX
---
### **Strategy**

Considering the core UX principles I first started to think about the strategy for this website and defined who the target users would be and what features/technologies they would want.

The SciAiMed target users are:

* People > 18 years old
* Biotech and Pharmaceutical Industry  and Clinical Research employees and employers
* People interested in medical data anlysis

What these users would be looking for:

* Clear, concise, easy-to-find information about services
* Clear and concise easy to read expertise section, on which the services are based

This website will offer these options, also allowing for intuitive navigation and comfortability of use. An effort was taken to not provide an overwhelming amount of information at first glance which would look less professional.
Due to ease of use, it is assumed that users will be also be viewing the site on their mobile phones and therefore creating a responsive design was important.

### **Scope**
In order to achieve the desired user & business goals, the following features are included in this release:

* Header and menu bar, to navigate to various sections of the page or to scroll down
* Introduction section to outline the overall goal of the page
* Services offered
* Expertise/education section
* Contact form with options to send an email, contact me via mbile and a link to my LinkedIn profile

### **Structure**

The webpage is built with a single main page for introduction, services and expertise as main contents, to allow to scroll through, but it has also a navigation bar in the header, to be able also to jump to each section. 

Additionally the website has a separate contact form, to allow easy contact via email, mobile and or LinkedIn, which is separated from the main page/ contents. 

After the introduction, I have chosen to start with the Services section, due to the fact, that it would be of key interest for users. 

Thereafter follows a summary of my education and expertise, which is important for users to see, because it is the basis, on which I am offering my services.

I chose the following order for the information 'Home/introduction> Services> Expertise, as I felt this would allow the information to be digested in the best way. Finally the contact form is separate, because it only serves the purpose of contacting me, which is separate from the rest of the main page/contents

### **Surfaces**

The colours and pictures:
I have chosen a mixture of different light blue and black background colours to give an elegant, orderly and easily readable impression with high contrast options.
Scientific/Clinical pictures are mostly light blue, due to the nature of DNA/RNA samples, serving well for the introduction, making clear, that this is a scientific/medical company. This continues in the blue colour scheme for the services offered in pale blue (rgb(150, 193, 242))
The black background of the header, expertise section sets a nice contrast to the blue colours in the introduction and services sections. 
I used Google fonts 'EB Garamond', serif;' due to its simple and elegant design
![](docs/images/google_fonts_selection_eb_garamont.png)

### **Features**
This is a fully responsive website that was designed to be also approriately displayed on mobile phones, although clients likely would mostly use large screens for a search of a Clinical Consultancy company and use mobile phones only during travel times.
The page is divided into the four sections listed in the navbar. 
The font used for the whole page is EB Garamont. No more fonts have been chosen,  due to the fact, that this is a scientific consultancy page, where users do not expect fancy design features, which would distract from the contents.
If the background colour is black, the text is chosen to be either white for the header and footer or white smoke for the expertise section. The colour of the subtitles of the Expertise section are chosen to be blue-green (#04948aed) to set a contrast to the rest of the text sections.

### **Title and Logo**
The title is designed with my company name: SciAiMed Ltd. and the celtic salomon’s knot, which is one of the most ancient symbols for the connection between humans and the divine and in recent times in science is used to symbolise atoms, where electrons are orbiting around the nucleus. It appeared therefore to me to be a nice choice. [wikipedia information about Salomon's knot](https://en.wikipedia.org/wiki/Solomon%27s_knot)

### **Navbar**
The navbar was created with help from W3 schools: [W3Schoollink to create the navbar](https://www.w3schools.com/howto/howto_css_navbar_icon.asp)
However, for a more elegant design, I decided to delete the icons (fontawsome), but used the code.

### **The introduction section**
This section outlines the general purpose of the consultancy company with a title (h1 element) describing the general purpose. The welcome section with the subtitle (h2 element), stating the company name, heads up the more detailed description of the company’s purpose.
The background image shows a typical scientific background with a DNA structure and sample tubes, which are normally used for clinical investigations and scientific experiments.

### **Services**
This section starts with an H2 heading and is then followed by an unordered list of tasks, which the company offers. The style of the unordered list has been created with flex box and the help of Dev community:
![3 ways how to display two divs side by side - Dev community](docs/images/flexboxmethod_parralel_lists_dev_to.png)

For these 2 parallel unordered lists, a media query has been added to stack them on top of each other, for screens smaller than 600 px.

### **Expertise**
This section includes the most information on the page, which I have ordered in general into 2 parralel blocks, which contain 3 sections with 3 titles: the left-block contains a 1 p-element with a summary of my expertise with an h2 title "Expertise" and 1 table which summarizes my education with the title "Education". The right block contains a larger table containing my roles over the years with a h2 title "Roles".
Both tables summarize my education and previous roles in chronological order, the education table in ascending order and the roles table in descending order according to importance.
The tables have been created with help from W3school: [HTML tables](docs/images/table_html.png)

### **Contact form**
The contact form will allow the user to get into contact with me. 
The form is created as a section without a title, as the page is selfexplaining. Within the section, 3 div elements are used, one for my email, one for my mobile phone number and one for the container of the input form, where the user can enter and submit his email, including  a text message. The input form was created with help from W3schools: [How to create a contact Form with CSS W3Schools](docs/images/contactform_w3school.png)

### **Technologies used**

I have used several technologies that have enabled this design to work:

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
    - Used as the basic building block for the project and to structure the content.
- [CSS](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/CSS_basics)
    - Used to style all the web content across the project.
- [Google Fonts](https://fonts.google.com/)
    - Used to obtain the fonts linked in the header, fonts used were Playfair and Cookie
- [Font Awesome](https://fontawesome.com/)
    - Used to obtain the social media icons used in the footer and the icons in La Petite Review.
- [Google Developer Tools](https://developers.google.com/web/tools/chrome-devtools)
    - Used as a primary method of fixing spacing issues, finding bugs, and testing responsiveness across the project.
- [GitHub](https://github.com/)
    - Used to store code for the project after being pushed.
- [Git](https://git-scm.com/)
    - Used for version control by utilising the Gitpod terminal to commit to Git and Push to GitHub.
- [Gitpod](https://www.gitpod.io/)
    - Used as the development environment.
- [Favicon.io](https://favicon.io/)
    - Used to create favicon's for my website
- [W3C Markup Validation Service](https://validator.w3.org/) 
    - Used to validate all HTML code written and used in this webpage.
- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/#validate_by_input)
    - Used to validate all CSS code written and used in this webpage.

### **HTML and CSS Validation**

I validated my index.html, contact.html and style.css while working on them. Finally they were free of mistakes. however, the contact form validation shows an error, which I decided to neglect: it says, that a section needs to have a title, but the contact form looks fine as it is and a title would not look right on this form.

![](docs/images/wcmarkup_validation_indexhtml.png)
![](docs/images/wcmarkup_validation_css.png)
![](docs/images/wcmarkup_validation_contacthtml.png)

## Deployment

I deployed this website by using GitPages and following the below steps:

*GitHub pages deployment* 

1. Log in to GitHub
2. In my Repository section, select the project, SciAiMed-P1, that I wanted wanted to deploy
3. In the menu located at the top of this section, click 'Settings'
4. Select 'Pages' on the left-hand menu - this is around halfway down
5. In the source section, select branch 'main' and save
6. The page is then given a site URL:

![](https://elisabethoelmann.github.io/SciAIMed-P1/)

## Credits

I have used a number of resources to produce this website, where codes have been used from another source:

The following websites/articles were used:

- [the celtic knot icon](https://www.iconarchive.com/show/celtic-knot-icons-by-shiftercat/blueknot-2-icon.html?utm_content=cmp-true)

-[color picker](https://www.w3schools.com/colors/colors_picker.asp)

-[responsive navbar](https://www.w3schools.com/howto/howto_css_navbar_icon.asp)

-[3 ways to display 2 divs side by side-Dev community](https://dev.to/dawnind/3-ways-to-display-two-divs-side-by-side-3d8b#:~:text=The%20most%20common%20way%20to,using%20inline%2Dblock%20css%20property.&text=The%20inline%2Dblock%20property%20on,like%20an%20inline%20element%20does.)

-[W3School tables](https://www.w3schools.com/html/html_tables.asp)

-[How to create a contact form](https://www.w3schools.com/howto/howto_css_contact_form.asp)

-[gitpod tips and tricks](https://github.com/gitpod-io/gitpod-docs/blob/master/src/52_Tips_and_Tricks.md#format-document)

## Acknowledgements

I like to thank the CodeInstitute tutors for frequently being available for questions and help with IDEs and especially my mentor Harry Dhillon for all advise during the finalization of my project.
