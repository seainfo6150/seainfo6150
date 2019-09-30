# INFO6150 Week 3 Assignments
Due by the beginning of class, week 4 (September 24).
You may revise once by the beginning of class, week 5 (October 2).

This week you will be practicing working in the web app, creating a branch and marking up text with HTML!

## create a week-3 branch
```
cd seainfo6150-webapp
git checkout master
git pull upstream master
git checkout -b week-3
```

## open /src/Article/Article.jsx in your web development IDE

## add HTML
Mark up the text of the news article with valid, semantically-appropriate HTML. **Using only HTML markup** follow the formatting shown in <a href="week-3-screenshot.png">this screenshot</a>. 

Consider block level and inline HTML elements, what kind of text this is and how you should properly cite the author, properly display the date, email address etc. Make sure to validate your text with an HTML validator like http://validator.w3.org!

Note: because you are writing this in the React app, HTML attributes work slightly differently. Most relevant for this assignment, you will use the following attribute for one of your tags: 

`dateTime="2018-11-22"` (note the camelCase syntax)

## start the webapp
Verify that the article displays properly in the app. 
```
npm install (only the first time you ever run the app)
npm start
```

## save it 
save and commit your work to the week-3 branch and push to your fork
```
git add . 
git commit -m "[your commit message]"
git push origin week-3
```

## send an email 
Send an email to Yiwei (luo.yiw@husky.neu.edu) with a link to your seainfo6150-webapp fork. 

<table>
  <caption>Rubric</caption>
  <tbody>
    <tr>
      <td>Created and saved assignment to week-3 branch</td>
      <td>2</td>
    </tr>
    <tr>
      <td>Semantic, properly marked-up article</td>
      <td>6</td>
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
