# QR-CODE
My first project from Front-end mentor.

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    
    <link rel="stylesheet" href="mentor.css" />
    <style>
    *{
  padding: 0;
  margin: 0;
  box-sizing: border-box;

}
main{
  align-items: center;
  height: 100vh;
width: 100%;
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
background-color: hsl(220, 67%, 88%);
}


main div img{
width: 200px;
border-radius: 5%;
border: none;
}
main div{
  width: 225px;
  height: 357px;
  align-items: center;
  padding-top: 10px;
  background-color: white;
  border-radius: 5%;
}
main div h3{
  font-size: 16px;
  width: 200px;
margin-left: 12px;
  font-family: Arial, Helvetica, sans-serif;
margin-top: 15px;
line-height: 20px;
margin-bottom: 10px;
text-align: center;
}
main div p{
  color: gray;
  font-size: 12px;
  width: 200px;
  line-height: 16px;
  margin-left: 12px;
  font-family: Arial, Helvetica, sans-serif;
}</style>
  </head>
  <body>
    <main>
      <div>
        <img src="images/image-qr-code.png" alt="" />
        <h3>Improve your front-end skills by building projects</h3>
        <p>
          Scan the QR code to visit Frontend Mentor and take your coding skills
          to the next level!
        </p>
      </div>
    </main>
  </body>
</html>

