<template>
    <div id="app">
        <header class="header">
            <a class="button" href="#">董旭阳 </a>
            <div class="enum">
                <a class="button" href="#">主页</a>
                <a class="button" href="#">关于OS</a>
                <a class="button" href="#">关于我</a>
                <a class="button" href="#">隐私</a>
            </div>
        </header>
        <main class="main">
            <div>
                <span class="text1">董旭阳的个人网站</span>
                <br />
                <span class="text2"> 精彩呈现 ...</span>
                <br />
                <span class="text3"> 敬请期待 ...</span>
            </div>
        </main>
        <footer class="footer">
            <a class="button1"> 董旭阳 </a>
            &emsp;|&emsp;
            <a class="button1"> www.dxy.today </a>
            &nbsp;|&nbsp;
            <a class="button1" target="_blank" href="https://beian.miit.gov.cn"> 京ICP备20008433号-1 </a>
        </footer>
    </div>
</template>

<script>
export default {
    name: 'App',
};
</script>

<style>
html,
body {
    width: 100%;
    height: 100%;
    padding: 0;
    margin: 0;
}
#app {
    width: 100%;
    height: 100%;
    color: #a9a9b3;
    background-color: #292a2d;
    font-size: 18px;
    font-family: '微软雅黑';
    position: relative;
}
.header {
    height: 64px;
    width: 1200px;
    margin: 0 auto;
    line-height: 64px;
}
.button {
    text-decoration: none;
    color: #a9a9b3;
    margin: 0 10px;
    cursor: pointer;
}
a:hover {
    color: #ffffff;
}
.enum {
    display: inline-block;
    float: right;
}
.main {
    position: absolute;
    left: 0;
    right: 0;
    top: 0;
    bottom: 0;
    margin: auto;
    width: 300px;
    height: 150px;
    text-align: center;
}
.footer {
    height: 64px;
    line-height: 64px;
    width: 1200px;
    position: absolute;
    bottom: 0;
    right: 50%;
    left: 50%;
    transform: translateX(-50%);
    text-align: center;
}
.button1 {
    font-size: 14px;
    cursor: pointer;
    text-decoration: none;
    color: #a9a9b3;
    cursor: pointer;
}

.text1 {
    font-size: 25px;
}
.text2 {
    font-size: 20px;
    opacity: 0.5;
}
.text3 {
    font-size: 15px;
    opacity: 0.25;
}
</style>
