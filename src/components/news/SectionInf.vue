<template>
<div class="sectionInf">
    <ul class="section2Lis">
        <li class="section2Item">
            <img src="@/assets/img-7.png" alt="foto">
        </li>
        <li class="section2Item">
            <p class="section2Data">10/10/2020</p>
            <p class="section2ItemTaitle">Lifestyle</p>
        </li>
        <li class="section2Item">
            <h3 class="sectionItemText">At vero eos et accusamus et iusto</h3>
        </li>
    </ul>
    <ul class="section2Lis">
        <li class="section2Item">
            <img src="@/assets/img-8.png" alt="foto">
        </li>
        <li class="section2Item">
            <p class="section2Data">10/10/2020</p>
            <p class="section2ItemTaitle">Lifestyle</p>
        </li>
        <li class="section2Item">
            <h3 class="sectionItemText">At vero eos et accusamus et iusto</h3>
        </li>
    </ul>
    <ul class="section2Lis">
        <li class="section2Item">
            <img src="@/assets/img-9.png" alt="foto">
        </li>
        <li class="section2Item">
            <p class="section2Data">10/10/2020</p>
            <p class="section2ItemTaitle">Lifestyle</p>
        </li>
        <li class="section2Item">
            <h3 class="sectionItemText">At vero eos et accusamus et iusto</h3>
        </li>
    </ul>
</div>
</template>
<style scoped>
.sectionInf{
    display: flex;
    justify-content: center;
    align-items: center;
}
.section2Lis{
    list-style: none;
}
.section2Item{
    display: flex;
    justify-content: space-between;
}
.section2Data{
    font-family: 'Kanit', sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 12px;
    line-height: 18px;
    letter-spacing: 6px;
    color: #1F1F1D;
}
.section2ItemTaitle{
    font-family: 'Kanit', sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 12px;
    line-height: 18px;
    text-align: right;
    text-decoration-line: underline;
    color: #000000;
    text-transform: uppercase;
}
.sectionItemText{
    font-family: 'Kanit', sans-serif;
    font-style: normal;
    font-weight: 500;
    font-size: 18px;
    line-height: 27px;
    text-transform: uppercase;
    color: #1F1F1D;
}
</style>
