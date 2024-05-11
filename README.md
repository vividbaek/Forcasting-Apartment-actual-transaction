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
  <img src="https://raw.githubusercontent.com/vividbaek/DAT_house_pirce/main/Code/images/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C.png" style="display: block;">
  <img src="https://raw.githubusercontent.com/vividbaek/DAT_house_pirce/main/Code/images/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C%20(1).png">
  <img src="https://raw.githubusercontent.com/vividbaek/DAT_house_pirce/main/Code/images/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C%20(2).png">
  <img src="https://raw.githubusercontent.com/vividbaek/DAT_house_pirce/main/Code/images/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C%20(3).png">
  <img src="https://raw.githubusercontent.com/vividbaek/DAT_house_pirce/main/Code/images/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C%20(4).png">
  <img src="https://raw.githubusercontent.com/vividbaek/DAT_house_pirce/main/Code/images/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C%20(5).png">
  <img src="https://raw.githubusercontent.com/vividbaek/DAT_house_pirce/main/Code/images/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C%20(6).png">
  <img src="https://raw.githubusercontent.com/vividbaek/DAT_house_pirce/main/Code/images/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C%20(7).png">
  <img src="https://raw.githubusercontent.com/vividbaek/DAT_house_pirce/main/Code/images/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C%20(8).png">
  <img src="https://raw.githubusercontent.com/vividbaek/DAT_house_pirce/main/Code/images/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C%20(9).png">
  <img src="https://raw.githubusercontent.com/vividbaek/DAT_house_pirce/main/Code/images/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C%20(10).png">
  <img src="https://raw.githubusercontent.com/vividbaek/DAT_house_pirce/main/Code/images/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C%20(11).png">
  <img src="https://raw.githubusercontent.com/vividbaek/DAT_house_pirce/main/Code/images/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C%20(12).png">
  <img src="https://raw.githubusercontent.com/vividbaek/DAT_house_pirce/main/Code/images/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C%20(13).png">
  <img src="https://raw.githubusercontent.com/vividbaek/DAT_house_pirce/main/Code/images/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C%20(14).png">
  <img src="https://raw.githubusercontent.com/vividbaek/DAT_house_pirce/main/Code/images/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C%20(15).png">
  <img src="https://raw.githubusercontent.com/vividbaek/DAT_house_pirce/main/Code/images/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C%20(16).png">
  <img src="https://raw.githubusercontent.com/vividbaek/DAT_house_pirce/main/Code/images/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C%20(17).png">
  <img src="https://raw.githubusercontent.com/vividbaek/DAT_house_pirce/main/Code/images/%EB%8B%A4%EC%9A%B4%EB%A1%9C%EB%93%9C%20(18).png">
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



