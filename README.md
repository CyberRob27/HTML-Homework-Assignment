# HTML-Homework-Assignment
HTML Homework Assignment

<!DOCTYPE html>
<html>
  <head>
    <title>Rob's Page</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
      body {
          font-family: Arial, Helvetica, sans-serif;
          margin: 0;
      }

      /* Style the header */
      .header {
          padding: 10px;
          text-align: center;
          background: #1abc9c;
          color: white;
          background-image: url('skyline.jpg');
          background-repeat: no-repeat;
          background-size: cover;
      }


      /* Increase the font size of the h1 element */
      .header h1 {
          font-size: 40px;
      }
      .footer {
          padding: 20px;
          text-align: center;
          background: #ddd;
      }
      * {
          box-sizing: border-box;
      }

      /* Create three equal columns that floats next to each other */
      .column {
          float: left;
          width: 33.33%;
          padding: 10px;
          height: 300px; /* Should be removed. Only for demonstration */
      }

      /* Clear floats after the columns */
      .row:after {
          content: "";
          display: table;
          clear: both;
      }

    </style>
</head>
<body>

<!-- Header Start -->
<header class="header">
  <h1>Rob's website</h1>
  <p>CS 612</p>
  <p>Prof. Brooks</p>
</header>
<!-- Header End -->

<div class="row">
  
  <!-- Left Column Start -->
  <div class="column" style="background-color:#aaa;">
    <nav>
<br><br>
<ul class="leftt">
  <li class="leftt">
  <a href="BrookesHW2.html">Home</a>
  </li>
  <li class="leftt">
  <a href="about.html">About me</a>
  </li>
  <li class="leftt">
  <a href="contact.html">Contact me</a>
  </li>
</ul>
</nav>
  </div>
  <!-- Left Column End -->

  <div class="column" style="background-color:#bbb;">
    <h2>About Me</h2>
    <p>AI'm a social multimedia guru, tech junkie, and combatant of fake news. I've been covering cyber security for the last few years and I am currently studying for my Master's in Computer Science to learn how to better defend our internet, data, and digital privacy. I currently work as the Content Coordinator with SC Magazine. Prior to that, I worked as the Social Media Coordinator for the AirbnbNYC Campaign. I have also worked as a Data Analyst with Dataminr Inc, and as a multimedia reporter for  Tribe Media, The Columbia Business Times, and NBC affiliate station KOMU 8. My hobbies are boxing, listening to hip hop music, and debating politics and world issues.</p>
  </div>
  <div class="column" style="background-color:#ccc;">
    <h2>Social Media</h2>
    <nav>
      <ul class="leftt">
      <li class="leftt">
      <a href="https://www.facebook.com/RobertJAAbel?ref=bookmarks">Facebook</a>
      </li>
      <li class="leftt">
      <a href="https://www.linkedin.com/in/robertjaabel/">LinkedIn</a>
      </li>
      <li class="leftt">
      <a href="https://www.robertjaabel.com/">Personal Site</a>
      </li>
      <li class="leftt">
      <a href="https://www.youtube.com/channel/UCG72WbiCvdB6JKU-3YRP8Kg">Favorite YouTube</a>
      </li>
      <li class="leftt">
      <a href="https://www.pace.edu/">Pace University</a>
      </li>
      </ul>
    </nav>
      </div>
    </div>
    <div class="footer">
      <h2>Footer</h2>
      <p>Copyright © HelloWord.com</p>
    </div>
</body>
</html>
