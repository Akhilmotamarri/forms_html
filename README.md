# forms_html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form</title>
</head>
<body>
    <h2>this is html form practice</h2>
    <form action="backend.php">
        <label for="name">Name</label>
        <div>
            <input type="text" name="myname" id="name">
        </div>
        <br>
        <div>
            Password: <input type="password" name="mypassword">
        </div>
        <br>
        <div>
            Email: <input type="email" name="myemail">
        </div>
        <br>
        <div>
            date: <input type="date" name="myname">
        </div>
        <br>
        <div>
            bonus: <input type="number" name="mybonus" id="">
        </div>
        <br>
        <div>
            are you eligible.?: <input type="checkbox" name="myeligiblity" checked required>
        </div>
        <br>
        <div>
            Gender: <input type="radio" name="mygenter" id="">Male<input type="radio" name="mygenter" id="">
            Female<input type="radio" name="mygenter" id="">
            Other
        </div>
        <br>
        <div>
            <input type="submit" value="submit now">
            <input type="reset" value="reset now">
        </div>
        <br>
        <div>
            RightAboutyourself<textarea name="mytextarea" id="" cols="30" rows="10"></textarea>
            Your idea<textarea name="mytextarea" id="" cols="30" rows="10"></textarea>
        </div>
        <br>
        <div>
            <select name="mycar" id="car">
                <option value="ind">indica</option>
                <option value="swf">swift</option>
            </select>
        </div>
        
    </form>


</body>
</html>
