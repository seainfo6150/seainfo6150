# INFO6150 Week 6 Assignments
Due by the beginning of class, week 7 (October 16).
You may revise once by the beginning of class, week 8 (October 23).

This week you will be practicing adding more styling to your components from last week.

**You should finish all your week 5 revisions before starting the week 6 assignment**

## create a week-6 branch from your week-5 branch
You will be using the components you created last week for this week's assignment.

```
cd seainfo6150-webapp
git checkout week-5
git pull upstream master
git checkout --b week-6
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
Send an email to Yiwei (luo.yiw@husky.neu.edu) with a link to your seainfo6150-webapp fork. 

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
