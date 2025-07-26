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
          for (let x = 0; x < 320; x += 20) {
           fill(`hsl(340 75% 50% ${h})`);
           rect(200, 100, 180, 120);
          }
        }
      }
    </script>
  </body>
</html>
