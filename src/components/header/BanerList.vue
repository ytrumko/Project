<template>
    <ul class="banerList">
        <li class="banerItem">
            <div class="banerItem1">
                <p class="data">10/10/2020</p>
                <p class="banerItemTaitle">Lifestyle</p>
            </div>
        </li>
        <li class="banerItem">
            <h1 class="banerTitle">At vero eos et accusamus et</h1>
        </li>
        <li class="banerItem">
            <p class="banerItemInform">odio dignissimos ducimus qui blanditiis</p>
        </li>
        <li class="banerItem">
            <button class="taitleButton">Read more</button>
        </li>
    </ul>
</template>
<style scoped>
.banerList{
list-style: none;
padding: 110px;
background: #000000;
padding-bottom: 150px;
min-height: 310px;
}
.banerItem1{
display: flex;
justify-content: space-between;
align-items: center;
}
.data{
    font-family: 'Kanit', sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 14px;
    line-height: 21px;
    letter-spacing: 7px;
    color: #FFFFFF;
}
.banerItemTaitle{
    font-family: 'Kanit', sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 16px;
    line-height: 24px;
    text-decoration-line: underline;
    color: #FFFFFF;
    text-transform: uppercase;
}
.banerTitle{
    font-family: 'Kanit', sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 28px;
    line-height: 42px;
    text-transform: uppercase;
    color: #FFFFFF;
}
.banerItemInform{
    font-family: 'Kanit', sans-serif;
    font-style: normal;
    font-weight: 300;
    font-size: 14px;
    line-height: 21px;
    color: #FFFFFF;
}
.taitleButton{
    font-family: 'Kanit', sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 12px;
    line-height: 18px;
    text-align: center;
    color: #FFFFFF;
    text-transform: uppercase;
    border: 1px solid #FFFFFF;
    background: #000000;
    padding-top: 19px;
    padding-bottom: 19px;
    padding-right: 65px;
    padding-left: 65px;
}
</style>
