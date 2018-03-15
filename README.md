<h1> Metode de dezvoltare software </h1>

<h3>Grupa 353 - Ceaușescu Ciprian Mihai - ciprianmihai94@gmail.com</h3>

<h3>Proiect - 3 puncte</h3>
[TFS with JAVA](https://www.youtube.com/watch?v=porFDKNPS2I)
<br>
[Echipe](https://drive.google.com/open?id=1bgJ4wDuw5l4lOAAcQ-X6H5-1oYYOaC-wH4Ygkps6x_o)
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
[Link](https://drive.google.com/open?id=1PQiNpw6a8_aB5MhDIzPYmEMAom_LBfRJ)
<br>
<h5>Eroare la conexiunea cu baza de date in proiectul de MVC<h5>
In Web config, trebuie modificat String-ul de conexiune:
<br>
<add name="SchoolContext" connectionString="Data Source=(LocalDb)\MSSQLLocalDB;Initial Catalog=ContosoUniversity1;Integrated Security=SSPI;" providerName="System.Data.SqlClient"/>
<br>
Daca Controllerul a fost creat cu Students, trebuie modificata si ruta:
<br>
@Html.ActionLink("Students", "Index", "Students")
