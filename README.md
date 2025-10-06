


<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>عبدالظاهر سامي - بروفايل شخصي</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="profile-container">
    <div class="profile-card">
      <img src="https://i.imgur.com/0y0y0y0.png" alt="صورة شخصية" class="profile-img">
      <h1>عبدالظاهر سامي</h1>
      <p class="job-title">مبرمج ويب - Java & Spring Boot</p>
      <p class="bio">طالب بكلية الحاسبات والمعلومات، مهتم بتطوير تطبيقات ويب باستخدام Java و Spring Boot، ولدي معرفة بأساسيات C++, Python, MySQL, OOP, و Data Structures.</p>

      <div class="social-links">
        <a href="mailto:abdulzaher.email@example.com" target="_blank">📧</a>
        <a href="https://www.linkedin.com/in/your-profile" target="_blank">LinkedIn</a>
        <a href="https://github.com/abdulzaher" target="_blank">GitHub</a>
      </div>
    </div>
  </div>
</body>
</html>

























* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Arial', sans-serif;
}

body {
  background: linear-gradient(to right, #4b6cb7, #182848);
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

.profile-container {
  padding: 20px;
}

.profile-card {
  background-color: white;
  padding: 30px;
  border-radius: 12px;
  text-align: center;
  box-shadow: 0 0 15px rgba(0,0,0,0.2);
  max-width: 400px;
}

.profile-img {
  width: 120px;
  height: 120px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 20px;
  border: 3px solid #4b6cb7;
}

h1 {
  font-size: 24px;
  color: #333;
}

.job-title {
  color: #4b6cb7;
  margin: 10px 0;
  font-weight: bold;
}

.bio {
  font-size: 14px;
  color: #555;
  margin: 10px 0 20px;
}

.social-links a {
  margin: 0 10px;
  text-decoration: none;
  font-size: 20px;
  color: #4b6cb7;
  transition: 0.3s;
}

.social-links a:hover {
  color: #182848;
}

