<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Web Intro</title>
    <link href="https://fonts.googleapis.com/css2?family=Baloo+Bhai+2&family=Rajdhani&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Rajdhani', sans-serif;
            background-image: linear-gradient(to right, #83a4d4, #b6fbff);
        }

        .container {
            margin: 20px;
            padding: 10px;
        }

        .student1 {
            height: 400px;
            width: 55%;
            padding: 20px;
            border: 2px solid;
            border-radius: 25px;
            font-family: 'Baloo Bhai 2', cursive;
            text-transform: capitalize;
            font-size: 20px;
            position: relative;
        }

        .shakal {
            border-radius: 50%;
            position: absolute;
            height: 15vw;
            top: 120px;
            right: 15px;
            
        }
        
        .copyright {
            font-family: monospace;
            position: fixed;
            bottom: 0px;
            right: 10px;
        }

       
        h1 {
            padding-left: 50px;
        }

        #hob4 {
            background: linear-gradient(to left, #FFE8D2, #b6fbff);
        }
    </style>
</head>

<body>
    <div class="container">
        <h1>Student's Profile</h1>
        <div class="student1">
            <p>
                suyash anurag here.
            </p>
            My Hobbies Would Be:
            <ul>
                <li><del>Dancing</del> Singing</li>
                <li>Playng Guitar</li>
                <li>Ineracting With New People</li>
                <li><span id="hob4">Web Development</span></li>
                <li>Helping Out</li>
            </ul>
            You can always find me <a href="#">here</a> :)

            <img class="shakal" src="Main Image.jpg" alt="Suyash's Image">
        </div>
        <div class="copyright">
            <p>&copy;Suyash_2020</p>
        </div>

    </div>
</body>

</html>
