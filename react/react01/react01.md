### React
angular  MVC 
react   v(视图层的框架)
view  mvvm
[官网](https://zh-hans.reactjs.org/)

#### React01
15.6
##### 创建组件 虚拟dom
React.createClass({
  render(){
    return(jsx 语法)
  }
})
React.createElement('div',{id:hehe,class:'red'},[
  React.createElement('span',{},[])
  React.createElement('h1',{},[])
  React.createElement('p',{},[])

])
render(){
  return(
    <div id='heh'>
    <span></span>
    </div> 
  )
}
##### 渲染元素
ReactDOM.render(组件,渲染元素)

##### jsx
javascriptxhtml 语法糖 帮助我们甜蜜蜜的创建虚拟dom
1.引入浏览器解析文件  bower.min.js
2.指定scriper 标签的类型  type=‘text/babel’
3.必须根元素 标签必须闭合

###
数据绑定  {}
v-if  1.三元表达式  2.|| 3.渲染函数
v-for react 会自动将一个数组展开 通过map 将数据 ['爱情','科幻']=>[<div>爱强</div>,<div>kehuan</div>]
v-bind  <div  属性名={表达式}> <img src={this.img}>
v-on  1.类似原生js  驼峰命名法 2.注意不要加() 3.通过bind 传参
注释  {/* 注释内容  */}