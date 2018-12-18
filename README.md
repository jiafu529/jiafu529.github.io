# jiafu529.github.io
看星星
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html,
        body {
            min-height: 100%;
        }

        body {
            font-family: "Microsoft YaHei";
            font-size: 14px;
            color: #333;
        }

        h1,
        h2,
        h3,
        h4,
        h5,
        h6 {
            font-weight: normal;
        }

        ul,
        ol {
            list-style: none;
        }

        a {
            text-decoration: none;
            color: #232323;
        }

        img {
            border: none;
            vertical-align: middle;
        }

        .clearfix:after {
            content: ".";
            width: 0;
            height: 0;
            visibility: hidden;
            display: block;
            clear: both;
            overflow: hidden;
        }

        .fl {
            float: left
        }

        .fr {
            float: right
        }

        table {
            border-collapse: collapse;
            table-layout: fixed;
        }

        input,
        textarea {
            outline: none;
            border: none;
        }

        .body {
            width: 1000px;
            margin: 0 auto;
        }

        .head {
            height: 70px;
            background-color: #c20c0c;
        }

        .h a {
            font-size: 18px;
            display: block;
            width: 207px;
            height: 70px;
            background: url(image/wyx.png);
            text-indent: -999px;
            overflow: hidden;
        }

        .h {
            float: left;
        }

        .body ul li {
            float: left;
        }

        .head_in {
            position: relative;
        }

        .head_in ul {
            position: absolute;
            right: 100px;
            top: 22px;cursor: pointer;
        }

        .head_in ul li {
            font-size: 18px;
            color: #fff;
            font-weight: 700;
            margin-left: 60px;
        }

        .box {
            height: 460px;
            overflow: hidden;
            position: relative;
        }

        .box ul {
            position: absolute;
            left: 0;
            top: 0px;
            width: 5000px;
        }

        .box ul li {
            width: 1000px;
            float: left;
        }

        .box li img {
            width: 100%;
        }

        .box ol {
            position: absolute;
            left: 50%;
            bottom: 10px;
            margin-left: -100px;
        }

        .box ol li {
            margin-right: 20px;
            float: left;
            width: 40px;
            height: 10px;
            background-color: #fff;
            border-radius: 3px;
        }

        .box .bgc {
            background-color: #c20c0c;
        }

        .box span {
            width: 40px;
            height: 40px;
            position: absolute;
            left: 5px;
            top: 50%;
            margin-top: -20px;
            background: #000;
            cursor: pointer;
            line-height: 40px;
            text-align: center;
            font-weight: bold;
            font-family: '黑体';
            font-size: 30px;
            color: #fff;
            opacity: 0.3;
            border: 1px solid #fff;
        }

        #right {
            right: 5px;
            left: auto;
        }

        .box1 {
            border-left: 1px solid #d9d9d9;
            border-right: 1px solid #d9d9d9;
            overflow: hidden;
        }

        .mover {
            padding-top: 35px;
            width: 950px;
            margin: 0 auto;
            border-bottom: 2px solid #c20c0c;
            overflow: hidden;
        }

        .mover img {
            margin-bottom: 10px;
            margin-left: 10px;
        }

        .mover h2 {
            font-size: 24px;
            margin-top: -7px;
            margin-left: 10px;
        }

        .mover ul li {
            float: left;
            margin-left: 10px;
            ;
            color: #8b8b8b;
        }

        .mover_t ul li {
            float: left;
            margin-left: 30px;
            margin-right: 28px;
            margin-top: 20px;
            width: 190px;
            height: 320px;
            position: relative;
        }

        .mover_t li img {
            width: 100%;
        }

        .mover_t li p {
            margin-top: 10px;
            color: black;
            font-size: 18px;
            font-weight: 500;
        }

        .mover_t li p span {
            display: inline-block;
            padding: 1px;
            height: 20px;
            width: 54px;
            border: 2px solid #d63636;
            border-radius: 3px;
            color: #d63636;
            font-size: 12px;
            font-weight: 700;
        }

        .mover_in {
            height: 38px;
            width: 190px;
            background: rgba(0, 0, 0, .5);
            position: absolute;
            top: 152px;
        }

        .mover_in span {
            margin-top: 11px;
            margin-left: 10px;
            display: inline-block;
            width: 20px;
            height: 20px;
            /* background: url(image/2129.png); */
        }

        .mover_t .mover_in p {
            display: inline-block;
            color: #b8b8b7;
            margin-top: 0;
            vertical-align: middle;
        }

        #span {
            float: right;
            margin-right: 10px;
            margin-bottom: 5px;
        }

        .footer {
            margin-top: 10px;
            height: 125px;
            background-color: #f2f2f2;
            border-top: 1px solid #d8d8d8;
        }

        .foot_l ul li {
            float: left;
            color: #bbbbbb;
            font-size: 12px;
            margin-right: 10px;
            margin-top: 40px;
        }

        .foot_l p {
            float: left;
            margin-top: 10px;
            font-size: 12px;
        }

        .foot_r span {
            display: inline-table;
            width: 54px;
            height: 62px;
            margin-top: 20px;
            margin-left: 35px;

        }
    </style>
</head>

<body>
    <div class="head">
        <div class="body head_in">
            <h1 class="h"><a href="#">网易云音乐</a></h1>
            <ul class="fl">
                <li>推荐</li>
                <li>排行榜</li>
                <li>歌单</li>
                <li>主播电台</li>
                <li>歌手</li>
                <li>新碟上架</li>
            </ul>
        </div>
    </div>
    <div class="box body" id="lbt">
        <ul>
            <li><img src="image/lbt1.png" alt=""></li>
            <li><img src="image/lbt2.png" alt=""></li>
            <li><img src="image/lbt3.png" alt=""></li>
            <li><img src="image/lbt4.png" alt=""></li>
        </ul>
        <ol>
            <!-- <li class="bgc"></li>
            <li></li>
            <li></li>
            <li></li> -->
        </ol>
        <span id="left">&lt;</span>
        <span id="right">&gt;</span>
    </div>
    <div class="body box1">
        <div class="mover">
            <img src="image/hd.png" alt="" class="fl">
            <h2 class="fl">热门推荐</h2>
            <ul>
                <li>华语</li>
                <li>丨</li>
                <li>流行</li>
                <li>丨</li>
                <li>摇滚</li>
                <li>丨</li>
                <li>民谣</li>
                <li>丨</li>
                <li>电子</li>
            </ul>
            <a href="#" class="fr">更多</a>
        </div>
        <div class="mover_t">
            <ul>
                <li>
                    <img src="image/li1.jpg" alt="">
                    <p>华语速爆新歌</p>
                    <div class="mover_in">
                        <span><img src="image/2129.png" alt=""></span>
                        <p>5254万</p>
                        <span id="span"><img src="image/2201.png" alt=""></span>

                    </div>
                </li>
                <li>
                    <img src="image/li2.jpg" alt="">
                    <p>下一站，遇见相似的灵魂</p>
                    <div class="mover_in">
                        <span><img src="image/2129.png" alt=""></span>
                        <p>60万</p>
                        <span id="span"><img src="image/2201.png" alt=""></span>

                    </div>
                </li>
                <li>
                    <img src="image/li3.jpg" alt="">
                    <p>你的名字美如诗</p>
                    <div class="mover_in">
                        <span><img src="image/2129.png" alt=""></span>
                        <p>295万</p>
                        <span id="span"><img src="image/2201.png" alt=""></span>

                    </div>
                </li>
                <li>
                    <img src="image/li4.jpg" alt="">
                    <p><span>电台节目</span> 听见肖邦</p>
                    <div class="mover_in">
                        <span><img src="image/2129.png" alt=""></span>
                        <p>9835</p>
                        <span id="span"><img src="image/2201.png" alt=""></span>

                    </div>
                </li>
                <li>
                    <img src="image/li5.jpg" alt="">
                    <p>「震撼心灵的史诗音乐」</p>
                    <div class="mover_in">
                        <span><img src="image/2129.png" alt=""></span>
                        <p>4364万</p>
                        <span id="span"><img src="image/2201.png" alt=""></span>

                    </div>
                </li>
                <li>
                    <img src="image/li6.jpg" alt="">
                    <p><span>电台节目</span> 霸凌、性侵，我用余生逃离我的童年</p>
                    <div class="mover_in">
                        <span><img src="image/2129.png" alt=""></span>
                        <p>26202</p>
                        <span id="span"><img src="image/2201.png" alt=""></span>

                    </div>
                </li>
                <li>
                    <img src="image/li7.jpg" alt="">
                    <p>「英伦摇滚」唱片中的昔日时光</p>
                    <div class="mover_in">
                        <span><img src="image/2129.png" alt=""></span>
                        <p>309万</p>
                        <span id="span"><img src="image/2201.png" alt=""></span>

                    </div>
                </li>
                <li>
                    <img src="image/li8.jpg" alt="">
                    <p><span>电台节目</span> 为什么越来越多人在朋友圈戒掉了情绪</p>
                    <div class="mover_in">
                        <span><img src="image/2129.png" alt=""></span>
                        <p>20万</p>
                        <span id="span"><img src="image/2201.png" alt=""></span>

                    </div>
                </li>
            </ul>
        </div>

    </div>
    <div class="footer">
        <div class="body">
            <div class="foot_l fl">
                <ul>
                    <li>关于网易</li>
                    <li>丨</li>
                    <li>客户服务</li>
                    <li>丨</li>
                    <li>服务条款</li>
                    <li>丨</li>
                    <li>网站导航</li>
                    <li>丨</li>
                    <li>意见反馈</li>
                </ul>
                <p>网易公司版权所有©1997-2017 杭州乐读科技有限公司运营：浙网文[2015] 0415-135号</p>

            </div>
            <div class="foot_r fr">
                <span><img src="image/711.png" alt=""></span>
                <span><img src="image/733.jpg" alt=""></span>
                <span><img src="image/805.png" alt=""></span>
                <span><img src="image/722.png" alt=""></span>
            </div>
        </div>
    </div>
</body>
<script>
    var lbt = document.getElementById('lbt')
    var ul = lbt.children[0];//图片盒子
    var ol = lbt.children[1];//标记盒子
    var left = document.getElementById('left');
    var right = document.getElementById('right');
    var imgWidth = lbt.offsetWidth;
    var index = 0;
    var count = ul.children.length; //ul中li的个数
    function animate(element, target) {
        clearInterval(element.timer);
        element.timer = setInterval(function () {
            var step = 10;
            var currentX = element.offsetLeft;
            step = target > currentX ? step : -step;
            if (Math.abs(target - currentX) <= Math.abs(step)) {
                clearInterval(element.timer);
                element.style.left = target + 'px';
                return;
            }
            element.style.left = currentX + step + 'px';
        }, 30)
    }
    for (var i = 0; i < count; i++) {
        var li = document.createElement('li');
        li.setAttribute('index', i); //设置标签属性，记录每个序号按钮的索引
        ol.appendChild(li);
        li.onclick = function () {
            for (var i = 0; i < count; i++) {
                ol.children[i].className = '';
            }
            this.className = 'bgc';
            var index = parseInt(this.getAttribute('index'));
            animate(ul, -index * imgWidth);
        }
    }
    ol.children[0].className = 'bgc';
    var firstLi = ul.children[0];
    ul.appendChild(firstLi.cloneNode(true))

    right.onclick = function () {
        if (index === count) {
            index = 0;
            ul.style.left = 0;
        }
        index++;
        if (index < count) {
            ol.children[index].onclick();
        } else {
            animate(ul, -index * imgWidth);
            for (var i = 0; i < count; i++) {
                ol.children[i].className = '';
            }
            ol.children[0].className = 'current';
        }
    };
    //点击左箭头显示上一张
    left.onclick = function () {
        if (index == 0) {
            index = count;
            ul.style.left = -index * imgWidth + 'px';
        }
        index--;
        ol.children[index].onclick();
    };
    var timer = setInterval(function () {
        right.onclick()
    }, 3000)
   
</script>

</html>
