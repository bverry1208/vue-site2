<template>
    <section id="bannerType" class="banner__wrap nexon">
        <h2 class="ir_so">슬라이드 영역</h2>
        <div class="banner__inner">
            <div class="banner">
                <div class="banner__img">
                    <div class="desc">
                        <h3>YOUTUBE</h3>
                        <p>더 많은 노래는 유튜브에서 확인하실 수 있습니다.<br/>
                            구독과 좋아요 알림 설정까지 ~!
                        </p>
                        <div class="btn">
                            <a href="#" class="white">자세히 보기</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.banner {
    position: relative;
}
.banner__img {
    background-color: lightgoldenrodyellow;
    background-position: center center;
    background-repeat: no-repeat;
    background-size: cover;
    width: 100%;
    /* height: 500px; */
}
.banner__img .desc {
    width: 1160px;
    margin: 0 auto;
    padding: 90px 20px;
    color: #000;
}
.banner__img .desc span {
    font-size: 16px;
    background: #fff;
    color: #000;
    padding: 2px 15px 0px;
    border-radius: 30px;
}
.banner__img .desc h3 {
    font-family: 'GmarketSans';
    font-size: 50px;
    font-weight: 500;
    margin-left: 70px;
    margin-bottom: 25px;
}
.banner__img .desc p {
    font-size: 17px;
    font-weight: 300;
    line-height: 1.4;
    margin-left: 75px;
    margin-bottom: 70px;
}
.banner__img .desc .btn a {
    font-size: 16px;
    padding: 11px 50px;
    margin-left: 75px;
    display: inline-block;

}
.banner__img .desc .btn .white {
    background: #fff;
    color: #000;
}
.banner__img .desc .btn .black {
    background: #000;
    color: #fff;
}
</style>