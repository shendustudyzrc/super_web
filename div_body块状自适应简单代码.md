<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <title>div的第一个作业</title>
    <style type="text/javascript">

    </style>
    <style type="text/css">
        * {
            margin: 0px;
            padding: 0px;
        }

        #container {
            width: 100%;
            height: 100%;
        }
        /* //顶端块，高度为80px */
        .top {
            top: 0px;
            width: 100%;
            height: 80px;
            background: red;
        }
        /* //间距块 */
        .top-middle {
            width: 100%;
            height: 20px;
            background: white;
        }
        /* //中间块，高度通过jquery赋值的形式 */
        .middle {
            top: 100px;
            width: 100%;
            background: orange;
        }
        /* //间距块 */
        .middle-button {
            width: 100%;
            height: 20px;
            background: white;
        }
        /* //底部块，高度为80px */
        .bottom {
            position: fixed;
            bottom: 0px;
            width: 100%;
            height: 80px;
            background: green;
        }
    </style>
</head>
<body>
    <!-- //定义一个主容器 -->
    <div id="container">
        <div class="top">
        </div>
        <div class="top-middle">
        </div>
        <div class="middle">
        </div>
        <div class="middle-button">
        </div>
        <div class="bottom">
    
        </div>
    </div>
    <!-- //中间的那个区间块由于受到不同浏览器的限制，高度会有所相应的变化，所以用jquery获取页面高度，再减去两端固定的距离，即可得到相对距离 -->
    <script language="JavaScript">
        function test() {
            var s = "";
            s += "\r\n" + window.screen.height;
            var s1 = s - 300;
            var h = document.getElementsByClassName('middle')[0];
            h.style.height = s1 + "px";
        }
        test();
    </script>
</body>
</html>