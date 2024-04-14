<!-- 
本项目作者微信:sjh201011040876
作者微信:sjh201011040876
留言板输入框可以伸缩
留言的内容在message/message.txt
 -->
<!DOCTYPE html>
<html lang="en">

<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge, chrome=1">
    <meta name="viewport" content="width=device-width,initial-scale=1,minimum-scale=1,maximum-scale=1,user-scalable=no,viewport-fit=cover">
    <meta name="applicable-device" content="pc, mobile">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="renderer" content="webkit">
    <meta name="force-rendering" content="webkit">
    <title>孙总的个人主页v2.1(非原创)</title>
    <meta name="keywords" content="孙总的个人主页">
    <meta name="description" content="孙总的个人主页">
    <meta name="author" content="孙总的个人主页">
    <meta property="og:type" content="index">
    <meta property="og:title" content="孙总的个人主页">
    <meta property="og:description" content="孙总的个人主页">
    <link rel="shortcut icon" href="favicon.png" type="image/x-icon">
    <link rel="stylesheet" href="css/style.css">
    <div id="xf-MusicPlayer" data-cdnName="https://player.xfyun.club/js" data-themeColor="xf-original"></div>
    <link rel="stylesheet" href="css/clock.css">
    <!-- 悬浮按钮 -->
    <div class="adiv" id="back-to-top">
        <svg t="1710053351094" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="2614" width="32" height="32">
            <path d="M436.48 814.592a21.76 21.76 0 0 0-21.76 21.76v107.52a21.76 21.76 0 0 0 43.52 0v-107.52a21.76 21.76 0 0 0-21.76-21.76zM516.096 819.2a22.016 22.016 0 0 0-22.016 22.016v159.744a22.016 22.016 0 0 0 44.032 0v-158.976a22.016 22.016 0 0 0-22.016-22.784zM768 438.784C773.376 143.104 528.896 9.216 512 0c-16.384 8.704-260.864 142.592-256 438.272a192.256 192.256 0 0 0-93.696 187.392c8.192 98.304 104.448 163.584 141.056 160s25.6-30.72 25.6-30.72l12.544-51.2s54.272 81.92 71.68 81.92h197.632c15.616 0 71.68-81.92 71.68-81.92l12.544 51.2s-10.752 27.392 25.6 30.72 132.864-61.696 141.056-160a192.256 192.256 0 0 0-93.696-186.88z m-256-14.592a102.4 102.4 0 1 1 102.4-102.4 102.4 102.4 0 0 1-102.4 102.4zM588.8 819.2a21.76 21.76 0 0 0-21.76 21.76v76.8a21.76 21.76 0 1 0 43.52 0v-76.8A21.76 21.76 0 0 0 588.8 819.2z" p-id="2615"></path>
        </svg>
    </div>
    <!-- 侧边栏 -->
    <div class="sidebar" id="sidebar">
        <div class="box_marqueep">
            <form>
                <marquee class="marqueep mx_font_div_size">广告位招租：有意者联系</marquee>
        </div>
        <div class="box_img_you">
            <button onclick='location.href=("替换为你的网址")' class="button">友情链接1号</button>
            <button onclick='location.href=("替换为你的网址")' class="button padbox">友情链接2号</button>
            <button onclick='location.href=("替换为你的网址")' class="button padbox">友情链接3号</button>
            <button onclick='location.href=("替换为你的网址")' class="button padbox">友情链接4号</button>
            <button onclick='location.href=("替换为你的网址")' class="button padbox">友情链接5号</button>
        </div>
        </form>
    </div>
    <div class="overlay" id="overlay"></div>
    <button class="openbtn" onclick="toggleSidebar()">
        <div class="containera">
            <div class="menu-btn one">
                <input type="checkbox">
                <span></span>
                <span></span>
                <span></span>
            </div>
    </button>
    <!-- 头像/名称/打字机/联系 -->
    <div class="box_head">
        <form>
            <div class="image">
                <img src="images/111.png">
                <!-- 将下面链接中的微信号填成自己的 -->
                <img src="https://q.qlogo.cn/headimg_dl?dst_uin=3125591974&spec=640&img_type=jpg">
            </div>
            <p class="box_image_p">孙总的个人主页</p>
            <p id="p" class="p2a"></p>
            <!-- 联系按钮 1-->
            <div class="icon-div">
                <a href="https://qm.qq.com/q/rtqkRAAzZK">
                    <div class="icon-img">
                        <svg t="1707741471422" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="2300" width="200" height="200">
                            <path d="M512 0C229.003636 0 0 229.003636 0 512s229.003636 512 512 512 512-229.003636 512-512S794.996364 0 512 0z m210.385455 641.396364c-7.447273 9.309091-26.996364-1.861818-41.89091-32.581819-3.723636 13.963636-13.032727 36.305455-34.443636 64.232728 35.374545 8.378182 44.683636 42.821818 33.512727 61.44-8.378182 13.032727-26.996364 24.203636-59.578181 24.203636-58.647273 0-83.781818-15.825455-95.883637-26.996364-1.861818-2.792727-5.585455-3.723636-10.24-3.723636-4.654545 0-7.447273 0.930909-10.24 3.723636-11.170909 11.170909-37.236364 26.996364-95.883636 26.996364-32.581818 0-52.130909-11.170909-59.578182-24.203636-12.101818-18.618182-1.861818-53.061818 33.512727-61.44-20.48-27.927273-29.789091-50.269091-34.443636-64.232728-13.963636 30.72-34.443636 42.821818-41.890909 32.581819-5.585455-8.378182-8.378182-26.065455-7.447273-38.167273 3.723636-46.545455 34.443636-85.643636 53.061818-106.123636-2.792727-5.585455-8.378182-40.029091 14.894546-63.301819v-1.861818c0-92.16 65.163636-158.254545 148.014545-158.254545 81.92 0 148.014545 66.094545 148.014546 158.254545v1.861818c23.272727 23.272727 17.687273 57.716364 14.894545 63.301819 17.687273 20.48 49.338182 59.578182 53.061818 106.123636 0.930909 12.101818-0.930909 29.789091-7.447272 38.167273z" fill="#30A5DD" p-id="2301"></path>
                        </svg>
                    </div>
                </a>
            </div>
            <!-- 联系按钮 2 -->
            <div class="icon-div">
                <a href="https://b23.tv/YHZSH51">
                    <div class="icon-img">
                        <svg t="1707741522447" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="3291" width="200" height="200">
                            <path d="M512 512m-512 0a512 512 0 1 0 1024 0 512 512 0 1 0-1024 0Z" fill="#EF6D8C" p-id="3292"></path>
                            <path d="M711.8592 471.5264a182.6304 182.6304 0 0 1 20.48-2.2272 382.1312 382.1312 0 0 1 6.8608 58.0608c-2.048 0.384-16.512 3.712-16.512 3.712-1.1008-7.68-10.5728-54.7328-10.752-59.5456m27.8272-5.376l7.68 60.288c3.8912-0.1792 19.6608-1.3056 21.1456-1.4848-2.2272-22.8096-6.1184-58.88-6.1184-58.88a58.0864 58.0864 0 0 0-22.6304 0m-15.0272 83.6608a131.6352 131.6352 0 0 1 46.7456-4.4544c6.2976 22.8096 17.92 150.8352 18.9184 156.0064-7.68 0.9216-33.28 3.1488-35.4304 3.712-1.664-9.6512-30.2336-149.1456-30.2336-155.264m127.0784-76.8a199.68 199.68 0 0 1 20.48-0.5376 472.6528 472.6528 0 0 1 0.1792 58.4448l-16.512 1.4848c-0.3584-7.424-4.4544-54.3744-4.0704-59.3664m28.0064-1.4848l1.4848 59.5456c3.8912 0 19.4816 0.9216 21.1456 0.7424-0.3584-22.8096 0-58.88 0-58.88a102.4 102.4 0 0 0-22.6304-1.4848m-23.936 79.9488a133.9392 133.9392 0 0 1 46.9504 0.9216c2.56 26.7264 2.2272 151.1936 2.56 156.3904-7.9872 0-33.28 0.3584-35.4304 0.7424-0.3584-9.6512-14.6432-151.936-14.1056-158.0544m-81.4336-153.0624c20.224 103.1424 35.6352 279.3984 36.1728 290.7136 0 0 15.9488 0.3584 33.9456 1.4848-10.5728-111.1296-23.552-288.6656-23.3728-294.4-4.4544-5.12-46.7456 2.2272-46.7456 2.2272m-44.5184 243.968c-3.8912-28.9536-107.52-61.7728-165.6576-51.2 0 0-7.2448-63.8208-10.0096-125.5936a1282.944 1282.944 0 0 1 0.1792-113.1776 439.552 439.552 0 0 0-68.4544 25.6 2678.2976 2678.2976 0 0 1 46.7456 352.4864 319.2064 319.2064 0 0 0 85.1456-7.04c53.76-10.3936 117.4272-42.8544 112.0512-81.0752m-126.5152 52.1216l-9.088-65.4848a475.1872 475.1872 0 0 1 64 23.3728 595.9936 595.9936 0 0 1-54.912 42.112m-322.56-223.0016a182.6304 182.6304 0 0 1 20.48-2.2272 383.8208 383.8208 0 0 1 6.8608 58.0608c-2.048 0.384-16.512 3.712-16.512 3.712-1.1264-7.68-10.5728-54.7328-10.752-59.5456m27.8272-5.376l7.68 60.288c3.8912-0.1792 19.6608-1.3056 21.1456-1.4848-2.4064-22.8096-6.1184-58.88-6.1184-58.88a58.0864 58.0864 0 0 0-22.6304 0m-15.0272 83.6608a131.6608 131.6608 0 0 1 46.7456-4.4544c6.2976 22.8096 17.92 150.8352 18.9184 156.0064-7.68 0.9216-33.28 3.1488-35.4304 3.712-1.664-9.6512-30.2336-149.1456-30.2336-155.264m127.0784-76.8a199.5264 199.5264 0 0 1 20.48-0.5376 473.6 473.6 0 0 1 0.1792 58.4448l-16.512 1.4848c-0.3584-7.424-4.2752-54.3744-4.0704-59.3664m28.0064-1.4848l1.4848 59.5456c3.8912 0 19.4816 0.9216 21.1456 0.7424-0.3584-22.8096 0-58.88 0-58.88a114.8672 114.8672 0 0 0-22.6304-1.4848m-23.936 79.9488a133.9392 133.9392 0 0 1 46.9504 0.9216c2.56 26.7264 2.2272 151.1936 2.56 156.3904-7.9872 0-33.28 0.3584-35.4304 0.7424-0.1792-9.6512-14.6432-151.936-14.1056-158.0544m-81.4336-153.0624c20.224 103.1424 35.6096 279.3984 36.1728 290.7136 0 0 15.9488 0.3584 33.9456 1.4848-10.5728-111.1296-23.552-288.6656-23.3728-294.6048-4.4544-4.8128-46.7456 2.4064-46.7456 2.4064m-44.5184 243.968c-3.8912-28.9536-107.52-61.7728-165.6832-51.2 0 0-7.2448-63.8208-10.0096-125.5936a1282.944 1282.944 0 0 1 0.1792-113.1776 461.2352 461.2352 0 0 0-68.4544 25.6 2676.8384 2676.8384 0 0 1 46.7456 352.4864 319.2576 319.2576 0 0 0 85.1456-7.04c53.76-10.3936 117.4272-42.8544 112.0512-81.0752m-126.5152 52.1216l-9.088-65.4848a474.5216 474.5216 0 0 1 64 23.3728 594.9952 594.9952 0 0 1-54.912 42.112" fill="#BF1E3F" p-id="3293"></path>
                            <path d="M737.4592 445.9264a182.6304 182.6304 0 0 1 20.48-2.2272 382.1312 382.1312 0 0 1 6.8608 58.0608c-2.048 0.384-16.512 3.712-16.512 3.712-1.1008-7.68-10.5728-54.7328-10.752-59.5456m27.8272-5.376l7.68 60.288c3.8912-0.1792 19.6608-1.3056 21.1456-1.4848-2.2272-22.8096-6.1184-58.88-6.1184-58.88a58.0864 58.0864 0 0 0-22.6304 0m-15.0272 83.6608a131.6352 131.6352 0 0 1 46.7456-4.4544c6.2976 22.8096 17.92 150.8352 18.9184 156.0064-7.68 0.9216-33.28 3.1488-35.4304 3.712-1.664-9.6512-30.2336-149.1456-30.2336-155.264m127.0784-76.8a199.68 199.68 0 0 1 20.48-0.5376 472.6528 472.6528 0 0 1 0.1792 58.4448l-16.512 1.4848c-0.3584-7.424-4.4544-54.3744-4.0704-59.3664m28.0064-1.4848l1.4848 59.5456c3.8912 0 19.4816 0.9216 21.1456 0.7424-0.3584-22.8096 0-58.88 0-58.88a102.4 102.4 0 0 0-22.6304-1.4848m-23.936 79.9488a133.9392 133.9392 0 0 1 46.9504 0.9216c2.56 26.7264 2.2272 151.1936 2.56 156.3904-7.9872 0-33.28 0.3584-35.4304 0.7424-0.3584-9.6512-14.6432-151.936-14.1056-158.0544m-81.4336-153.0624c20.224 103.1424 35.6352 279.3984 36.1728 290.7136 0 0 15.9488 0.3584 33.9456 1.4848-10.5728-111.1296-23.552-288.6656-23.3728-294.4-4.4544-5.12-46.7456 2.2272-46.7456 2.2272m-44.5184 243.968c-3.8912-28.9536-107.52-61.7728-165.6576-51.2 0 0-7.2448-63.8208-10.0096-125.5936a1282.944 1282.944 0 0 1 0.1792-113.1776 439.552 439.552 0 0 0-68.4544 25.6 2678.2976 2678.2976 0 0 1 46.7456 352.4864 319.2064 319.2064 0 0 0 85.1456-7.04c53.76-10.3936 117.4272-42.8544 112.0512-81.0752m-126.5152 52.1216l-9.088-65.4848a475.1872 475.1872 0 0 1 64 23.3728 595.9936 595.9936 0 0 1-54.912 42.112m-322.56-223.0016a182.6304 182.6304 0 0 1 20.48-2.2272 383.8208 383.8208 0 0 1 6.8608 58.0608c-2.048 0.384-16.512 3.712-16.512 3.712-1.1264-7.68-10.5728-54.7328-10.752-59.5456m27.8272-5.376l7.68 60.288c3.8912-0.1792 19.6608-1.3056 21.1456-1.4848-2.4064-22.8096-6.1184-58.88-6.1184-58.88a58.0864 58.0864 0 0 0-22.6304 0m-15.0272 83.6608a131.6608 131.6608 0 0 1 46.7456-4.4544c6.2976 22.8096 17.92 150.8352 18.9184 156.0064-7.68 0.9216-33.28 3.1488-35.4304 3.712-1.664-9.6512-30.2336-149.1456-30.2336-155.264m127.0784-76.8a199.5264 199.5264 0 0 1 20.48-0.5376 473.6 473.6 0 0 1 0.1792 58.4448l-16.512 1.4848c-0.3584-7.424-4.2752-54.3744-4.0704-59.3664m28.0064-1.4848l1.4848 59.5456c3.8912 0 19.4816 0.9216 21.1456 0.7424-0.3584-22.8096 0-58.88 0-58.88a114.8672 114.8672 0 0 0-22.6304-1.4848m-23.936 79.9488a133.9392 133.9392 0 0 1 46.9504 0.9216c2.56 26.7264 2.2272 151.1936 2.56 156.3904-7.9872 0-33.28 0.3584-35.4304 0.7424-0.1792-9.6512-14.6432-151.936-14.1056-158.0544m-81.4336-153.0624c20.224 103.1424 35.6096 279.3984 36.1728 290.7136 0 0 15.9488 0.3584 33.9456 1.4848-10.5728-111.1296-23.552-288.6656-23.3728-294.6048-4.4544-4.8128-46.7456 2.4064-46.7456 2.4064m-44.5184 243.968c-3.8912-28.9536-107.52-61.7728-165.6832-51.2 0 0-7.2448-63.8208-10.0096-125.5936a1282.944 1282.944 0 0 1 0.1792-113.1776 461.2352 461.2352 0 0 0-68.4544 25.6 2676.8384 2676.8384 0 0 1 46.7456 352.4864 319.2576 319.2576 0 0 0 85.1456-7.04c53.76-10.3936 117.4272-42.8544 112.0512-81.0752m-126.5152 52.1216l-9.088-65.4848a474.5216 474.5216 0 0 1 64 23.3728 594.9952 594.9952 0 0 1-54.912 42.112" fill="#FFFFFF" p-id="3294"></path>
                        </svg>
                    </div>
                </a>
            </div>
            <!-- 联系按钮 3 -->
            <div class="icon-div">
                <a href="weixin://">
                    <div class="icon-img">
                        <svg t="1707741586222" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="4504" width="200" height="200">
                            <path d="M352.814545 385.396364m-33.512727 0a33.512727 33.512727 0 1 0 67.025455 0 33.512727 33.512727 0 1 0-67.025455 0Z" fill="#50B674" p-id="4505"></path>
                            <path d="M502.690909 384.465455m-33.512727 0a33.512727 33.512727 0 1 0 67.025454 0 33.512727 33.512727 0 1 0-67.025454 0Z" fill="#50B674" p-id="4506"></path>
                            <path d="M576.232727 534.341818m-23.272727 0a23.272727 23.272727 0 1 0 46.545455 0 23.272727 23.272727 0 1 0-46.545455 0Z" fill="#50B674" p-id="4507"></path>
                            <path d="M694.458182 536.203636m-23.272727 0a23.272727 23.272727 0 1 0 46.545454 0 23.272727 23.272727 0 1 0-46.545454 0Z" fill="#50B674" p-id="4508"></path>
                            <path d="M512 0C229.003636 0 0 229.003636 0 512s229.003636 512 512 512 512-229.003636 512-512S794.996364 0 512 0z m-87.505455 630.225455c-26.996364 0-48.407273-5.585455-75.403636-11.17091l-75.403636 37.236364 21.410909-64.232727c-53.992727-37.236364-85.643636-85.643636-85.643637-145.221818 0-102.4 96.814545-182.458182 215.04-182.458182 105.192727 0 198.283636 64.232727 216.901819 150.807273-6.516364-0.930909-13.963636-0.930909-20.48-0.93091-102.4 0-182.458182 76.334545-182.458182 170.356364 0 15.825455 2.792727 30.72 6.516363 44.683636-7.447273 0-13.963636 0.930909-20.48 0.93091z m314.647273 75.403636l15.825455 53.992727-58.647273-32.581818c-21.410909 5.585455-42.821818 11.170909-64.232727 11.170909-102.4 0-182.458182-69.818182-182.458182-155.461818s80.058182-155.461818 182.458182-155.461818c96.814545 0 182.458182 69.818182 182.458182 155.461818 0 47.476364-31.650909 90.298182-75.403637 122.88z" fill="#50B674" p-id="4509"></path>
                        </svg>
                    </div>
                </a>
            </div>
    </div>
    </form>

    <!-- 时间/日期 -->
    <div class="box padbox">
        <form>
            <div id="time1"></div>
    </div>
    </form>
    <!-- 一言 -->
    <div class="box padbox">
        <form>
            <div id="cardContainer"></div>
        </form>
    </div>
    <div class="mx_container padbox">
        <div class="box mx_clock_div">
            <form class="mx_clock">
                <center>
                    <div class="clock">
                        <div class="hand hours"></div>
                        <div class="hand minutes"></div>
                        <div class="hand seconds"></div>
                        <div class="point"></div>
                        <div class="marker">
                            <span class="marker__1"></span>
                            <span class="marker__2"></span>
                            <span class="marker__3"></span>
                            <span class="marker__4"></span>
                        </div>
                    </div>
                </center>
            </form>
        </div>
        <!-- 信息 -->
        <div class="box mx_information_div">
            <form class="mx_information">
                <p id="greeting"></p>
                <p id="myIP"></p>
                <p id="browser"></p>
                <p id="os"></p>
            </form>
        </div>
    </div>
    <!-- 留言板 开始 -->
    <div class="liuyan">
        <div class="container">
            <p class="box_size">留言板</p>
            <form id="messageForm" action="message/save_message.php" method="POST">
                <textarea name="message" placeholder="请输入留言内容" class="input_input"></textarea>
                <button type="submit" class="button_tijiao">提交</button>
            </form>
        </div>
    </div>
    <!-- 留言板 结束 -->
    <div class="div_box">
        <p class="canyu">我的站点</p>
        <button onclick='location.href=("替换为你的网址")' class="button">暂无网站</button>
        <button onclick='location.href=("替换为你的网址")' class="button padbox">暂无网站</button>
        <button onclick='location.href=("替换为你的网址")' class="button padbox">暂无网站</button>
        <button onclick='location.href=("替换为你的网址")' class="button padbox">暂无网站</button><br>
    </div>
    <div class="box_img">
        <img src="https://www.loliapi.com/acg/pc/" class="img_box_meiri">
    </div>
    <!-- 页脚 -->
    <div class="footer">
        <p>孙总的个人微信：sjh201011040876</p>
        <p>ICP备案: 已备案</p>
        <p>公安备案: 已备案</p>
        <span id="runtime_span"></span>
    </div>
    <!--底部波浪开始-->
    <div class="wiiuii_layout">
        <svg class="editorial" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" viewBox="0 24 150 28" preserveAspectRatio="none">
            <defs>
                <path id="gentle-wave" d="M-160 44c30 0 
    58-18 88-18s
    58 18 88 18 
    58-18 88-18 
    58 18 88 18
    v44h-352z" />
            </defs>
            <g class="parallax">
                <use xlink:href="#gentle-wave" x="50" y="0" fill="#4579e2" />
                <use xlink:href="#gentle-wave" x="50" y="3" fill="#3461c1" />
                <use xlink:href="#gentle-wave" x="50" y="6" fill="#2d55aa" />
            </g>
        </svg>
    </div>
    <!--底部波浪结束-->
    </body>

    <script>
        function show_runtime() {
            window.setTimeout("show_runtime()", 1000);
            X = new
            Date("02/22/2024 15:10:00");
            Y = new Date();
            T = (Y.getTime() - X.getTime());
            M = 24 * 60 * 60 * 1000;
            a = T / M;
            A = Math.floor(a);
            b = (a - A) * 24;
            B = Math.floor(b);
            c = (b - B) * 60;
            C = Math.floor((b - B) * 60);
            D = Math.floor((c - C) * 60);
            runtime_span.innerHTML = "本站勉强运行: " + A + "天" + B + "小时" + C + "分" + D + "秒"
        }
        show_runtime();

        function generateQuotes() {
            const apiUrl = 'https://v1.hitokoto.cn/';

            return fetch(apiUrl)
                .then(response => response.json())
                .then(data => {
                    const quote = data.hitokoto;
                    return quote;
                })
                .catch(error => {
                    console.error('随机文案获取失败:', error);
                    showMessage("获取随机文案失败");
                });
        }

        async function createCard() {
            const cardContainer = document.getElementById('cardContainer');
            cardContainer.innerHTML = '';

            for (let i = 0; i < 1; i++) {
                const quote = await generateQuotes();
                const card = document.createElement('div');
                card.classList.add('card');
                card.textContent = quote;

                const copyButton = document.createElement('button');
                copyButton.classList.add('copy-button')

                copyButton.addEventListener('click', () => {
                    copyToClipboard(quote, card);
                });


                cardContainer.appendChild(card);
            }
        }

        function restart() {
            createCard();
        }
        createCard();

        function toggleSidebar() {
            const sidebar = document.getElementById('sidebar');
            sidebar.classList.toggle('open');
            const overlay = document.getElementById('overlay');
            overlay.classList.toggle('show');
        }
    </script>

</html>
<script src="https://player.xfyun.club/js/xf-MusicPlayer/js/xf-MusicPlayer.min.js"></script>
<script src="js/script.js"></script>
<script src="js/sakura.js"></script>
<script src="js/clock.js"></script><!-- 
本项目作者微信:sjh201011040876
作者微信:sjh201011040876
留言板输入框可以伸缩
留言的内容在message/message.txt
 -->
<!DOCTYPE html>
<html lang="en">

<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge, chrome=1">
    <meta name="viewport" content="width=device-width,initial-scale=1,minimum-scale=1,maximum-scale=1,user-scalable=no,viewport-fit=cover">
    <meta name="applicable-device" content="pc, mobile">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="renderer" content="webkit">
    <meta name="force-rendering" content="webkit">
    <title>孙总的个人主页v2.1(非原创)</title>
    <meta name="keywords" content="孙总的个人主页">
    <meta name="description" content="孙总的个人主页">
    <meta name="author" content="孙总的个人主页">
    <meta property="og:type" content="index">
    <meta property="og:title" content="孙总的个人主页">
    <meta property="og:description" content="孙总的个人主页">
    <link rel="shortcut icon" href="favicon.png" type="image/x-icon">
    <link rel="stylesheet" href="css/style.css">
    <div id="xf-MusicPlayer" data-cdnName="https://player.xfyun.club/js" data-themeColor="xf-original"></div>
    <link rel="stylesheet" href="css/clock.css">
    <!-- 悬浮按钮 -->
    <div class="adiv" id="back-to-top">
        <svg t="1710053351094" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="2614" width="32" height="32">
            <path d="M436.48 814.592a21.76 21.76 0 0 0-21.76 21.76v107.52a21.76 21.76 0 0 0 43.52 0v-107.52a21.76 21.76 0 0 0-21.76-21.76zM516.096 819.2a22.016 22.016 0 0 0-22.016 22.016v159.744a22.016 22.016 0 0 0 44.032 0v-158.976a22.016 22.016 0 0 0-22.016-22.784zM768 438.784C773.376 143.104 528.896 9.216 512 0c-16.384 8.704-260.864 142.592-256 438.272a192.256 192.256 0 0 0-93.696 187.392c8.192 98.304 104.448 163.584 141.056 160s25.6-30.72 25.6-30.72l12.544-51.2s54.272 81.92 71.68 81.92h197.632c15.616 0 71.68-81.92 71.68-81.92l12.544 51.2s-10.752 27.392 25.6 30.72 132.864-61.696 141.056-160a192.256 192.256 0 0 0-93.696-186.88z m-256-14.592a102.4 102.4 0 1 1 102.4-102.4 102.4 102.4 0 0 1-102.4 102.4zM588.8 819.2a21.76 21.76 0 0 0-21.76 21.76v76.8a21.76 21.76 0 1 0 43.52 0v-76.8A21.76 21.76 0 0 0 588.8 819.2z" p-id="2615"></path>
        </svg>
    </div>
    <!-- 侧边栏 -->
    <div class="sidebar" id="sidebar">
        <div class="box_marqueep">
            <form>
                <marquee class="marqueep mx_font_div_size">广告位招租：有意者联系</marquee>
        </div>
        <div class="box_img_you">
            <button onclick='location.href=("替换为你的网址")' class="button">友情链接1号</button>
            <button onclick='location.href=("替换为你的网址")' class="button padbox">友情链接2号</button>
            <button onclick='location.href=("替换为你的网址")' class="button padbox">友情链接3号</button>
            <button onclick='location.href=("替换为你的网址")' class="button padbox">友情链接4号</button>
            <button onclick='location.href=("替换为你的网址")' class="button padbox">友情链接5号</button>
        </div>
        </form>
    </div>
    <div class="overlay" id="overlay"></div>
    <button class="openbtn" onclick="toggleSidebar()">
        <div class="containera">
            <div class="menu-btn one">
                <input type="checkbox">
                <span></span>
                <span></span>
                <span></span>
            </div>
    </button>
    <!-- 头像/名称/打字机/联系 -->
    <div class="box_head">
        <form>
            <div class="image">
                <img src="images/111.png">
                <!-- 将下面链接中的微信号填成自己的 -->
                <img src="https://q.qlogo.cn/headimg_dl?dst_uin=3125591974&spec=640&img_type=jpg">
            </div>
            <p class="box_image_p">孙总的个人主页</p>
            <p id="p" class="p2a"></p>
            <!-- 联系按钮 1-->
            <div class="icon-div">
                <a href="https://qm.qq.com/q/rtqkRAAzZK">
                    <div class="icon-img">
                        <svg t="1707741471422" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="2300" width="200" height="200">
                            <path d="M512 0C229.003636 0 0 229.003636 0 512s229.003636 512 512 512 512-229.003636 512-512S794.996364 0 512 0z m210.385455 641.396364c-7.447273 9.309091-26.996364-1.861818-41.89091-32.581819-3.723636 13.963636-13.032727 36.305455-34.443636 64.232728 35.374545 8.378182 44.683636 42.821818 33.512727 61.44-8.378182 13.032727-26.996364 24.203636-59.578181 24.203636-58.647273 0-83.781818-15.825455-95.883637-26.996364-1.861818-2.792727-5.585455-3.723636-10.24-3.723636-4.654545 0-7.447273 0.930909-10.24 3.723636-11.170909 11.170909-37.236364 26.996364-95.883636 26.996364-32.581818 0-52.130909-11.170909-59.578182-24.203636-12.101818-18.618182-1.861818-53.061818 33.512727-61.44-20.48-27.927273-29.789091-50.269091-34.443636-64.232728-13.963636 30.72-34.443636 42.821818-41.890909 32.581819-5.585455-8.378182-8.378182-26.065455-7.447273-38.167273 3.723636-46.54
