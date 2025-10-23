    <div class="lowbar">
        <img class="lowImg" src="comparison.png"><a class="lowT">Сравнение</a>
        <img class="lowImg" src="fav.png"><a class="lowT">Избранное</a>
        <img class="lowImg" src="bin.png"><a class="lowT">Корзина</a>
    </div>
.lowbar{
    position: fixed;
    bottom: 0;
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    justify-content: center;
    align-items: center;
    flex-grow:1;
    background-color: white;
    padding: 5px;
    width:20%;
    height: 50px;
    border-radius:20px;
}
.lowT{
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    justify-content: center;
    align-items: center;
    flex-grow:1;
}