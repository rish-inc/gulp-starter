<<<<<<< HEAD
### bullet
- リストの中黒のコンポーネント
=======
.c-bullet {
    list-style: none;
    &__item {
        line-height: 2.8;
        &::before {
            display: inline-block;
            content: "";
            margin: 17px 10px 0 0;
            width: 8px;
            height: 8px;
            vertical-align: top;
            border-radius: 5px;
            background-color: #897C70;

        }
        &:last-child {
            margin-bottom: 0;
        }
    }
}
>>>>>>> 979a4a2c6915e6ca2506b450df08150711824837
