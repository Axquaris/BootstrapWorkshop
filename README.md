# Bootstrap Workshop

This is a workshop for Hack Club showing how to use bootstrap to make a cool portfolio.

Make sure you allready know how to setup a github page and use the cloud9 editor.

## Outline

1. Setup project
2. Go through using bootstrap features
3. Introduce to documentation and w3 schools bootstrap examples
4. Celebrate! 

### Setup
  First make a new project with [cloud9](https://c9.io/). Then make a new file named `index.html`. Add the following code to the file, doing this will set a webpage title and allow us to use bootstrap.
  ```html
  <!DOCTYPE html>
  <html lang="en">
  <head>
    <title>My Portfolio</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
  </head>
  <body>
      
  </body>
  </html>
  ```
  
  
### Adding Bootstrap Elements

#### Jumbotron
  
  First let's add a jumbotron, a nice looking element to act as a header:
  
  ![Image Failed To Load :(](img/jumbotron.png "Jumbotron")


  ```html
  <div class="container">
    <div class="jumbotron">
      <h1>My Portfolio</h1>
      <p>Yay</p>
    </div>
  </div>
  ```
  
  [documentation](http://getbootstrap.com/components/#jumbotron)
  
#### Columns

  ```html
  <div class="row">
    <div class="col-xs-4">
      <h3>About Me</h3>
      <p>bla bla bla</p>
    </div>
    <div class="col-xs-4">
      <h3>My Projects</h3>
      <p>bla bla bla</p>
    </div>
    <div class="col-xs-4">
      <h3>How to Contact Me</h3>
      <p>bla bla bla</p>
    </div>
  </div>
  ```
  You can grab some natural-looking filler text [here](http://www.lipsum.com/)
  
  [documentation](http://getbootstrap.com/css/#grid)
  
#### Styled Images

  ```html
  <img src="images/yourimage.jpg" class="img-thumbnail" width="100%">
  ```
  See more bootstrap image styles [here](http://getbootstrap.com/css/#images)

#### Navbar

  ```html
  <nav class="navbar navbar-default">
    <div class="container-fluid">
      <div class="navbar-header">
        <a class="navbar-brand" href="index.html">Portfolio</a>
      </div>
      <ul class="nav navbar-nav">
        <li class="active"><a href="index.html">Home</a></li>
        <li><a href="#">Page 1</a></li>
        <li><a href="#">Page 2</a></li>
        <li><a href="#">Page 3</a></li>
      </ul>
    </div>
  </nav>
  ```
##### Adding links
  
  ```html
  <ul class="nav navbar-nav">
    <li class="active"><a href="index.html">Home</a></li>
    <li><a href="projects.html">My Cool Projects</a></li>
    <li><a href="https://github.com/Axquaris/BootstrapWorkshop/commits/master">Github</a></li>
    <li><a href="https://www.linkedin.com/">Linkedin</a></li>
  </ul>
  ```
  
  [documentation](http://getbootstrap.com/components/#navbar)

#### Adding a page
  