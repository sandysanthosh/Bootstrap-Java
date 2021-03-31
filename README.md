# Bootstrap-Java
step by step process to use Java in Boostrap


#### Header.jspf:

```
<@ include file ="/jsp/core.jspf/" %>
<@ include file ="/jsp/core.jspf/" %>
<@ include file ="core.jspf" %>
<@ page ContentType = "text/html; charset=utf-8 %>
```

#### Header.jsp:

```
<% include file = "/common/jsp/header.jspf" %>
<% page import = "java.math.*" %>
<% page import = "java.util.*" %>
```
#### Main.jsp:
```
<% page  include ="/Header.jspf" %>
<% java.lang.string name = model.getname(); %>
<% boolean name = model.istrue(); %>
<% java.lang.string namecondition = "  " %>

<body>
  
  <% if(namecondition) { %>
  <table>
  <tr>
    <td> name :</td>  <%= name %>
    <td valid="top" alignt="left"><IMG SRC="<%= style.get(info, "InfoButtion"); %>"></td>
    <td> values </td>
    </tr>
    </table>
    <% } %>
    </body>
    
```

