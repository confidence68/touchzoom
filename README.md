Scale Image
=========
##  简介

是一个纯js写的手机端图片放大，多点触控插件

## 用法

### html：

        <ul class="list">
            <li><img src="themes/images/2.jpg" /></li>
            <li><img src="themes/images/3.jpg" /></li>
            <li><img src="themes/images/4.jpg" /></li>
            <li><img src="themes/images/5.jpg" /></li>
            <li><img src="themes/images/1.jpg" /></li>
        </ul>

        <section class="imgzoom_pack">
            <div class="imgzoom_x">X</div>
            <div class="imgzoom_img"><img src="" /></div>
        </section>

### js

很简单，直接饮用<script src="js/scale.js"></script>然后

    ImagesZoom.init({
                    "elem": ".list"
                });

在 init中传一个elem就可以了。