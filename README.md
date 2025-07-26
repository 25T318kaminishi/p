<!DOCTYPE html>
<html lang="ja">
  <head>
    <meta charset="UTF-8" />
    <title>P5.js 練習問題解答</title>
    <script src="https://cdn.jsdelivr.net/npm/p5@2.0.3/lib/p5.min.js">
    </script>
  </head>
  <body>
    <h1>P5.js 練習問題解答</h1>
    <script>
      function setup() {
        createCanvas(320, 180);
      }

      function draw() {
        stroke("black");
        strokeWeight(0.1);
        for (let y = 0; y < 180; y += 20) {
          for (let x = 0; x < 180; y += 20) {
          fill(`oklch(90% ${100 - x / 3.2}% ${y * 2})`);
          ellipse(x + 5, y + 5, 8, 8); 
           
          }
        }
      }
    </script>
  </body>
</html>
