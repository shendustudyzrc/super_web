<%@ page language="java" contentType="text/html; charset=UTF-8"
    pageEncoding="UTF-8"%>
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<script src="http://cdn.static.runoob.com/libs/jquery/1.10.2/jquery.min.js"></script>
<title>Java</title>
<style type="text/css">
  *{
   margin:0px;
   padding:0px;
  }
  .container{
   width:100%;
   height:100%;
  }
  .header{
   width:100%;
   height:140px;
  }
  .header_up{
   width:100%;
   height:100px;
   background:#f6f6f6;
  }
  .header_nav{
   width:100%;
   height:40px;
   background:#96b97d;
  }
  .middle_body{
   top:140px;
   width:100%;
   background:#f6f6f6;
  }
  .body_left{
    width:10%;
    margin-left:25px;
    float:left;
    background:#f0f0f0;
  }
  .body_right{
   width:75%;
   margin-left:13%;
   background:#ffffff;
  }
  .footer{
  /*  position:fixed; */
   /* bottom:0px; */
   width:100%;
   height:280px;
  
  }
  .sousuo{
    padding-top:40px;
    margin-left:1100px;
  }
  .zrc{
   padding-top:20px;
   margin-left:120px;
   float:left;
  }
  .footer-left{
   width:75%;
   height:280px;
   background:#ffffff;
   float:left;
  }
  .footer-right{
   width:25%;
   margin-left:75%;
   height:280px;
   background:black;
  }
  .footer_table{
   margin-left:10%;
  }
  .header_nav ul{
   width:1200px;
   border:1px solid #000;
   margin:0px auto*;  
  }
  .header_nav ul li{
   list-style:none;
   float:left;
  }
  .header_nav ul li a{
   width:100px;
   height:28px;
   line-height:28px;
   display:block;
   color:#FFF;
   text-align:center;
   text-decoration:none;
   display:block;
  }
  .header_nav  ul li a:hover{
   width:80px;
   height：28px;
   line-height:10px;
   border:1px solid green;
   text-align:center;
   text-decoration:none;
  }
</style>
</head>
<body>
<div class="container">
  <div class="header">
    <div class="header_up">
     <div class="zrc">
     <span></span><h1>www.ZRC.com</h1> 
     </div>
     <div class="sousuo">
       <form>
        <table border="1"><tr><td width="173px" height="40px">
       <input style="height:40px" type="text" name="name" placeholder="搜索名字信息" ></td><td><button  style="height:40px">搜索</button>
       </td></tr></table>
       </form>
     </div>
    </div>
    <div class="header_nav">
      <ul>
		<li><a href="/">首页</a></li>
		<li><a href="/">Java笔记</a></li>
		<li><a href="/">Java工具</a></li>
		<li><a href="/">参考手册</a></li>
		<li><a href="/">笔记列表</a></li>
		<li><a href="/">测验/考试</a></li>
		<li><a href="/">登录</a></li>
	  </ul>
    </div>
  </div>
  <div class="middle_body" id="middle_body">
  <div class="body_left">
    <ul>
     <li><a>Mysql数据库</a></li>
     <li><a>Java基础</a></li>
     <li><a>Java高级</a></li>
     <li><a>HTML</a></li>
     <li><a>Javaweb</a></li>
     <li><a>Struts2</a></li>
     <li><a>Spring</a></li>
    </ul> 
  </div>
  <div class="body_right">
   <table width="800px" border="1" cellpadding="0" cellspacing="0" style="margin-left:180px;border-collapse:collapse">
     <tr height="15px"><td colspan="3">Mysql数据库</td>
     <tr height="50px"><td>安装Mysql</td><td>学会增操作</td><td>学会删操作</td></tr>
     <tr height="50px"><td>学会改操作</td><td>学会查操作</td><td>学会建表操作</td></tr>
     <tr height="50px"><td>索引操作</td><td>sql语句</td></tr>

     <tr height="15px"><td colspan="3">Java基础</td>
     <tr height="50px"><td>安装Mysql</td><td>学会增操作</td><td>学会删操作</td></tr>
     <tr height="50px"><td>学会改操作</td><td>学会查操作</td><td>学会建表操作</td></tr>
     <tr height="50px"><td>索引操作</td></tr>
   
     <tr height="15px"><td colspan="3">Java高级</td>
     <tr height="50px"><td>安装Mysql</td><td>学会增操作</td><td>学会删操作</td></tr>
     <tr height="50px"><td>学会改操作</td><td>学会查操作</td><td>学会建表操作</td></tr>
     <tr height="50px"><td>索引操作</td></tr>

     <tr height="15px"><td colspan="3">HTML</td>
     <tr height="50px"><td>HTML语句</td><td>HTML语法</td><td>HTML</td></tr>
     <tr height="50px"><td>HTML</td><td>HTML</td><td>HTML</td></tr>
     <tr height="50px"><td>HTML链接</td></tr>

     <tr height="15px"><td colspan="3">Javaweb</td>
     <tr height="50px"><td>安装Mysql</td><td>学会增操作</td><td>学会删操作</td></tr>
     <tr height="50px"><td>学会改操作</td><td>学会查操作</td><td>学会建表操作</td></tr>
     <tr height="50px"><td>索引操作</td></tr>

     <tr height="15px"><td colspan="3">strut2</td>
     <tr height="50px"><td>strut2的lib包</td><td>strut2的语法</td><td>strut2的语句</td></tr>
     <tr height="50px"><td>strut2的xml</td><td>strut2的模式结构</td><td>strut2的思想</td></tr>
     <tr height="50px"><td>strut2的注意事项</td></tr>

     <tr height="15px"><td colspan="3">hibernate</td>
     <tr height="50px"><td>hibernate的lib包</td><td>hibernate的语法</td><td>hibernate的语句</td></tr>
     <tr height="50px"><td>hibernate的xml</td><td>hibernate的模式结构</td><td>hibernate的思想</td></tr>
     <tr height="50px"><td>hibernate的注意事项</td></tr>
  
     <tr height="15px"><td colspan="3">Spring</td>
     <tr height="50px"><td>Spring的lib包</td><td>Spring的语法</td><td>Spring的语句</td></tr>
     <tr height="50px"><td>Spring的xml</td><td>Spring的模式结构</td><td>Spring的思想</td></tr>
     <tr height="50px"><td>Spring的注意事项</td></tr>

     <tr height="15px"><td colspan="3">SpringMVC</td>
     <tr height="50px"><td>SpringMVClib包</td><td>SpringMVC语法</td><td>SpringMVC的sql语句</td></tr>
     <tr height="50px"><td>SpringMVC的xml</td><td>SpringMVC的模式结构</td><td>SpringMVC的思想</td></tr>
     <tr height="50px"><td>SpringMVC的注意事项</td></tr>

     <tr height="15px"><td colspan="3">Mybatis</td>
     <tr height="50px"><td>Mybatis包</td><td>Mybatis的sql语句</td><td>Mybatis的xml配置</td></tr>
     <tr height="50px"><td>Mybatis的namespace</td><td>Mybatis+Spring</td><td>Mybatis+SpringMVC</td></tr>
     <tr height="50px"><td>Mybatis+SpringMVC+maven</td></tr>
   </table>

  </div>
  </div>
  <div class="footer">
  <div class="footer_top">
  <div class="footer-left">
   <table  width="70%" height="280px" class="footer_table">
    <tr>
     <td>
     <table width="200px" height="280px">
       <tr><td height="15px"><h2>在线实例</h2></td></tr>
       <tr><td height="15px"><a href="#">Java实例1</a></td></tr>
       <tr><td height="15px"><a href="#">Java实例2</a></td></tr>
       <tr><td height="15px"><a href="#">Java实例3</a></td></tr>
       <tr><td height="15px"><a href="#">Java实例4</a></td></tr>
     </table>
     <td>
    <td>
      <table width="200px" height="280px">
       <tr><td height="15px"><h2>在线实例</h2></td></tr>
       <tr><td height="15px"><a href="#">Java实例1</a></td></tr>
       <tr><td height="15px"><a href="#">Java实例2</a></td></tr>
       <tr><td height="15px"><a href="#">Java实例3</a></td></tr>
       <tr><td height="15px"><a href="#">Java实例4</a></td></tr>
      </table>
     </td>
     <td>
      <table width="200px" height="280px">
       <tr><td height="15px"><h2>在线实例</h2></td></tr>
       <tr><td height="15px"><a href="#">Java实例1</a></td></tr>
       <tr><td height="15px"><a href="#">Java实例2</a></td></tr>
       <tr><td height="15px"><a href="#">Java实例3</a></td></tr>
       <tr><td height="15px"><a href="#">Java实例4</a></td></tr>
      </table>
     </td>
     <td>
      <table width="200px" height="280px">
       <tr><td height="15px"><h2>在线实例</h2></td></tr>
       <tr><td height="15px"><a href="#">Java实例1</a></td></tr>
       <tr><td height="15px"><a href="#">Java实例1</a></td></tr>
       <tr><td height="15px"><a href="#">Java实例1</a></td></tr>
       <tr><td height="15px"><a href="#">Java实例1</a></td></tr>
      </table>
     </td>
    </tr>
   </table>
  </div> 
  <div class="footer-right">
   <img width="350px" height="280px" src="/ee/view/ee/WEB-INF/images/wechat.jpg">
  </div>
  </div>
  <div class="footer_buttom" style="width:100%;height:60px;background:#f6f6f6">
   <span style="margin-left:500px;color:green;">Copy right@zhangrichao www.zrc.com 欢迎你的到来</span>
  </div>
</div>
</div>
     <script>
        function test() {
           /*   var s = "";
             s += "\r\n" + window.screen.height;
             var s1 = s - 220;
             var h = document.getElementsByClassName('middle_body')[0];
             h.style.height = s1 + "px"; */
             var s=$("#middle_body").height();
             var h=document.getElementsByClassName('middle_body')[0];
             var h1=document.getElementsByClassName('body_left')[0]; 
             h.style.height=s+"px";
             h1.style.height=s+"px"; 
        }
        test();
    </script>
</body>
</html>