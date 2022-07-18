<template>
    <section id="imageType" class="image__wrap section nexon">
        <h2>Artist gallery</h2>
        <p>아티스트의 스냅입니다. 더 많은 사진은 아티스트의 이름을 클릭해주세요.</p>
        <div class="image__inner container">
            <article class="image">
                <div class="image__header">
                    <figure class="image__figure">
                        <img src="http://res.heraldm.com/phpwas/restmb_allidxmake.php?idx=5&simg=201903111510202682667_20190311151139_02.jpg" alt="애교만점 웰시코기"/>
                    </figure>
                </div>
                <div class="image__body">
                    <a href="#" class="image__btn">pH-1</a>
                </div>
            </article>
            <article class="image">
                <div class="image__header">
                    <figure class="image__figure">
                        <img src="https://img.vogue.co.kr/vogue/2022/05/style_628edcc00b58b-800x1109.jpg" alt="애교만점 웰시코기"/>
                    </figure>
                </div>
                <div class="image__body">
                    <a href="#" class="image__btn">백예린</a>
                </div>
            </article>
            <article class="image">
                <div class="image__header">
                    <figure class="image__figure">
                        <img src="https://img.hankyung.com/photo/202111/p1065581082501208_548_thum.JPG" alt="애교만점 웰시코기"/>
                    </figure>
                </div>
                <div class="image__body">
                    <a href="#" class="image__btn">Ash Island</a>
                </div>
            </article>
        </div>
    </section>
</template>

<style scoped>
.image__wrap {
    width: 100%;
    /* background: rgba(0,0,0,0.2); */
}
.image__inner {
    display: flex;
    justify-content: space-between;
}
.image__inner .image {
    width: 300px;
    /* height:450px; */
    overflow: hidden;
    position: relative;
    background-size: cover;
}

.image__figure{
    overflow: hidden;
    height: 415px;
}

.image__figure img {
    width: 100%;
    /* height: 500px; */
    vertical-align: top;
}
.image__body {
    position: absolute;
    left: 90px;
    bottom: 30px;
    color: #000;
    text-align: center;
}
.image__title {
    font-size: 32px;
    font-weight: 300;
    margin-bottom: 10px;
}
.image__desc {
    font-size: 16px;
    font-weight: 400;
    line-height: 140%;
    margin-bottom: 16px;
}
.image__btn {
    width:90px;
    text-decoration: none;
    color: #fff;
    background: #BE4E15;
    padding: 10px 20px;
    display: inline-block;
}
.image__btn.yellow {
    background: #C9931D;
}
</style>