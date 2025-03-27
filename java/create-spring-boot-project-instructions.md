# Create Spring Boot Project Instructions

1. Make sure the Java 21 SDK is installed on your system. Run this command and check the version of Java.

   ```bash
   java -version
   ```

2. Execute this command to download a Spring Boot project template

   ```bash
   curl https://start.spring.io/starter.zip \
     -d applicationName=DemoWebApplication \
     -d artifactId=demo-web \
     -d dependencies=web,data-jpa,h2,postgresql,lombok \
     -d description="Demo Web Application" \
     -d javaVersion=21 \
     -d name=demo-web \
     -d packageName=com.example \
     -d packaging=jar \
     -d type=maven-project \
     -o demo-web.zip
   ```

3. Unzip the downloaded file

   ```bash
   unzip demo-web.zip -d .
   ```

4. Remove the zip file

   ```bash
   rm -f *.zip
   ```

Let's do this step by step.
