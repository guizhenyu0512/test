<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>纯CSS实现百叶窗</title>
        <style type="text/css">
            * {
               margin: 0;
               padding: 0;
               }
            
            #parent >li> span{background: #999999;display: block;width: 200px;border:1px solid #ECEEF2;}
            li {line-height: 40px;display: block;}
            li  p{
                    display: inline-block;
                    width: 0px;
                    height: 0px;
                    border-left: 5px solid transparent;
                    border-right: 5px solid transparent;
                    border-top: 5px solid#2f2f2f;
                      }
             li>ul{display: none;}
             li>ul>li{border: 1px solid #DEDEDE;width: 199px;}
             #parent span:hover + ul{display: block;}
             #parent span:hover >p{
                     display: inline-block;
                    width: 0px;
                    height: 0px;
                    border-top: 5px solid transparent;
                    border-bottom: 5px solid transparent;
                    border-left: 5px solid#2f2f2f;}
        </style>
    </head>
    <body>
        <ul id="parent">
            <li>
                <span><p></p>列表</span>
                <ul>
                    <li>子列表</li>
                    <li>子列表</li>
                    <li>子列表</li>
                </ul>
            </li>
            <li>
                <span><p></p>列表</span>
                <ul>
                    <li>子列表</li>
                    <li>子列表</li>
                    <li>子列表</li>
                </ul>
            </li>
            <li>
                <span><p></p>列表</span>
                <ul>
                    <li>子列表</li>
                    <li>子列表</li>
                    <li>子列表</li>
                </ul>
            </li>
        </ul>
    </body>
</html>
