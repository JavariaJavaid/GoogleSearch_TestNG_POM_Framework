# GoogleSearch_TestNG_POM_Framework

To avoid compatibilities issue of TESTNG I used Eclipse EE IDE Version: 2022-03 (4.23.0)
other than that

if import project and error in jre unbound-->(right click on project--> click on build path-->then click on add libraries tab-->remore jre unbound and add new library-->click on jre system -->apply and save


Steps for TestNG
1: Add TestNG plugin from (eclipse->help tab->market place->search test NG and install->testNG and M2E..MAVEN Integration eclipse should be download)
2:Add testNG libraries
  2.1: for first of all we should create Maven Project
  2.2: There is an pom.xml file 
  2.3: Add libraries from the official website Testng.org or from mvnrepository.com
  2.4: the testNG libraries consist of this type of code
                              <dependencies>

<!-- https://mvnrepository.com/artifact/org.testng/testng -->
<dependency>
    <groupId>org.testng</groupId>
    <artifactId>testng</artifactId>
    <version>7.6.1</version>
    <scope>test</scope>
</dependency>


  </dependencies>
  
  2.5 if there is an error try this:
  
      2.51: Right click on project 
      2.52: click on Maven
      2.53: then click on update maven project
      
      
      (Not work for me )
  2.6 MAVEN dependency folder should be exist in project folder if not the try this
  
      2.61: Right click on project
      2.62: click on Maven
      2.63: then click on Add dependency
 
3: Validate
