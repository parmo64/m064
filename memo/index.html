<?php

// 保存するファイル
$file = "memo.txt";

// 保存ボタンが押された場合
if ($_SERVER["REQUEST_METHOD"] === "POST") {

    // 入力されたメモを取得
    $memo = $_POST["memo"] ?? "";

    // サーバーに保存
    file_put_contents($file, $memo);

    // 保存後にリロード
    header("Location: index.php?saved=1");
    exit;
}

// 保存されているメモを読み込む
$memo = "";

if (file_exists($file)) {
    $memo = file_get_contents($file);
}

?>

<!DOCTYPE html>
<html lang="ja">

<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>オンラインメモ</title>

<style>

body {
    margin: 0;
    font-family: sans-serif;
    background: #f5f5f5;
}

.container {
    max-width: 800px;
    margin: 40px auto;
    padding: 20px;
}

h1 {
    margin-bottom: 20px;
}

textarea {
    width: 100%;
    height: 500px;
    box-sizing: border-box;
    padding: 15px;
    font-size: 16px;
    border: 1px solid #ccc;
    border-radius: 10px;
    resize: vertical;
    background: white;
}

button {
    margin-top: 15px;
    padding: 12px 25px;
    font-size: 16px;
    border: none;
    border-radius: 8px;
    background: #333;
    color: white;
    cursor: pointer;
}

button:hover {
    opacity: 0.8;
}

.saved {
    margin-left: 15px;
    color: green;
}

</style>

</head>

<body>

<div class="container">

<h1>オンラインメモ</h1>

<form method="POST">

<textarea name="memo" placeholder="ここにメモを書く"><?php
echo htmlspecialchars($memo, ENT_QUOTES, "UTF-8");
?></textarea>

<br>

<button type="submit">保存</button>

<?php

if (isset($_GET["saved"])) {
    echo '<span class="saved">保存しました</span>';
}

?>

</form>

</div>

</body>
</html>