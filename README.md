<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://getbootstrap.com/docs/5.2/assets/css/docs.css" rel="stylesheet">
    <link href="facebook.css"type="text/css"rel="stylesheet">
    <title>fb</title>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/js/bootstrap.bundle.min.js"></script>
    <script src='https://kit.fontawesome.com/a076d05399.js' crossorigin='anonymous'></script>
    
</head>
<body>
   <div class="container">
        <div class="header" style="border: outset">
            <div class="logo">
                <a class="logo-text"href="facebook.html">facebook</a>
            </div>
        <div class="login">
            <form action="get">
                <table class="login-control"></table>
                <tr>
                <td><input class="in" type="text" placeholder="Email or phone"></td>
                <td><input class="in" type="text" placeholder="Password"></td>
                <input class="sub-btn" type="submit" value="log in">
                </tr>  
                <a class="forgot" href="forgot.html" >Forgetten account?</a>
        
            </form>
        </div>
        <div class="main-body">
            <section>
               <img class="img"src="https://scontent.fccj1-1.fna.fbcdn.net/v/t39.30808-6/311978652_10161713091011729_8457832338774311713_n.png?_nc_cat=1&ccb=1-7&_nc_sid=e3f864&_nc_ohc=cz7Ig0TCuIcAX9YtY7h&_nc_ht=scontent.fccj1-1.fna&oh=00_AT_Uyc3Q4tVtAh_W9oZ0fLZuGcY7SVoe4xH-NMQwKvgC9g&oe=635CEA54" alt="" >
            </section>
            <div class="top">
                <img class="fb" src="https://scontent.fccj1-1.fna.fbcdn.net/v/t1.6435-9/58978526_10158354585751729_7411073224387067904_n.png?_nc_cat=1&ccb=1-7&_nc_sid=09cbfe&_nc_ohc=8gOFKlZ8d0cAX_G1LBM&_nc_ht=scontent.fccj1-1.fna&oh=00_AT-rnq6z3ZreVyyu_vmSLK3Aw4pZGpRcOYhIQ3k-KYaLsg&oe=637E79D5">
                <h3 style="padding-left: 400px; padding-top: 30px;"><b>Facebook</b></h3>
                <p style="padding-left: 400px;">@facebook  · Internet company</p>
                <table class="ftable">
                    <tr>
                        
                        <td><button id="sendmsg"><i class="fab fa-facebook-messenger"></i>Send Message</button></td>
                    </tr>
                    <tr>
                    <td ><p id="text">Hi! Please let us know how we can help.</p></td>
                    </tr>
                </table>
                <hr>
            </div>
            <nav class="navbar navbar-expand-lg navbar-dark bg-light">
                  <div class="container-fluid">
                      
                    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarExternalContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                      <span class="navbar-toggler-icon"></span>
                    </button>
                    <div class="collapse navbar-collapse" id="navbarExternalContent">
                      <ul class="nav nav-pills flex-column flex-sm-row">
                        <li class="nav-item">
                          <a class="nav-link " aria-current="page"  exact activeClassName="underline" href="#">Home</a>
                        </li>
                        <li class="nav-item">
                          <a class="nav-link" href="#">About</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Photos</a>
                          </li>
                          <li class="nav-item">
                            <a class="nav-link" href="#">Videos</a>
                          </li>
                        <li class="nav-item dropdown">
                          <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                            more
                          </a>
                          <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                            <li><a class="dropdown-item" href="#">Event</a></li>
                            <li><a class="dropdown-item" href="#">Live</a></li>
                            <li><a class="dropdown-item" href="#">Community</a></li>
                            <li><a class="dropdown-item" href="#">Group</a></li>
                          </ul>
                        </li>
                        <div class="dropdown">
                          <button onclick="myFunction()" class="dropbtn">...</button>
                          <div id="myDropdown" class="dropdown-content">
                            <a href="#"><i class="fas fa-share"></i>Share</a>
                            <a href="#"><i class="fas fa-chart-pie"></i>Block Page</a>
                            <a href="#"><i class="fas fa-globe-asia"></i>Switch Region</a>
                          </div>
                        </div>
                    </div>
                  </div>
            </nav>
        </div>
        
            <div class="card-deck" style="background-color:rgb(215, 211, 211) ">
            <div class="card col-sm-3">
            
              <img src="Facebook.png"alt="Avatar" style="width:100% ;"><br>
              <div col>&nbsp;</div>
              <img src="Facebook.png"alt="Avatar" style="width:100% ;">
            </div>
            </div>
        <div class="footer">
          <h1 id="htext"><b>See more of Facebook on Facebook</b></h1>
          <table style="margin-left:500px ;">
            <td><button  class="loginlast"href="login.html">log in</button></td>
            <td>or</td>
            <td><a href="createfb.html"><button class="create">create new account</button></a></td>
          </table>
        </div>
            


        </div>
      </div>
        
   </div>
   <script>
    function myFunction() {
  document.getElementById("myDropdown").classList.toggle("show");
}

// Close the dropdown menu if the user clicks outside of it
window.onclick = function(event) {
  if (!event.target.matches('.dropbtn')) {
    var dropdowns = document.getElementsByClassName("dropdown-content");
    var i;
    for (i = 0; i < dropdowns.length; i++) {
      var openDropdown = dropdowns[i];
      if (openDropdown.classList.contains('show')) {
        openDropdown.classList.remove('show');
      }
    }
  }
}
   </script>
</body>
</html>
