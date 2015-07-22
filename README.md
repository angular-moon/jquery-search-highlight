# jquery-search-highlight
搜索页面关键字高亮显示
==========================================

#### exact (string, default value:"exact")
"exact" : 完全匹配

"whole" : 部分匹配单词,但高亮整个单词

"partial": 部分匹配


#### style_name (string, default value:"hilite")
高亮样式的名称


#### style_name_suffix (boolean, default value:true)
如果为true表明,每种风格将会增加一个数字。(hilite1 hilite2 hilite3…)这有助于找到特定的匹配和风格不同。


#### highlight (jQuery selector or object, default value:null)
需要匹配的范围


#### nohighlight (jQuery selector or object, default value:null)
不需要匹配的范围


#### keys (string, default value:null)
搜索的关键字


```js
var highLightOptions = {
      exact:"partial",
      style_name_suffix:false,
      highlight:"#highlightScope",
      keys:"key1 key2 key3"
};
      
$(document).SearchHighlight(highLightOptions);
```
