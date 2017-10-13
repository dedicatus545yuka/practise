# 雙飛翼佈局
今天是第一次在這裡寫點東西，其實我英文不好，用起這個網站來還是很吃力的一件事，特別是我對MK還不是很了解  
  
 ```html   
<!Doctype Html> 
<Html lang="en">  
  <head>  
    <meta charset="UTF-8">  
    <title>雙飛翼佈局</title>
    <link rel="stylesheet" href="雙飛翼.css">
  </head> 
  <body>
    <div class="box">
      <div class="center">
            <div class"wrap"></div>
      </div>    
      <div class="left"></div>    
      <div class="right"></div>    
  </div>    
  </body>
</html> 
```
`雙飛翼.css`
```css
body {
    margin: 0px;
}
.windows {
    width: 80%;
    height: 300px;
    border: 5px solid lightslategrey;
    margin: 0 auto;
}
.center {
    width: 100%;
    height: 300px;
    background-color: lawngreen;
    /* 给元素设置基本数值 */
    float: left;
}
.left,.right {
    width: 100px;
    height: 300px;
    float: left;
}
.left {
    background-color: lightpink;
    margin-left: -100%;
}
.right {
    background-color: lightskyblue;
    margin-left: -100px;
}
.wrap {
    margin: 0 100px;
}
header,footer {
    width: 100%;
    height: 100px;
    background: lightgoldenrodyellow;
}
```

  
  
