JSP Tags
1. Scripting Tags (<% ... %>)
These tags allow embedding Java code inside JSP pages.

  i)Scriptlet Tag: <% ... %> → Used for writing Java code inside JSP.
  ii)Declaration Tag: <%! ... %> → Used for declaring variables and methods.
  iii)Expression Tag: <%= ... %> → Used to output values directly to the response.
2. Directive Tags (<%@ ... %>)
Directive tags provide global settings and instructions to the JSP engine.

   i)Page Directive: <%@ page attribute="value" %> → Defines page settings like language, session, etc.
   ii)Include Directive: <%@ include file="filename.jsp" %> → Includes static content from another JSP file.
   iii)Taglib Directive: <%@ taglib uri="URI" prefix="prefix" %> → Used for including custom tags and JSTL libraries.
3. Action Tags (<jsp: ... />)
These tags define dynamic behavior inside JSP.

     i)Include Tag: <jsp:include page="filename.jsp" /> → Includes another JSP at runtime.
     ii)Forward Tag: <jsp:forward page="destination.jsp" /> → Redirects the request to another resource.
     iii)Bean Action Tags:
         <jsp:useBean id="beanName" class="package.ClassName" scope="scope" /> → Creates or retrieves a JavaBean.
         <jsp:setProperty name="beanName" property="propertyName" value="value" /> → Sets properties of a JavaBean.
         <jsp:getProperty name="beanName" property="propertyName" /> → Retrieves properties of a JavaBean.
