<!DOCTYPE html>
<html>
    <head>
        <title>Login</title>
        <link rel="Stylesheet"
        href="Index.css">
        </style>
    </head>
    <body>
        <div class="center">
        <div class="container">
            
            <form action="login" method="post">
                <h1><span style="color: green;">Login</span></h1>
            <label for="Fname">
                <b>First Name</b>
                            </label>
                            <input type="text"
                placeholder="Enter first name"
                name="First Name" id="First name" required>
                            <label for="lName">
                <b>Last Name</b></label>
                                <input type="text"
                placeholder="Enter Last name"
                name="Last Name" id="Last name" required>
                <label for="Uname">
<b>Username</b></label>
                <input type="text" placeholder="Enter Username"
                name="Uname" required>
                <label for="psw">
<b>password</b> 
                <input type="password"
placeholder="Enter password"
name="psw"></label>
                    <label for="Email">
<b>Email</b></label>
                    <input type="text" placeholder="Enter email address"
                     name="Email" required>
                    <button type="submit">Login</button>
                    <label>
                        <input type="checkbox"
                        name="remember">Remember me
                    </label>
                    <button type="reset"
                    class="cancelbtn">Cancel</button>
                <p>Sign up <a href="Register.html">Don't have an account?</a></p>
                </form>
            </div>
        </div>
    </body>
</html>
