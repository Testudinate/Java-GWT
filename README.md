# Java-GWT

1.https://netbeans.org/kb/74/web/quickstart-webapps-gwt_ru.html

Google Web Toolkit (GWT, ˈɡwɪt) — свободный Java-фреймворк, который позволяет веб-разработчикам создавать Ajax-приложения. Его особенность - это компилятор Java -> JavaScript, позволяющий почти всю разработку клиента и сервера реализовать на основе Java и лишь на последнем этапе создать соответствующие JavaScript, HTML и CSS. 
Выпускается под лицензией Apache версии 2.0. GWT делает акцент на повторное использование и кросс‐браузерную совместимость.

2.Плагин GWT для разработчки 
https://developers.google.com/eclipse/docs/install-eclipse-4.4?hl=ru 

https://developers.google.com/eclipse/docs/creating_new_webapp?hl=ru

Дома проверить \ протестировать  

3.Плагин версии 2.5.1 - http://www.gwtproject.org/versions.html
4.1 Создать тестовое приложение Web Application Project - > запустить шаблон (далее установить плагин для Chrome 	
"GWT Developer Plugin Options" - > добавить localhost.

4.1.1 Первый запуск приложения :

Initializing App Engine server
дек 14, 2015 2:12:19 PM com.google.appengine.tools.development.SystemPropertiesManager setSystemProperties
INFO: Overwriting system property key 'java.util.logging.config.file', value 'C:\Users\Stanislav.Klevtsov\Downloads\eclipse-jee-mars-1-win32-x86_64\eclipse\plugins\com.google.appengine.eclipse.sdkbundle_1.9.30\appengine-java-sdk-1.9.30\config\sdk\logging.properties' with value 'WEB-INF/logging.properties' from 'C:\Users\Stanislav.Klevtsov\workspace\TestGWT_1\war\WEB-INF\appengine-web.xml'
дек 14, 2015 2:12:19 PM com.google.apphosting.utils.jetty.JettyLogger info
INFO: Logging to JettyLogger(null) via com.google.apphosting.utils.jetty.JettyLogger
дек 14, 2015 2:12:19 PM com.google.appengine.tools.development.DevAppServerImpl setServerTimeZone
WARNING: Unable to set the TimeZone to UTC (this is expected if running on JDK 8)
дек 14, 2015 2:12:19 PM com.google.apphosting.utils.jetty.JettyLogger info
INFO: jetty-6.1.x
дек 14, 2015 2:12:20 PM com.google.apphosting.utils.jetty.JettyLogger info
INFO: Started SelectChannelConnector@0.0.0.0:8888
дек 14, 2015 2:12:20 PM com.google.appengine.tools.development.AbstractModule startup
INFO: Module instance default is running at http://localhost:8888/
дек 14, 2015 2:12:20 PM com.google.appengine.tools.development.AbstractModule startup
INFO: The admin console is running at http://localhost:8888/_ah/admin
дек 14, 2015 2:12:20 PM com.google.appengine.tools.development.DevAppServerImpl doStart
INFO: Dev App Server is now running

development mode: 

http://127.0.0.1:8888/TestGWT_1.html?gwt.codesvr=127.0.0.1:9997

4.2.1 Как лечить эту ошибку \ сообщение : 

Initializing App Engine server
дек 14, 2015 2:06:12 PM com.google.appengine.tools.development.SystemPropertiesManager setSystemProperties
INFO: Overwriting system property key 'java.util.logging.config.file', value 'C:\Users\Stanislav.Klevtsov\Downloads\eclipse-jee-mars-1-win32-x86_64\eclipse\plugins\com.google.appengine.eclipse.sdkbundle_1.9.30\appengine-java-sdk-1.9.30\config\sdk\logging.properties' with value 'WEB-INF/logging.properties' from 'C:\Users\Stanislav.Klevtsov\workspace\TestGWT_1\war\WEB-INF\appengine-web.xml'

************************************************
Could not open the requested socket: Address already in use: bind
Try overriding --address and/or --port.

5.https://www.eclipse.org/egit/download/ 
плагин для git-а

6.Download UML DesignerVersion 5.0

https://marketplace.eclipse.org/category/free-tagging/free-uml-eclipse

http://marketplace.obeonetwork.com/module/uml/download

7.UML documentation

http://www.umldesigner.org/

8.http://marketplace.obeonetwork.com/module/uml2java-generator

9.Плагин для отрисовки пакетов в Java

MoDisco - этим плагином генерировать .xmi файл и UML , а UML Disainer 5.0 уже из UML строит диаграмму пакетов, он и диаграмму классов сможет построить , если xmi файл MoDisco более расширенный сгенерировать 

 https://wiki.eclipse.org/MoDisco/Installation
 
 https://wiki.eclipse.org/MoDisco/SimpleTransformationChain



