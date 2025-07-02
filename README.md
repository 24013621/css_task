**Question :**
```Design a profile page using CSS. The profile picture must appear circular with a colored border. Center the user's name below the image, and use a custom font for the description text. The layout should be mobile responsive.```

**Code :**
```<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Jaseer</title>
  <style>
    body {
      display: flex;
      height: 100vh;
      align-items: center;
      justify-content: center;
      background-color: #f2f2f2;
      font-family: Arial, sans-serif;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 8px;
      text-align: center;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }
    img {
      width: 100px;
      height: auto;
      border-radius: 50%;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>
  <div class="card">
    <img src="profile.jpg" alt="Jaseer's photo">
    <h2>Jaseer</h2>
    <p>Great web design without functionality is like a sports car with no engine</p>
  </div>
</body>
</html>
```

**Output :**

![Screenshot 2025-07-02 105920](https://github.com/user-attachments/assets/4889ebc2-a95a-4007-9b2f-a06326bd9e9f)
