# INFO6150 Week 5 Assignments
Due by the beginning of class, week 6 (October 9).
You may revise once by the beginning of class, week 7 (October 16).

This week you will be practicing working in the web app, creating a branch from an existing branch, creating a couple of React components and adding styling. 

## create a week-5 branch from your week-4 branch
This means that a local branch is created from the `week-4` branch you created in week 4. **Make sure that you have completed week 4's assignment and any revisions you wish to make before starting this week's assignment.**
```
cd seainfo6150-webapp
git checkout week-4
git checkout -b week-5
```

## create a button component
Create a new functional component in `ArticleList` named `SlugButton.jsx` that, when clicked, displays an alert message that displays the "slug" attribute of the article. **You should use the button you created in week 4 as the basis of this new component.**

`SlugButton` must accept these 2 props:
* buttonText: a string, the display text of the button
* slug: a string, the slug of an article


## import and use the component
In `src/ArticleList/ArticleListItem.jsx`, import and use your new `SlugButton` component. You will pass this new component 2 props: the article's author for the buttonText prop and the article's slug for the slug prop. (These can be viewed in `src/data/articles.json`)

 Make sure to validate your components with an HTML validator like http://validator.w3.org!


## style the components
Create styles for the three components in `ArticleList` in files named 

* `ArticleList.module.css`
* `ArticleListItem.module.css` 
* `SlugButton.module.css` 

Make sure to import the css into `ArticleList/ArticleList.jsx`, `ArticleList/ArticleListItem.jsx`, and  `ArticleList/SlugButton.jsx` as demonstrated in class using CSS modules. Please style your components to match <a href="./week-5-screenshot.png">this screenshot</a> as closely as possible.


## start the webapp
Start the webapp and verify that it is displayed as shown in <a href="./week-5-screenshot.png">this screenshot</a>.
```
npm start
```

## save it 
save and commit your work to the week-5 branch and push to your fork
```
git add . 
git commit -m "[your commit message]"
git push origin week-5
```

## send an email 
Send an email to Yiwei (luo.yiw@husky.neu.edu) with a link to your seainfo6150-webapp fork. 

<table>
  <caption>Rubric</caption>
  <tbody>
    <tr>
      <td>Created and saved assignment to week-5 branch</td>
      <td>1</td>
    </tr>
    <tr>
      <td>Semantic, properly marked-up slug button component</td>
      <td>3</td>
    </tr>
    <tr>
      <td>Styled functional components `ArticleList`, `ArticleListItem`, and `SlugButton` as closely to screenshot as possible</td>
      <td>4</td>
    </tr>
    <tr>
      <td>Valid HTML</td>
      <td>1</td>
    </tr>
    <tr>
      <td>App runs and displays article properly</td>
      <td>1</td>
    </tr>
  </tbody>
  <tfoot>
    <td>Total:</td>
    <td>10</td>
  </tfoot>
</table>
