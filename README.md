itempro
=======

item project

@media 常见的媒体类型有：all(所有), screen(屏幕), print(打印), tv(电视), braille(盲文),
       新增：3d-glasses(3d眼镜)
       默认媒体类型：screen(屏幕)

在媒体查询中有三个不同的逻辑运算符，分别是and(与)、not(非)、only(唯一)
PS：当同时使用非和唯一逻辑运算符，媒体类型就会失效，这种情况下媒体类型是默认的所有设备。


响应式布局需要注意的点：
1.宽度需要使用百分比: #head{ width: 100%; }
2.处理图片缩放的方法：img{ width:auto; max-width: 100%; }
3.其他例如iframe，pre，video等，都需要和img一样控制好宽度。对于table，建议不要增加padding属性，低分辨率下使用内容居中
  table th, table td{ padding:0; text-align: center; }
4.流式嵌入媒体：(iframe类) 具体看参见refer②




refer:
1.http://caibaojian.com/356.html
2.http://www.w3cplus.com/css/advanced-html-css-lesson4-responsive-web-design.html