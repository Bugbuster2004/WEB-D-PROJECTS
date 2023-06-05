# WEB-D-PROJECTS
Creating my Web-D projects

created a gym website landing page using HTML and CSS
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <title>Fitness</title>

</head>
<link rel="stylesheet" href="CSS/style.css">
<style>
    body {
        color: aliceblue;
        margin: 0px;
        padding: 0px;
        /* background: url('IMAGE/bg.jpg'); */
        background: url('IMAGE/bg.jpg ');
    }

    .left {
        /* border: 2px solid red; */
        display: inline-block;
        position: absolute;
        left: 10px;
        top: 1px;

    }

    .mid {
        /* border: 2px solid orange; */
        display: block;
        margin: auto;
        width: 46%;


    }

    .right {
        /* border: 2px solid greenyellow; */
        display: inline-block;
        position: absolute;
        right: 23px;
        top: 17px;

    }

    .navbar ul {
        /* border: 2px solid green; */
        padding: 2px 3px;
        margin: 2px 264px width 46%;
    }

    .navbar li {
        /* border: 2px solid purple; */
        padding: 4px 3px;
        display: inline-block;
        text-decoration: none;
        margin: 2px 32px;
    }

    .navbar li a {
        /* border: 2px solid orange; */
        text-decoration: none;
        color: aliceblue;
        padding: 23px 5pxpx;

    }

    img {
        width: 150px;
        margin: -15px 13px;


    }

    .navbar li a:hover,
    .navbar li a.active {
        text-decoration: underline;
        background-color: rgb(69, 62, 54);
    }

    .left div {
        text-align: center;
        margin: 1px;
    }

    .btn {
        margin: 2px 3px;
        padding: 4px 20px;
        border: 2px solid grey;
        border-radius: 10px;
        cursor: pointer;
    }

    .container {
        margin: 94px 664px;
        padding: 64px 28px;
        border: 2px solid white;
        width: 36%;
        border-radius: 20px;

    }
    .form-action{
        margin: 5px 8px;
        padding:4px 2px;
        text-align: center;
    }
    .form-action input{
        text-align: center;
    }
    .container button{
        display: block;
        width: 120px;
        margin: auto;
    }
</style>

<body>
    <header>
        <div class="left">
            <img src='IMAGE/gym.png' alt="">
            <div>Bansal Fitness</div>

        </div>
        <div class="mid">
            <nav class="navbar">
                <ul>
                    <li><a href="#" class="active">Home</a></li>
                    <li><a href="#">About</a></li>
                    <li><a href="#">Fitness Calculator</a></li>
                    <li><a href="#">Contact Us</a></li>


                </ul>
            </nav>

        </div>
        <div class="right">
            <button class="btn">Call Us</button><button class="btn">Email Us</button>


        </div>

    </header>
    <div class="container">
        <form action="noaction.php">
            <div class="form-action">
                  <h1>JOIN THE CBUM WORKOUT!!</h1>
                    <input type="text" name="" placeholder="Enter your Name">
                  
                  </div>
                  <div class="form-action">

                      <input type="text" name="" placeholder="Enter Age">
                  </div>
                  <div class="form-action">

                      <input type="text" name="" placeholder="Enter Contact">
                  </div>
                  <div class="form-action">

                      <input type="text" name="" placeholder="Enter Email">
                  </div>
                <button class="btn">Submit Now</button>
            
        </form>
    </div>
</body>

</html>
