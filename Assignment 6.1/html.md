<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Box Model Inspection</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>CSS Box Model Inspection</h1>

  <div class="card card-one">
    <h2>Content Box</h2>
    <p>With content-box, padding and border are added outside the declared width.</p>
  </div>

  <div class="card card-two">
    <h2>Border Box</h2>
    <p>With border-box, the declared width includes the content, padding, and border.</p>
  </div>

  <div class="card card-three">
    <h2>Custom Box</h2>
    <p>This box uses different padding, border, and margin values.</p>
  </div>

  <section class="box-model">
    <h2>Box Model Parts</h2>
    <div class="margin">
      <span>Margin</span>
      <div class="border">
        <span>Border</span>
        <div class="padding">
          <span>Padding</span>
          <div class="content">Content</div>
        </div>
      </div>
    </div>
  </section>
</body>
</html>