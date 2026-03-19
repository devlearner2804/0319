# <video src="URL"
width="400" 가로
height="320" 세로
controls  비디오 조정 기능 (중지,재생,소리조절 등등)
autoplay 자동재생
loop 반복재생
muted 오디오를 끌 때 사용

페이지 안의 페이지
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
<hr>
<iframe src="iframe1.html" 
width="1000"
height="500"    
srcdoc="
<html>
<head></head>
<h3>iframe 안의 제목 </h3>
<body>
iframe 밑의 설명
</body>
</html>
"
</iframe>
</body>
</html>