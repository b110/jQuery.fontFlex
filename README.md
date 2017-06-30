# jQuery.fontFlex
Lightweight jQuery extension for dynamically changing font sizes according to container / browser width.
根据容器/浏览器宽度动态更改字体大小的轻量级jQuery扩展。
Intended for use with responsive or adaptive `CSS` layouts.
用于响应式布局的CSS样式处理。

## Installation
Include the latest version of [jQuery](http://jquery.com/download) and `jQuery.fontFlex.js` in the `<head>` of your HTML document:
添加jq和jq.fontflex.js到html页面中
```html
<script src="jQuery.min.js"></script>  
<script src="jQuery.fontFlex.js"></script>
```

## How to Use

Define a default `CSS` font base by setting `font-size: 1em` and `line-height: 150%` on the `body` or intended element. Declaring the `font-size` is optional, but highly recommended in case javascript is disabled. Finally, call the plugin on said element. Live Demo: 
建议定义一个默认的` CSS `字体大小：` 1em `和`行高：150% `。当然这个声明“字体大小”是可选的，但强烈建议在禁用JavaScript的情况下使用。案例如下：
[code.nath.co/fontFlex](http://code.nath.co/fontFlex)  

**Syntax Example**  
```javascript
$(function() {

  // All elements
  $('body').fontFlex(14, 20, 70);

  // H1 only
  $('h1').fontFlex(24, 36, 70);	
  
});
```

**Custom Parameters**   
`min` Minimum font-size in pixels  
`max` Maximum font-size in pixels 
`mid` Mid-range buffer. Values ranging from 60 to 70 produce the best results. Lower values produce a larger initial font-size, while higher values produce the opposite. Adjust accordingly to fit your requirements. 
中间值，从60到70会产生最好的结果。较低的值产生较大的初始字体大小，而较高的值则产生相反的大小。慢慢调整以适合您的要求。
## Browser Support
– Google Chrome  
– Safari ( Desktop and Mobile )  
– Internet Explorer ( 8, 9, 10+ )  
– Firefox

## Feedback
If you discover any issues or have questions regarding usage, please send a message to [code@nath.co](mailto:code@nath.co) or find me on GitHub [@nathco](https://github.com/nathco).
如果有问题请联系作者
