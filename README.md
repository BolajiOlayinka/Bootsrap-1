# Bootstrap-1
i created a bootstrap carousel, the nav bar is static, it does not move along with the page, i grided the page such that it is responsive on medium size, small and extra small devices
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css"  rel="stylesheet">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>
    <title>Bootstrap site </title>

<style>

</style>
    
    
</head>
<body>

    <nav class="navbar navbar-inverse navbar-fixed-top">
            <div class="container-fluid">
              <div class="navbar-header">
                    <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
                            <span class="icon-bar"></span>
                            <span class="icon-bar"></span>
                            <span class="icon-bar"></span> 
                          </button>
                <div class="collapse navbar-collapse" id="myNavbar">
                <a class="navbar-brand" href="#">WebSite Name</a>
              
              
              <ul class="nav navbar-nav">
                <li class="active"><a href="#">Home</a></li>
                <li><a href="#">Carousel</a></li>
                <li><a href="#">Home</a></li>
                <li><a href="#">Links</a></li>
                <li class="disabled"><a href="#">Disabled</a></li>
              </ul>
            
            <form class="navbar-form navbar-left" action="/action_page.php">
                <div class="form-group">
                  <input type="text" class="form-control" placeholder="Search">
                </div>
                
                <button type="submit" class="btn btn-default">Submit</button>
            
              </form>
                </div>
                </div>
              
            </div>
          </nav>

          <div id= "my carousel" class="carousel slides" data-ride="carousel">
            
                <ol class="carousel-indicators">
                    <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
                    <li data-target="#myCarousel" data-slide-to="1" ></li>
                    <li data-target="#myCarousel" data-slide-to="2" ></li>
                </ol>
                <!--Wrapper-->
            <div class="carousel-inner">
                <div class="item active"> <img src="/media 1/1.jpg " alt="Headline" width="1350" height="500"> <div class="carousel-caption">
                    <h1>One for good measure</h1>
                </div></div>
                <div class="item"><img src="/media 1/2.jpeg" alt="com 2" width="1350" height="500"><div class="carousel-caption">
                    <h1>Examples Headlines</h1>
                </div></div>
                <div class="item"><img src="/media 1/3.jpg" alt="com 3" width="1350" heght="500"><div class="carousel-caption">
                    <h1>Another Example</h1>
                </div></div>
            </div>

    
            <a class="left-carousel-control" href="#myCarousel"role="button" data-slide="prev">
                <span class="glyphicon glyphicon-chevron-left"></span>
                <span class="sr-only">Previous</span>
            </a>
            <a class="right carousel-control" href="#myCarousel" data-slide="next">
                <span class="glyphicon-glyphicon-chevron-right"></span>
                <span class="sr-only">Next</span>
            </a>
          
                <div class="container">    
                        <div class="row text-center" >
                            <div class="col-md-4 col-sm-8 col-xs-8">
                                <img src="https://placehold.it/150x80?text=IMAGE" class="img-responsive img-circle" style="width:100%" alt="Image"><br>
                                <h2>Heading</h2><br><p>Donec sed odio dui. Etiam porta sem <br>malesuada
                                    magna mollis euismod. Nullam id<br> dolor id nibh ultricies vehicula ut id elit. Morbi
                                    <br>leo risus, porta ac consectetur ac, vestibulum at eros. Praesent commodo cursus magna.</p><br>
                                    <button type="button" class="btn">View Details >></button>
                            </div>
                            <div class="col-md-4 col-sm-8 col-xs-8"> 
                                <img src="https://placehold.it/150x80?text=IMAGE" class="img-responsive img-circle" style="width:100%" alt="Image"><br>
                                <h2>Heading</h2><br> <p>Duis mollis, est non commodo luctus, nisi erat<br>
                                    porttitor ligula, eget lacinia odio sem nec elit.<br>
                                    Cras mattis consectetur purus sit amet <br>
                                    fermentum. Fusce dapibus, tellus ac cursus<br>
                                    commodo, tortor mauris condimentum nibh.
                                    </p><br><button type="button" class="btn">View Details >></button>
                                    
                            </div>
                            <br>
                            <div class="col-md-4 col-sm-8 col-xs-8"> 
                                    <img src="https://placehold.it/150x80?text=IMAGE" class="img-responsive img-circle" style="width:100% " alt="Image">
                                    <h2>Heading </h2>    <p>Donec sed odio dui. Cras justo odio, dapibus<br>
                                        ac facilisis in, egestas eget quam. Vestibulum <br>
                                        id ligula porta felis euismod semper.<br> Fusce dapibus,
                                        tellus ac cursus commodo, tortor<br>
                                        mauris condimentum nibh, ut fermentum<br> massa justo sit amet risus.
                                        </p><br> <button type="button" class="btn">View Details >></button><br>
                            </div>
                       
                        </div>
                    <br>
                            <div style="background:transparent !important "class="jumbotron">
                                <div class="row">
                                <div class="col-md-7 col col-sm-7 col-xs-7" class="text-justify"> <h1>First featurette<br>heading. <small> it'll blow
                                        <br> your mind.</small></h2> <h3><small> Donec Ullamcorper nulla non metus auctor
                                        fringilla. Vestibulum id lingua<br> porta felis euismod semper. Praesent commodo
                                        cursus magna vel<br> scelerisque nisl  consectur. Fusce diapibus, tellus ac <br>
                                        cursus commodo</small></h3>
                                        </p> </div>
                                    <div class="col-sm-5 col-md-5 col-xs-5 ">
                                            <img src="https://placehold.it/150x80?text=IMAGE" class="img-responsive" width="500px" height="500px" alt="Image"> 
                                    </div>
                                </div>
                            </div>  
                    <br>
                                
                            <div style="background:transparent !important" class="jumbotron">
                                <div class="row">
                                    <div class="col-sm-5 col-md-5 col-xs-5"> <img src="https://placehold.it/150x80?text=IMAGE" class="img-responsive" style="width:100%" alt="Image"> </div>
                                        <div class="col-sm-7 col-md-7-col-xs-7 text-justify text-right">  <h1>Oh yeah, it is that good.<small> see for
                                                 yourself.</small></h1> <h2><small> Donec Ullamcorper nulla non metus auctor
                                                fringilla.<br> Vestibulum id lingua porta felis  euismod semper. Praesent<br> commodo
                                                cursus magna vel scelerisque nisl consectur. <br> Fusce diapibus, tellus ac 
                                                cursus commodo</small></h2>
                                         
                                        </div>
                                </div>
                            </div>
                    <br>

                    <div style="background:transparent !important" class="jumbotron">
                            <div class="row">
                            <div class="col-sm-7 col-sm-7 col-xs-7" class="text-justify"> <h1>And Lastly, this one<br> <small>
                                    Checkmate</small></h2> <h3><small> Donec Ullamcorper nulla non metus auctor
                                    fringilla. Vestibulum id lingua<br> porta felis euismod semper. Praesent commodo
                                    cursus magna vel<br> scelerisque nisl  consectur. Fusce diapibus, tellus ac <br>
                                    cursus commodo</small></h3>
                                    </p> </div>
                                <div class="col-sm-5 col-md-5 col-xs-5">
                                        <img src="https://placehold.it/150x80?text=IMAGE" class="img-responsive" width="500px" height="500px" alt="Image"> 
                                </div>
                            </div>
                        </div>  
                
                            <nav class="navbar navbar-default navbar-bottom">
                                <div class="container-fluid">
                                <div class="navbar-header">
                            <p>Copyright 2015-2017 company, inc<a href="#">Privacy.Terms<Privacy class="Terms"></Privacy></a>
                            <a href class="navbar navbar-right">Back to the top</a></p>
                    
                  </div>
                  
                </div>
                </nav>                       

            </div>

    

                    

    
</body>
</html>
