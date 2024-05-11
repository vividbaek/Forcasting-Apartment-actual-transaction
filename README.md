# DAT_house_pirce
[DAT 2기 러닝메이트 학회보고서.docx](https://github.com/vividbaek/DAT_house_pirce/files/15281702/DAT.2.docx)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Image Slider</title>
<style>
  body { display: flex; justify-content: center; align-items: center; height: 100vh; }
  .slider { width: 60%; }
  img { width: 100%; display: none; }
</style>
</head>
<body>

<div class="slider">
  <!-- 이미지 태그 예시, 실제 이미지 경로로 교체 필요 -->
  <img src="https://example.com/path/to/your/image1.jpg" style="display: block;">
  <img src="https://example.com/path/to/your/image2.jpg">
  <img src="https://example.com/path/to/your/image3.jpg">
  <!-- 이미지 추가 필요 -->
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
