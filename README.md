body{
           
    background-image:url('23790.jpg');
    background-repeat:no-repeat;
    background-attachment:fixed;
    background-size:100% 100%;
    margin: 0px;
    
    

      }

    
      nav{
  height: 60px;
  width: 1530px;
  background: white;
  padding: 20px;
  position:sticky;
  top: 0;
}
nav ul{
  float: right;
  margin-right: 40px;
}
nav li{
  display: inline-block;
  margin: 0 30px;
  line-height: 50px;

}
nav a{
  font-size: 25px;
  text-decoration: none;
  color: #005E98;
}
nav a :hover{
  border: 4px solid #005E98;
  background-color: #005E98;
  color: white;
  padding: 5px;
  border-radius: 25px;
}
.container{
    height: 620px;
    width: 1500px;
    display: grid;
    grid-template-columns: 150px 150px ;
    grid-template-rows: 150px;
    column-gap: 670px;
    padding: 30px;
}
.item{
    
    height: 500px;
    width: 500px;
}
.item2{
    display: grid;
    padding: 70px;

}
.subitem2{
    
    height: 500px;
    width: 520px;
}
.login-box{
    position: relative;
    width: 450px;
    height: 480px;
    background-color:#005E98;
    border-radius: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
    border: 2px solid rgba(255, 255, 255, .5);

}
h2{
    font-size: 2em;
    color: #fff;
    text-align: center;
}
.input-box{
    width: 310px;
    margin: 30px 0;
    border-bottom: 2px solid #fff;
}
.input-box label{
    position: absolute;
    
    left: 2px;
    transform: translatey(-50%);
    font-size: 1em;
    color: #fff;
    pointer-events: none;
    
}
.input-box input{
    width: 100%;
    height: 50px;
    background: transparent;
    border: none;
    outline: none;
    font-size: 1em;
    color: #fff;
}
.remember-forgot{
    color: #fff;
}
.remember-forgot label input{
    margin-right: 3px;
}
.remember-forgot a {
    color: #fff;
    text-decoration: none;

}
button{
    width: 100%;
    height: 40px;
    background-color: #fff;
    border: none;
    outline: none;
    border-radius: 40px;
    cursor: pointer;
    font-size: 1em;
    color: black;
    font-weight: 500;
}
