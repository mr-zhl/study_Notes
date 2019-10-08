# study_Notes
spring-boot数据库的学习笔记,欢迎大家访问!
学习思路:一.spring-boot入门:1,什么是spring-boot;
                         2.好处;
                         3.maven工程的创建,从网首站上下载;
                         4.使用spring-boot建议的目录,(application,domain,servise,controller);
                         5.引入web模块,jar架包;
                         6.在启动类中运行@ResponseBody,以JSON的形式输出
            ---------------华丽的分割线-------------------------
           二.spring-boot和mybatis的集成:
           1.需要添加的依赖:(spring-boot:https://start.spring.io/)
                a.DecTools(热部署)
                b.mysql数据库(选5.1.39)
                c.myBatisd.web(view)
                d.添加druid(数据源)
                e.添加lombok(优雅的编码)
           2.两种形式的配置,一种是properties,另一种是yml语言的配置(1.连接数据库2.mybatis配置);
           3.generatorConfig.xml中修改包名,工程名,自动生成.
           4.spring-boot 的热部署,简单的数就是不用多次启动项目
           5.lombok优雅的编.
           6.spring-boot分页查询
           7.spring-boot-restful



