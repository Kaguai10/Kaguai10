<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My GitHub Profile</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: url('https://source.unsplash.com/random/1600x900') no-repeat center center fixed;
            background-size: cover;
            overflow: hidden;
        }
        
        #overlay {
            position: fixed;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5);
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            text-align: center;
        }
        
        h1 {
            color: white;
            font-size: 3em;
        }
        
        .btn {
            margin-top: 20px;
            padding: 15px 30px;
            font-size: 18px;
            border: none;
            cursor: pointer;
            border-radius: 10px;
        }
        
        .btn1 { background: red; color: white; }
        .btn2 { background: black; color: green; }
        .btn3 { background: purple; color: white; }
        
        .popup {
            display: none;
            position: fixed;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            background: white;
            padding: 20px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.3);
            border-radius: 10px;
        }
        
        .popup img {
            width: 200px;
            height: auto;
        }
    </style>
</head>
<body>
    <audio autoplay loop>
        <source src="your-song.mp3" type="audio/mpeg">
    </audio>
    
    <div id="overlay">
        <h1>Welcome to My GitHub Profile</h1>
        <button class="btn btn1" onclick="showPopup('popup1')">For You</button>
        <button class="btn btn2" onclick="showPopup('popup2')">My Secret</button>
        <button class="btn btn3" onclick="showPopup('popup3')">I Love You</button>
    </div>
    
    <div id="popup1" class="popup">
        <img src="https://cdn-icons-png.flaticon.com/512/833/833472.png" alt="Heart">
    </div>
    <div id="popup2" class="popup">
        <img src="https://cdn-icons-png.flaticon.com/512/1305/1305386.png" alt="Hacking">
    </div>
    <div id="popup3" class="popup">
        <p>I'm so grateful to have you in my life, I love you ❤️</p>
    </div>
    
    <script>
        function showPopup(id) {
            var popup = document.getElementById(id);
            popup.style.display = 'block';
            setTimeout(() => popup.style.display = 'none', 3000);
        }
    </script>
</body>
</html>
