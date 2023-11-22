# codsoft_TASK-2-level-1-
Landing page code and output task 2 (level 1)
#HTML CODE
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix India - Watch TV Shows</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
   <div class="nav">
       <img class="logo" src="logo.png" alt="">
       <label for="Language"></label>
       <select name="Language" id="">
           <option value="English">English</option>
           <option value="English">Hindi</option>
       </select>
       <a class="btn" href="#">Sign In</a>
   </div> 
   <div class="content">
       <h1>Unlimited movies, TV <br> shows and more.</h1>
       <h2>Watch anywhere. Cancel anytime.</h2>
       <p>Ready to watch? Enter your email to create or restart your membership.</p>
       <div class="mail">
           <input type="text" placeholder="Email address">
           <a href="#">Get Started</a>
       </div>
   </div>
</body>
</html>

#CSS CODE

body{
  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  background: rgba(0, 0, 0, 0.6) url('image.jpg');
  background-blend-mode: darken;
}

.logo{
  width: 12%;
}

.btn{
  padding: 8px 15px;
  color: #fff;
  background-color: #e50914;
  display: inline-block;
  text-decoration: none;
  cursor: pointer;
}

.nav{
  padding-top: 5px;
  padding-left: 2vw;
  padding-right: 5vw;
  height: 10vh;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

select{
  margin-left: 70%;
  padding: 8px;
}

.content{
  color: #fff;
  position: absolute;
  margin-top: 8%;
  margin-left: 30%;
}

.content h1{
  font-size: 50px;
}

.content h2{
  font-size: 30px;
}

.mail{
  width: 100%;
  height: fit-content;
  align-items: center;
  background-color: #fff;
  display: flex;
  justify-content: space-between;
}

.mail input{
  outline: none;
  border: none;
  padding: 12px 10px;
  size: 1em;
}

.mail a{
  height: fit-content;
  background-color: #e50914;
  color: #fff;
  padding: 18px 12px;
  text-decoration: none;
}
