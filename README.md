<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Would You Like to Go Out With Me?</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            margin: 50px;
        }

        h1 {
            color: #333;
        }

        p {
            color: #666;
        }

        form {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-top: 20px;
        }

        button {
            margin-top: 10px;
            padding: 10px 20px;
            font-size: 16px;
            background-color: #4CAF50;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <h1>Would You Like to Go Out With Me?</h1>
    <p>Hi there! I've been meaning to ask you something special...</p>
    <p>Would you be interested in going out with me?</p>

    <form>
        <label>
            <input type="radio" name="response" value="yes" required> Yes, I'd love to!
        </label>
        <label>
            <input type="radio" name="response" value="no" required> Sorry, I can't make it.
        </label>

        <button type="submit">Submit</button>
    </form>
</body>
</html>
