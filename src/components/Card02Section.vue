<template>
    <section id="cardType" className="card__wrap section nexon">
        <h2>Album Review</h2>
        <p>
            앨범리뷰입니다.<br/> 
            Gmarket Sans Light 22px 150% #67778A 
        </p>
        <div className="card__inner container">
            <article className="card">
                <figure className="card__header">
                    <img className="img" src="https://cdn.music-flo.com/image/v2/album/708/537/06/04/406537708_61386d6c_s.jpg?1631087982172/dims/resize/500x500/quality/90" alt="이미지1"/>
                </figure>
                <div className="card__body">
                    <h3 className="title">백예린 [선물]</h3>
                    <p className="desc">
                        선물은 보통 포장지로 감싸거나 그럴듯한 종이백 안에 넣어 주곤 한다. 앨범의 제목 '선물'이라는 단어에 담은 것은 온전히 나의 개인적인 감정일 뿐, 결국 선물을 받는 사람이 포장을 한 겹 한 겹 뜯고 느낄 감정이 무엇일지 나는 알 수 없다. 이 곡들을 다시 부르며 내가 느낀 것들을 담아 포장을 열심히 해보았는데 잘 전달되었으면 좋겠다.
                    </p>
                    <a className="btn" href="#">
                        더 자세히 보기
                        <svg width="52" height="8" viewBox="0 0 52 8" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M51.3536 4.35355C51.5488 4.15829 51.5488 3.84171 51.3536 3.64645L48.1716 0.464466C47.9763 0.269204 47.6597 0.269204 47.4645 0.464466C47.2692 0.659728 47.2692 0.976311 47.4645 1.17157L50.2929 4L47.4645 6.82843C47.2692 7.02369 47.2692 7.34027 47.4645 7.53553C47.6597 7.7308 47.9763 7.7308 48.1716 7.53553L51.3536 4.35355ZM0 4.5H51V3.5H0V4.5Z" fill="#5B5B5B"></path>
                        </svg>
                    </a>
                </div>
            </article>
            <article className="card">
                <figure className="card__header">
                    <img className="img" src="https://cdn.music-flo.com/image/album/121/387/02/04/402387121_5c9f766a.jpg?1553954411278/dims/resize/500/quality/90" alt="이미지2"/>
                </figure>
                <div className="card__body">
                    <h3 className="title">PRADA (Feat. pH-1)</h3>
                    <p className="desc">주영의 새 디지털 싱글 ‘PRADA (Feat. pH-1)’는 주영의 매력적인 목소리와 아티스트 pH-1의 랩피처링이 더해져 감성적이면서 트렌디한 분위기를 자아낸다. 이별을 반어적으로 표현한 메시지로, 주영만의 감각적인 가사를 담았으며, pH-1의 랩이 노래의 완성도를 더했다.</p>
                    <a className="btn" href="#">
                        더 자세히 보기
                        <svg width="52" height="8" viewBox="0 0 52 8" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M51.3536 4.35355C51.5488 4.15829 51.5488 3.84171 51.3536 3.64645L48.1716 0.464466C47.9763 0.269204 47.6597 0.269204 47.4645 0.464466C47.2692 0.659728 47.2692 0.976311 47.4645 1.17157L50.2929 4L47.4645 6.82843C47.2692 7.02369 47.2692 7.34027 47.4645 7.53553C47.6597 7.7308 47.9763 7.7308 48.1716 7.53553L51.3536 4.35355ZM0 4.5H51V3.5H0V4.5Z" fill="#5B5B5B"></path>
                        </svg>
                    </a>
                </div>
            </article>
            <article className="card">
                <figure className="card__header">
                    <img className="img" src="https://cdn.music-flo.com/image/album/531/320/02/04/402320531_5c9d2f8f.jpg?1553805200624/dims/resize/500x500/quality/90" alt="이미지3"/>
                </figure>
                <div className="card__body">
                    <h3 className="title">김수영 [Behind]</h3>
                    <p className="desc">안녕하세요 김수영입니다.
                        이번 [Behind] 에는 제가 느끼는 사랑의 감정, 그리운 사람에게 부르는 노래, 혼자 있을 때 느꼈던 마음의 노래를 담아보았습니다. </p>
                    <a className="btn" href="#">
                        더 자세히 보기
                        <svg width="52" height="8" viewBox="0 0 52 8" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <path d="M51.3536 4.35355C51.5488 4.15829 51.5488 3.84171 51.3536 3.64645L48.1716 0.464466C47.9763 0.269204 47.6597 0.269204 47.4645 0.464466C47.2692 0.659728 47.2692 0.976311 47.4645 1.17157L50.2929 4L47.4645 6.82843C47.2692 7.02369 47.2692 7.34027 47.4645 7.53553C47.6597 7.7308 47.9763 7.7308 48.1716 7.53553L51.3536 4.35355ZM0 4.5H51V3.5H0V4.5Z" fill="#5B5B5B"></path>
                        </svg>
                    </a>
                </div>
            </article>
        </div>
    </section>
</template>

<style scoped>
.card__inner {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    text-align: left;
    /* background-color: #F6F4E0; */
}
/* .card__inner {
    display: flex;
    justify-content: space-between;
    background: lightblue;
} */
.card {
    width: 24%;
}

.card__header img{
    border-radius: 7px;
}

.card__body {
    padding: 24px 0;
    /* background: #fff; */
    text-align: left;
}


.card__body .title {
    font-size: 24px;
    font-weight: 500;
    margin-bottom: 10px;
}
.card__body .desc {
    font-size: 16px;
    line-height: 1.5;
    color: #5b5b5b;
    font-weight: 300;
    margin-bottom: 20px;
    overflow: hidden;
    text-overflow: ellipsis;
    display: -webkit-box;
    -webkit-line-clamp: 4; 
    -webkit-box-orient: vertical;
    word-break: keep-all;
}

.card__body .title .btn img{
    position: absolute;
    width: 23px;
    height: 23px;
    margin-left: 10px;
}
</style>