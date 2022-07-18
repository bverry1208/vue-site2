<template>
    <header id="headerType" class="header__wrap nexon">
        <h1 class="header__logo">
            <a href="/">Music <em>on</em></a>
        </h1>
        <div class="header__inner">
            <nav class="header__menu">
                <h2 class="ir_so">메인 메뉴</h2>
                <ul>
                    <li><a href="/">Header</a></li>
                    <li><a href="/">Slider</a></li>
                    <li><a href="/">Images</a></li>
                    <li><a href="/">Contents</a></li>
                    <li><a href="/">Footer</a></li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<style scoped>
.header__inner {
    display: flex;
    align-items: center;
    justify-content: space-between;
    /* border-bottom: 1px solid #ccc; */
    padding: 0 30px;
}
.header__logo {
    flex-basis: 20%;
    text-align: center;
}
.header__logo a {
    font-size: 30px;
    display: inline-block;
    padding: 15px;
}
.header__logo em {
    font-size: 18px;
    /* font-weight: 300;
    text-transform: uppercase; */
}
.header__menu {
    flex-basis: 100%;
    text-align: center;
}
.header__menu ul {
    padding-bottom: 15px;
}
.header__menu li {
    display: inline;
}
.header__menu li a {
    padding: 15px 30px;
    transition: background 0.3s;
}
.header__menu li a:hover {
    background: #f1f1f1;
    border-radius: 5px;
}
</style>