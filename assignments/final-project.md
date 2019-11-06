# SEA INFO-6150 Final Project

Your team has been tasked with designing, building and testing a new website concerning some business, school, event, or topic. 

You may choose any kind of website that your team would like to build. Here are some ideas:
- a car dealership website
- a university website that lists classes/graduate programs
- a tech magazine
- a recipe website 
- an event website for a conference

Your role is to coordinate with the other members of your team to build the React components and CSS stylesheets that display the data in a usable, accessible and attractive way.

You are encouraged to do research and look at other websites that are similar to the website you want to  build to get ideas about how to present your website.


## Project requirements/notes

### Design
Your website must use at least 2 different fonts in some way. Many websites use one font for body text and another for headers. 

### React
Your site must be built using the team React app repo. You must have **at least** 5 components that use/consume props in some way.

### HTML
The HTML for your website must be semantically correct and valid to the best of your ability. I will be validating the site with the W3 HTML Validator (http://validator.w3.org).

### Layout
The website should be both responsive and adaptive; you must implement at least 3 breakpoints where the layout updates in an obvious fashion. You also must use both grid and flexbox in some fashion on the site. 

### Images
Your website must feature responsive images. In at least 1 place, you must use 1 HTML-based responsive image solution (either the resolution switching or art direction switching solution).

I have included a picture of a treefrog on the team repo homepage as an example of where you can place images and how to reference them from your app.

### 404 Not found
The website should display an attractive, usable and accessible 404 page when visiting an unmatched route.

### Navigation
The website must display **at least** 1 navigation element on every page.

### Homepage
Your website must feature a homepage for your website. The name of your website must appear on the homepage and in the title of every page of the website.

Your homepage (as well as the rest of the site) should use good principles of usability and accessibility discussed in class.

### Template pages
Your website must feature **at least** 4 different kinds of template pages. 

Some examples of different template pages for a website that sells a certain kind of product might be: 

- Home page
- A page of product categories
- An individual product detail page
- A text-based page like an About The Company page

### Content
Your website must feature **at least** 20 distinct content pages. 

If your team buit a site that sold 15 kinds of products in 5 categories, your pages might be numbered as follows: 

- (1) Homepage
- (1) All Categories page
- (5) Individual category pages
- (15) Individual product detail pages
- (1) Order page
- (1) Order confirmation page
- (1) Thank You page
- (1) About Us page
- (1) Contact Us page
- (1) 404/Error page

Total: 28 pages

**You are not required to write/create original content.** You may copy text and images from eleswhere to fill your website. 

You may choose to create static components for your content or use a dynamic data approach.  (Remember that ** at least** 5 components must pass props in some way.) Please refer to the `seainfo6150-webapp` and your week-4, etc. assignment branches for an example of how to push content from a JSON file into your component via props.

### Form
Your site must feature at least 1 HTML form with the following elements:
- 5 text inputs -- 3 of these inputs must be required and 2 must follow a specific format that can be validated, for example a telephone number, a birthdate, a currency, etc.
- 2 dropdowns
- 1 group of radio and/or checkboxes with at least 3 inputs

Your website should display the data entered in the form back to the user in a usable, attractive way.

I have provided a basic Form component that has a single text input; it demonstrates how to retrieve the contents of a form for display.

## Routes
All of the pages should be available via components controlled by a router. This simplifies the process of linking the pages together and gives a straightforward mapping of which component is associated with which URL of the website.

There is already a router implemented with the following routes in place. You will need to update the routes and components in order to set up navigation for your own site.

#### `/`
corresponds to `http://localhost:3000/` and the `Home` component; the homepage of the website.

#### `/foo`
corresponds to `http://localhost:3000/foo` and the `Foo` component.

#### `/bar`
corresponds to `http://localhost:3000/bar/:categoryId/:productId` and the `Bar` component. This gives an example of how you could pass props that come from the URL

#### `/baz`
corresponds to `http://localhost:3000/baz` and the `Baz` component. This gives an example of how you could pass external content (from a JSON file, for example) as props to your component. 

#### `/404`
corresponds to `http://localhost:3000/404` and the `Error` component; the 404/error page of the website.


## Schedule

### Week 10, November 6
I will present the project requirements and make assignments for any remaining teams as necessary. With your team, you will work on look and feel, wireframes, user flows and sitemap for the website.

The following pieces should be submitted to me **by 2pm PST, November 13** (ie, the beginning of Week 11 class) so that I can sign off on your project. You can email them, share them in a Word doc, send me a Framebox link, etc.

#### Look and feel
Your team should give me 3 look and feel words (eg, "bold", "calm", "fun") that you want your website to convey and an explanation of how your website will convey that **using the design theory concepts discussed in class during week 2**.

#### Wireframes
You must have wireframes for at least 4 different kinds of template pages. Some examples of different templates might be: Home page, a page of product categories, an individual product detail page, a text-based page like an About page. 

#### Site map
You must create a sitemap showing all 10 (or more) pages of the site

### User flows
You must identify and diagram out at least 3 user flows that you want your user to be able to accomplish on your site. We will use these as the basis for usability testing in week 12. Some example of user flows might be: 

- A user can travel from the homepage to a product detail page to find the price of a specific product
- A user can travel from a degree program page to a calendar page to find out how many days are university holidays
- A user can successfully complete signing up for a newsletter


### Week 11, November 13
With your team, you will work on project implementation and come up with the tasks for usability testing during week 12. (More on this TBD.)


### Week 12, November 20
In class, we will conduct usability testing on each others' websites and provide feedback that teams can use to finalize their projects.


### Week 13, November 27
Thanksgiving break, NO CLASS. However, you should continue to work on your websites and incorporate the feedback from usability testing.


### Week 14, December 4
Each team will demonstrate their final website to the rest of the class. Personal journals/writeups should be shared in a document or emailed to a.bingham@northeastern.edu **by midnight PST, December 4**.


## Rubric
This project is worth 30% of your final grade. 

### Final website
## Due in class December 4
15% of your final grade will be the total score of the website produced based on the rubric below. The same score will be awarded identically among all team members.

Projects will be evaluated on a 0-125 scale for each of 5 sections. Each section score will be multiplied by .20 and the 5 sections will be added together to calculate the final 0-125 score. (Scores above 100 will be counted as extra credit towards your final grade.)

<table>
  <thead>
    <tr>
      <th></th>
      <th>Exceeds expectations (125-100)</th>
      <th>Meets expectations (100-75)</th>
      <th>Mostly meets expectations (75-50)</th>
      <th>Does not meet expectations/Incomplete (50-0)</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1. HTML</td>
      <td>Site validation has no errors or warnings, HTML is semantic and well-formed</td>
      <td>Site validation has one or two errors and/or warnings, HTML is mostly semantic and well-formed.</td>
      <td>Site validation has several errors and/or warnings, HTML is not very semantic.</td>
      <td>Site validation has many errors and/or warnings, HTML is not semantic or unfinished.</td>
    </tr>
    <tr>
      <td>2. CSS</td>
      <td>CSS shows mastery, is clearly organized using CSS modules, fully responsive and has more than 3 adaptive breakpoints</td>
      <td>CSS shows pretty good practices, is mostly to fully responsive and has at least 3 adaptive breakpoints</td>
      <td>CSS shows OK practices, has some responsiveness and has at least 2 adaptive breakpoints</td>
      <td>CSS is very crude, near non-existent and/or unfinished, is not responsive responsive and/or has 1 or no adaptive breakpoints</td>
    </tr>
    <tr>
      <td>3. Usability/accessibility</td>
      <td>Project shows excellent principles of usability and accessibility. It is well-thought-out, clear and easy to use/navigate both with a mouse and keyboard and using other ways of navigating (keyboard only, for example).</td>
      <td>Project shows good principles of usability and accessibility. It is clear and easy to use/navigate and might have one or two aspects that could be improved.</td>
      <td>Project shows some principles of usability and accessibility but could use much improvement.</td>
      <td>Project is difficult to use/navigate (even with a mouse and keyboard) and shows little or no principles of usability/accessibility.</td>
    </tr>
    <tr>
      <td>4. Requirements</td>
      <td>Team went above and beyond product requirements and found ways of adding features that might involve research or advanced techniques (Stateful React components, CSS animations, complicated grid layouts, etc.)</td>
      <td>Project requirements are fully or almost fully implemented</td>
      <td>Project requirements are mostly implemented</td>
      <td>Project requirements are mostly not implemented or project is unfinished</td>
    </tr>
    <tr>
      <td>5. Overall result/presentation</td>
      <td>Project presented in class shows great effort, refinement and a lot of care and thought</td>
      <td>Project presented in class shows good effort and refinement</td>
      <td>Project presented in class shows OK effort and refinement</td>
      <td>Project presented in class shows low effort, project was not presented in class and/or project shows barely any effort</td>
    </tr>
  </tbody>
  <tfoot>
    <td colspan="5">Total: </td>
  </tfoot>
</table>

### Journal/writeup
## Due by midnight PST, December 4

15% of your final grade will be your individual score as determined by the level of effort/participation detailed in your project journal/writeup. You should keep this journal while your team is working on the project as a record of your individual participation.

In this writeup, you should include a detailed description of your contributions to the project: a description of your day-to-day contributions, any challenges that came up and how you personally contributed to solving them, any difficulties or obstacles your team as a whole faced, etc. 

Feel free to include things like links to your shared team repo, screenshots, google docs histories, etc. to support your description. 

Journals/writeups that are late will have 5% deducted from the maximum score possible for each day late.

<table>
  <thead>
    <tr>
      <th></th>
      <th>125-100</th>
      <th>100-75</th>
      <th>75-50</th>
      <th>50-0</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Participation</td>
      <td>Writeup provides detailed descriptions and is well supported by checkins to repo, screenshots, etc.</td>
      <td>Writeup provides mostly thorough description and has some supporting details.</td>
      <td>Writeup is brief and provides few details.</td>
      <td>Writeup is very brief, incomplete or unfinished/missing.</td>
    </tr>
  </tbody>
  <tfoot>
    <td colspan="5">Total: </td>
  </tfoot>
</table>