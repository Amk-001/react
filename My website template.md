<!DOCTYPE html>
<html lang="my">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Myanmar Network App</title>
  <style>
    body {
      margin: 0;
      background-color: #000; /* Blue Nero */
      color: #800080; /* Black*/
      font-family: Arial, sans-serif;
    }
    .title {
      text-align: center;
      font-size: 24px;
      padding: 20px;
      color: #800080;
          }
    .public-post {
      width: 100%;
      max-width: 300px;
      height: 100px;
      background-color: #800080;
      color: #fff;
      margin-bottom: 20px;
      text-align: center;
      line-height: 100px;
    }
    .frame {
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    .search-box {
      width: 100%;
      max-width: 400px;
      height: 40px;
      border: 2px solid #800080;
      border-radius: 5px;
      margin-bottom: 20px;
    }
    .about-box {
      width: 300px;
      height: 100px;
      background-color: #800080;
      color: #fff;
      text-align: center;
      line-height: 100px;
      border-radius: 10px;
    }
  </style>
</head>
<body>
  <div class="title">Myanmar Network App</div>
  <div class="frame">
    <div class="public-post">Public Post</div>
    <input type="text" class="search-box" placeholder="Search...">
    <div class="about-box">About Us</div>
  </div>
</body>
</html>
