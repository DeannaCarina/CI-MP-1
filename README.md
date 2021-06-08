** Things to do before submission **
1. Run code through validators.
2. Clean up code.
3. Finish README.md

# Travel Caribbean

Milestone One Project: HTML/CSS Essentials - Code Institute - Deadline 1st July 2021

This is my submission for Code Institute's Milestone One Project. It is a fictitious company with coresponding website which provides the service of planning customers' holidays in The Caribbean. The website is created with **ONLY** HTML5 and CSS3. The website covers the most basic function of the company: "The new way to plan your Caribbean getaway", the steps a customer can take to get started on their holiday ideas, reviews from customers, a gallery page and a page to sign up to the company's brochure which is published every month, as well as two pages to help the customer make the decision of where they would like to go (Islands) and what type of holiday they would like to partake in (Types). There are also contact links at the bottom of all pages with personal links to my own Instagram acount as many static images have come from my own photography portfolio (from index.html, gallery.html and contact.html, as well as the background images of the brochure downloadable).

# Contents

<ul>
    <li>
        <a href="#demo"><strong>Demo</strong></a>
    </li>
    <li>
        <a href="#UX"><strong>UX</strong></a>
        <ul>
            <li>
                <a href="#Strategy">Strategy</a>
            </li>
            <li>
                <a href="#Scope">Scope</a>
            </li>  
            <li>
                <a href="#Structure">Structure</a>
            </li>    
            <li>
                <a href="#Skeleton">Skeleton</a>
            </li>        
            <li>
                <a href="#Surface">Surface</a>
            </li>
        </ul>                
    </li>
    <li>
        <a href="#Technologies"><strong>Technologies</strong></a>
    </li>
    <li>
        <a href="#Features"><strong>Features</strong></a>
    </li>
    <li>
        <a href="#Testing"><strong>Testing</strong></a>   
    </li>
    <li>
        <a href="#Deployment"><strong>Deployment</strong></a>
    </li>
    <li>
       <a href="#Credits"><strong>Credits</strong></a> 
    </li>
    <li>
        <a href="#Screenshots"><strong>Screenshots</strong></a>
    </li>
    <li>
        <a href="#References"><strong>References</strong></a>
    </li>
</ul>

<hr>


# Demo
A live demo of the website can be found <a href="https://deannacarina.github.io/CI-MP-1/index.html" target="_blank">**HERE**</a>

<img src="assets/images-readme/gif-index.gif" alt="Demo of Travel Caribbean Landing Page" width="100%">
<a href="#Contents">Back to the top.</a>

# UX
As more people rely on accessing services online the role of UX design has become increasingly important in our digitized world. The five planes provide a conceptual framework for breaking down the task of designing experiences into component elements so that we can understand the problem as a whole [1]. As this framework is structured, regularly used and consistently reliable, I have chosen to use the Five Planes method to design and implement my own website.
## Strategy
### Vision
<em>Travel Caribbean</em> is a specialist travel website focusing on travel to the Caribbean. Planning a holiday to the Caribbean can be daunting and confusing for many people due to the massive amount of choice that the Caribbean provides [2][3]. As a frequent traveller to the Caribbean, I felt there was a gap in the market to provide potential travellers to the Caribbean with a straightforward and easy means of learning about the 
potential locations to travel to, and the different types of holiday they can go on, as well as the different activites and excursions customers can go on once they are in
the Caribbean to experience the best the Caribbean has to offer. Much like an online travel-agent, I hope the website can provide confidence to customers to take the 
leap and book their holiday to the Caribbean as there are so many amazing things to see and do, as well as incredible cultures to experience. From personal experience however, I have found that many online travel agent websites are confusing to navigate and have an overabundance of information, it is my aim to make my own website easily navigatable and provide customers with a structured and logical delivery of information. By doing this, it will encourage customers to stay on the site and want to use the company's services rather than navigate away from the page due to information overload.

### Aims
<ol>
    <li>To earn commision from partner companies that are advertised via the website</li>
    <li>To earn income from customers by charging a fee to plan and organise their Caribbean Holiday (fee included in overall holiday price)</li>
    <li>To build a database of customers that have used the services of the website for future holidays</li>
    <li>To be easily findable via search engines</li>
    <li>To be shareable between current customers and potential customers for potential future revenue</li>
    <li>To help customers decide on where they would like to go on their Caribbean Holiday</li>
    <li>To help customers decide on what type of holiday they would like for their Caribbean getaway</li>
    <li>To help customers decide what they would like to do on their Caribbean Holiday for excursions and activities</li>
    <li>To visually help customers by providing a gallery page of images taken in the Caribbean</li>
    <li>To provide customers with an easy to use and intuitive contact form to be able to request extra information</li>
    <li>To make the site intuative and easily usable to enable customers learn about the Caribbean</li>
    <li>To provide customers with a downloadable brochure to advertise examples of package holidays they can have in the Caribbean</li>
</ol>

### Target Audience
There are a number of target audiences for this website due to the range and number of different locations and holiday types on offer.<br>
The theory of potential target audiences are as follows:
<ul>
    <li><strong>Age 18-30</strong> - This is the group of potential customers that are most likely to want to experience 'rustic' travel [4] </li>
    <li><strong>Age 30-60</strong> - This is the group of potential customers that are more likly to want family holidays</li>
    <li><strong>Age 60+</strong> - This is the group of potential customers that are likely to want holidays away during their retirement, paticularly cruises. This demographic also has a likelihood of having a large proportion of solo travellers [5]</li>
    <li><strong>Naturists</strong> - as clothing optional holidays are very niche, it is important for this group of individuals to have a place to go to cater to their more specialist wants and needs</li>
    <li><strong>Adventurous People</strong> - This is the group of people more likely to use the services of the website to plan and book excursions in the Caribbean</li>
    <li><strong>Newly engaged couples</strong> - This is the group of people more likely to want to organise group holidays for hen and stag parties</li>
    <li><strong>Newly married couples</strong> - This is the group of people more likely to want to use the services of the website to plan a honeymoon</li>
    <li><strong>British People</strong> - Britains account for nearly 40% of foreign tourist arrivals in Barbados [6], I would like to utilise this and target the website towards British travellers as there is a huge market for Caribbean travel from the United Kingdom and Ireland, especially due to the direct flights from international airports such as Manchester and Heathrow.</li>
</ul>

### User stories
#### Customer
<strong>As a new <em>AND</em> returning customer I want to...</strong>
<ol>
    <li>Know the purpose of the website as soon as I navigate to the home/landing page</li>
    <li>Navigate the website quickly and effectively</li>
    <li>Find everything in the website that I need to find with ease<br>
    <img src="assets/images-readme/image-home.png" alt="Screenshot of top of landing page" width="100%"></li>
    <li>Learn about the different locations that are available to me as a holiday destination in the Caribbean<br>
    <img src="assets/images-readme/image-islands.png" alt="Screenshot of top of islands page" width="100%"></li>
    <li>Learn about the different holiday types that are available to me<br>
    <img src="assets/images-readme/image-types.png" alt="Screenshot of top of types page" width="100%"></li>
    <li>Have a visual aid to help the decision making process of what I would like to do on my holiday to the Caribbean</li>
    <li>Have a visual aid to help the decision making process of where I would like to go on my holiday to the Caribbean</li>
    <li>Know what other customers have said about the company to ensure the company is genuine and good at what they do<br>
    <img src="assets/images-readme/image-reviews.png" alt="Screenshot of top of reviews section" width="100%"></li>
    <li>Have some examples of what the company can offer to me for my holiday in the Caribbean via a brochure</li>
    <li>Have updated deals and offers from the company for potential Caribbean holidays<br>
    <img src="assets/images-readme/image-brochure.jpeg" alt="Screenshot of top of downloadable brochure" width="100%"></li>
    <li>Have a quick and easy way to contact the company/for the company to contact me<br>
    <img src="assets/images-readme/image-contact.png" alt="Screenshot of top of contact page" width="100%"></li>
    <li>Have updated information about locations in the Caribbean that may or may not be suitable for travel at that time</li>
    <li>Have links to social media platforms related to the company to view further customer testomonies</li>
    <li>Have links to social media platforms related to the company to view further images of potential locations and excusrions<br>
    <img src="assets/images-readme/image-links.jpeg" alt="Screenshot of top of reviews section" width="100%"></li>
    <li>Be assured that the locations and excursions advertised by the website are rated and reviewed by customers not affiliated to the company</li>
    <li>Browse the website and get information from the company without an obligation to book a holiday</li>
    <li>Have easy navigation to external sources to further knowledge of different locations to aid in decision making</li>
</ol>

#### Business Operator
<strong>As the business operator I want to...</strong>
<ol>
    <li>Create and maintain a database of clients and customers that have organised travel to the Caribbean via the website</li>
    <li>Create and maintain a database of clients and customers that have expressed interest in travel to the Caribbean via the website</li>
    <li>Create and maintain a database of external companies that do (and would like to) work in partnership with <em>Travel Caribbean</em></li>
    <li>Ensure the website is easily maintainable by software developers by having intutitive and neat code</li>
    <li>Have any media content displayed in the website accessible at all times via a linked file system</li>
    <li>Ensure all navigation links (internal or external) are always fully functional for ease of use</li>
    <li>Ensure the website is fully accessible to users that may have visual imparement</li>
    <li>Ensure the website is intuitive for all age groups and abilities</li>
    <li>Gain comission from external companies advertised via the website and in partnership with the company</li>
    <li>Gain income from customers via a fee placed within the total price of the booked holiday to the Caribbean</li>
    <li>Create a visually stimulating environment for customers to see what is available to them during a Caribbean holiday and increase the 
    liklihood of booking and future potential revenue</li>
    <li>Stand out from other forms of online travel agent to reduce the chance of customers booking Caribbean holidays via competitors</li>
    <li>To provide customers with links to associated social media sites</li>
</ol>

#### Partnership Company
<strong>As a company in partnership with <em>Travel Caribbean</em> I want to...</strong>
<ol>
    <li>Ensure that <em>Travel Caribbean</em> is a company with good reputation that I can affiliate my own company with</li>
    <li>Ensure that any comission paid to <em>Travel Caribbean</em> will result in a guarenteed flow of customers to my own company for guaranteed future revenue</li>
    <li>Have a fast and easy way to contact <em>Travel Caribbean</em> to discuss partnership terms and comission fees</li>
    <li>To have little competition with other external companies affiliated with <em>Travel Caribbean</em> that offer similar products to my own commpany</li>
    <li>Have any advertising via <em>Travel Caribbean</em> to be positive and promotional</li>
    <li>Have a fast and easy way for customers to be able to navigate to my own company's website via <em>Travel Caribbean</em></li>
</ol>
<a href="#Contents">Back to the top.</a>

## Scope
Due to the pitfalls of developing a website based on the MVP (Minimum Viable Product) model such as lack of user experience and enjoyment due to a lack of content, I have chosen instead to base the development of my product using the MMP (Minimum Marketable Product) as this allows a fully functional application to be used by the customer and can solve user problems with the minimum amount of features while still being completely usable [7] - this however does mean that more time must be spent developing and deploying the application without the guarantee of user satisfaction and possibly result in some 'rough edges' that need to be rectified and de-bugged at a later date. By using this method, any feedback from customers will be based on a fully working web-app and result in fully qualitative data due to the product being in a finished state; rather than feedback based on a web-app that has intentionally been left incomplete resulting in feedback from customers who may believe the site to be inadaquate due to lack of content and intuitiveness.
I have been able to confidently use the MMP model due to my own history of travel to the Caribbean and booking holidays in this area of the world. As a customer myself, I can base the functions needed for the website on my own needs and wants from the past, as well as for the future. By incorporating into the website features that I would want to see on websites that I book my own holidays on, I hope that my wants and needs will translate to the wants and needs of the customers visiting the <em>Travel Caribbean</em> website.
The MMP model will:
<ul>
    <li>Create a clear website with enough content for the customers wants and needs to be fulfilled</li>
    <li>Allow me to work within the scope of my abilitiy while also allowing me to challenge myself in areas that I may need to adapt for the needs of the business and website</li>
    <li>Result in a website with high levels of UX</li>
    <li>Show the consumer the level of knowledge the company has in this area of tourism by having adequate amount of content as well as customer testomonials</li>
    <li>Meet the needs of the business and user</li>
</ul>
While following the MMP model, to meet the user and business goals, my website will include:
<ul>
    <li>A self-designed logo on all pages as assurance to the customer we are a trusted-business with our own identity</li>
    <li>A nav-bar on all pages to be able to navigate to separate pages on the website</li>
    <li>Links to associalted social media on all pages within the footer</li>
    <li>A large amount of visual content as booking holidays is a very visual experience - would you book a holiday without seeing where you're going?</li>
    <li>Information for customers of different locations for their holidays and the different types of holidays they can go on including excursions and experiences</li>
    <li>Customer testimonials from previous clients</li>
    <li>Downloadable brochure from website for customers to see what's on offer</li>
    <li>A large gallery (including videos) to allow customers to visualise their potential holiday destinations</li>
    <li>Contact forms to allow customers to contact the company and book holidays</li>
</ul>
<a href="#Contents">Back to the top.</a>

## Structure
This website consists of multiple pages. By having multiple page we can separate large amounts of information into logical sections to make it easier for the user to find what they are looking for. The navigation bar at the top of all of the pages allows the user to easily navigate to the page of the website they are most interested in. There are also certain pages (islands.html and types.html) that have their own internal navigation sections due to these pages being split into logical sections for different islands and different types; these internal page navigation areas mean that the user can be even more specific about what they would like and find it easily.<br><br>
<strong>On index.html</strong>: I chose for the 'hero video' to be at the top, the next section to be text to capture the user and to further explain the function of the website, the next section to explain the steps the customer should take in choosing their holiday - this section is very straightforward and minimal to allow for intuitive browsing, the next section to be holiday types - just the types, no extra information, then the review section and finally a link to the contact form and brochure. This is the layout that I found to be most logical; as the user moves down the page they are slowly given the information they need in order to organise a holiday to the Caribbean with the company - this avoids information overload and increases the chance of the customer staying on the website. Some of the sections in index.html also have links within them to be able to navigate to other pages on the site to allow for intuitive browsing - whenever this is available to the user, the destination of the link always has a back button just in case the user wants to go back to where they were before e.g. the user clicks on the 'Beach' type button on in the index page which will take them to the Beach section of types.html, however they may want to go back to the index page to the area they were at previously - the back button provided will take them there. I wanted these sections on the home page to be the most important to the user as they have key information within them.<br><br>
<strong>On islands.html</strong>: I chose to have an iframe at the top from Google Maps, to allow the customer the opportunity to do some exploring of the area themselves should they wish. Under the iframe there is an internal nav area, each link representing a different island or island group. These are mainly organised geographically from the islands at the top of the caribbean moving round in a clockwise fashion ending with the ABC islands. Organising by geographical location made most sense to me, and would make it easier to find particular islands on the iframe map. Within each of the sections I have included a back-to-top button, as the page has a lot of information, I didn't want the user to be constantly scrolling up and down the page to see what other island options there are by viewing the nav-bar.<br><br>
<strong>On types.html</strong>: I chose to have the same types section from the home page as the internal nav bar, this provides continuity and familiarity for the user. Underneath the nav bar there are nine sections, each representing a type of holiday the customer could have. These don't have a particular order, however I have tried to arrange them as possible popularity - these can easily be moved around and re-ordered as necessary in the future. Within each of the sections I have included a back-to-top button, as the page has a lot of information, I didn't want the user to be constantly scrolling up and down the page to see what other types of holiday there are by viewing the nav-bar.<br><br>
<strong>On gallery.html</strong>: I have included a large number of images, as from personal experience I like to look at images of places before I choose them as a potential holiday destination. Under the images, I have also incuded videos via YouTube iframe, these videos are made and published via external sources and are to further help the customer decide where they would like to go on holiday and what they would like to do.<br><br>
<strong>On contact.html</strong>: There are two main sections - one for the downloadable brochure and the other for the contact form. The image of the brochure contains a button to be able to download the brochure pdf file. <br><br>
<a href="#Contents">Back to the top.</a>

## Skeleton
<img src="assets/images-readme/wire-index.png" alt="Wireframe plan of index.html" width="90%"><br>
<ul>
    <li>Click <a href="assets/images-readme/wire-islands.png" target="_blank">HERE</a> for islands.html Wireframe</li>
    <li>Click <a href="assets/images-readme/wire-types.png" target="_blank">HERE</a> for types.html Wireframe</li>
    <li>Click <a href="assets/images-readme/wire-gallery.png" target="_blank">HERE</a> for gallery.html Wireframe</li>
    <li>Click <a href="assets/images-readme/wire-contact.png" target="_blank">HERE</a> for contact.html Wireframe</li>
    <li>Click <a href="assets/images-readme/wire-thanks.png" target="_blank">HERE</a> for thanks.html Wireframe</li>
    <li>Click <a href="assets/images-readme/wire-404.png" target="_blank">HERE</a> for 404.html Wireframe</li>
    <li>Click <a href="assets/images-readme/wire-bigmap.png" target="_blank">HERE</a> for large map page linked via islands.html Wireframe</li>
</ul>
<br>
<a href="#Contents">Back to the top.</a>


## Surface
### Design
#### Typography
<img src="assets/images-readme/satisfy.png" alt="Font used for headings" width="70%">

#### Color Scheme
As I want the website to be visual, it made more sense to me to choose a colour scheme based on an image that is regularly used throughout the site. When I think of the Caribbean, I think of the blue and turquoise waters of the sea, so want to have the colour scheme pulled from an image that has these colours within it. I chose the image that is repeated at the bottom of the main pages of the turtle as this has the blues that remind me of the Caribbean. 
<img src="assets/barbados2.jpg" alt="Image used to generate colour pallette" width="70%"><br>
I then used the services of the website "colormind.io" as this allows the creation of a colour pallette from an image rather than a single colour choice. The colour pallette below is the pallette generated from the turtle image. I really love the range of blues and will use these throughout my website as background colours and decoration colours. The majority of the pages on the website will have image backgrounds to aid in the visual appeal of the website, however I still want some continuity of colour throughout. As the majority of backgrounds are images, many of the text overlays will have to have a neutral background to have the text be more readable without clashing with the background image, therefore I have chosen the majority of text boxes to have the neutral colour of grey - ranging from darker greys on backgrounds that have a more toned down overall colour (such as the hero video in index.html and the background of the review text boxes), to lighter and less transparent grey on backgrounds that are more vibrant and could cause problems with reading text (such as those in idlands.html and types.html). 
<img src="assets/images-readme/colour-pallette.png" alt="Generated colour pallette" width="70%">
<img src="assets/image-readme/colour-hero-box.png" alt="Image showing background colour of text box over the hero video" width="100%">
<img src="assets/image-readme/colour-review-box.png" alt="Image showing background colour of text box in the reviews section" width="100%">
<img src="assets/image-readme/colour-island-box.png" alt="Image showing background colour of text box in islands.html" width="40%">
<img src="assets/image-readme/colour-type-box.png" alt="Image showing background colour of text box in types.html" width="40%">

#### Design - Images
#### Design - Video

<a href="#Contents">Back to the top.</a>

# Technologies
<a href="#Contents">Back to the top.</a>

# Features
## Features left to implement
<a href="#Contents">Back to the top.</a>

# Testing
## Functionality
## Compatibility
## User Testing Stories
## Code Validation
## Issues found during development
## Performance Testing (lighthouse)
<a href="#Contents">Back to the top.</a>
    
# Deployment
<a href="#Contents">Back to the top.</a>

# Credits
## Content
## Credits - Images
## Credits - Video
## Acknowledgements
<a href="#Contents">Back to the top.</a>

# Screenshots

<img src="assets/images-readme/screen-index.png" alt="Screenshot of index.html" width="90%"><br>
<ul>
    <li>Click <a href="assets/images-readme/screen-types.png" target="_blank">HERE</a> for types.html Screenshot</li>
    <li>Click <a href="assets/images-readme/screen-gallery.png" target="_blank">HERE</a> for gallery.html Screenshot</li>
    <li>Click <a href="assets/images-readme/screen-contact.png" target="_blank">HERE</a> for contact.html Screenshot</li>
    <li>Click <a href="assets/images-readme/screen-thanks.png" target="_blank">HERE</a> for thanks.html Screenshot</li>
    <li>Click <a href="assets/images-readme/screen-404.png" target="_blank">HERE</a> for 404.html Screenshot</li>
    <li>Click <a href="assets/images-readme/screen-map.png" target="_blank">HERE</a> for large map page linked via islands.html Screenshot</li>
</ul>
<br>
<a href="#Contents">Back to the top.</a>

# References
<ol>
    <li>[1]U. Qureshi, "UX Design using the Five Planes Method", Medium, 2021. [Online]. Available: https://medium.com/designcentered/ux-design-5-planes-method-b1b1d6587c05. [Accessed: 06- Jun- 2021].</li>
    <li>[2]Lonely Planet, 2021. How to choose a Caribbean island – [online]. Available: https://www.lonelyplanet.com/articles/how-to-choose-caribbean-island [Accessed: 05- June- 2021].</li>
    <li>[3]Caribbean Currency, Thomas Cook, 2021. [Online]. Available: https://www.thomascook.com/holidays/caribbean/travel-money. [Accessed: 05- Jun- 2021].</li>
    <li>[4]"10 Backpacking Myths That Shouldn't Stop You Travelling - Backpacker Advice", Backpacker Advice, 2021. [Online]. Available: https://backpackeradvice.com/blog/backpacking-myths.html. [Accessed: 05- Jun- 2021].</li>
    <li>[5]D. Horscroft and D. Horscroft, "Population estimates by marital status and living arrangements, England and Wales - Office for National Statistics", Ons.gov.uk, 2021. [Online]. Available: https://www.ons.gov.uk/peoplepopulationandcommunity/populationandmigration/populationestimates/bulletins/populationestimatesbymaritalstatusandlivingarrangements/2002to2017. [Accessed: 06- Jun- 2021].</li>
    <li>[6]C. Jönsson and D. Devonish, "Does Nationality, Gender, and Age Affect Travel Motivation? a Case of Visitors to The Caribbean Island of Barbados", Journal of Travel & Tourism Marketing, vol. 25, no. 3-4, pp. 398-408, 2008. Available: 10.1080/10548400802508499 [Accessed 5 June 2021].</li>
    <li>[7]Django Stars Blog. 2021. Your Guide to MVP, MMP, MLP, MDP and MAP Startup Stages. [online] Available at: https://djangostars.com/blog/guide-mvp-mmp-mlp-mdp-map-startup-stages [Accessed 7 June 2021].</li>
</ol>