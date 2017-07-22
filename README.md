# Spring SpringMVC MyBaits Boilerplate.

1. Create Gradle based Java Web project in Intellij IDEA.
2. Generate WEB-INF/web.xml
3. Edit build.gradle file
4. Create webapp/default.jsp
5. Edit web.xml
    - welcome-file-list
    - encoding filter
    - spring dispatcher servlet
    - default servlet
    - spring context loader listener
    - spring context config location
6. Create resources/applicationContext.xml
7. Create resources/jdbc.properties
    - jdbc_driverClassName
    - jdbc_url
    - jdbc_username
    - jdbc_password
8. Edit applicationContext.xml
    - context:properties-placeholder
    - data source bean
    - sqlSession factory bean
    - sqlSession template bean
9. Create WEB-INF/web-servlet.xml
10. Edit web-servlet.xml
    - mvc:annotation-driven
    - context:component-scan
        - ssm.controller
        - ssm.dao.impl
        - ssm.service.impl
11. Create ssm.controller.BaseController class
12. Create ssm.model.BaseModel class
13. Create commons/inc.jsp
14. Create webapp/assets directory
15. Create util.Constant interface
16. Create util.Pagination class
17. Create dao.GenericDao interface
18. Create dao.impl.GenericDaoImpl class
19. Create service.GenericService interface
20. Create service.impl.GenericServiceImpl class
21. Create resources/freemarker.xml
    - freemarker bean    
22. Create commons/page.jsp
23. import jquery.js into assets/js
24. Create freemarker templates
    - code
        - Dao.ftl
        - Dao.Impl.ftl
        - Service.ftl
        - Service.Impl.ftl
        - Controller.ftl
    - config
        - mapper.ftl
    - page
        - index.ftl
        - add.ftl
        - list.ftl
        - edit.ftl
25. Create ssm.util.ComponentGenerator class