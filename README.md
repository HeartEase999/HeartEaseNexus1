<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>簡單表單</title>
</head>
<body>
  <h1>物資需求表單</h1>
  <form action="#" method="post">
    <label for="name">姓名：</label><br>
    <input type="text" id="name" name="name" required><br><br>
    
    <label for="item">需求物資：</label><br>
    <input type="text" id="item" name="item" required><br><br>
    
    <label for="quantity">數量：</label><br>
    <input type="number" id="quantity" name="quantity" required><br><br>
    
    <label for="comments">備註：</label><br>
    <textarea id="comments" name="comments" rows="4" cols="30"></textarea><br><br>
    
    <button type="submit">提交</button>
  </form>
</body>
</html>
