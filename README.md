<h1>Second Project Java: REST API with Spring Boot</h1>
<h3>Overview</h3>
<p>This project demonstrates the development of a professional RESTful API designed to manage a product catalog. It transitions from basic Java logic to a robust, database-driven system using industry-standard frameworks.</p>
<h3>Key Features & Accomplishments</h3>
<ul>
  <li>Layered Architecture: Organized the code into distinct layers (Controller, Service, Repository, and Domain) to ensure high maintainability and clean separation of concerns.</li>
  <li>Full CRUD Functionality: Implemented a complete set of operations to Create, Read, Update, and Delete products within the system.</li>
  <li>Database Persistence: Integrated Spring Data JPA with an in-memory H2 Database, moving away from temporary storage to structured SQL tables.</li>
  <li>Global Exception Handling: Developed a @ControllerAdvice handler to provide user-friendly, custom 404 Not Found error messages.</li>
  <li>Interactive Documentation: Configured Swagger UI (OpenAPI) for real-time API testing and automated documentation.</li>
</ul>
<h3>How to test the app:</h3>
<ul>
  <li>Launch the Project in IntelliJ IDEA</li>
  <li>Wait for Maven to download dependencies.</li>
  <li>Go to: http://localhost:8080/swagger-ui/index.html or use Postman (as I did)</li>
  <li>Use the <b>POST</b> endpoint to add new products.</li>
  <li>Use the <b>GET, PUT</b> and <b>DELETE</b> endpoints to manage the data.</li>
</ul>
<h4>Use the <b>GET, PUT</b> and <b>DELETE</b> endpoints to manage the data.</h4>
<ul>
  <li>Go to: http://localhost:8080/console</li>
  <li>JDBC URL: jdbc:h2:mem:testdb</li>
  <li>User: sa (Leave password blank).</li>
  <li>Run SELECT * FROM PRODUCTS; to see your data live in the database.</li>
</ul>

<h2>Example:</h2>
<div>Here I am using method <b>POST</b> to add name</div>
<img width="1920" height="1080" alt="Снимок экрана (196)" src="https://github.com/user-attachments/assets/9fdbb386-b6d6-4e10-a7c3-7171cd76b127"/>
<div>And here using method <b>GET</b> to check if the name "Mama" was added</div>
<img width="1920" height="1080" alt="Снимок экрана (196)" src="https://github.com/user-attachments/assets/252a4161-2deb-4dab-9514-4350aea2c936" />
<div>Then here I'm using method <b>PUT</b> to change info</div>
<img width="1920" height="1080" alt="Снимок экрана (197)" src="https://github.com/user-attachments/assets/0b0794d4-c243-416b-b18b-f9922649a6f7" />
<div>On this photo usinf method <b>DELETE</b> to delete info</div>
<img width="1920" height="1080" alt="Снимок экрана (199)" src="https://github.com/user-attachments/assets/d16dff5c-a755-41fb-a7bf-de069bcf6c05" />
<div>And we see that name: Papa was successfully deleted</div>
<img width="1920" height="1080" alt="Снимок экрана (199)" src="https://github.com/user-attachments/assets/c48c968c-259a-4b89-8013-98f9ba4aa37d" />


<h3>Adding Databases to Project</h3>
<div>On this photo I'm checking all informations (names and ids) that I have added</div>
<img width="1920" height="1080" alt="Снимок экрана (230)" src="https://github.com/user-attachments/assets/ab783a12-6624-4f63-9a00-20ec1ae4b53d" />
<div>Using this site: Go to: http://localhost:8080/console we are verifying what contains in our database</div>
<img width="1920" height="1080" alt="Снимок экрана (231)" src="https://github.com/user-attachments/assets/17f04cbc-d6ff-4804-b83d-b37a86651b10" />

<h3>Conclusion</h3>
<p>This project successfully bridges the gap between backend logic and database management, resulting in a scalable and well-documented API.</p>











