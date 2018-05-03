<h1> Metode de dezvoltare software </h1>

<h3>Grupa 353 - Ceaușescu Ciprian Mihai - ciprianmihai94@gmail.com</h3>

<h3>Proiect - 3 puncte</h3>
<a href="https://www.youtube.com/watch?v=porFDKNPS2I">TFS with JAVA</a>
<br>
<a href="https://drive.google.com/open?id=1bgJ4wDuw5l4lOAAcQ-X6H5-1oYYOaC-wH4Ygkps6x_o">Echipe</a>
<h4>Cerințe:</h4>
<ol>
  <li>
    (1p) Aplicație MVC - folosind Entity Framework (C#) / Hibernate (Java).
    <br>
    Trebuie să prezentați tema proiectului, specificațiile acestuia și detaliile de implementare.
  </li>
  <li>
    (1.5p) Servicii - fiecare membru al echipei trebuie să realizeze un serviciu care să funcționeze independent (folosind orice limbaj de programare). Acesta va rula local, dar și în Cloud.
    <br>
    Aplicația MVC trebuie modificată pentru a consuma aceste servicii realizate.
  </li>
  <li>
    (0.5p) Dificultatea proiectului. Se acordă cele 0.5p în funcție de dificultatea proiectului realizat.
  </li>
</ol>
Deadlines: 
<ul>
  <li>Săptămâna 5 - idei + specificații.</li>
  <li>Săptămâna 9 - MVC + prezentare.</li>
  <li>Săptămâna 11 - 1 serviciu funcțional - deploy Cloud.</li>
  <li>Săptămâna 13/14 - prezentare finală.</li>
</ul>
 
<br>
<h3>Laborator</h3>
<h3>MVC - Entity Framework</h3>
<a href="https://drive.google.com/open?id=1PQiNpw6a8_aB5MhDIzPYmEMAom_LBfRJ">EF Tutorial</a>
<br>
<h5>Eroare la conexiunea cu baza de date in proiectul de MVC<h5>
In Web config, trebuie modificat String-ul de conexiune:
<br>
connectionString="Data Source=(LocalDb)\MSSQLLocalDB;Initial Catalog=ContosoUniversity1;Integrated Security=SSPI;"
<br>
Daca Controllerul a fost creat cu Students, trebuie modificata si ruta:
<br>
@Html.ActionLink("Students", "Index", "Students")
<br>
<br>
<h3>Laborator Servicii</h3>
<a href="https://docs.microsoft.com/en-us/dotnet/framework/wcf/getting-started-tutorial">Servicii</a>
<br>
<a href="http://wcftutorial.net/">WCF Tutorial</a>
<br>
<h3>Laborator Servicii 2 </h3>
<a href="https://msdn.microsoft.com/en-us/library/bb386386.aspx">Servicii 2</a>
<br>
<h3>CI / CD</h3>
<a href="https://docs.microsoft.com/en-us/vsts/build-release/test/example-continuous-testing?view=vsts">CI CD Tutorial</a>
<h3>Laborator Servicii 3 </h3>
<a href="https://channel9.msdn.com/Blogs/OneCode/How-to-create-and-host-WCF-services-in-Azure">WCF in cloud</a>
<br>
LV: Microservice development with ASP.NET Core, Docker, and Azure App Services (problem with Docker).
<br>
<h3>Github</h3>
LV: Getting Started with Git using Team Foundation Server 2018
<br>
<h3>Docker</h3>
<a href="https://training.docker.com/">Training Docker</a>
<br>
LV: Install and Configure SQL Server Docker Containers on Ubuntu Linux
<br>
<a href="https://docs.microsoft.com/en-us/dotnet/standard/microservices-architecture/docker-application-development-process/docker-app-development-workflow">Docker application development process</a>
<br>
<h3>How to create services in Java?</h3>
<ol>
  <li><a href="https://www.tutorialspoint.com/restful/index.htm">REST Tutorial</a></li>
  <li><a href="https://memorynotfound.com/jax-ws-soap-web-service-example/">SOAP Example</a></li>
  <li><a href="https://www.mkyong.com/webservices/jax-ws/jax-ws-hello-world-example-document-style/">JAX-WS Hello World Example</a></li>
</ol>


