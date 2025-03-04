# fikryakrm
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>login page</title>
    <link rel="stylesheet" href="style.css">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
</head>
<body>
    <div class="wrapper">
        <form action="">
            <h1>LOGIN</h1>
            <div class="input-box">
                <input type="text" placeholder="username"required>
                <i class='bx bx-user'></i>
            </div>
            <div class="input-box">
                <input type="password" placeholder="password"required>
                <i class='bx bx-lock-alt'></i>
            </div>  
            <div class="ingat-tidak">
                <label><input type="checkbox">
                    ingat saya   
                </label>    
                <a href="#">lupa password?</a>            
            </div>
            <button type="submit" class="btn">Login</button>
            <div class="register">
                <p>
                    tidak punya akun?<a href="#">daftar disini</a>
                </p>
                
            </div>
        </form>
    </div>
</body>
</html>

<css>
* {
    border: none;
    outline: none;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}
body{
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background : url('circle.jpg') no-repeat;
    background-position: center;
    background-size: cover;
}
.wrapper{
    background: transparent;
    color: aliceblue;
    width: 450px;
    border: 2px solid rgba(225, 225, 225, .2);
    backdrop-filter:blur(20px);
    box-shadow: 0 0 10px rgba( 0, 0, 0, .2);
    border-radius: 65px;
    padding: 30px 40px;
}
.wrapper h1{
    font-size: 39px;
    text-align: center;
    color: aliceblue;
}
.wrapper .input-box {
    position: relative;
    width: 100%;
    height: 50px;
    color: aquamarine;
    
}
.input-box input {
    width: 100%;
    height: 100%;
    background: transparent;
    border: none;
    outline: none;
    border: 2px solid color(srgb rgb(57, 56, 56) rgb(46, 46, 46) rgb(49, 49, 50));
    border-radius: 40px;
    font-size: 17px;
    color: white;
    padding: 20px 45px 20px 20px;
}

.input-box input ::placeholder{
color: white;
}
.input-box i{
    position: absolute;
    right: 20px;
    top: 50%;
    transform: translateY(-50%);
    font-size: 20px;
}

.wrapper .ingat-tidak {
    display: flex;
    justify-content: space-between;
    font-size: 15px;
    margin-left: 10px;
}
.ingat-tidak label input {
    accent-color: white;
    margin-right: 4px;
}

.ingat-tidak a {
    color: white;
    text-decoration: none;
    margin-top: 4px;
}
.ingat-tidak a:hover {
    text-decoration: underline;    
}

.wrapper .btn {
    width: 100%;
    height: 50px;
    border: none;
    outline: none;
    border-radius: 40px;
    cursor: pointer;
    font-size: 20px;
    color: rgb(49, 49, 50);
    font-weight: 600;
    margin-top: 15px
    
}

.wrapper .register {
    font-size: 15px;
    text-align: center;
    justify-content: space-between;
    margin: 20px 0 16px;
}

.register p a {
    color: white;
    font-weight: 600;
    text-decoration: none;
}

.register p a:hover {
    text-decoration: underline;

}
</css>

<img>circle.jpg</img>
