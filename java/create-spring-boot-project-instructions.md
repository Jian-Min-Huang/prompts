# Create Spring Boot Project Instructions

1. Create a new directory for your project

   ```bash
   mkdir -p ~/demo-web && cd ~/demo-web
   ```

2. Execute this command to download a Spring Boot project template

   ```bash
   curl https://start.spring.io/starter.zip \
     -d applicationName=DemoWebApplication \
     -d artifactId=demo-web \
     -d dependencies=web \
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

5. Open the project with Visual Studio Code

   ```bash
   code-insiders .
   ```

Let's do this step by step.
