![Header](https://github.com/amarnadh98/amarnadh98/blob/main/AMARNADH%20REDDY%20github%20banner%20main.png "Header")

<h1 align="center">Hola <img src="https://github.com/amarnadh98/amarnadh/blob/main/wave.gif" width="30px"></h1>




- 🌱 I’m good at ****Python, SQL, Machine Learning, DEEP LEARNING****

- 📫 Reach me at **avenkatamarnadh@gmail.com**

<!--Image slider for certificates-->
<div style="overflow: hidden;">
  <img src="image1.jpg" alt="Image 1" style="width: 100%; height: auto;">
  <img src="image2.jpg" alt="Image 2" style="width: 100%; height: auto;">
  <img src="image3.jpg" alt="Image 3" style="width: 100%; height: auto;">
</div>

<!--Navigation buttons-->
<div style="text-align: center; margin-top: 10px;">
  <button onclick="prevSlide()">Previous</button>
  <button onclick="nextSlide()">Next</button>
</div>

<script>
  let currentIndex = 0;
  const images = document.querySelectorAll('img');

  function showSlide(index) {
    if (index < 0) {
      currentIndex = images.length - 1;
    } else if (index >= images.length) {
      currentIndex = 0;
    }
    for (let i = 0; i < images.length; i++) {
      if (i === currentIndex) {
        images[i].style.display = 'block';
      } else {
        images[i].style.display = 'none';
      }
    }
  }

  function prevSlide() {
    currentIndex--;
    showSlide(currentIndex);
  }

  function nextSlide() {
    currentIndex++;
    showSlide(currentIndex);
  }

  // Show the initial slide
  showSlide(currentIndex);
</script>


<h3 align="left">Connect with me:</h3>
<p align="left">
  <a href="https://www.linkedin.com/in/amarnadh-avuduri/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/amarnadh-avuduri/" height="30" width="40" /></a>
  <a href="https://www.hackerrank.com/amarnadh98?hr_r=1" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hackerrank.svg" alt="https://www.hackerrank.com/amarnadh98?hr_r=1" height="30" width="40" /></a>
</p>

<!-- <h3 align = "left">My Achievements</h3>
<p align="left">
  <a href="https://www.hackerrank.com/amarnadh98?hr_r=1" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/hackerrank.svg" alt="https://www.hackerrank.com/amarnadh98?hr_r=1" height="30" width="40" /></a>
  <a href=""
</p>
-->
<h3 align="left">Languages and Tools:</h3>

<p align="left"> 
  <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> 
  <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> 
  <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> 
  <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> 
  <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> 
  <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> </a> 
</p>
