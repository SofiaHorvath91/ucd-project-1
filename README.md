# Dalí's Surreal Dreams (UCD Project 1)
Tribute to Salvador Dalí's Surreal Dreams

The aim of this site is to present the great artist Salvador Dalí and his works in a simple and interactive way. Users can discover his life and his artworks, learn about surrealism, and they can also access other relevant and interesting materials about Dalí and his art. If you wish to dive into the surreal world, this may be a good place to start and get know the main principles through the great artworks and extraordinary life of Salvador Dalí!

![responsive-design](https://user-images.githubusercontent.com/83947734/132755719-33b0a1df-3216-4b4f-b59c-f311b5ccee44.PNG)

Deployed site (Github Pages) : https://sofiahorvath91.github.io/ucd-project-1/.

## UX
### 1. User stories
* Expectations as a user :
  * be able to navigate through the site easily through any device.
  * be able to learn about the life of Dalí.
  * be able to understand the principles and see examples of Dalí’s art.
  * be able to understand the basics of surrealism.
  * be able to navigate to other relevant sites for more information.
  * be able to leave my feedback and/or ask my questions regarding the site/content.
* Expectations as a site owner :
  * the site to be tastefully and creatively designed (regarding the subject).
  * the site to be clearly structured for easy navigation.
  * information to be clear and interesting.
  * the visual content to be rich and relevant.
  * the users to get attracted to Dalí’s art and surreal artistic style
### 2. Strategy
* Purpose of Project
  * To promote the art of Dalí;
  * To educate people about the surreal art.
  * To get people dive further in this topic by directing them to additional resources.
  * To encourage people to develop their imagination by presenting them the surreal way of seeing the world.
### 3. Scope
* I wanted a simple, evident and user-friendly UX experience.
* I wanted clear and informative content.
* Regarding the subject, I wanted a visually appealing and creative design.
* Information about:
  * the exceptional life of Salvador Dalí;
  * the different artistic works of Dalí;
  * the surreal art and way of thinking;
  * where to find further resources in the given subject;
* Ways to provide feedback to site owner for constant UX development.
### 4. Structure
* The layout is simple and clear to ensure the easy navigation through site content by users
* The navbar is clear, visible and responsive with matching site logo and dropdown clearly indicated to facilitate navigation through pages. 
* The content is easy to read and the sections are clearly distinguished on each page, with section titles highlighted.
* The Index page displays clearly the site’s main subject (Art & Life of Salvador Dalí) and allows to navigate to main pages of site.
* The Biography page presents the life of Dalí, using collapsible sections for avoiding too crowded content and for facilitating navigation.
* The Art Gallery is consisted of three pages through a dropdown menu (Gallery, Museums and Other Works), allowing the discover Dalí’s artworks via different aspects.
* The Surrealism page presents basic information about the surrealist art in general, and also allows users to discover other famous surrealist painters.
* The Feedback page allows users to leave feedback, questions and rating about the site, enabling site owner to further improve the site’s UX
* In the Footer, users can find the sources and copyrights of different contents used to create the site, all completed with hyperlinks toward the original source, as well as icon buttons to share site on different social media platforms.
### 5. Skeleton
The very basic skeleton of the site was modelled by Wireframes via Balsamiq, and during site development, additional design elements was added for better UX.
* [Index Page Wireframe](https://github.com/SofiaHorvath91/ucd-project-1/blob/main/img/readme/balsamiq-Index.png)
* [Biography Page Wireframe](https://github.com/SofiaHorvath91/ucd-project-1/blob/main/img/readme/balsamiq-Biography.png)
* [Gallery Page Wireframe](https://github.com/SofiaHorvath91/ucd-project-1/blob/main/img/readme/balsamiq-Gallery.png)
* [Museums Page Wireframe](https://github.com/SofiaHorvath91/ucd-project-1/blob/main/img/readme/balsamiq-Museums.png)
* [Other Works Page Wireframe](https://github.com/SofiaHorvath91/ucd-project-1/blob/main/img/readme/balsamiq-OtherWorks.png)
* [Surrealism Page Wireframe](https://github.com/SofiaHorvath91/ucd-project-1/blob/main/img/readme/balsamiq-Surrealism.png)
* [Feedback Page Wireframe](https://github.com/SofiaHorvath91/ucd-project-1/blob/main/img/readme/balsamiq-Feedback.png)
### 6. Style
* Design & Colours
  * When planning the project, knowing that a rich visual material (photos and paintings) will be used as illustration, I wanted a simple, almost minimalist design and colour theme for the background and UI elements.
Therefore I chose a basic black and white design with simple blue (#0000ff) and red (#ff0000) highlights. I prepared the background wallpapers with Photoshop, using free png/svg images.
* Font Selection
  * The main font type was chosen with [Google Fonts](https://fonts.google.com/) and is used across the whole of the website: [Averia Serif Libre](https://fonts.google.com/specimen/Averia+Serif+Libre). This is a well readable yet a bit dream-like font type which suits well to the theme of the site.
## Features
### 1. Existing Features
* Navigation Bar
  * Featured on all pages, the navigation bar includes links to all subpages and is identical on each page for smooth navigation. The navbar is fully responsive on all screen sizes: for smaller devices, a hamburger navbar view is included with the help of Bootstrap for better UX and easier navigation.

Navbar on Desktop
![Navbar desktop](/img/readme/features-navbar.PNG)
Navbar on Mobile
![Navbar mobile](/img/readme/features-navbar-small.PNG)

* Index page
  * Attention-catching site title and visually backed up links to the main site pages (Biography, Art Gallery, and Surrealism) for easier navigation

![Index Page](/img/readme/features-index.PNG)

* Biography page
  * For simple design and easy user navigation, the biography of Dalí is divided into four collapsible sections, summarizing the different chronological periods of his life, with a slideshow gallery of his paintings made in the given period included in each section as visual backup. The sections are titled after a famous painting made during the highlighted period, and these section titles are highlighted upon hovering and opening.
An audio file can be also played by users to provide further insight into Dalí’s life : a part of a radio interview made with him in 1958 by Mike Wallace, where he talks about genius, personality, the subconscious and dreams. Users can also navigate to the full interview if are interested in it.

![Biography Page](/img/readme/features-biography.PNG)
![Biography Section](/img/readme/features-biography2.PNG)

* Art Gallery pages
  * The Art Gallery part of the site is consisted of three pages, which can be reached through a drop menu item and which present different sub-categories of Dalí’s artistic heritage. The dropdown option is indicated in the navbar, and the dropdown items are styled to be readable and visible in all cases.

* Art Gallery pages : Gallery page
  * This page features an image gallery of 45 selected works of Dalí. Upon hovering, the users can see the name and creation date of each painting. The gallery is fully responsive on all devices, varying the number of columns to show based on screen size. 
Users can also watch a video which features 933 of Dalí’s works with musical background on the page or on Youtube, and may also follow a link to Wikiart where they discover all of Dalí’s works.

* Art Gallery pages : Museums page
  * This page presents the all the museums world-wide which hold a permanent Dalí collection in a styled table. For each museum, an image, a description, a link toward the museum’s site, and the museum’s location included with link to Google Maps. The table design is fully responsive, adapting to the screen size of any device.
Users can also watch a video of the Dalí Museum (Floride, USA) on the page or on Youtube, and may also follow a link to the Dalí Museum’s Yotube channel to find more similar videos.

* Art Gallery pages : Other Works page
  * This page features The Andalusian Dog, the only short film directed by Dalí (together with director Luis Buñuel) and the two biography books written by Dalí himself.
Users can watch the full short film on the page or on Youtube, and also redirect to Amazon to buy the books online and discover other related literature.

* Surrealism page
  * This page allows users to learn more about the surreal art in general and about other famous surrealist painters (Ernst, Magritte, and Picasso) with visual illustrations of their works to awake interest. If interested, users can navigate to their full Wikiart page to discover their life and art.
As a page main illustration, a dynamically rotating, styled image is used which presents well the essence of surrealism I think.

* Feedback
  * This page consists of a responsive form with two fieldsets, allowing users to leave their details (name, email, phone, the level of their knowledge about Dalí), and a rating with comment regarding the site’s quality, content or just to have a question. Only some fields are required for submission, all marked with an asterix, for not discouraging users from leaving a feedback, and if they change their mind, they can clear all fields. 

* Footer
  * The footer section includes sources and copyrights for all content used to create the page with external hyperlinks to the sites. This encourages users to dive deeper into the subject through other websites and to get know other great resources and artists.
The footer section allows to share this website with other people through social media sites and email via social share buttons. 
### 2. Future Features
* Modal boxes for allowing see gallery images in bigger version
* Another dropdown item in art gallery for sculptures
## Code validation
