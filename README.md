<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Love Message for My Baby</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: black; /* Black background */
            color: white; /* White text */
            font-family: 'Courier New', monospace; /* Set font to typewriter-like style */
            overflow: hidden; /* Prevent scrolling */
        }
        .message {
            border: 1px solid #ccc;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.8); /* Semi-transparent background for the message */
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
            width: 80%;
            max-width: 600px;
            text-align: left; /* Align text to the left */
            font-size: 18px;
            white-space: pre-wrap; /* Preserve line breaks and spacing */
        }
    </style>
</head>
<body>

    <div class="message" id="message"></div>

    <script>
        const messageText = "This message is for my one and only Buddy, Best friend, Girlfriend, Fiancee, and lastly my Wife, my beautiful Wife. First of all, thank you for staying even if this past month isn't for us, for our relationship. I love you so much just for that, mahal. Second, I wanna say thank you because na titimpi mo yung pagiging bata ko sayo, pagiging mataray ko minsan. I love you for accepting me for who I am. I don't need to change my own personality when I'm with you; I don't need to change my own voice. I don't have to make it sound more fem para lang maging comfortable ka. Thank you for putting up with me, mahal, I'm really really grateful for that mahal ko, I love you! 🎀 ..."; 

        let index = 0;

        function typeMessage() {
            if (index < messageText.length) {
                document.getElementById("message").innerHTML += messageText.charAt(index);
                index++;
                setTimeout(typeMessage, 50); // Speed of typing effect (50ms per character)
            }
        }

        typeMessage(); // Start typing the message
    </script>

</body>
</html>
