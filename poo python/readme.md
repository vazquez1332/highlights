
Object-oriented programming with reading csv files and efficient use of lists

STATEMENT

The UNSJ social work (DAMSU) has a file with the personal data of the agents
who work at the UNSJ, called affiliates.csv and a file with the services provided to their
affiliates during the month of April called attentions.csv
The affiliate file records: DNI, name and surname and the unit in which they provide service
(FCEFyN, FASCO, etc.)
The care file records: DNI, date of care in format (dd/month/year), amount of
care, provider entity and the percentage of coverage that the member has.
Note: the files are not in any particular order, and the separator used is “;”.
The Social Work systems analyst asks you for a Python program to
process both files.
The program must:
1. Create the Affiliates and Attentions classes. File data represents the state
of the objects belonging to these classes.
2. Load the Affiliate data into an AffiliateManager which will have the
attribute a list, reading the data from the file “affiliates.csv”
3. Load the Attentions data into an AttentionsManager which will have the
attribute a list, reading the data from the “attentions.csv” file.
Through a menu of options, carry out the following functionalities (NOT
ALLOWS LISTS TO BE DRAWN FROM THE HANDLERS TO RESOLVE THE
FUNCTIONALITIES REQUESTED BELOW):
to. Read a date and the name of an entity by keyboard, and report: attention
carried out on said date and the total amount that the Social Projects must provide to
payment to the entity on that date.
            The report must have the following format
           Attentions Date: day/month/year
           DNI Member name Amount
             xx xxxx xxxx
             xx xxxx xxxx
                   Total xxxx
Note: the amount that Obra Social must pay for each service is calculated
subtracting from the amount of care the amount resulting from the coverage percentage
that the affiliate has.
b. Read a DNI by keyboard, and report: Name and number of services received.
c. List the Affiliates in order from smallest to largest by unit and name.
Business rule: To resolve this last point, the analyst asks you to
overload the “<” operator.
d. List names of affiliates who did not receive any attention


ENUNCIADO EN ESPAÑOL

La obra social de la UNSJ (DAMSU) posee un archivo con los datos personales de los agentes 
que trabajan la UNSJ, llamado afiliados.csv y un archivo con las atenciones realizadas a sus 
afiliados  durante el mes de abril llamado atenciones.csv 
El archivo de afiliados registra: DNI, nombre y apellido y la unidad  en la que presta servicio 
(FCEFyN, FASCO, etc.)  
El archivo atenciones registra: DNI, fecha de atención en formato (dd/mes/año), importe de 
atención, entidad prestadora y el porcentaje de cobertura que tiene el afiliado.  
Nota: los archivos no presentan ningún orden en particular, y el separador utilizado es el “;”. 
El analista de sistemas de la Obra Social le solicita a usted un programa en Python, para 
procesar ambos archivos.  
El programa debe: 
1.  Crear las clases Afiliados y Atenciones. Los datos de los archivos representan el estado 
de los objetos pertenecientes a estas clases. 
2.  Cargar los datos de los Afiliados en un ManejadorAfiliados el cual tendrá como 
atributo una lista, leyendo los datos del archivo “afiliados.csv” 
3.  Cargar los datos de las Atenciones en un ManejadorAtenciones el cual tendrá como 
atributo una lista, leyendo los datos del archivo “atenciones.csv”. 
A través de un menú de opciones, llevar a cabo las siguientes funcionalidades (NO SE 
PERMITE  SACAR  LISTAS  A  PARTIR  DE  LOS  MANEJADORES  PARA  RESOLVER  LAS 
FUNCIONALIDADES QUE SE SOLICITAN A CONTINUACIÓN): 
a.  Leer por teclado una fecha y el nombre de una entidad, e informar: las atenciones 
realizadas en dicha fecha y el importe total que debe disponer la Obra Social para 
el pago a la entidad en esa fecha. 
            El informe debe tener el siguiente formato            
           Atenciones     Fecha : dia/mes/año      
           DNI          Nombre afiliado   Importe 
             xx              xxxx       xxxx     
             xx               xxxx      xxxx 
                   Total    xxxx 
Nota: el importe que debe pagar  la Obra Social por cada atención se calcula 
restando al importe de atención el importe que resulta del porcentaje de cobertura 
que tiene el afiliado. 
b.  Leer por teclado un DNI, e informar : Nombre y cantidad de atenciones que tuvo. 
c.  Listar los Afiliados por ordenados de menor a mayor por unidad y nombre. 
Regla de negocio: para resolver este último punto, el analista le solicita que 
sobrecargue el operador “<”. 
d.  Listar nombre de los afiliados que no tuvieron ninguna atención

