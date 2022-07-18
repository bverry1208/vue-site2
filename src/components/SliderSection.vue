<template>
    <section id="sliderType" class="slider__wrap nexon">
    <h2 class="ir_so">슬라이드 영역</h2>
    <div class="slider__inner">
        <div class="slider">
            <div class="slider__img">
                <div class="desc">
                    <h3>LIFE <br/> 
                        = MUSIC</h3>
                    <p>music is my life <br/> 
                        언젠간 내게 기회가 올거야<br/>
                        내 노래를 들려줄
                    </p>
                    <div class="btn">
                        <a href="#" class="white">자세히 보기</a>
                    </div>
                </div>
            </div>
            <div class="slider__arrow">
                <a href="#" class="left"><span class="ir_pm">이전이미지</span></a>
                <a href="#" class="right"><span class="ir_pm">다음이미지</span></a>
            </div>
            <div class="slider__dot">
                <a href="#" class="dot active"><span class="ir_pm">1</span></a>
                <a href="#" class="dot"><span class="ir_pm">2</span></a>
                <a href="#" class="dot"><span class="ir_pm">3</span></a>
                <a href="#" class="dot"><span class="ir_pm">4</span></a>
                <a href="#" class="play"><span class="ir_pm">자동플레이</span></a>
                <a href="#" class="stop"><span class="ir_pm">정지</span></a>
            </div>
        </div>
    </div>
</section>
</template>

<style scoped>
.slider {
    position: relative;
}
.slider__img {
    background-color: lightgoldenrodyellow;
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
    width: 100%;
    /* height: 500px; */
}
.slider__img .desc {
    width: 1160px;
    margin: 0 auto;
    padding: 60px 20px;
    color: #000;
}
.slider__img .desc span {
    font-size: 16px;
    background: #fff;
    color: #000;
    padding: 2px 15px 0px;
    border-radius: 30px;
}
.slider__img .desc h3 {
    font-family: 'GmarketSans';
    font-size: 90px;
    font-weight: 700;
    margin-left: 70px;
    margin-bottom: 10px;
}
.slider__img .desc p {
    font-size: 17px;
    font-weight: 300;
    line-height: 1.4;
    margin-left: 75px;
    margin-bottom: 30px;
}
.slider__img .desc .btn a {
    font-size: 16px;
    padding: 11px 50px;
    margin-left: 75px;
    display: inline-block;

}
.slider__img .desc .btn .white {
    background: #fff;
    color: #000;
}
.slider__img .desc .btn .black {
    background: #000;
    color: #fff;
}
.slider__arrow a {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    width: 27px;
    height: 39px;
    background: url(../assets/img/slider_icon.svg);
}
.slider__arrow .left{
    left: 10px;
    background-position: 0 -50px;
}
.slider__arrow .right {
    right: 10px;
    background-position: -23px -50px;
}
.slider__dot {
    position: absolute;
    left: 50%;
    bottom: 25px;
    transform: translateX(-50%);
}
.slider__dot a {
    width: 14px;
    height: 14px;
    background: url(../assets/img/slider_icon.svg);
    display: inline-block;
    margin: 2px;
}
.slider__dot .dot {
    background-position: -70px -50px;
}
.slider__dot .dot.active {
    background-position: -50px -50px;
}
.slider__dot .play {
    background-position: -88px -50px;
}
.slider__dot .stop {
    background-position: -110px -50px;
}
</style>