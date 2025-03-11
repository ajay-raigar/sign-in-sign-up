<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign up</title>
    <link rel="stylesheet" href="style.css">
    <style>
      * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    height: auto;
    width: 100%;
    background-color: #f8f8f8;
}

.box {
    max-width: 1100px;
    margin: auto;
    display: flex;
    background-color: white;
    box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
    margin-top: 15px;
    border-radius: 10px;
    overflow: hidden;
}

.container {
    background-color: #333;
    height: auto;
    width: 100%;
    text-align: center;
}

.container img {
    height: 50px;
    width: 50px;
    margin: 10px auto;
}
.text {
    height: 420px;
    text-align: center;
    flex: 1;
    width: 50%;
    background: linear-gradient(to right, #ff416c, #ff4b2b);
}

.text h1 {
    font-size: 2rem;
    margin-top: 15px;
    margin-bottom: 5px;
    color: white;
}

.text p {
    font-size: 1.5rem;
    margin: 20px;
    color: white;
}

.text button {
    padding: 5px;
    width: 035;
    border-radius: 10px;
    border: 2px solid white;
    background-color: transparent;
    font-size: 1rem;
    color: white;
    display: block;
    margin: 10px auto;
}

.text button a {
    color: white;
    text-decoration: none;
    font-size: 1rem;
}

.text button a:hover {
    color: white;
    text-decoration: underline;
}

.form {
    flex: 1;
    width: 50%;
    text-align: center;
    padding: 40px;
}

.form h1 {
    font-size: 2rem;
    margin-bottom: 20px;
    color: blue;
}

.form input {
    width: 80%;
    padding: 10px;
    margin: 10px 0;
    border-radius: 10px;
    border: 1px solid #ccc;
    font-size: 1rem;
}

.form button {
    padding: 10px;
    width: 20%;
    border-radius: 10px;
    border: none;
    background-color: #e74c3c;
    color: whitesmoke;
    font-size: 1rem;
    margin-top: 10px;
}

.form button:hover {
    background-color: #c0392b;
}

@media(max-width:1024px){
    .container img{
        text-align: center;
    }
 
    .logo p{
        margin-left:50px;
        margin-top: 10px;
    }
    .first p{
        margin: 10px;
    }
    
}

@media (max-width: 768px) {

    .container img {
        text-align: center;
    }

    .box {
        flex-direction: column;
        width: 90%;
    }

    .text {
        width: 100%;
        text-align: center;
    }

    .form {
        width: 100%;
    }

    .form button {
        width: 100%;
    }
    

}

@media (max-width: 480) {
  

    .container img {
        text-align: center;
    }
   

    .box {
        flex-direction: column;
        width: 90%;
    }

    .text {
        width: 100%;
        text-align: center;
    }

    .form {
        width: 100%;
    }

    .form button {
        width: 100%;
    }

}

    </style>

</head>

<body>
    <div class="container">
        <img src="img/esdc-logo.png" alt="">
    </div>
    <div class="box">
        <div class="text">
            <h1>Sign Up</h1>
            <p>please enter your personal details to sign up</p>
            <img src="img/sign up.png" height="200px" width="200px" alt="">
            <button><a href="sign in .html">Sign in</a> /Sign Up</button>
        </div>
        <div class="form">
            <h1>Sign up </h1>
            <form action="">
                <input type="text" placeholder="Name" required>
                <input type="text" placeholder="E-mail" required>
                <input type="number" placeholder="Number" required>
                <input type="password" placeholder="password" required>
                <button>Submit</button>
            </form>
        </div>
    </div>
   

</body>

</html>
