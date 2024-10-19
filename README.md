# HTML-2010-Google
This is a HTML project that makes Google 2010 style (like the 1998 easter egg.) Here it is:



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google 2010</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ffffff;
            text-align: center;
            margin: 0;
            padding: 50px;
        }
        #logo {
            margin-bottom: 20px;
        }
        #search-form {
            display: inline-block;
            margin-bottom: 20px;
        }
        #search-input {
            width: 400px;
            padding: 10px;
            font-size: 16px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        #search-button {
            padding: 10px 20px;
            font-size: 16px;
            border: 1px solid #f8f8f8;
            background-color: #f8f8f8;
            border-radius: 5px;
            cursor: pointer;
            margin-left: 5px;
        }
        #search-button:hover {
            background-color: #e8e8e8;
        }
    </style>
</head>
<body>

    <div id="logo">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/24/Google_logo_2010.svg/2560px-Google_logo_2010.svg.png" alt="Google" width="272" height="92">
    </div>

    <form id="search-form" action="https://www.google.com/search" method="get">
        <input type="text" id="search-input" name="q" placeholder="Search Google or type a URL" required>
        <input type="submit" id="search-button" value="Google Search">
    </form>

    <div>
        <a href="https://www.google.com/preferences">Preferences</a> |
        <a href="https://www.google.com/advanced_search">Advanced search</a>
    </div>

</body>
</html>

