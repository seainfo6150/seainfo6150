# INFO6150 Week 8 Assignments

Due by the beginning of class, week 9 (October 30).
You may revise once by the beginning of class, week 10 (November 6).

This week you will be practicing adding flexbox and grid to your components from last week.

**You should finish all your week 6 revisions before starting the week 8 assignment**


## create a week-8 branch from your week-6 branch
You will be using the components you created last week for this week's assignment.

```
cd seainfo6150-webapp
git checkout week-6
git pull upstream master
git checkout --b week-8
```

## style the components
Update the styles for the ArticleList/ArticleListItem/ArticleImage/SlugButton components from week 6 to match <a href="./week-8-screenshot.png">this screenshot</a> as closely as possible. You should find that you use both flexbox and grid techniques to achieve the display.


## start the webapp

Start the webapp and verify that it is displayed as shown in <a href="./week-8-screenshot.png">this screenshot</a>.

```
npm start
```

## save it

save and commit your work to the week-8 branch and push to your fork

```
git add .
git commit -m "[your commit message]"
git push origin week-8
```

## send an email 
Send an email to Yiwei (luo.yiw@husky.neu.edu) with a link to your seainfo6150-webapp fork. 

<table>
  <caption>Rubric</caption>
  <tbody>
    <tr>
      <td>Created and saved assignment to week-8 branch</td>
      <td>1</td>
    </tr>
    <tr>
      <td>Styled the articles list with flexbox and grid</td>
      <td>7</td>
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
