body{
    font-family: Robots;
    background-color: chocolate;
    display: flex;
    align-items: center;
    justify-content: center;
}    

.login{
    background-color: #0b132b;
    width: 400px;
    color: #f8f9fa;
    padding: 40px;
    box-shadow: 10px 10px 25px #000000;
    text-align: center;
}

.login input{
    display: block;
    margin: 20px auto; 
    text-align: center;
    background: none;
    padding: 12px;
    font-size: 15px;
    border-radius: 22px;
    outline: none;
    color: #f8f9fa;
}

.login input[type="text"], .login input[type="password"]{
    border: 2px solid #3498bd;
    width: 220px;
}

.login input[type="submit"]{
    width: 150px;
    border: 2px solid #2ecc71;
    cursor: pointer;
}

.login input[type="text"]:focus, .login input[type="password"]:focus{
    border-color: #2ecc71;
    width: 280px;
    transition: 0.5s;
}

.login input[type="submit"]:hover{
    background-color: #2ecc71;
    transition: 0.5s;
}  
