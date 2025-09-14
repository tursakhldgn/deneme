<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Benim Hakkımda</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .container {
            background-color: #ffffff;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.1);
            text-align: center;
            max-width: 400px;
            width: 100%;
        }

        .profile-img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 20px;
            border: 3px solid #4CAF50;
            transition: transform 0.3s;
        }

        .profile-img:hover {
            transform: scale(1.1);
        }

        h1 {
            margin: 10px 0;
            font-size: 24px;
            color: #333;
        }

        p {
            color: #555;
            font-size: 16px;
            line-height: 1.6;
        }

        .social-links {
            margin-top: 25px;
            display: flex;
            flex-direction: column;
            gap: 15px;
            align-items: center;
        }

        .social-links a {
            text-decoration: none;
            color: #fff;
            padding: 10px 20px;
            border-radius: 50px;
            width: 200px;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: 0.3s;
            font-weight: 500;
        }

        .social-links a i {
            margin-right: 10px;
            transition: transform 0.3s;
        }

        .social-links a:hover i {
            transform: rotate(360deg);
        }

        .facebook { background-color: #3b5998; }
        .twitter { background-color: #1da1f2; }
        .instagram { background-color: #e4405f; }
        .linkedin { background-color: #0077b5; }
    </style>
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>
    <div class="container">
        <img src="profil.jpg" alt="Profil Fotoğrafı" class="profile-img">
        <h1>Murat Karaca</h1>
        <p>
            Merhaba! Ben dijital dünyada kendini geliştirmeyi seven bir bireyim. 
            Çeşitli projelerde yer aldım ve her zaman yeni şeyler öğrenmeye açık biriyim. 
            Sade ve modern tasarım anlayışını benimsiyorum.
        </p>
        <div class="social-links">
            <a href="https://facebook.com" target="_blank" class="facebook">
                <i class="fab fa-facebook-f"></i>Facebook
            </a>
            <a href="https://twitter.com" target="_blank" class="twitter">
                <i class="fab fa-twitter"></i>Twitter
            </a>
            <a href="https://instagram.com" target="_blank" class="instagram">
                <i class="fab fa-instagram"></i>Instagram
            </a>
            <a href="https://linkedin.com" target="_blank" class="linkedin">
                <i class="fab fa-linkedin-in"></i>LinkedIn
            </a>
        </div>
    </div>
</body>
</html>
