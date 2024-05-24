# demo_form
This is my first Git Repository.
<br>
Author-Devendra Nafade
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forms amd input tags in html </title>
</head>

<body>
    <h1> Form to apply for I.M.R Colleg..

    </h1>
    <form action="">
        <div>
            <label for="username">Enter your username</label>

            <input type="text" id="username" placeholder="Enter your username">
        </div>
        <div>
            <input type="radio" id="male" name="gender" value="male">
            <label for="male">Male</label>
            <input type="radio" id="female" name="gender" value="female">
            <label for="female">Female</label>
        </div>
        <div>
            <input type="checkbox" id="subscribe" name="subscribe" value="yes">
            <label for="subscribe">Subscribe to newsletter</label>
        </div>
        <div>
            <label for="Comment">Enter your comment here...</label>
            <br>
            <textarea name="comment" rows="4" cols="50"></textarea>
        </div>
        <div>
            <select name="fruits">
                <option value="apple">Apple</option>
                <option value="banana">Banana</option>
                <option value="cherry">Cherry</option>
          </select>
        </div>

    </form>

</body>

</html>
