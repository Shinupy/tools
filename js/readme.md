// stringformat.js 使用
var str="我是{name},年龄{age}";
var s=str.format({name:"lily",age:22});
console.log(s);
var str2="{0},{1},{2},{3},{4},{5},{6},{7},{8},{9},{10}";
var s2=str2.format(0,1,2,3,4,5,6,7,8,9,10);
console.log(s2);
