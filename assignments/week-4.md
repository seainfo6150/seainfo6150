# INFO6150 Week 4 Assignments
Due by the beginning of class, week 5 (February 5).

This week you will be practicing working in the web app, creating a tracking branch, creating a React component and passing props. 

## fetch branches and create a week-4 branch that tracks the upstream/week-4 branch
This means that a local branch is created from the `week-4` branch from upstream
```
cd seainfo6150-webapp
git fetch upstream
git checkout --track upstream/week-4
```

## create a component
Create a functional component that displays some data about each article that is being passed to it. **You should not need to use any CSS for this assignment.**

You **must** name this component `src/ArticleList/ArticleListItem.jsx`.

ArticleListItem.jsx accepts 1 prop:
* article: the news article being passed to this component in `src/ArticleList/ArticleList.jsx`.

### article attributes
You should create valid, semantically-appropriate HTML to display the following article attributes (these can be viewed in `src/data/articles.json`). 

* title: the title of the article
* shortText: a short description of the article
* pubDate: the publishing date of the article

Consider block level and inline HTML elements, how you should properly display the date, etc. Make sure to validate your text with an HTML validator like http://validator.w3.org!

Note: for this assignment, since pubDate is not a machine-readable format, you will use the following attribute for one of your tags: 
`datetime={props.article.pubYear}`

### a button! 
Your component should also include a button that says "show article slug" and, when clicked, displays an alert message that displays the "slug" attribute of the article. In the `seainfo6150-webapp` repo, there are a couple of example components that show you how create a button and call a handler. These were demonstrated in class, also. 


## import the component
In `src/ArticleList/ArticleList.jsx`, import and render the functional component so that the list of all the articles are displayed on the main app page (http://localhost:3000). Don't forget to pass the article prop to it!

## start the webapp
Start the webapp and verify that it looks something like <a href="./week-4-screenshot.png">this screenshot</a>. **Your formatting does not need to be exactly the same. You will be graded on valid HTML and the functionality of your component.**

```
npm start
```

## save it 
save and commit your work to the week-4 branch and push to your fork
```
git add . 
git commit -m "[your commit message]"
git push origin week-4
```

## send an email 
Send an email to Tianyu (20spr.info6150@gmail.com) with a link to your seainfo6150-webapp fork. 

<table>
  <caption>Rubric</caption>
  <tbody>
    <tr>
      <td>Created and saved assignment to week-4 branch</td>
      <td>2</td>
    </tr>
    <tr>
      <td>Semantic, properly marked-up article attributes</td>
      <td>2</td>
    </tr>
    <tr>
      <td>Created and imported functional component `src/ArticleList/ArticleListItem.jsx`</td>
      <td>4</td>
    </tr>
    <tr>
      <td>Valid HTML</td>
      <td>1</td>
    </tr>
    <tr>
      <td>App runs and displays articles</td>
      <td>1</td>
    </tr>
  </tbody>
  <tfoot>
    <td>Total:</td>
    <td>10</td>
  </tfoot>
</table>
