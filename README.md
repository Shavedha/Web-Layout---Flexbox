# EXPERIMENT 3 -  Create a Web-Layout using FLEXBOX
## AIM
To create a web-layout using flexbox
## ALGORITHM
1. Create a html document.
2. Set the body element to display as a flex container.
3. Style the header, nav, main, and footer elements with desired background colors.
4. Use properties like justify-content, align-items, or flex property.
5. Add styling to elements such as padding, margin, or text alignment.
## PROGRAM
### flexbox.html
```
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" type="text/css" href="flexbox.css">
</head>
<body>
  <header>
    <h1>HEADER SECTION</h1>
  </header>
  <nav>
    <ul>
      <li><a href="#">Element 1</a></li>
      <li><a href="#">Element 2</a></li>
      <li><a href="#">Element 3</a></li>
      <li><a href="#">Element 4</a></li>
    </ul>
  </nav>
  <main>
    <section class="left-section">
      <h2>Left Section</h2>
      <p>Add content.....</p>
    </section>
    <section class="right-section">
      <h2>Right Section</h2>
      <p>Add content.....</p>
    </section>
  </main>
  <footer>
    <p>© 2023 My Website. All rights reserved.</p>
  </footer>
</body>
</html>

```
### flexbox.css
```
body {
    display: flex;
    flex-direction: column;
    min-height: 100vh;
    margin: 0;
  }
  
  header {
    background-color: #1c76dd;
    padding: 20px;
  }
  
  nav {
    background-color: #9cb2fa;
    padding: 10px;
  }
  
  nav ul {
    list-style-type: none;
    display: flex;
    justify-content: space-around;
    margin: 0;
    padding: 0;
  }
  
  nav ul li {
    flex: 1;
    text-align: center;
  }
  
  nav ul li a {
    text-decoration: none;
    color: #000;
  }
  
  main {
    flex: 1;
    display: flex;
    justify-content: space-between;
    background-color: #f0bbc0;
    padding: 20px;
  }
  
  .left-section {
    flex: 1;
    background-color: #e3f39d;
    padding: 10px;
  }
  
  .right-section {
    flex: 1;
    background-color: #63bbcf;
    padding: 10px;
  }
  
  footer {
    background-color: #343a40;
    color: #fff;
    padding: 10px;
    text-align: center;
  }
  
```
## OUTPUT
<img width="960" alt="Screenshot 2023-06-11 205306" src="https://github.com/Shavedha/Web-Layout---Flexbox/assets/93427376/e1b0c422-32d5-427a-9983-b516800085b0">

## RESULT
Thus a web-layout using flexbox is implemented.
