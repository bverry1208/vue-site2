<template>
    <section id="textType" class="text__wrap section nexon">
        <div class="text__inner container">
            <div class="text__inner__wrap">
                <div class="text">
                    <span>MY Artist</span>
                    <h3>나의 아티스트</h3>
                    <p>좋아하는 아티스트의 정보입니다.<br/>
                        더 많은 정보는 프로필을 클릭해주세요 .
                    </p>
                </div>
            </div>
            <div class="text__inner__wrap">
                <div class="text">
                    <h3>pH-1</h3>
                    <p>H1GHR MUSIC의 창립 멤버이자 소속 래퍼이다. 미국 국적이며 뉴욕 롱아일랜드 출신이다. 메킷레인의 오왼과 함께 듀오 그룹인 'SOUS CHEFS' 활동을 한 경력이 있다.</p>
                </div>
                <div class="text">
                    <h3>Toil</h3>
                    <p>대한민국의 힙합 프로듀서이다.
                        Daytona Entertainment의 소속 아티스트다. 베이스를 전공했으며 기타를 기반으로 하는 록 사운드의 비트가 특징이다.
                    </p>

                </div>
            </div>
            <div class="text__inner__wrap">
                <div class="text">
                    <h3>원슈타인</h3>
                    <p>대한민국의 래퍼 겸 싱어송라이터로, 마미손과 김승민 등이 소속되어 있는 뷰티풀노이즈에 소속되어 있었으나 뷰티플 노이즈와는 2022년 4월 13일 계약이 종료되었다.</p>
                </div>
                <div class="text">
                    <h3>백예린</h3>
                    <p>밴드 The Volunteers의 프론트맨이자 싱어송라이터이다. 탄탄한 기본기와 발성, 독보적인 음색으로 주목받았고 거의 모든 장르를 자신만의 감성으로 감쌀 정도로 가창력과 곡 해석이 뛰어나다는 평을 받고 있다.</p>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
.text__inner {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    text-align: left;
}

.text__inner__wrap{
    width:31%;
}

.text__inner .text:nth-child(1),
.text__inner .text:nth-child(2),
.text__inner .text:nth-child(3) {
    margin-bottom: 70px;
}

.text__inner .text span {
    font-size: 16px;
    background: lightcoral;
    color: #fff;
    padding: 2px 15px 0px;
    border-radius: 30px;
}

.text__inner .text h3 {
    font-size: 24px;
    font-weight: 500;
    margin-bottom: 10px;
    padding-top: 60px;
    position: relative;
}

.text__inner__wrap:first-child h3{
    font-size: 30px;
    font-weight: 700;
}

.text__inner__wrap:first-child h3::before{
    content: '';
    background: none;
}

.text__inner .text h3::before {
    content: '';
    width: 50px;
    height: 50px;
    border-radius: 50%;
    position: absolute;
    left: 0; top: 0;
    background-size: cover;
    background-color: #D3D8FA;
}
.text__inner__wrap:nth-child(1) .text h3::before {
    background: none;
}

.text__inner__wrap:nth-child(2) .text:nth-child(1) h3::before{
    background-image: url(https://cdn.music-flo.com/image/artist/575/943/02/04/402943575_5e16ea38.jpg?1578560057455/dims/resize/500x500/quality/90);
}
.text__inner__wrap:nth-child(2) .text:nth-child(2) h3::before{
    background-image: url(https://cdn.music-flo.com/image/v2/artist/840/300/03/04/403300840_6287589e_s.jpg?1653037216626/dims/resize/x500/quality/90);
}
.text__inner__wrap:nth-child(3) .text:nth-child(1) h3::before{
    background-image: url(https://cdn.music-flo.com/image/artist/040/241/03/04/403241040_5f45ae35.jpg?1598402102243/dims/resize/x500/quality/90);
}
.text__inner__wrap:nth-child(3) .text:nth-child(2) h3::before{
    background-image: url(https://cdn.music-flo.com/image/album/429/526/02/04/402526429.jpg?1553114160869/dims/resize/500x500/quality/90);
}

.text__inner .text p {
    font-size: 16px;
    font-weight: 300;
    line-height: 1.6;
    text-align: justify;
}
</style>