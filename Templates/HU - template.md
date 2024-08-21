Createted:: <% tp.file.creation_date()%>
Last_Modificated:: <% tp.file.last_modified_date("dddd Do MMMM YYYY HH:mm:ss") %>
tags:: <% tp.system.suggester(["Módulo PEI", "Módulo POI", "Módulo PESEM"], ["Módulo PEI", "Módulo POI", "Módulo PESEM"]) %>
category:: <% tp.system.suggester(["Planeamiento", "Seguimiento", "Evaluación", "Mejora continua"], ["Planeamiento", "Seguimiento", "Evaluación", "Mejora continua"])%>
<% await tp.file.functions.move("/2_Requisitos/") %>
tipo: [[Home_Backlog_Aplicativo_Ceplan_V2.0]]


# Título:  <% tp.system.prompt("Ingresa el título de la nota") %>

## Tareas del Día 

- [ ] Tarea 1 
- [ ] Tarea 2 
- [ ] Tarea 3 
 

## Reflexiones 
- 


# Plan semanal
- **Lunes** [[ Nota diaria <% tp.date.weekday("DD-MM-YYYY", 1) %>]]
	- Actividad 1: <% tp.system.prompt("Ingrese el nombre de la actividad")%>

 - **Martes** [[ Nota diaria <% tp.date.weekday("DD-MM-YYYY", 2) %>]]


- **Miércoles** [[ Nota diaria <% tp.date.weekday("DD-MM-YYYY", 3) %>]]


- **Jueves** [[ Nota diaria <% tp.date.weekday("DD-MM-YYYY", 4) %>]]
- **Viernes** [[ Nota diaria <% tp.date.weekday("DD-MM-YYYY", 5) %>]]
- **Sábado** [[ Nota diaria <% tp.date.weekday("DD-MM-YYYY", 6) %>]]
- **Domingo** [[ Nota diaria <% tp.date.weekday("DD-MM-YYYY", 7) %>]]


