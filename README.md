<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Matthieu's Toolbox</title>
  <style>
    body {
      font-family: sans-serif;
      background: #b3e0f2;
      margin: 0;
      padding: 20px;
    }
    h2, h3 {
      text-align: center;
      margin-top: 10px;
    }
    .toolbox {
      display: flex;
      flex-direction: column;
      gap: 30px;
      max-width: 1200px;
      margin: 40px auto;
    }
    .row {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }
    .block {
      background: white;
      border-radius: 12px;
      padding: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      display: flex;
      flex-direction: row;
      gap: 10px;
      align-items: center;
      flex-wrap: wrap;
    }
    .block img {
      height: 50px;
      transition: transform 0.2s;
    }
    .block img:hover {
      transform: scale(1.1);
    }
    .contact {
      text-align: center;
      font-size: 1.1em;
      margin-top: 10px;
    }
  </style>
</head>
<body>

  <h2>Hi 👋, I'm Matthieu</h2>
  <h3>Industrial engineer in Automation and Robotics, currently PhD student in Machine Learning applied to Genetics</h3>
  <p class="contact">
    🔭 I’m currently working on polishing my machine learning skills<br>
    📫 Reach me at: <a href="mailto:m.c.de.hemptinne@vu.nl">m.c.de.hemptinne@vu.nl</a>
  </p>

  <h1 style="text-align: center;">🧰 Current Toolbox</h1>

  <div class="toolbox">
    <!-- Hardware & Version Control -->
    <div class="row row-top">
      <div class="block">
        <img src="assets/icons/hardware.png" alt="Hardware">
        <img src="assets/icons/raspberry.png" alt="Raspberry Pi">
        <img src="assets/icons/arduino.png" alt="Arduino">
        <img src="assets/icons/jetson.png" alt="Jetson">
      </div>
      <div class="block">
        <img src="assets/icons/github.png" alt="GitHub">
        <img src="assets/icons/git.png" alt="Git">
      </div>
      <div class="block">
        <img src="assets/icons/linux.png" alt="Linux">
        <img src="assets/icons/apple.png" alt="macOS">
        <img src="assets/icons/windows.png" alt="Windows">
      </div>
    </div>
    <!-- Web + Cloud -->
    <div class="row row-web-backend">
      <div class="block">
        <img src="assets/icons/html.png" alt="HTML">
        <img src="assets/icons/css.png" alt="CSS">
        <img src="assets/icons/javascript.png" alt="JavaScript">
        <img src="assets/icons/ruby.png" alt="Ruby">
      </div>
      <div class="block">
        <img src="assets/icons/mongo.png" alt="MongoDB">
        <img src="assets/icons/postgres.png" alt="PostgreSQL">
      </div>
      <div class="block">
        <img src="assets/icons/google_cloud.png" alt="Google Cloud">
        <img src="assets/icons/aws.png" alt="AWS">
        <img src="assets/icons/heroku.png" alt="Heroku">
      </div>
    </div>
    <!-- Programming + Stats -->
    <div class="row row-code">
      <div class="block">
        <img src="assets/icons/bash.png" alt="Bash">
        <img src="assets/icons/python.png" alt="Python">
        <img src="assets/icons/cpp.png" alt="C++">
      </div>
      <div class="block">
        <img src="assets/icons/R_studio.png" alt="R Studio">
        <img src="assets/icons/matlab.png" alt="MATLAB">
        <img src="assets/icons/stats.png" alt="Stats">
      </div>
    </div>
    <!-- ML + Containers -->
    <div class="row row-ml">
      <div class="block">
        <img src="assets/icons/torch.png" alt="PyTorch">
        <img src="assets/icons/scikit_boost.png" alt="Scikit/XGBoost">
        <img src="assets/icons/tensorflow.png" alt="TensorFlow">
      </div>
      <div class="block">
        <img src="assets/icons/docker.png" alt="Docker">
        <img src="assets/icons/k8.png" alt="Kubernetes">
      </div>
    </div>
    <!-- Vision, Modeling, Robotics -->
    <div class="row row-bottom">
      <div class="block">
        <img src="assets/icons/tracking.png" alt="CV">
        <img src="assets/icons/photogrammetry.png" alt="Photogrammetry">
      </div>
      <div class="block">
        <img src="assets/icons/blender.png" alt="Blender">
        <img src="assets/icons/SW.png" alt="SolidWorks">
        <img src="assets/icons/3d.png" alt="3D">
      </div>
      <div class="block">
        <img src="assets/icons/ros.png" alt="ROS">
        <img src="assets/icons/gazebo.png" alt="Gazebo">
        <img src="assets/icons/robot.png" alt="Robot">
      </div>
    </div>

  </div>

</body>
</html>
