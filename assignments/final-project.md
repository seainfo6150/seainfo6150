# SEA INFO-6150 Final Project

You have been tasked with designing, building and testing a new website concerning some business, school, event, or topic. 

You may choose any kind of website that you or your team would like to build. 

Here are some ideas. **THESE ARE ONLY IDEAS, YOU ARE NOT REQUIRED TO CHOOSE FROM THIS LIST.**
- a car dealership website
- a university website that lists classes/graduate programs
- a tech magazine
- a recipe website 
- an event website for a conference

Your role is to build the React components and CSS stylesheets that display the data in a usable, accessible and attractive way.

You are encouraged to do research and look at other websites that are similar to the website you want to  build to get ideas about how to present your website.


## Project requirements/notes
Please read the following carefully as part of your grade depends on how well you fulfill the rquirements.

### Design
Your website must use **at least** 2 different fonts in some way. Many websites use one font for body text and another for headers. 

### React
Your site must be built using the final project React app repo April will set up for you. You must have **at least** 5 components that accept props in some way and display dynamic data.

For example, you might have components that use props to:
- display the user's name based on what they entered in a form
- display different content based on which button was clicked on
- filter opetions in a list based on some criteria the user selected

**THESE ARE ONLY IDEAS, YOU ARE NOT REQUIRED TO CHOOSE FROM THIS LIST.**


### HTML
The HTML for your website must be semantically correct and valid to the best of your ability. I will be validating the site with the W3 HTML Validator (http://validator.w3.org).

### Layout
The website should be both responsive and adaptive; you must implement **at least** 3 breakpoints where the layout updates in an obvious fashion. You also must use both grid and flexbox in some fashion on the site. 

### Images
Your website must feature responsive images. In **at least** 1 place, you must use 1 HTML-based responsive image solution (either the resolution switching or art direction switching solution discussed in lecture: https://github.com/aprilbingham-neu/seainfo6150/blob/master/docs/Image%20and%20effects%20for%20the%20web.pdf).

I have included a picture of a treefrog on the project repo homepage as an example of where you can place images and how to reference them from your app.

### 404 Not found
The website should display an attractive, usable and accessible 404 page when visiting an unmatched route.

### Navigation
The website must display **at least** 1 navigation element on every page.

### Homepage
Your website must feature a homepage for your website. The name of your website must appear on the homepage and in the title of every page of the website.

Your homepage (as well as the rest of the site) should use good principles of usability and accessibility discussed in class.

### Template pages
<a id="template-pages"></a>
Your website must feature **at least** 5 different kinds of template pages. 

Some examples of different template pages for a website that sells a certain kind of product might be: 

- Home page
- A page of product categories
- An individual product detail page
- An order-form page
- A text-based page like an About The Company page

 **THESE ARE ONLY IDEAS, YOU ARE NOT REQUIRED TO FOLLOW THIS LIST EXACTLY.**

### Content
<a id="content"></a>

**IF YOU ARE WORKING INDIVIDUALLY**
Your website must feature **at least** 10 distinct content pages. 

**IF YOU ARE WORKING AS PART OF A TEAM**
Your website must feature **at least** 30 distinct content pages. 

For example, if your website sold 15 kinds of products in 5 categories, your pages might be numbered as follows: 

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

**THESE ARE ONLY IDEAS, YOU ARE NOT REQUIRED TO FOLLOW THIS LIST EXACTLY.**

**You are not required to write/create original content.** You may copy text and images from eleswhere to fill your website. 

You may choose to create hard-coded components for your content or use a dynamic data approach.  (Remember that **at least** 5 components must accept props in some way and display dynamic data.) Please refer to the `seainfo6150-webapp` and your weeks 4-8 assignment branches for an example of how to push content from a JSON file into your component via props.

### Form
Your site must feature **at least** 1 HTML form with the following elements:
- 5 text inputs -- 3 of these inputs must be required and 2 must follow a specific format that can be validated, for example a telephone number, a birthdate, a currency, etc.
- 2 dropdowns
- 1 group of radio and/or checkboxes with **at least** 3 inputs

**Your website should validate these elements and display appropriate error/help messages to the user to allow them to complete the form properly.**

**Your website should display the data entered in the form back to the user in a usable, attractive way.**

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

### A note about 3rd-party libraries like bootstrap, etc.
While I have not explicitly prohibited 3rd party libraries like bootstrap, etc. I strongly advise against using them, as they can add extra HTML and CSS that could interfere with your code. **You are responsible for any invalid HTML/CSS that results from 3rd party code and I will grade accordingly!** I have had teams in the past be marked down significantly because of libraries they chose to use.

Remember, this project is a chance to showcase what YOU have learned over this semester, not simply what libraries you can choose!


## Schedule

### Week 10, March 11
<a id="week-10"></a>
I will upload the project requirements and be available during our regular class period (2pm-5pm) via Slack for any real-time questions you may have regarding the project. 

During Week 10, you should 
* decide if you are working individually or on a team
* decide what kind of website you want to develop 
* work on look and feel, wireframes, user flows and sitemap for the website

**The following pieces should be submitted to me by 2pm PST, March 18** (ie, the beginning of Week 11 class) so that I can sign off on your project. You can email them, share them in a Word doc, send me a Framebox link, etc.

#### 1. The class members who will be working on your website
You must submit a list of all the class members who will be working on the website, their email addresses and the github profile they use for the class. Please do this even if you are working individually. This will allow me to set up a repository for your project. If you choose to work as part of a team, you must form your own team; I will not be assigning teammembers. **If you choose to form a team, please limit the number of team members to no more than 4.** 

#### 2. Look and feel
Your team should give me 3 look and feel words (eg, "bold", "calm", "fun") that you want your website to convey and an explanation of how your website will convey that **using the design theory concepts discussed in class during week 2**.

#### 3. Wireframes
You must have wireframes for **at least 5 different kinds of template pages**. Some examples of different templates might be: Home page, a page of product categories, an individual product detail page, a text-based page like an About page. (see the <a href="#template-pages">template pages section</a> above.)

#### 4. Site map
You must create a sitemap showing all the pages of the site. (Please see the <a href="#content">content section</a> for more information.)

#### 5. User flows
You must identify and diagram out **at least** 3 user flows that you want your user to be able to accomplish on your site. Some example of user flows might be: 

- A user can travel from the homepage to a product detail page to find the price of a specific product
- A user can travel from a degree program page to a calendar page to find out how many days are university holidays
- A user can successfully complete signing up for a newsletter

**THESE ARE ONLY IDEAS, YOU ARE NOT REQUIRED TO FOLLOW THIS LIST EXACTLY.**

### Week 11, March 18
You will work on project implementation. I will be available during our regular class period (2pm-5pm) via Slack for any real-time questions you may have regarding the project. 

### Week 12, March 25
You will work on project implementation. I will be available during our regular class period (2pm-5pm) via Slack for any real-time questions you may have regarding the project. 

### Week 13, April 1
<a id="week-13"></a>

You will come up with tasks for usability testing.

Based on the 3 user flow statements that you created in week 10, you should develop 3 __user tasks__ that can be tested. 

For example:

If your user flow was something like **A user can find a vegetarian recipe on our website**</br>
A user task might be **Explore the website and find a vegetarian recipe you would like to cook for dinner tonight**.

You should come up with a user task for each user scenario and be ready to have someone use your team's website to complete them. 

**User tasks are due by midnight PDT, April 5.**

Here are some resources on usability tests and writing user tasks that may be helpful to read:
* https://www.nngroup.com/articles/better-usability-tasks/
* https://adamfard.com/ux-design-blog/how-to-successfully-conduct-user-testing-in-6-simple-steps/
* https://medium.com/@CanvasFlip/creating-task-scenarios-that-improves-usability-test-results-eece56959d19
* https://blog.testlodge.com/usability-testing-examples/
* https://uxplanet.org/how-to-conduct-a-usability-test-in-six-steps-from-start-to-finish-4082e8d57858
* https://medium.com/user-research/user-research-basics-creating-a-test-and-script-bef65496292c
* https://www.nngroup.com/articles/task-scenarios-usability-testing/
* https://blog.maze.design/write-great-usability-tasks/

During this week, you should also work on project implementation. I will be available during our regular class period (2pm-5pm) via Slack for any real-time questions you may have regarding the project.  

### Week 14, April 8
You will work on project implementation. I will be conducting usability tests during our regular class period (2pm-5pm) and **will not** be available for questions during this time. You may reach out via email or Slack and I will get back to you! I will have all usability feedback to teams by Friday, April 10.

### Week 15, April 15
You should have all work committed to the final project repo by class period, **ie by 2pm PST**. Personal journals/writeups should be shared in a document or emailed to a.bingham@northeastern.edu **by midnight PST, April 15**. Peer evaluations (if applicable) should be submitted **by midnight PST, April 15**.


## Rubric
This project is worth 30% of your final grade. 

### Final website
#### Due by class period, 2pm PST, April 15

#### IF YOU ARE WORKING INDIVIDUALLY
15% of your final grade will be the total score of the website produced based on the rubric below. 

#### IF YOU ARE WORKING ON A TEAM
5% of your final grade will be the total score of the website produced based on the rubric below. The same score will be awarded identically among all team members.

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
      <td>CSS shows pretty good practices, is mostly to fully responsive and has 3 adaptive breakpoints</td>
      <td>CSS shows OK practices, has some responsiveness and has 2 adaptive breakpoints</td>
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
#### Due by midnight PST, April 15

15% of your final grade will be your individual score as determined by the level of effort/participation detailed in your project journal/writeup. You should keep this journal while you are working on the project as a record of your individual participation.

In this writeup, you should include a detailed description of your contributions to the project: a description of your day-to-day contributions, any challenges that came up and how you personally contributed to solving them, any difficulties or obstacles your team as a whole faced, etc. 

Please see the two following examples of writeups from past classes -- these writeups are excellent examples of what I'm looking for!
* https://github.com/aprilbingham-neu/seainfo6150/tree/master/examples/final-project/writeup-1.pdf
* https://github.com/aprilbingham-neu/seainfo6150/tree/master/examples/final-project/writeup-2.pdf

Feel free to include things like links to your final project repo, screenshots, google docs histories, etc. to support your description. 

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


### Peer evaluation
#### Due by midnight PST, April 15

**Peer evaluations are only required if you are working as part of a team.**
10% of your final grade will be the average score of the evaluations submitted by the other members of your team. April will provide a link and instructions for peer evaluations. 


### Extra credit project presentation
#### Due by midnight PST, April 22
For each individual/team project completing this extra credit, I will add 3% to the overall class grade to each member who worked on the project. 

Create a presentation that demonstrates your final project. This could be a screen recording which steps through the various pages/features, a powerpoint with screenshots of the various pages, a video of your demonstration, or something more creative! 

**The presentation must be submitted to me by midnight PST, April 22. Late submissions will be awarded no extra credit.** 
