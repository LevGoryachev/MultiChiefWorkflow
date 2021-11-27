# MultiChiefWorkflow
<p><b>MultiChief</b> is an experimental microservice-based ERP system for construction industry (on-line and off-line interaction between departments and employees). <p/>
<p><b>MultiChiefConstruction</b> is a microservice that is responsible for preparing data (DTO) for orchestrators (modules of <a href="https://github.com/LevGoryachev/MultiChiefMain">MultiChiefMain</a>).</p> 
<p><b>Summary: Java 11, Spring-Boot, Spring Security, Spring Data JPA (Hibernate)</b></p>
<p><b>Database: PostgreSQL</b></p>

<p>Database structure in files:</p>
<ul>
<li><b>MultiChiefWorkflow_DDL_v1.1.sql</b></li>
</ul>

<h3>Database scheme</h3>

![MultiChiefMRP_DB_v1_1](https://user-images.githubusercontent.com/61917893/135180107-8bce0b15-a7ba-4c82-b900-2598669bf85e.jpg)


<p>Descriptions:</p>

<ul>
<li>bow - bill of works</li>
<li>completion - completed works can be related with "construction" through bills of works (bow) to awoid different constructions in a work completion certificate</li>
</ul>

<p>MultiChief (ERP). License: GNU GPL v3. Copyright (C) 2021 Lev Goryachev.</p>
