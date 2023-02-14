# Day 2

Date: 14/02/2023

<br>

## Objective 

- Post on Project Team - First Discussion Forum
- Finish PERCIPIO - Skills-Based Learning Web Design Module

<br>

## Web Design

### Web Design Basics

#### Identify Purpose and Audience

Think about three questions:

- **What is the purpose of the website?**

- **Who is the site targeting?** - Could influence on website design (Type of navigation, colour choice etc. Eg. Elders have difficulties in controlling the mouse, so maybe design the website button or text larger)
- **What is the expected age range?** - Kids/Teens/Adults/Elderly

Website types could be:

- E-commerce
- E-portfolio
- Blog (Enable communications between users, comment function etc.)
- Presence Only (Introduce the company, provide links to contact either by phone or email)
- News
- Forums
- Charity
- Content only
- Classified ads
- Dating 
- Gallery
- Wiki (What I Know Is)
- ....

<br>

#### Identify Business Requirements

- **What are the business requirements for your site?** --> Determines the front-end and back-end design decisions.
  - Eg. E-commerce site. Require end-user authentication process/Add items to cart and more.
  - Blogs site. Requires the ability to post articles/Make comments and more.

<br>

#### Identify Back-end Considerations

- **Identify the data required for your site**.
  - Eg. Product information/Customer contact information/Images and more.
- **Determine the frequency of updates**
  - Change every month/week/minute?
  - So we can decide what type of back-end system we need to support our site.
- **Choose a data repository**
  - The volume of data expected. Eg Excel stylesheet for small data needs or a relational database for a large amount of data.
- **Back-end consists of a server-side language and database, need to choose the appropriate one**.
  - Eg. PHP, Ruby, Python etc.
  - Connects to database: MySQL, SQL, Access etc.
  - Capture and store statistics about the visitor to our site. (Where is the most traffic coming from?)
  - Customer subscriptions? and more.

<br>

#### Designing Storyboards

Spend time designing storyboards, and planning out the site's look and feel. Could save time on rework later.

**The components of a storyboard?**

- The storyboard is a graphic organizer.  
- First, **create an overall web page template** (By using pencil and paper or using the computer)
- Organize the pages into a **site hierarchy diagram** (Describe the navigation of the site)

*Web page template example*

![image-20230214151928767](https://raw.githubusercontent.com/JinchuanL/PicGoStorage/master/image-20230214151928767.png)

<br>

#### Examining Page Layout

- **Create a prototype** of the site using the storyboard as the basis of the design
- **Save time on rework** later **if the site doesn't meet the business requirements**

<br>

#### Exploring Color and Font

- The number one rule is **consistency**. --> Otherwise, the website will look messy, with too many different colours and contrast. Once the colour scheme and font choices have been made, use the same value for all pages.
- **Avoid red text on a blue background and vice-versa**. (Ugly, human eyes can't focus on certain shades of red and blue at the same time)
- **Use good contrast between text colour and page background to catch the reader's attention**. (Use a very light colour for the background and dark colours for the text. Use **colour wheel**) 
- **Have a good amount of white space on a page** (Letting user rest their eyes)

<br>

#### Considering Devices

- **Use emulator**. (Eg. iPhone, iPad, Android, Tablet and more)

- **Different browser**. (Eg. IE, Chrome, Edge, Firefox and more)

- **Different systems**. (Eg. MacOX, Windows, Linux, iOS)

<br>

#### Examining the Software Development Life Cycle

**Software Development Life Cycle (SDLC)**

- **Analysis** (Business requirements obtained.)
- **Design** (Brainstorm, choose the best design)
- **Code** (Front-end and back-end)
- **Test** (Someone other than the one who codes the program, allow testing to be unbiased.)
- **Implementation** (Made available to users)

This is a cycle which means all these are continuing processes of always trying to improve the website/application by analysing any future modifications that can make the application better.

<br>

#### Perform Testing

Preventing error happens. (Eg. 404 page not found and more)

Testing site performance (Eg. Response time, image loading, data retrieving from the database, information capsulation and more)

<br>

#### Examining Testing Tools

Testing sites in different devices - Emulator

Validate your code - World Wide Web Consortium/W3C (https://validator.w3.org) or IDE-embedded testing tools

<br>

#### Examining HTML5 Standards

<br>

### Summary

What type of site is used when a company has services to sell, such as a nursing home or landscaping business, and want to have their name available and searchable on the Internet?

- Presence Only

What type of site would likely need an end-user authentication process?

- E-commerce

What are examples of server-side code?

- Ruby
- PHP

What is the home page of a web site also referred to?

- Landing page

What are the key components that most web sites contain?

- A title or banner
- Navigation area
- Main body

What is the most common example of text with adornment?

- Times New Roman

What is the most common difference between web sites viewed in a browser and on a mobile device?

- Sections are vertical rather than horizontal

What is used to illustrate the flow of an application, also known as SDLC?

- Software Development Life Cycle

What type of testing is done to prevent errors and determine responsiveness?

- Performance testing

What can be identified when using tools for functionality testing?

- Slow pages
- Broken links
- Unused pages

What elements are new to HTML5?

- Nav
- Header

<br>

### Designing & Building a Basic Web Page

#### Creating Basic Web Pages

\<!DOCTYPE html>

<br>

#### Formatting with Tags

```html
<!-- Formatting information on the page -->
<h1>This is the largest heading Tag</h1>
<h2>This is an H2 Tag</h2>
<h3>This is an H3 Tag</h3>
<h4>This is an H4 Tag</h4>
<h5>This is an H5 Tag</h5>
<h6>This is an H6 Tag</h6>
<p>This is a paragraph</p>
<hr> <!-- This is a horizontal line -->
```

<br>

#### Using styles

```html
<!-- We can use RGB values represented in a hexadecimal notation -->
<!-- This indicated how much red, green and blue (RGB) -->
<!-- E6 for red, E6 for green and E6 for blue, this is a shade of grey -->
<!-- If all Fs is white. All 0s is the absence of color/black -->
<!-- Change the background color of the page to light grey, all h tags font change to comic sans ms-->
<body style="background-color: #E6E6E6; font-family:comic sans ms">
<!-- Change the text color of the headings to the first six colors of the rainbow -->
<!-- Red, Orange, Yellow, Green, Blue, Indigo-->
<h1 style="color:red">This is the largest heading Tag</h1>
<h2 style="color:Orange">This is an H2 Tag</h2>
<h3 style="color:yellow">This is an H3 Tag</h3>
<h4 style="color:Green">This is an H4 Tag</h4>
<h5 style="color:blue">This is an H5 Tag</h5>
<h6 style="color:indigo">This is an H6 Tag</h6>
<!-- Change the weight of the line to be thicker and color to Green -->  
<hr style="border: 5px solid Green;">
<!-- Change the text to be centered with a verdana font -->  
<p style="text-align:center; font-family:verdana;">This is a paragraph</p>
<!-- Change to orangered, verdana and 200% larger than normal -->  
<p style="color:OrangeRed; font-family:verdana; font-size:200%">This is a paragraph</p>  
</body>
```

<br>

#### Formatting Text

```html
<b>Bold</b>
<i>Italic</i>
<strong>Strong</strong>
<em>Em</em>
<br/>
<small>Small</small>
<mark>Mark</mark>
<del>Deleted</del>
<ins>Insert</ins>
<sub>Subscript</sub>
<sup>Superscript</sup>
```

<br>

#### Creating Links

```html
<!-- Three tags can be used as links <a></a> or <area> or <link> -->
<!-- a shorts for Anchor Tag -->
<!-- Below use relative address because Home.html and About.html are in the same folder -->
<!-- URL such as www.northglenn-fitness.com is absolute reference --> 
<a href="Home.html">Home</a> | <a href="About.html" target="_blank">About us</a>
```

<br>

#### Adding Images

```html
<!-- It is better to use a graphics editor to resize the image before adding it to the site-->
<!-- It is always a good practice to specify the alternative text value, width and height of your image -->
<!-- If width and height are not specified, the page will flicker while the image loads -->
<img src="text.png" alt="This is a text image" width="400" height="242" />
<!-- There are three main types of images can be displayed by browsers -->
<!-- Photograph .jpg stands for Joint Photographic Group -->
<!-- .png stands for Portable Network Graphics -->
<!-- .gif stands for Graphical Interchange Format -->
<!-- .png and .gif are used more for graphic designs -->

<!-- Even if this img is setting before the paragrahph text, it will still be located at the right part of the page, because we set style flaot to be right -->
<p><img src="Img2.jpg" width=200 height=134 style="float:right" alt="Image 2"/>Here is xxxx</p>
```

<br>

#### Using Tables

```html
<!-- tr:table row   th:table header    td:table data -->
<table style="border: 1px solid black; width=75%">
  <!-- This is first row -->
  <tr style="background-color:purple; color:white">
    <th>Membership Type</th>
    <th>Monthly Charge</th>
    <th>Yearly Charge</th>
  </tr>
  <!-- This is second row -->
  <tr>
    <td style="padding-left:10px;">Basic (3 visits per week)</td>
    <td style="padding-left:10px;">$10</td>
    <td style="padding-left:10px;">$100</td>
  </tr>
  <!-- This is third row -->
  <tr style="background-color:#E6CCE6;">
    <td style="padding-left:10px;">Premium (Unlimited visits)</td>
    <td style="padding-left:10px;">$20</td>
    <td style="padding-left:10px;">$200</td>
  </tr>
  <!-- This is fourth row -->
  <tr>
    <td style="padding-left:10px;">Premium Plus (Unlimited visits plus use of tanning beds)</td>
    <td style="padding-left:10px;">$25</td>
    <td style="padding-left:10px;">$250</td>
  </tr>
</table>
```

<br>

#### Working with Lists

```html
<!-- ul:unordered list   li:line item -->
<h2>List:</h2>
<ul>
  <li>Item1</li>
  <li>Item2</li>
  <li>Item3</li>
  	<ul>
      <li>Nest Item1</li>
      <li>Nest Item2</li>
  	</ul>
</ul>
<!-- List: -->
<!-- • Item1 -->
<!-- • Item2 -->
<!-- • Item3 -->
<!--     ○ Nest Item1 -->
<!--     ○ Nest Item2 -->

<!-- ol:ordered list -->
<!-- Having type can be set to English letter, romman number, by default is numbers -->
<!-- aside tag show up on the right hand side -->
<aside style="position:absolute; right:50px; width:340px; border:3px solid purple; padding: 10px;">
  <h3>How to Sign up:</h3>
  <ol>
    <li>Stop by any one of</li>
    <li>Fill out a form</li>
    <li>Come in for free</li>
	</ol>
</aside>

<!-- Another type of list called Description List -->
<!-- Allows to add terms and definitions -->
<!-- dl:description list   dt:define the term   dd:define the definition-->
<dl>
  <dt></dt>
  <dd></dd>
</dl>
```

<br>

#### Examining Web Site Layout

Create a style that can adapt when the page is resized without losing content to show the site is responsive. 

Use the **viewport feature in HTML5** to achieve this.

```html
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
      img {
        max-width:100%;
        height:auto;
      }
    </style>
  </head>
</html>
```

<br>

#### Exploring Responsive Web Design

- **Responsive Web Design (RWD)**
- Page can be delivered in variable sizes
- RWD is a must for tablets and mobile devices (because nowadays more and more mobile devices)
- Adapts the viewing environment by using **fluid styling**
- **HTML5** adds semantic elements for the page header. section, article, footer, etc.
- Combine these elements with **CSS3** (Cascading Style Sheets) to handle RWD 
- CSS3 provides a new feature called **media queries** that allow developers to check for the device's max screen width and choose the appropriate style sheet based on the device size.

<br>

#### Examining Iframes

Iframe, stands for Inline Frame. Used to display a webpage within another web page.

It uses the src (source tag) to identify the URL to be displayed inside the web page, including the width and height.

Also can use style property to remove the border, change border size or color.

Can be used as a target frame for a link. The target attribute of the link must refer to the name attribute of the iframe.

```html
<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d26520.068596857123!2d-117.95193318437498!3d33.81209180000002!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x80dcd7d12b3b5e6b%3A0x2ef62f8418225cfa!2sDisneyland%20Park!5e0!3m2!1sen!2sau!4v1676363254724!5m2!1sen!2sau" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade">
</iframe>
```

<br>

#### Examining Form Elements

```html
<form>
  First Name:<br>
  <input type="text" name="firstname">
  <br><br>
  Last Name:<br>
  <input type="text" name="lastname">
  Message:<br>
  <textarea name="message" rows="10" cols="100">
  </textarea>
  <input type="submit" value="Send"> <br>
  <input type="reset" value="Reset">
</form>
```

<br>

#### Examining Input Types

```html
<form>
  First Name:<br>
  <input type="text" name="firstname">
  <br><br>
  Last Name:<br>
  <input type="text" name="lastname">
  Gender:<br>
  <input type="radio" name="sex" value="male">Male
  <input type="radio" name="sex" value="female">Female
  Birthday:<br>
  <input type="date" name="birthday">
  Email:<br>
  <input type="email" name="email">
  Numbers:<br>
  <input type="number" name="numbers">
  Message:<br>
  <textarea name="message" rows="10" cols="100">
  </textarea>
  <input type="submit" value="Send"> <br>
  <input type="reset" value="Reset">
</form>
```

<br>

#### Examining Input Attributes

Autocomplete attribute automatically completes values based on what the user has entered before.

Works with the form tag and several individual input types

```html
<input type="date" name="birthday" autofocus=true>

<!-- This is like a dropdown list -->
Choose your membership type:
<input list="membership">
<datalist id="membership">
	<option value="Family Membership">
  <option value="Single Membership">
  <option value="Pool Only">  
</datalist>

<!-- Limit number range from 1-10 -->
Numbers of hours:<br>
<input type="number" name="numbers" min="1" max="10">
```

<br>

#### Exercise: Design and Build a Basic Web Page

```html
<!DOCTYPE html>
<html>
    <head style="font-family: Arial, Helvetica, sans-serif;">
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>My Favorite Things</title>
        <h1>This is about things I LOVED.</h1>
        <hr>
    </head>
    <body style="font-family: Arial, Helvetica, sans-serif;">
        <p>There are couple of things I loved. I divide them into different areas.</p>
        <section>
            <h2>Food</h2>
            <p>For food, I LOVE SPICY. Nothing are more attractive to me than CHILI. SPICY CHILI.</p>
            <h2>Scene</h2>
            <p>For scenes, I love details around my life, around the world. The light and shadow, the sunshine through the leaves and more and more.</p>
            <h2>UNKNOWN THINGS</h2>
            <p>For UNKNOWN THINGS, I would like to say it is the Black Hole. If one day I am going to die, I would like to driving a spaceship heading to the black hole.</p>
            <a href="https://www.nasa.gov/audience/forstudents/k-4/stories/nasa-knows/what-is-a-black-hole-k4.html" target="_blank">Black hole</a>
        </section>
        <hr>
    </body>
    <footer style="text-align: center; font-family: Arial, Helvetica, sans-serif;">Copyright &copy; 2023 Andy. All rights reserved.</footer>
</html>
```

