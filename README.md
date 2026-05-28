📘 Day 7 – Project 2: Spring Boot Greeting Application

📌 Project Overview



Project Name: day7proj2phase1



A beginner-level Spring Boot REST API project demonstrating:



Custom server port configuration via application.properties



Multiple REST controllers with clean package separation



Path variable usage with @PathVariable



Embedded Tomcat server (via spring-boot-starter-web)



📌 Project Info



Field | Details



Day | Day 7 – Project 2



Type | Spring Boot REST Application



Tech Stack | Java 17, Spring Boot 3.x, Maven, Tomcat



Architecture | Controller · Main · Resources



🗂️ Project Structure



day7proj2phase1/



├── pom.xml ← Maven build file



└── src/



└── main/



├── java/



│ └── com/



│ └── day7/



│ └── helloproject/



│ ├── SpringbootGreetingApplication.java ← Entry point (main class)



│ └── controller/



│ ├── HelloController.java ← /hello endpoint



│ └── GreetController.java ← /greet/{name} endpoint



└── resources/



└── application.properties ← Custom port config



🧩 Features



\# | Feature | Description



1 | 🌐 Hello Endpoint | Returns a basic greeting message



2 | 👋 Greet Endpoint | Returns a personalized greeting using path variable



3 | ⚙️ Custom Port | App runs on port 9090 instead of default 8080



4 | 🔌 Embedded Tomcat | No external server setup needed



5 | 📦 Clean Structure | Separate controller package for REST endpoints



🖥️ Sample Output



. \_\_\_\_ \_ \_\_ \_ \_



/\\\\ / \_\_\_'\_ \_\_ \_ \_(\_)\_ \_\_ \_\_ \_ \\ \\ \\ \\



( ( )\\\_\_\_ | '\_ | '\_| | '\_ \\/ \_` | \\ \\ \\ \\



\\\\/ \_\_\_)| |\_)| | | | | || (\_| | ) ) ) )



' |\_\_\_\_| .\_\_|\_| |\_|\_| |\_\\\_\_, | / / / /



=========|\_|==============|\_\_\_/=/\_/\_/\_/



:: Spring Boot :: (v3.x)



Tomcat started on port 9091



GET /hello



→ Hello from Spring Boot!



GET /greet/Keerthana



→ Hello, KEERTHANA!!! Welcome to Spring Boot.



🏗️ Architecture Overview



SpringbootGreetingApplication.java (Main / Entry Point)



│



▼



HelloController.java (GET /hello)



GreetController.java (GET /greet/{name})



│



▼



application.properties (server.port=9090)



Main Layer — SpringbootGreetingApplication.java launches the Spring Boot app



Controller Layer — HelloController.java and GreetController.java handle REST requests



Config Layer — application.properties sets the custom server port to 9091



👩‍💻 Author



AKSHAYA SATHIANARAYANAN

