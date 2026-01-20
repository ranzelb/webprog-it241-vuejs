<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/flexbox.css">

    <title>WEBPROG IT241</title>
   
</head>
<body>

<h1>My Personal Profile Web page</h1>
<p>
<img src="https://scontent.fmnl17-2.fna.fbcdn.net/v/t1.15752-9/607059133_4386102214944020_8834524784734252105_n.png?stp=dst-png_p480x480&_nc_cat=107&ccb=1-7&_nc_sid=0024fc&_nc_ohc=4U0ROIfUSKQQ7kNvwHc8L8P&_nc_oc=Adk8iGlEEZWznVZNe9Osxh7ImxQLW8iBe7-aP9iCpFExR_lLIESpp0GcEU8K7tVLfjk&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=scontent.fmnl17-2.fna&oh=03_Q7cD4QEuDOAtzD3Ui3hE8oQg_wJy5rRF8SxrkyXtQBRC-mStfQ&oe=698303D2" alt="Picture of me" width="500" height="600">
</p>

<div class="container">

  <div>
    <p><strong>About Me</strong></p>
    <ul>
      <li><strong>Name:</strong> Ranzel John P. Binggoy</li>
      <li><strong>Age:</strong> 19</li>
      <li><strong>Personality:</strong> Friendly</li>
      <li><strong>Course:</strong> Bachelor of Science in Information Technology</li>
    </ul>
  </div>

  <div>
    <p><strong>School / Education</strong></p>
    <ul>
      <li>Bangkal Elementary School</li>
      <li>Bangkal High School Main</li>
      <li>Maximo Estrella Senior High School</li>
      <li>Asia Pacific College</li>
    </ul>
  </div>

  <div>
    <p><strong>Hobbies</strong></p>
    <ul>
      <li>Gaming</li>
      <li>Anime</li>
      <li>Sports</li>
      <li>Travel</li>
    </ul>
  </div>

  <div>
    <p><strong>Skills</strong></p>
    <ul>
      <li>Oral Communication</li>
      <li>Critical Thinking</li>
      <li>Problem Solving</li>
      <li>Computer Literacy</li>
      <li>Leadership</li>
    </ul>
  </div>

  <div>
    <p><strong>Goal</strong></p>
    <ul>
      <li>Graduate from college</li>
      <li>Become financially stable</li>
      <li>Start a startup company</li>
    </ul>
  </div>

  <div>
    <p><strong>Resources</strong></p>
    <ul>
      <li><a href="https://www.codechef.com/html-online-compiler" target="_blank">HTML Online Compiler</a></li>
      <li><a href="https://chatgpt.com/share/695ba739-0cc8-800f-ba66-4d50d99f9a4e" target="_blank">ChatGPT Reference</a></li>
      <li><a href="https://scontent.fmnl17-2.fna.fbcdn.net/v/t1.15752-9/607059133_4386102214944020_8834524784734252105_n.png?stp=dst-png_p480x480&_nc_cat=107&ccb=1-7&_nc_sid=0024fc&_nc_ohc=4U0ROIfUSKQQ7kNvwHc8L8P&_nc_oc=Adk8iGlEEZWznVZNe9Osxh7ImxQLW8iBe7-aP9iCpFExR_lLIESpp0GcEU8K7tVLfjk&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=scontent.fmnl17-2.fna&oh=03_Q7cD4QEuDOAtzD3Ui3hE8oQg_wJy5rRF8SxrkyXtQBRC-mStfQ&oe=698303D2" target="_blank">Profile Image Source</a></li>
    </ul>
  </div>
    
</div>

</body>
</html>

body {
    background-image: url('https://scontent.fmnl17-3.fna.fbcdn.net/v/t1.15752-9/610459653_1632231908215702_2996603428213222403_n.jpg?stp=dst-jpg_s640x640_tt6&_nc_cat=106&ccb=1-7&_nc_sid=0024fc&_nc_ohc=Si5tpmVFuVQQ7kNvwF5VvV6&_nc_oc=AdlG0rLHKI6lRIhTXXDs-tCzLfPwvwKgCx9PhA3gmSW5uIFxIMtidH_JY8czGc1V2Mo&_nc_ad=z-m&_nc_cid=0&_nc_zt=23&_nc_ht=scontent.fmnl17-3.fna&oh=03_Q7cD4QGfXga0iQ_252fCeKWOwhtrnEmUTCde5VuvrUSAiAdo3A&oe=69833EBC');
    background-size: cover;
    background-position: center;
    background-attachment: fixed;
    background-repeat: no-repeat;
    font-family: Arial, sans-serif;
    text-align: center;
    margin: 0;
    padding: 0;
}


h1 {
    color: white;
    background-color: rgba(0, 51, 102, 0.85);
    display: inline-block;
    padding: 20px 40px;
    margin: 30px auto;
    border-radius: 15px;
    text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.5);
    font-size: 36px;
    letter-spacing: 2px;
}


p {
    color: black;
    text-shadow: 1px 1px 5px gray;
    font-size: 18px;
}


img {
    margin-top: 20px;
    border: 3px solid lightblue;
    box-shadow: 0 0 20px lightblue;
}


.container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin-top: 30px;
}


.container div {
    background-color: white;
    border: 1px solid lightblue;
    width: 300px;
    margin: 10px;
    color: black;
    font-size: 18px;
    display: flex;
    flex-direction: column;
    align-items: center;
    box-shadow: 0 0 15px white;
    padding: 15px;
    box-sizing: border-box;
}


.container div:hover {
    background-color: lightblue;
    color: black;
    cursor: pointer;
}


.container ul {
    list-style-type: disc;
    padding-left: 20px;
    text-align: left;
}

.container li {
    font-weight: bold;
    color: black;
    margin-bottom: 8px;
}


.container a {
    color: #003366;
    text-decoration: none;
    word-break: break-all;
}

.container a:hover {
    text-decoration: underline;
    color: #0055aa;
}


.container-bottom {
    position: fixed;
    bottom: 0;
    left: 0;
    right: 0;
    background-color: white;
    padding: 10px 0;
    text-align: center;
    box-shadow: 0 -5px 10px rgba(255, 0, 0, 0.5);
    z-index: 1000;
}

.container-bottom .container div {
    width: 200px;
    font-size: 16px;
    padding: 10px;

}

