# Exp1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Profile Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            background-color: #ddd;
            align-content: center ;
            
        }

        h1 {
            color: #337ab7;
            text-align: left;
        }

        img {
            max-width: 200px;
            border-radius: 50%;
        }

        audio, video {
            max-width: 400px;
        }

        table {
            border-collapse: collapse;
        }

        th, td {
            padding: 10px;
            border: 1px solid #ddd;
        }

        th {
            background-color: #f2f2f2;
        }

        a {
            color: #337ab7;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>My Profile</h1>
    </header>
    <main>
        <section>
            <h2>Personal Details</h2>
            <table>
                <tr>
                    <th>Name:</th>
                    <td>Rushikesh Yeole</td>
                </tr>
                <tr>
                    <th>Email:</th>
                    <td>rushyeole24@gmail.com</td>
                </tr>
                <tr>
                    <th>Location:</th>
                    <td>Koperkhairne, Navi Mumbai</td>
                </tr>
            </table>
        </section>

        <section>
            <h2>Skill Sets</h2>
            <ul>
                <li>HTML5</li>
                <li>CSS3</li>
                <li>JavaScript</li>
                <li>Python</li>
                <li>Web Design</li>
                <li>Problem Solving</li>
            </ul>
        </section>

        <section>
            <h2>Photograph</h2>
            <img src="your_photo.jpg" alt="Your Photo">
        </section>

        <section>
            <h2>Introduction Audio</h2>
            <audio controls>
                <source src="intro_audio.mp3" type="audio/mpeg">
                Your browser does not support the audio element.
            </audio>
        </section>

        <section>
            <h2>Introduction Video</h2>
            <video controls>
                <source src="intro_video.mp4" type="video/mp4">
                Your browser does not support the video element.
            </video>
        </section>
    </main>
    <footer>
        <p>Contact: <a href="mailto:you@example.com">rushyeole24@gmail.com</a></p>
    </footer>
</body>
</html>
