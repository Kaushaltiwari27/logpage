![image](https://github.com/Kaushaltiwari27/logpage/assets/153057797/388f6cf6-5cb7-40dd-a949-b8145231d573)
# logpage
html code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" type="text/css" href="style.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">

</head>
<body class="web">
    <div class="container1">
        <div class="container2">
            <div class="container3">
                <div class="right">
                <img src="https://ui-practise.vercel.app/static/images/landingView/logo.png">
                <div class="sidecontent">Say hello to global food and beverage producers and suppliers,all in one place</div>
                </div>
                <div class="rightwrap">
                    <div class="formtitle">
                        Let's get started
                        <br>
                        with a few simple steps</div>
                        <div class="formdata">
                            <div class="inputdiv">
                                <div class="inputWrap">
                                    <div class="text-label">
                                        Email
                                    </div>
                                    <input type="text" class="inputbox">
                                </div>
                                <div class="inputWrap">
                                    <div class="text-label">
                                        FullName
                                    </div>
                                    <input type="text" class="inputbox">
                                </div>
                                <div class="inputWrap">
                                    <div class="text-label">
                                        Password
                                    </div>
                                    <input type="text" class="inputbox">
                                </div>
                            </div>
                            <div class="btnwrap">
                                <div class="btntxt">
                                    Sign up
                                </div>
                            </div>
                            <div class="linkwrap">
                                <div class="designtxt">
                                By siging up, you agree to our
                                    <span>Terms of Service</span>
                                    .
                                </div>
                                <div class="testingdesign">
                                 Already have an account?
                                    <span>Log in</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </div>
    </div>
</body>
</html>



css code
body {
    font-family: sans-serif;
    margin: 0;
    padding: 0;
}

.container {
    max-width: 400px;
    margin: 100px auto;
    padding: 20px;
    background-color: #fff;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.container h2 {
    text-align: center;
    margin-bottom: 20px;
}

form input {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 3px;
    box-sizing: border-box;
}

form button {
    width: 100%;
    padding: 10px;
    background-color: #007bff;
    color: #fff;
    border: none;
    border-radius: 3px;
    cursor: pointer;
}

form button:hover {
    background-color: #0056b3;
}

.form-switch {
    text-align: center;
    margin-top: 15px;
}

.form-switch a {
    color: #007bff;
    text-decoration: none;
}

.form-switch a:hover {
    text-decoration: underline;
}


.web{
    background-image: url(https://ui-practise.vercel.app/static/images/landingView/Background.png);
}
.container1 {
   border: 1px solid rgb(164, 228, 127);
   width: 1160px;
    height: 792px;
    border-radius: 50px;
    align-items: center;
    justify-content: center;
    background-color: white;
    display: flex;
    margin-left: 10%;
}
.container3{
    display: flex;
}
.right{
    background-color: rgb(8, 75, 62);
    padding: 33px 51px;
    border-radius: 50px 0px 0px 50px;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    width: 400px;
    height: 690px;
}
.right img{
    width: 171.48px;
    height: 94.462px;
}
.sidecontent{
    color: rgb(249, 226, 186);
    font-size: 39px;
    font-style: normal;
    font-weight: 500;
    line-height: 45px;
    max-width: 350px;
}
.rightwrap{
    border-radius: 50px;
    background: rgb(255, 255, 255);
    padding: 55px 52px;
    display: flex;
    flex-direction: column;
    gap: 77px;
}
.formtitle{
    color: rgb(35, 35, 35);
    font-size: 36px;
    font-weight: 500;
    line-height: 42px;
    letter-spacing: -0.5px;

}
.formdata{
    display: flex;
    flex-direction: column;
    width: 450px;
    gap: 50px;

}
.text-lable{
    color: rgb(52, 52, 52);
    font-size: 16px;
    font-style: normal;
    font-weight: 550;
    line-height: normal;
}
.inputbox{
    line-height: 24px;
    border-top: none;
    border-right: none;
    border-left: none;
    width: 90%;
    border-bottom: 2px solid black;
    margin-bottom: 10%;
}
.btnwrap{
    width: 450px;
    height: 76px;
    justify-content: center;
    align-items: center;
    border-radius: 20px;
    background: rgb(0, 195, 139);
    cursor: pointer;
}
.btntxt{
    color: rgb(255, 255, 255);
    text-align: center;
    font-size: 20px;
    font-style: normal;
    font-weight: 550;
   margin-top: 6%;
    
}
.designtxt{
    color: rgb(189, 189, 189);
    font-size: 14px;
    font-style: normal;
}
.testingdesign{
    color: rgb(189, 189, 189);
    font-size: 14px;
    font-style: normal;
}
.testingdesign span{
    color: rgb(25, 176, 126);
    text-decoration-line: underline;
    cursor: pointer;
}
