## 选择 45分

1.src 属性 标签

2.

3.css样式选择器优先级描述正确的

**4.给定一个Servlet的doGet代码片段如下**

```jsp
request.setAttribute(“name”,”zhang”);
response.sendRedirect(“http://localhost:8080/servlet/MyServlt”);
```

**那么在MyServlet 中可以使用()方法把属性name的值取出来。**

A.String str=request.getAttribute(“name”);

B.String str=(String)request.getAttribute(“name”);

C.Object str=request.getAttribute(“name”);

D.无法取出来

**5.javaee jsp el表达式${user.loginName}执行效果相同的是**

<font color=red>A.<%=user.getLoginName()%></font>>
B.<%user.getLoginName();%>
C.<%=user.loginName%>
D.<%user.loginName;%>

**6.对于转发与重定向描述错误的是**

A.重定向是在客户端发生作用，通过请求新的地址实现页面转向

B.使用转发时由于是服务器内部控制权的转移，因而地址栏中的URL没有变化

C.使用重定向时可以在地址栏中看到转向后的URL

<font color=red>D.转发与重定向都可以实现在页面跳转，因而没有区别</font>

7.一个web对象中文件对象的根目录是哪一个

8.以下代码执行效果为

9.js中哪种可以获取xml

**10.jsp中 关于Cookie理解错误的是**

A.Cookie是在客户端保存用户相关数据的
B.Cookie可以保存字符串
<font color=red>C.Cookie可以保存任意类型的对象</font>
D.不建议在Cookie中保存比较重要或敏感的内容

**11.css三种引入方式**

<font color=red>内联、内嵌、外联、导入</font>

12.userlist hashtable 并逐行显示其中的值

**13.在javaee中，servlet 实例化到消亡的生命周期描述正确的**

A.在典型的Servlet生命周期模型中，每次Web请求就会创建一个Servlet实例，请求结束Servlet就消亡了。

<font color=red>B.init()方法是容器调用的Servlet实例的第一个方法。</font>

C.在容器把请求传送给Servlet之后，和在调用Servlet实例的doGet或者doPost方法之前，容器不会调用Servlet实例的其他方法。D.在Servlet 实例消亡之前，容器调用Servlet实例的close()方法。

**14.哪个对象从不同的作用域中获取值**

A.application

B.session

C.request

<font color=red>D.pagecontext</font>

**15.在jsp中哪种注释方式页面不能显示，而服务器能执行的**

```html
<!-- -->
```

**16.使用el表达式如何显示多选下拉页表框**

```jsp
<c:forEach items="${session.list}" varStatus="i" var="item" >
</c:forEach>
```

**17.在部署带有servlet的java web程序时，哪个文件不是必须的**

A.web.xml文件

B.index.html文件

C.WEB-INF文件

<font color=red>D.classes文件</font>

**18.servlet中实现和jsp相同的jsp跳转的方法**

<font color=red>forward sendRedirect</font>

19.使用需要jstl标签，在session作用域中增加一个 对象哪个做法是正确的

**20.在js中定义 var x,y = 100 请问x,y的值分别是什么**

``` javascript
x=undefined, y=100
```

**21.javaee中，text.jsp文件如下 试图运行时会发生什么错误**

```jsp
<html>
<% String str=null;%>
str is <%=”str”%>
</html>
```

A.转译期错误
B.编译期错误
C.运行后，浏览器上显示：str is null
D.运行后，浏览器上显示：str is str

22.session的说法正确的是

A.session的属性可以在站点内多个页面跳转之间共享，但不可以在站点外共享。

B.session能通过。

C.关闭浏览器的时候session属性被清空。

D.页面跳转的时候，session属性被清空。

**23.js中 5 === 5**

<font color=red> true</font>

24.

```html
<div id="mydiv">我是div <xx>我是xx</xx></div> 
document.getElementById(“mydiv”).children[0]
```

<font color=red>object HTMLxxElement</font>

**25.下面哪个servlet方法载入执行时只执行一次，负责对servlet进行初始化**

A.service

<font color=red>B.init</font> 

C.dopost

D.destory

**26.css作为超链接伪类的正确顺序是**

<font color=red>link visited hover active</font>

**27.location对象哪种页面跳转没有历史记录**

A.assign

B.reload

<font color=red>C.replace</font>

D.href

**28.对于ServletRequest的接口请求参数的方法哪一个是正确的**

A.如果一个参数key有多个值，那么getParameterV alues(key)方法会返回一个包含所有值的字符串数组。

B.getParameter方法返回Object对象，使用前要强制类型转换：如String str=(String)request.getParameter(key)。

C.如果一个参数key有多个值，那么getParameter(key)方法会返回空。

<font color=red>D.getParameter方法只用于接受post请求参数，接收get请求参数需要使用getQueryString方法。</font>

29.Ajax请求服务器中json 数据格式哪一个是正确的()

string=name

**30.有关会话跟踪技术描述正确的是**

<font color=red>A.Cookie是Web服务器发送给客户端的一小段信息，客户端请求时，可以读取该信息发送到服务器端。</font>

B.关闭浏览器意味着会话ID丢失，但所有与原会话关联的会话数据仍保留在服务器上，直至会话过期。

<font color=red>C.在禁用Cookie时可以使用URL重写技术跟踪会话。</font>

D.隐藏表单域将字段添加到HTML表单并在客户端浏览器中显示。

## 简答题 25分

**1.jsp中四大作用域的对象是什么**

<font color=red>四大作用域：page、request、session、application</font>

<font color=red>九大内置对象：out, config, page, pageContext, exception, request, response, application, session</font>

<font color=red>后四个比较常用</font>

**2.请写出div和span中分别让文字居中的代码**

```html
//div
div{text-align:center}
//span
span{text-align:center;display:block}
```

**3.请阐述一下web应用程序中所有乱码出现的场合以及解决方案**

<font color=red>1.页面参数的编码类型与系统默认的编码类型不一致造成的乱码：强制指定request获取参数的编码方式，如下</font>

`request.setCharacterEncoding("UTF-8");`

<font color=red>2.jsp在页面显示是出现乱码。在页面中设置编码格式,代码如下</font>

`response.setContentType("text/html;charset= UTF-8");`
<font color=red>3.比解决方案2更简单的方法是使用filter进行过滤。</font>

<font color=red>4.jsp与数据库之间的乱码解决方案。可以在驱动的URL参数中直接进行指定</font>

`jdbc:mysql://localhost/your_DB_name?user=root&password=root&useUnicode&characterEncoding=UTF-8`

<font color=red>5.java与文件，流之间乱码。java往往通过FileReader和FileWirter这两个类完成字符类型的读写，但这两个类的默认构造函数会使用系统的编码方式，如果文件的内容与系统的编码方式不一样，便会出现乱码。建议使用其父类，即</font>`InputStreamReader(InputStream in,Character cs)`<font color=red>和</font>`OutputStreamWriter(OutputStream out,Character cs)`

<font color=red>引入jsp，c:import的方式，例：</font>`<c:import url="/jsp/system/panelBar.jsp" charEncoding="UTF-8"></c:import>`<font color=red>这里记得加上编码设置</font>

**4.请描述 http session管理机制，并说明在web应用中如何监听session事件**

<font color=red>1.新客户端向服务器发送第一次请求的时候，request中并无sessionID。</font>

<font color=red>2.在服务器端会创建一个session对象，并分配一个sessionid，session对象会保存在服务器端。</font>

<font color=red>3.服务器端处理完，会将sessionid随同response一同传回给客户端，并存入客户端的cookie对象中。</font>

<font color=red>4.当客户端再次发送请求时，会将sessionid同request一起传给服务器。</font>

<font color=red>5.服务器根据sessionid将保存在服务器端的session对象进行关联。</font>



<font color=red>监听session事件，首先创建一个监听器</font>

```java 
implements HttpSessionListener
```

<font color=red>在web.xml加上这个</font>

```xml
<listener>

    <listener-class>

      ******

    </listener-class>

</listener>
```

**5.请描述jsp servlet 请求转发和重定向的区别，以及request作用域在这两种情况下的值是否能够传递。**

<font color=red>**重定向和请求转发的区别：**</font>

<font color=red>其实第一个区别我们在上面已经说过了， 但为了便于方便查找，以及保证文章结构清晰，我就再赘述一遍：重定向是浏览器客户端向Web应用服务器端发送两次请求，服务器端也向客户端返回两次处理结果，最后在浏览器地址栏中显示的是第二次访问的地址；而请求转发是浏览器向Web应用服务器端发送一次请求，服务器端也只向客户端返回一次处理结果，最后在浏览器地址栏中显示的是第一次访问的原地址。</font>

<font color=red>第二个区别是页面的跳转，还记得上面介绍重定向时说过的response.sendRedirect("./target.jsp");吗？引号里也可以写https://www.baidu.com，这样第二次访问的页面就是百度了。所以第二个区别就是重定向对页面的跳转没有限制，可以是本Web应用系统的资源，也可以是其他Web应用的资源；而请求转发处理页面跳转时，跳转的新地址必须是本Web应用系统的资源，不可以访问其他Web应用的资源。</font>

<font color=red>第三个区别是重定向无法在新的页面获取request.setAttribute("key", "value");中保存的数据，若非要使用<%= request.getAttribute("key") %>获取，则获取到的值为null;而请求转发就可以在新的页面获取到request.setAttribute("key", "value");中保存的数据。</font>

<font color=red>最后一个区别可以说是请求转发的一个特性：Web项目中WEB-INF文件夹是最安全的目录，该目录内的资源只能通过请求转发获取，重定向的方式无法获取!</font>

<font color=red>请求转发中，request作用域的值可以传递</font>

<font color=red>重定向，request作用域的值不可以传递</font>

## 程序设计 30分

1.请编写一段javascripts代码实现复选框的全选和全不选的功能

```html
<input class = 'check' type="checkbox" >
<input class = 'check' type="checkbox">
<input class = 'check' type="checkbox">
<input class = 'check' type="checkbox">
<input class = 'check' type="checkbox">
<input id="checkAll" type="button" value="全选">
<input id="unCheckAll" type="button" value="全不">
<input id="reverseCheck" type="button" value="反选">
```

```javascript
<script>
  /*一：需求分析：
      (1)点击全选：选中所有选择框（设置checked属性为true）
      (2)点击全不选：不选中所有选择框（设置checked属性为false）
      (3)点击反选：让每一个选择框的checked属性与自身相反
    二：思路分析
        1.获取元素
        2.注册事件
        3.事件处理
  */
  //1.获取页面元素
  var checkAll = document.getElementById('checkAll');//全选
  var unCheckAll = document.getElementById('unCheckAll');//全不选
  var reverseCheck = document.getElementById('reverseCheck');//反选
  var checkList = document.getElementsByClassName('check');//选择框列表
  //2.注册事件
  //2.1 全选
  checkAll.onclick = function(){
    //3.事件处理：选中所有选择框（设置checked属性为true）
    for(var i = 0;i<checkList.length;i++){
      checkList[i].checked = true;
    }
  }
  //2.2 全不选
  unCheckAll.onclick = function(){
    //3.事件处理:不选中所有选择框（设置checked属性为false）
    for(var i = 0;i<checkList.length;i++){
      checkList[i].checked = false;
    }
  }
  //2.3 反选
  reverseCheck.onclick = function(){
    //3.事件处理:让每一个选择框的checked属性与自身相反
    for(var i = 0;i<checkList.length;i++){
      checkList[i].checked = !checkList[i].checked;//逻辑非取反
      // if (checkList[i].checked == true){
      //   checkList[i].checked = false;
      // }else{//false
      //   checkList[i].checked = true;
      // }
    }
  }
</script>
```



2.请编写一个过滤器，实现以下功能

验证用户登录，如果用户未登录，跳转到log.jsp页面

设置请求响应的字符编码编码为uft-8

验证所有请求的url路径，排除log.jsp和log.do地址

```java
package com.student.filter;  
  
import com.student.entity.Users;  
import com.sun.deploy.net.HttpRequest;  
  
import javax.servlet.*;  
import javax.servlet.annotation.WebFilter;  
import javax.servlet.http.HttpServlet;  
import javax.servlet.http.HttpServletRequest;  
import javax.servlet.http.HttpServletResponse;  
import javax.servlet.http.HttpSession;  
import java.io.IOException;  
import java.io.PrintWriter;  
  
/** 
 * @Description 
 * @Author 单继重 
 * @Date 2016/10/24 10:19 
 */  
@WebFilter(filterName = "LoginFilter")  
public class LoginFilter implements Filter {  
    public void destroy() {  
    }  
  
    public void doFilter(ServletRequest req, ServletResponse resp, FilterChain chain) throws ServletException, IOException {  
        //chain.doFilter(req, resp);  
        HttpServletRequest request = (HttpServletRequest)req;  
        HttpServletResponse response = (HttpServletResponse)resp;  
        request.setCharacterEncoding("UTF-8");  
        response.setContentType("text/html;charset=UTF-8");  
        HttpSession session = request.getSession();  
        PrintWriter out = response.getWriter();  
        Users user = (Users)session.getAttribute("user");  
        if(user != null){  
            chain.doFilter(request,response);  
        } else{  
            out.println("您还未登陆，三秒钟后跳转至登录页面");  
            //out.println("<script language='javascript'>alert('你还未登录');");  
            response.setHeader("refresh","3;/pages/users/login.jsp");  
            //response.sendRedirect("/pages/users/login.jsp");  
            //request.getRequestDispatcher("/pages/users/login.jsp").forward(request,response);  
        }  
    }  
  
    public void init(FilterConfig config) throws ServletException {  
  
    }  
  
}  
```

```xml
<filter>  
        <filter-name>LoginFilter</filter-name>  
        <filter-class>com.student.filter.LoginFilter</filter-class>  
    </filter>  
    <filter-mapping>  
        <filter-name>LoginFilter</filter-name>  
        <url-pattern>/pages/student/*</url-pattern>  
    </filter-mapping>  
    <filter-mapping>  
        <filter-name>LoginFilter</filter-name>  
        <url-pattern>/pages/users/update.jsp</url-pattern>  
    </filter-mapping>  
    <filter-mapping>  
        <filter-name>LoginFilter</filter-name>  
        <url-pattern>/index.jsp</url-pattern>  
    </filter-mapping>  
    <filter-mapping>  
        <filter-name>LoginFilter</filter-name>  
        <url-pattern>/servlet/StudentServlet</url-pattern>  
    </filter-mapping>  
```

