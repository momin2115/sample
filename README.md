# sample
sample website
<html>
    <head>
        <title>test</title>
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css">
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
        <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js"></script>
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js"></script>
        <script src="https://use.fontawesome.com/release/v5.0.8/js/all.js"></script>
        <link href='https://fonts.googleapis.com/css?family=Roboto' rel='stylesheet'>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <link rel="stylesheet" href="newstyle.css">
    </head>
    <body>
        <!--navbar section-->
        <nav class="navbar navbar-expand-md navbar-light bg-light ">
            <a class="navbar-brand" href="#">"thinkinglama"</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavDropdown">
              <ul class="nav navbar-nav ml-auto">
                <li class="nav-item active">
                  <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">About</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Services</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Team</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Connect</a>
                </li>
              </ul>
            </div>
        </nav>
        <!--carousel section-->
        <div id="demo" class="carousel slide" data-ride="carousel">
                  <ul class="carousel-indicators">
                  <li data-target="#demo" data-slide-to="0" class="active"></li>
                  <li data-target="#demo" data-slide-to="1"></li>
                  <li data-target="#demo" data-slide-to="2"></li>
                </ul>
 
                <div class="carousel-inner">
                  <div class="carousel-item active">
                    <img src="pic1.jpg" alt="Los Angeles" width="auto" height="auto">
                    <div class="carousel-caption">
                        <h1 class="display-4"> BOOTSTRAP 4 </h1>
                        <h3> Complete website layout </h3>
                        <button type="button" class="btn btn-outline-primary btn-lg">VIEW DEMO</button>
                        <button type="button" class="btn btn-primary btn-lg">Get Started</button>
                    </div>
                  </div>
                  <div class="carousel-item">
                    <img src="pic2.jpg" alt="Chicago" width="auto" height="auto">
                  </div>
                  <div class="carousel-item">
                    <img src="pic3.jpg" alt="New York" width="auto" height="auto">
                  </div>
                </div>
                
               
                <a class="carousel-control-prev" href="#demo" data-slide="prev">
                  <span class="carousel-control-prev-icon"></span>
                </a>
                <a class="carousel-control-next" href="#demo" data-slide="next">
                  <span class="carousel-control-next-icon"></span>
                </a>
              </div>
              
        <!--jumbotron section-->
        <div class=" row jumbotron">
            <div class="col-xs-12 col-sm-12 col-md-9 col-lg-9 col-xl-10">
                <h6>Hi! How are you doing??</h6>
                <p class="lead">This is a jumbotron with a button and a heading.</p>
            </div>
            <div class="col-xs-12 col-sm-12 col-md-3 col-lg-3 col-xl-2">
               <a href="#"><button type="button" class="btn btn-outline-secondary">HELLO</button></a>
            </div>
        </div>
        
        <!--Welcome Section-->
        <div class="container-fluid padding">
            <div class="row text-center padding">
                <div class="col-12">
                    <h1 class="display-4">Welcome to the webpage</h1>
                    <hr>
                </div>
                <div class="col-12">
                    <p class="lead">Welcome to the bootstrap designed page. hope you all like it </p>
                </div>
            </div>
        </div>
        
        <!--three coloumn section-->
        <div class="container-fluid padding">
            <div class="row text-center padding">
                <div class="col-xs-12 col-sm-6 col-md-4 abc">
                    <i class="fas fa-code"></i>
                    <h3>HTML 5</h3>
                    <p> This site is built with the latest html5</p>
                </div>
                <div class="col-xs-12 col-sm-6 col-md-4 abc">
                        <i class="fas fa-bold"></i>
                        <h3>HTML 5</h3>
                        <p> This site is built with the latest html5</p>
                </div>
                <div class="col-xs-12 col-sm-12 col-md-4 abc">
                        <i class="fab fa-css3"></i>
                        <h3>HTML 5</h3>
                        <p> This site is built with the latest html5</p>
                </div>
            </div>
        </div>
        
        <!--two coloumn section-->
        <div class="container fluid padding">
            <div class="row padding">
                <div class="col-xs-12 col-sm-12 col-md-6">
                    Dell is a US multinational computer technology company that develops, sells, repairs, and supports 
                    computers and related products and services. Named after its founder, Michael Dell, the
                    company is one of the largest technological corporations in the world, employing more than
                    145,000 people in the U.S. and around the world.<br>
                    <a href="#"><button type="button" class="btn btn-info mno"> Learn More</button></a>
                </div>
                <div class="col-xs-12 col-sm-12 col-md-6 text-center">
                    <img src="dell laptop.jpg" class="abc">
                </div>
            </div>
        </div>
        
        <!--hidden content-->
        <div class="container-fluid">
            <button class="btn btn-outline-secondary btn-block" type="button" data-toggle="collapse" data-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">
            click for fun
            </button>
            </p>
            <div class="collapse" id="collapseExample">
            <div class="container-fluid padding">
                <div class="row padding">
                    <div class="col-xs-12 col-sm-6 col-md-3 text-center">
                        <img src="Heart-eyes-emoji.jpg" class="emoji">
                    </div>
                    <div class="col-xs-12 col-sm-6 col-md-3 text-center">
                        <img src="Heart-eyes-emoji.jpg" class="emoji">
                    </div>
                    <div class="col-xs-12 col-sm-6 col-md-3 text-center">
                        <img src="Heart-eyes-emoji.jpg" class="emoji">
                    </div>
                    <div class="col-xs-12 col-sm-6 col-md-3 text-center">
                        <img src="Heart-eyes-emoji.jpg" class="emoji">
                    </div>
                </div>
            </div>
        </div>
        
        <!--team profile 3coloumn cards-->

        <h1 class="display-2">"Meet the Team!"</h1>
        <hr>
        <div class="container-fluid padding">
            <div class="row padding">
                <div class="col-sm-12 col-md-4">
                        <h2>ABC</h2>
                        <p>Architect and Engineer</p>
                        <div class="card">
                          <img class="card-img-top" src="saluteemoji.jpg" alt="Card image" style="width:100%">
                          <div class="card-body">
                            <h4 class="card-title">ABC</h4>
                            <p class="card-text">Some example text some example text. ABC is an architect and engineer</p>
                            <a href="#" class="btn btn-primary">See Profile</a>
                          </div>
                        </div>
                </div>
                <div class="col-sm-12 col-md-4">
                        <h2>ABC</h2>
                        <p>Architect and Engineer</p>
                        <div class="card">
                          <img class="card-img-top" src="saluteemoji.jpg" alt="Card image" style="width:100%">
                          <div class="card-body">
                            <h4 class="card-title">ABC</h4>
                            <p class="card-text">Some example text some example text. ABC is an architect and engineer</p>
                            <a href="#" class="btn btn-primary">See Profile</a>
                          </div>
                        </div>
                </div>
                <div class="col-sm-12 col-md-4">
                        <h2>ABC</h2>
                        <p>Architect and Engineer</p>
                        <div class="card">
                          <img class="card-img-top" src="saluteemoji.jpg" alt="Card image" style="width:100%">
                          <div class="card-body">
                            <h4 class="card-title">ABC</h4>
                            <p class="card-text">Some example text some example text. ABC is an architect and engineer</p>
                            <a href="#" class="btn btn-primary">See Profile</a>
                          </div>
                        </div>
                </div>
            </div>
        </div>
        
        <!--2 coloumn section-->
        <div class="container fluid padding">
                <div class="row padding">
                    <div class="col-xs-12 col-sm-12 col-md-6">
                        <h1> Our philosophy</h1>
                        <hr>
                            <p class="lead">he general appearance of a place; the aggregate of features that give character to a landscape.
                            hangings, draperies, structures, etc., used on a stage to represent a locale or furnish decorative background.
                                </p>
                    </div>
                    <div class="col-xs-12 col-sm-12 col-md-6 text-center">
                        <img src="pic2.jpg" class="abc" width="350px" height="auto">
                    </div>
                </div>
            </div>
            <hr>
            
        <!--social media icons-->
            <h1 class="display-4 text-center">Connect</h1>
            <center>
            <a href="https://www.facebook.com" class="fa fa-facebook"></a>
            <a href="https://www.twitter.com" class="fa fa-twitter"></a>
            <a href="https://www.instagram.com" class="fa fa-instagram"></a>
            <a href="https://www.linkedin.com" class="fa fa-linkedin"></a>
            </center>
            
        <!--footer 3column-->
        <footer class="footer bg-dark">
            <div class="container-fluid padding">
                <div class="row padding">
                    <div class="col-xs-12 col-sm-12 col-md-4 mno text-center">
                        <a class="navbar-brand" href="#">"thinkinglama"</a>
                        <hr>
                        555-555-5555<br>
                        emailid@email.com<br>
                        address...address...address<br>
                        city......state....country
                    </div>
                    <div class="col-xs-12 col-sm-12 col-md-4 mno text-center ">
                        <hr>
                        <h3> Our Services </h3>
                        <hr>
                        Monday: 9 a.m - 9p.m <br>
                        Saturday: 9 a.m - 6 p.m <br>
                        Sunday Closed.       
                    </div>
                    <div class="col-xs-12 col-sm-12 col-md-4 mno text-center">
                        <hr>
                        <h3> Service Area </h3>
                        <hr>
                        Kolkata<br>
                        Chennai<br>
                        Bangalore<br>
                        Mumbai       
                    </div>
                </div>
                <hr>
                <h3 class="text-center">"thinkinglama"</h3>
            </div>
        </footer>
    </body>
</html>
