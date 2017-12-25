# vue-Note
Vue学习笔记
## v-text 取代{{ }} 闪烁
 - v-cloak 
 ````
 <style>
    [v-cloak]{
      display:none;
    }
 </style>
 
//html
<div id='app' v-cloak>
 ...
</div>
````
 - 默认隐藏，vue渲染后显示
