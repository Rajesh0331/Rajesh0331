super over league

html 

<!DOCTYPE html>
<html lang="en">
  <head>
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;1,100;1,300;1,400;1,500;1,700&display=swap"
      rel="stylesheet"
    />
    <link rel="stylesheet" href="index.css" />
    <script src="https://unpkg.com/react@17.0.0/umd/react.development.js"></script>
    <script src="https://unpkg.com/react-dom@17.0.0/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/@babel/standalone@7.12.4/babel.js"></script>
  </head>
  <body>
    <div id="root"></div>
    <script type="text/babel" src="./index.js"></script>
  </body>
</html>


js

const element = (
<div className="container">
    <h1>Super Over League</h1>
    <div>
        <img src="https://assets.ccbp.in/frontend/react-js/rcb-img.png" />
         <img src="https://assets.ccbp.in/frontend/react-js/csk-img.png" />
    </div>
</div>
);

ReactDOM.render(element, document.getElementById('root'));

css

*{
    box-sizing: border-box;
    margin: 0;
}
.container{
    background-color: #0f172a;
    color: #f8fafc;
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}
img{
    width: 150px;
}
h1{
    margin-bottom:20px ;
    font-size: 25px;
}
@media (min-width:"768px"){
    img{
    width: 300px;
}
h1{
    
    font-size: 30px;
}
}
