# Demo
this is first repository
<%@ page language="java" contentType="text/html; charset=UTF-8"
    pageEncoding="UTF-8"%>
<!DOCTYPE html>
<html>
<head>
 <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazing Profile Card</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: url('image/back.jpeg') center/cover no-repeat fixed;
            color: #f0f0f0;
            margin: 0;
            display: flex;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }

        .profile-card {
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            width: 300px;
            max-width: 100%;
            text-align: center;
        }

        .profile-image {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-bottom: 2px solid #ddd;
        }

        .profile-info {
            padding: 20px;
        }

        .profile-info h1 {
            margin: 0;
            color: #333;
        }

        .profile-info p {
            color: #777;
            margin: 10px 0;
        }

        .social-links {
            display: flex;
            justify-content: center;
            margin-top: 20px;
        }

        .social-link {
            margin: 0 10px;
            color: #333;
            text-decoration: none;
            font-size: 20px;
            transition: color 0.3s;
        }

        .social-link:hover {
            color: #4183D7;
        }
        
        
    </style>
</head>
<body>

<div class="profile-card">
    <img class="profile-image" src="image/Umar.jpg" alt="Profile Image">
    <div class="profile-info">
        <h1>Shaikh Umar</h1>
        <p>Web Developer</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vestibulum tortor ac dapibus consectetur.</p>
        <div class="social-links">
            <a href="#" class="social-link" target="_blank">🌐</a>
            <a href="#" class="social-link" target="_blank">📷</a>
            <a href="#" class="social-link" target="_blank">📧</a>
        </div>
    </div>
</div>


</body>
</html>
