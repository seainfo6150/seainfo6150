# INFO6150 Week 9 Assignments

Due by the beginning of class, week 10 (November 6).
You may revise once by the beginning of class, week 11 (November 13).

This week you will be practicing adding an adaptive layout to your components from last week.

**You should finish all your week 8 revisions before starting the week 9 assignment**

## create a week-9 branch from your week-8 branch
You will be using the components you created last week for this week's assignment.

```
cd seainfo6150-webapp
git checkout week-8
git pull upstream master
git checkout --b week-9
```

## add media queries
Create media queries for week 8's assignment to make it adaptive as well as responsive. You may add whatever breakpoints and flex/shuffle the layout as you like, but there must be at least 3 breakpoints and your layout must demonstrate good principles of usability. For example, think about readability in terms of line length, font sizes, etc. 

## start the webapp

Start the webapp and verify that your layout is both responsive and adaptive.

```
npm start
```

## save it

save and commit your work to the week-9 branch and push to your fork

```
git add .
git commit -m "[your commit message]"
git push origin week-9
```

## send an email 
Send an email to Yiwei (luo.yiw@husky.neu.edu) with a link to your seainfo6150-webapp fork. 

<table>
  <caption>Rubric</caption>
  <tbody>
    <tr>
      <td>Created and saved assignment to week-9 branch</td>
      <td>1</td>
    </tr>
    <tr>
      <td>Adaptive layout with 3 breakpoints that demonstrates good usability principles</td>
      <td>5</td>
    </tr>
    <tr>
      <td>Layout is also still responsive</td>
      <td>2</td>
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


