# Andrew Purdy's CS 499 ePortfolio

## Professional Self-Assesment

Hello, my name is Andrew Purdy. I have been attending the SNHU Computer Science program for about two years, before which I attended my local community college to knock out basic courses and even received a certificate in programming. Throughout my educational journey, especially during my time in the Computer Science program, I have gained many skills and perspectives in software development. Of these skills, I feel collaborating in a team environment is one of, if not the most important aspects of moving into a professional software development role. Working as a team to develop software and applications allows for faster development times and greater coverage of business requirements. Learning how to use version control tools, such as GitHub or Bitbucket, has given me a deeper understanding of how team collaboration happens and insights into how to accomplish proper code reviews and the general flow for making changes and additions to a codebase in a team environment. 

Beyond learning about collaboration and teamwork tools, I gained a firm understanding of how to communicate with stakeholders of an application or project. This includes interviews with users of a system to gather business requirements, planning overall system architecture, assumptions, and design constraints. After gathering information, all of the information needs to be put into a software design document that is easy to read, understand, and present to the stakeholders. 

In the end, though, my greatest takeaway from the program was the technical skills I honed throughout my journey. I gained understanding of data structures and algorithms by implementing concepts like linked lists and sorting algorithms. While there are built-in tools and libraries for these in most languages, implementing them from scratch gave me a deep knowledge of how they work under the hood and allowing for proper implementation in my code. I also gained a good understanding of databases, both relational and non-relational, and how to determine when to use one versus the other. The program also offered great insights into security concerns when developing an application. We explored how to secure from common vulnerabilities and the importance of authentication and authorization. Combined, all of the experiences I have had in this program have shaped how I view software development as a whole. From using version control tools to thorough planning of a database, all aspects of a project require care and thought in both planning and implementation. 


## Code Review

The link below is a short video showing a code review of the artifact I chose to include for all three of my enhancements
https://youtu.be/yNnlJa9RPXw

## Enhancements

The artifact I have chosen to showcase all three of my enhancements is the Destination Slideshow created in CS 250: Software Development Lifecycle. This application was a simple Java slideshow that made use of HTML to display small slides in a desktop application. I saw the potential to make this slideshow into a modern, scalable, and secure web application that would demonstrate my skills in all three major enhancement categories: Software Design, Data Structures and Algorithms, and Databases. 

### Repository and Site Links

<a href="https://github.com/TyrotoxismBooth/CS499-Artifact-Enhancement"> See the full code of my enhancements here </a>

I am hosting a live version on the slideshow site <a href="https://snhu.purdy.world">here</a>. I have chosen not to host a live version of my admin SPA. 

### Software Design and Engineering
 
My plan for enhancement involves doing a full port of this application into a MEAN(MongoDB, Express, Angular, Node.js) stack application. This will showcase my knowledge of current and widely used technologies to implement a user friendly interface that is scalable, maintainable, and secure. Since this milestone is focused on Software Design, my enhancements so far include the creation of the structure I will use for my ported application. This aligns directly with course outcomes 1 and 4. In the case of outcome 1, “Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science”, creating a fullstack application helps build a collaborative environment where a team split into front and back-end developers can simultaneously work on a improve the app as it grows. The backend team can adjust data flow and add components while the front end team can work to polish the UI to appeal to larger audiences. This also improves organizational decision making by avoiding cascading decisions, ie. Making certain changes are less likely to affect other aspects or components of the app. As for outcome 4, “Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals (software engineering/design/database)”, the plan to port to a MEAN stack application uses a well founded technology stack that will help add value to the organization it is intended for by appealing to a larger audience, since it is web based. Porting the app also allows for a more scalable and maintainable solution which allows for future growth and lowering the cost of maintenance. I will also add outcome 5 as an outcome that is touched upon with this enhancement. While, right now, the app_admin section has not been implemented, this will be an Angular SPA(singe page application) with administrative functionality that requires authentication and authorization. 
During this enhancement, I had realized It has been a while since I had worked through the Fullstack Development course where I first learned how to use and implement the MEAN stack so I had to refresh on most of the process. In the end, I set up most of the design how I remembered it.

<img width=auto height=auto alt="image" src="https://github.com/user-attachments/assets/d40fc6ac-712a-40db-9f42-723c9c1a3851" />

### Data Structures and Algorithms

I have made decent progress into the overall enhancement, though I haven’t yet fully implemented my plans for data structures and algorithms at this time. This is due to the fact that I wanted to get the database structured and connected with the backend logic first. I have made some progress towards course outcome 3 by implementing the CRUD operations on the back end api which make use of the find(), findone(), insert(), and update() functions that use algorithmic concepts to make queries on the database and return the results via an API endpoint. I’ve also implemented a database schema for the destination objects to be stored in the database, which demonstrates abilities in the data structure category. Further plans include implementing an auto incrementing function for assigning the next available integer for the destinationId field, which will also showcase an understanding of algorithmic and logic principles. I have also debated implementing an in memory caching system, though I am not sure I plan on doing this as it will add time and complexity while not offering the performance increase at the small scale it is at now, but would rather be a feature that allows for smoother scaling down the road. 

### Database

I included this artifact in my database enhancement because I saw the opportunity to port the entire application into a web app using the modern and functional MEAN stack. There was very little separation of concerns in the original artifact and my overall enhancements not only make the app more marketable and accessible to the public, but also greatly increase the scalability. For this enhancement, the database was created, allowing the addition, or removal, of data, in this case resort destinations, to be performed outside of the core logic code itself. I have also added and plan to make use of a users table to put authentication into place to allow real time editing of the destination content with an Angular Single Pace Application (SPA). 
From within the SPA, admin users will have the ability to perform all CRUD operations on the database. This is made possible by making authenticated API calls to the back end framework and showcases my ability to both implement a database, but also allow users of the site to manipulate it from within the webapp itself. I believe this enhancement hits all of the course outcomes in one way or the other. By allowing CRUD operations from authenticated users allows for a more collaborative environment and does so in a secure manner. Furthermore, the implementation of the database and operations to manipulate the data show skills in both database structure and design as well as algorithmic principles and overall software design. Lastly, this write-up offers skills in written and oral communications. 
While the database has been fully designed and implemented, I faced the largest hurdles of this project to date during this week. When trying to right my handlebars templates for the server-side rendering aspect, I initially got all of the original slides to show on my page, but all as cards on a single page. In the spirit of making a slideshow, like the original app, I had to figure out a way to accomplish this. I decided that a Carousel component using Bootstrap seemed like a relatively simple implementation with some good documentation to follow. Implementing the slideshow, however, proved to be rather difficult with several hurdles to overcome, but in the end I made it work with my existing template. Beyond that, while I am using the “travlr” app we made in the Fullstack Development course as a template of sorts for my MEAN stack app, I am still trying to finish the SPA implementation. 

### Pictures of Completed Enhancements
Home Page (Slide One)
<img width=auto height=auto alt="image" src="https://github.com/user-attachments/assets/88c59c9f-cabd-4f68-a5de-1d98e851d800" />

Home Page (Slide Three)
<img width=auto height=auto alt="image" src="https://github.com/user-attachments/assets/ce908721-6ae6-4f79-acc1-31467bf0e644" />

Admin SPA (Pre Login)
<img width=auto height=auto alt="image" src="https://github.com/user-attachments/assets/6e716306-b34a-4ae5-a498-743ea2ffe2ab" />

Admin Login Page
<img width=auto height=auto alt="image" src="https://github.com/user-attachments/assets/e25fc36c-a961-4a10-9a09-7cde028cdf5c" />

Admin SPA (Post Login)
<img width=auto height=auto alt="image" src="https://github.com/user-attachments/assets/02fbb8f1-741c-49d3-98fd-1170e3c0b9eb" />

Add Destination Page
<img width=auto height=auto alt="image" src="https://github.com/user-attachments/assets/13c4b817-97f1-43b3-ba2b-44675476cf40" />

Edit Destination Page
<img width=auto height=auto alt="image" src="https://github.com/user-attachments/assets/d00c9384-438e-4aeb-9942-fcc115635071" />

Destinations Collection
<img width=auto height=auto alt="image" src="https://github.com/user-attachments/assets/31ac1a57-1bc3-4ac6-bc77-56d191bba0a5" />

User Collection (Notice passwords are salted and hashed)
<img width=auto height=auto alt="image" src="https://github.com/user-attachments/assets/a5825500-9b79-4991-bd63-af1aa3fbf24c" />
