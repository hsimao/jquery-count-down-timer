# count-down-timer
## jQuery extend 倒數計時器插件

live demo https://hsimao.github.io/jquery-count-down-timer

### 基礎設置  

`$('.timer')._countTime('2018-05-26 12:30:00')`

### 自訂參數  
### 多行文本框   
    这是一个有多行的文本框 
    你可以写入代码等,每行文字只要输入两个Tab再输入文字即可 
    这里你可以输入一段代码 
    $('.timer')._countTime('2018-05-27 12:00:00', {
        isActive: true,
        str: {
            title: 'Countdown: ',
            day: 'day',
            hour: 'hour',
            min: 'min',
            seconds: 's'
        }
    })

### 自訂參數isActive: true
自動添加.js-count-active class 將“秒”包住, 可針對該class設置樣式
`<span class="js-count-active">30</span>`
ex:
`.js-count-active {
    font-size: 30px;
   font-weight: bold;
    color: #f1c40f;
}`