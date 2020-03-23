# Schulich Ignite Website

Here is all the code for the [schulich ignite website](https://schulichignite.com/) it's hosted on github pages, uses ionos for name registration, and cloudflare for DNS.

[DNS](https://dash.cloudflare.com/login)

[Domain Name Registrar](https://login.ionos.ca/)



### Updating Slides

##### Where to upload

To update the slides simply put the content in the folder for current term (i.e. ```assets/winter_2020```) with the naming convention *```lecture_<number>.pptx```*. 



#### How to update HTML

Then go to ~line 90 in the ```index.html``` file and find the right lecture number, then uncomment it and move the comment down one lecture. For example if we are on lecture 4 and are going into lecture 5 in winter 2020 it would look like this:



**Before**

```html
...
<tr>
    <td>4
    </td>
    <td>Basic classes and arrays</td>
    <td><a href="assets/winter_2020/lecture_4.pptx">Download slides</a></td>
</tr>

<!--<tr>
    <td>5
    </td>
    <td>For and While loops</td>
    <td><a href="assets/winter_2020/lecture_5.pptx">Download slides</a></td>
</tr>

<tr>
    <td>6
    </td>
    <td>Functions</td>
    <td><a href="assets/winter_2020/lecture_6.pptx">Download Slides</a></td>
</tr>-->
```



**After**

```html
...
<tr>
    <td>4
    </td>
    <td>Basic classes and arrays</td>
    <td><a href="assets/winter_2020/lecture_4.pptx">Download slides</a></td>
</tr>

<tr>
    <td>5
    </td>
    <td>For and While loops</td>
    <td><a href="assets/winter_2020/lecture_5.pptx">Download slides</a></td>
</tr>

<!--<tr>
    <td>6
    </td>
    <td>Functions</td>
    <td><a href="assets/winter_2020/lecture_6.pptx">Download Slides</a></td>
</tr>-->
```

