<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Multiple Columns</title>
    <style>
        ::selection {
           color: antiquewhite;
           background-color: gray;
        }
        .gallery-img {
            width: 100%;
            border-radius: 10px;
            transition: 0.5s;
        }
        .gallery {
            column-count: 3;
            column-gap: 20px;
            column-rule: 5px solid #001211;
           
        }
        .gallery-img:hover {
            transform:scale(1.1) ;
        }
    </style>
</head>
<body>
    <h1>Jennie Kim</h1>
    <div class="gallery">
        <img src="https://pm1.narvii.com/6711/4c561144cb158b62fb46ab5c1609ec3150731b3b_hq.jpg" class="gallery-img">
        <img src="https://www.12thblog.com/wp-content/uploads/2020/03/Jennie-Kim-11.jpg" class="gallery-img">
        <img src="https://static.asiachan.com/Jennie.Kim.full.130860.jpg" class="gallery-img">
        <img src="https://i.pinimg.com/originals/62/f6/eb/62f6eba7f04f3a7e343c2d3f65e71e93.jpg" class="gallery-img">
        <img src="https://i.pinimg.com/originals/49/45/36/4945364cfd466f77a51d0672d3300fcd.jpg" class="gallery-img">
        <img src="https://i.pinimg.com/originals/33/c7/a1/33c7a184ecfe424f74222f13f8221481.jpg" class="gallery-img">
        <img src="https://i.pinimg.com/originals/19/d1/b4/19d1b4e45991be96da56655bb9191739.jpg" class="gallery-img">
        <img src="https://i.pinimg.com/originals/84/8c/7e/848c7ededf121126a8752a7d4c8fe239.jpg" class="gallery-img">
        <img src="https://i.pinimg.com/originals/b7/e4/d3/b7e4d312c6c6ee5909433e9957eda62e.jpg" class="gallery-img">
        <img src="https://i.pinimg.com/originals/0c/0f/f3/0c0ff3dbcdbb1472ce5a0b1a9b4a9442.jpg" class="gallery-img">
        <img src="https://i.pinimg.com/originals/85/9b/23/859b237185ea53d485749927e744a3ac.jpg" class="gallery-img">
        <img src="https://i.pinimg.com/originals/ef/05/0e/ef050e8f265136cdaf7876deea2ccb83.jpg" class="gallery-img">
        <img src="https://i.pinimg.com/564x/cb/b8/12/cbb8122b9dcdc67aaf05e372168836d7.jpg" class="gallery-img">
        
    </div>
</body>
</html>
