# DAT_house_pirce
[DAT 2기 러닝메이트 학회보고서.docx](https://github.com/vividbaek/DAT_house_pirce/files/15281702/DAT.2.docx)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<h1>진행한 부동산 가격 예측 프로젝트(DAT 러닝메이트팀)</h1>
<title>Image Slider</title>
<style>
  body { display: flex; justify-content: center; align-items: center; height: 100vh; }
  .slider { width: 60%; }
  img { width: 100%; display: none; }
</style>
</head>
<body>

<div class="slider">
  <img src="images/다운로드.png" style="display: block;">
  <img src="images/다운로드(1).png">
  <img src="images/다운로드(2).png">
  <img src="images/다운로드(3).png">
  <img src="images/다운로드(4).png">
  <img src="images/다운로드(5).png">
  <img src="images/다운로드(6).png">
  <img src="images/다운로드(7).png">
  <img src="images/다운로드(8).png">
  <img src="images/다운로드(9).png">
  <img src="images/다운로드(10).png">
  <img src="images/다운로드(11).png">
  <img src="images/다운로드(12).png">
  <img src="images/다운로드(13).png">
  <img src="images/다운로드(14).png">
  <img src="images/다운로드(15).png">
  <img src="images/다운로드(16).png">
  <img src="images/다운로드(17).png">
  <img src="images/다운로드(18).png">
</div>

<script>
  let current = 0;
  const images = document.querySelectorAll('.slider img');

  function nextImage() {
    images[current].style.display = 'none';
    current = (current + 1) % images.length;
    images[current].style.display = 'block';
  }

  setInterval(nextImage, 3000); // Change image every 3 seconds
</script>

</body>
</html>
