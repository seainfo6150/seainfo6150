# INFO6150 Week 6 Assignments
Due by the beginning of class, week 7 (February 18).

This week you will be practicing adding more styling to your components from last week.

## fetch branches and create a week-6 branch that tracks the upstream/week-6 branch
This means that a local branch is created from the `week-6` branch from upstream
```
cd seainfo6150-webapp
git fetch upstream
git checkout --track upstream/week-6
```

## create an article image componennt
Create a new functional component in the `ArticleList` directory that displays the image associated with each of the news articles in `seainfo6150-webapp/src/data/articles.json`.

Your component must be named `ArticleList/ArticleImage.jsx` and must accept 2 props:

- url: a string
- title: a string

Your image must have semantically-valid, accessible HTML.  Make sure to validate your components with an HTML validator like http://validator.w3.org!

## import and use the component
In the appropriate component, import and use the new `ArticleImage.jsx` so that each article is displayed with its image as shown in as shown in <a href="./week-6-screenshot.png">this screenshot</a>.

## style the components
Style the image in the article as shown in <a href="./week-6-screenshot.png">this screenshot</a> using a CSS module created for the ArticleImage component. Also, create more styles for your article list components to match <a href="./week-6-screenshot.png">this screenshot</a> as closely as possible.

## start the webapp
Start the webapp and verify that it is displayed as shown in <a href="./week-6-screenshot.png">this screenshot</a>.
```
npm start
```

## save it 
save and commit your work to the week-6 branch and push to your fork
```
git add . 
git commit -m "[your commit message]"
git push origin week-6
```

## send an email 
Send an email to Tianyu (20spr.info6150@gmail.com) with a link to your seainfo6150-webapp fork. 

<table>
  <caption>Rubric</caption>
  <tbody>
    <tr>
      <td>Created and saved assignment to week-6 branch</td>
      <td>1</td>
    </tr>
    <tr>
      <td>Created functional components `ArticleImage`</td>
      <td>2</td>
    </tr>
    <tr>
      <td>Styled functional components as closely to screenshot as possible</td>
      <td>5</td>
    </tr>
    <tr>
      <td>Valid HTML</td>
      <td>1</td>
    </tr>
    <tr>
      <td>App runs and displays article list properly</td>
      <td>1</td>
    </tr>
  </tbody>
  <tfoot>
    <td>Total:</td>
    <td>10</td>
  </tfoot>
</table>
