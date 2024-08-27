<center>

[comment]: <img src="./media/media/image1.png" style="width:1.088in;height:1.46256in" alt="escudo.png" />

![./media/media/image1.png](./media/logo-upt.png)

**UNIVERSIDAD PRIVADA DE TACNA**

**FACULTAD DE INGENIERIA**

**Escuela Profesional de Ingeniería de Sistemas**

**Proyecto *Herramienta de Seguimiento y Evaluación del Desempeño de Red y Hardware en Computadoras UPT***

**Curso:** Inteligencia de Negocios

**Docente:** Mag. Patrick Cuadros Quiroga

**Integrantes:**

Escobar Rejas, Carlos Andrés (2021070016)  
Apaza Ccalle, Albert Kenyi (2021071075)  
Ricardo Cutipa Gutierrez (2021069827)  
Erick Churacutipa Blass (2020067578)  
Jesus Huallpa Maron (2021071085)

**Tacna – Perú**

**2024**

</center>
<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1\.0|Apaza|ELV|ARV|24/08/2024|Versión Original|












**Sistema *Herramienta de Seguimiento y Evaluación del Desempeño de Red y Hardware en Computadoras UPT***

**Documento de Visión**

**Versión *{1.0}***
**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

|CONTROL DE VERSIONES||||||
| :-: | :- | :- | :- | :- | :- |
|Versión|Hecha por|Revisada por|Aprobada por|Fecha|Motivo|
|1\.0|MPV|ELV|ARV|10/10/2020|Versión Original|


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>


**INDICE GENERAL**
#
[1.	Introducción](#_Toc52661346)

1.1	Propósito

1.2	Alcance

1.3	Definiciones, Siglas y Abreviaturas

1.4	Referencias

1.5	Visión General

[2.	Posicionamiento](#_Toc52661347)

2.1	Oportunidad de negocio

2.2	Definición del problema

[3.	Descripción de los interesados y usuarios](#_Toc52661348)

3.1	Resumen de los interesados

3.2	Resumen de los usuarios

3.3	Entorno de usuario

3.4	Perfiles de los interesados

3.5	Perfiles de los Usuarios

3.6	Necesidades de los interesados y usuarios

[4.	Vista General del Producto](#_Toc52661349)

4.1	Perspectiva del producto

4.2	Resumen de capacidades

4.3	Suposiciones y dependencias

4.4	Costos y precios

4.5	Licenciamiento e instalación

[5.	Características del producto](#_Toc52661350)

[6.	Restricciones](#_Toc52661351)

[7.	Rangos de calidad](#_Toc52661352)

[8.	Precedencia y Prioridad](#_Toc52661353)

[9.	Otros requerimientos del producto](#_Toc52661354)

b) Estandares legales

c) Estandares de comunicación	](#_toc394513800)37

d) Estandaraes de cumplimiento de la plataforma	](#_toc394513800)42

e) Estandaraes de calidad y seguridad	](#_toc394513800)42

[CONCLUSIONES](#_Toc52661355)

[RECOMENDACIONES](#_Toc52661356)

[BIBLIOGRAFIA](#_Toc52661357)

[WEBGRAFIA](#_Toc52661358)


<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

**<u>Informe de Visión</u>**

1. <span id="_Toc52661346" class="anchor"></span>**Introducción**
   Este documento presenta el proyecto para la recopilación y análisis de datos del sistema de computadoras en la Universidad Privada de Tacna, en el contexto del curso de Inteligencia de Negocios. El propósito principal es evaluar el rendimiento de los equipos y la eficiencia del uso de recursos en el área de soporte de la Escuela Profesional de Ingeniería de Sistemas (EPIS), turno tarde.



    1.1	Propósito
       
        Recopilar y analizar datos del sistema: Obtener información detallada sobre el uso de recursos de las computadoras en el laboratorio de pruebas.
       
        Evaluar el rendimiento y el consumo: Identificar el consumo de energía, el rendimiento en términos de uso de CPU, RAM y GPU, así como el consumo de internet.
       
        Optimización del soporte: Proporcionar datos útiles para mejorar el soporte técnico y el mantenimiento de las computadoras.


    1.2	Alcance
       
       Área de estudio: Computadoras en el laboratorio de pruebas de la Universidad Privada de Tacna.
       
        Datos a recopilar: Temperatura durante la sesión, número de sesiones, consumo de internet (Mbps), número de clics, programas más utilizados, y software con mayor consumo de recursos (CPU, RAM, GPU).
    
        Metodología: Utilización de un script en Python con la biblioteca psutil para recopilar datos de rendimiento y actividad.
   
   

    1.3	Definiciones, Siglas y Abreviaturas
       
        CPU: Unidad Central de Procesamiento (Central Processing Unit).
       
        RAM: Memoria de Acceso Aleatorio (Random Access Memory).
       
        GPU: Unidad de Procesamiento Gráfico (Graphics Processing Unit).
       
        Mbps: Megabits por segundo (Megabits per second).
       
        psutil: Biblioteca de Python para la recopilación de información del sistema y el monitoreo de recursos.
   

    1.4	Referencias
    
        Documentación de psutil: https://psutil.readthedocs.io
            Guías de Python: https://docs.python.org
            Manual de la Universidad Privada de Tacna: Normas y permisos para el uso de laboratorios.

    1.5	Visión General

        Este proyecto se centrará en la recopilación de datos relevantes del sistema para identificar patrones y áreas de mejora. Se llevará a cabo de la siguiente manera:
                
           Implementación del script: El script en Python se ejecutará en el laboratorio de pruebas con el permiso de la escuela para capturar los datos necesarios.
                Análisis de datos: Evaluar los datos recopilados para determinar el consumo de recursos y el rendimiento general del sistema.
                Informe de resultados: Presentar un informe detallado con los hallazgos y recomendaciones para optimizar el uso de los recursos en las computadoras.

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

2. <span id="_Toc52661347" class="anchor"></span>**Posicionamiento**

    2.1	Oportunidad de negocio

    2.2	Definición del problema

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

3. <span id="_Toc52661348" class="anchor"></span>**Vista General del Producto**

    3.1	Resumen de los interesados

    3.2	Resumen de los usuarios

    3.3	Entorno de usuario

    3.4	Perfiles de los interesados

    3.5	Perfiles de los Usuarios

    3.6	Necesidades de los interesados y usuarios

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

4. <span id="_Toc52661349" class="anchor"></span>**Estudio de
    Factibilidad**

    4.1	Perspectiva del producto

    4.2	Resumen de capacidades

    4.3	Suposiciones y dependencias

    4.4	Costos y precios

    4.5	Licenciamiento e instalación

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

5. <span id="_Toc52661350" class="anchor"></span>**Características del producto**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

6. <span id="_Toc52661351" class="anchor"></span>**Restricciones**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

7. <span id="_Toc52661352" class="anchor"></span>**Rangos de Calidad**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

8. <span id="_Toc52661353" class="anchor"></span>**Precedencia y Prioridad**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

9. <span id="_Toc52661354" class="anchor"></span>**Otros requerimientos del producto**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

<span id="_Toc52661355" class="anchor"></span>**CONCLUSIONES**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

<span id="_Toc52661356" class="anchor"></span>**RECOMENDACIONES**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

<span id="_Toc52661357" class="anchor"></span>**BIBLIOGRAFIA**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>

<span id="_Toc52661358" class="anchor"></span>**WEBGRAFIA**

<div style="page-break-after: always; visibility: hidden">\pagebreak</div>
