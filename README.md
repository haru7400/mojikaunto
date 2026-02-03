<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<title>文字数カウンター</title>
<style>
  body { font-family: sans-serif; padding: 20px; }
  textarea { width: 100%; height: 200px; font-size: 16px; }
</style>
</head>
<body>

<h1>文字数カウンター</h1>
<textarea id="text"></textarea>
<p>文字数：<span id="count">0</span></p>

<script>
const text = document.getElementById("text");
const count = document.getElementById("count");

text.addEventListener("input", () => {
  count.textContent = text.value.length;
});
</script>

</body>
</html>
# mojikaunto
