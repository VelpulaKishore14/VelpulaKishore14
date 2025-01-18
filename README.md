## Hi there 👋

<!--
**VelpulaKishore14/VelpulaKishore14** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

currently pursuing B.Tech 3rd year Information technology
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Upload</title>
</head>
<body>
    <h2>Upload an Image</h2>
    <img scr="https://cdn.pixabay.com/photo/2023/12/01/10/20/ai-generated-8423424_640.jpg" alt="image" width="200">
    <form action="/upload" method="POST" enctype="multipart/form-data">
        <label for="image">Choose an image to upload:</label>
        <input type="file" id="image" name="image" accept="image/*" required>
        <br><br>
        <button type="submit">Upload Image</button>
    </form>
</body>
</html>
