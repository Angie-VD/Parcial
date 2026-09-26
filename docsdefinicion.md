# **Plataforma Web de Finanzas Personales**

**Introducción: Nombres de los creadores del proyecto  
<br/>**Miguel Angel Holguin

Angie Juliana Vargas

Ana Sofía Henao Agudelo

## **1\. Descripción general**

La plataforma de Finanzas Personales es una aplicación web diseñada para ayudar a las personas a organizar y controlar de manera sencilla sus ingresos, gastos, presupuestos y metas de ahorro desde un mismo lugar. Con esto, el usuario evita la mezcla de saldos entre transacciones y previene errores a la hora de tomar decisiones sobre los fondos verdaderamente disponibles.

Cada usuario registra sus movimientos financieros, los clasifica mediante categorías y consulta la información resumida sobre el estado de sus finanzas. A través de un panel principal, el usuario podrá visualizar cuánto dinero ha recibido, cuánto ha gastado y cuál es el saldo disponible durante un periodo determinado, por medio de reportes y gráficos dinámicos que faciliten la interpretación de sus datos. De esta manera, el usuario podrá analizar la distribución de sus gastos de forma intuitiva y comprender con claridad la evolución de sus hábitos financieros. .

La plataforma contará con dos roles principales: **usuario** y **administrador**. El usuario podrá administrar exclusivamente su propia información financiera, mientras que el administrador tendrá funciones relacionadas con la gestión de usuarios y el mantenimiento general de la plataforma. El acceso a las funciones privadas se realizará mediante un sistema de inicio de sesión con correo electrónico y contraseña.

## **2\. Problema**

Muchas personas llevan el control de sus finanzas personales de manera informal mediante apuntes físicos, hojas de cálculo, historial de sus cuentas bancarias o simplemente recuerdan sus gastos sin registrarlos en algún medio; esto puede dificultar conocer con precisión cuánto dinero ingresa, cuánto se gasta, cuánto queda disponible, identificar en qué categorías se concentra el mayor gasto o determinar si el dinero restante es suficiente para cubrir las necesidades del periodo.

## **3\. Objetivos**

### **Objetivo general**

Desarrollar una plataforma web que permita a los usuarios registrar, organizar y consultar sus ingresos y gastos personales, así como establecer presupuestos y visualizar información financiera de manera organizada.

### **Objetivos específicos**

- Permitir que cada usuario registre sus ingresos y gastos indicando información como valor, fecha, categoría y descripción.
- Permitir consultar el historial de movimientos financieros registrados por el usuario.
- Calcular y mostrar el saldo disponible a partir de los ingresos y gastos registrados.
- Permitir establecer presupuestos para diferentes categorías de gastos.
- Mostrar mediante gráficos y resúmenes la distribución de los gastos y los ingresos durante un periodo determinado.
- Permitir al administrador gestionar las cuentas de los usuarios registrados en la plataforma.
- Garantizar que cada usuario solamente pueda consultar y modificar su propia información financiera.

## **4\. Stakeholders, actores y roles**

### **Stakeholders**

| **Stakeholder**      | **Interés en el proyecto**                                                                                 |
| -------------------- | ---------------------------------------------------------------------------------------------------------- |
| Usuarios             | Organizar y consultar sus finanzas personales.                                                             |
| ---                  | ---                                                                                                        |
| Administrador        | Gestionar los usuarios y mantener el funcionamiento general de la plataforma.                              |
| ---                  | ---                                                                                                        |
| Equipo de desarrollo | Diseñar, desarrollar, probar y mantener la plataforma.                                                     |
| ---                  | ---                                                                                                        |
| Docente/evaluador    | Revisar el cumplimiento de los requisitos académicos y técnicos del proyecto. Dar sugerencias al respecto. |
| ---                  | ---                                                                                                        |

### **Actores y roles**

#### **Usuario**

El usuario es la persona que utiliza la plataforma para administrar sus finanzas personales.

Puede:

- Iniciar sesión.
- Registrar ingresos.
- Registrar gastos.
- Editar sus movimientos.
- Eliminar sus propios movimientos.
- Consultar su historial financiero.
- Crear categorías personales.
- Establecer presupuestos.
- Consultar reportes.
- Visualizar gráficos financieros.
- Consultar su saldo disponible.

#### **Administrador**

El administrador se encarga de las funciones generales de gestión de la plataforma.

Puede:

- Iniciar sesión.
- Consultar usuarios registrados.
- Crear usuarios.
- Editar información básica de usuarios.
- Desactivar usuarios.
- Consultar información general del sistema.
- Eliminar usuarios

### **Login**

Los usuarios y administradores ingresarán mediante correo electrónico y contraseña, el sistema identificará el rol asociado a la cuenta y mostrará las funciones correspondientes.

Un usuario no podrá acceder a las funciones exclusivas del administrador.

## **5\. Alcance**

### **Incluye**

La primera versión del proyecto incluirá:

- Registro de ingresos.
- Registro de gastos.
- Consulta del historial de movimientos.
- Edición y eliminación de movimientos propios.
- Consulta del saldo disponible.
- Dashboard financiero.
- Gráficos de ingresos y gastos.
- Reportes financieros básicos.

**Pendientes**

Aquí están las ideas que planeamos añadir en la primera versión pero que dejaremos en futuras versiones del proyecto:

- Registro e inicio de sesión.
- Gestión de usuarios.
- Gestión de categorías..
- Creación de presupuestos.
- Consulta del cumplimiento de presupuestos.
- Gráficos de ingresos y gastos.
- Reportes financieros básicos.
- Administración de usuarios por parte del administrador.
- Base de datos para almacenar la información del sistema.

### **No incluye**

Aquí están los objetivos que se planean alcanzar a largo plazo, en caso tal de llevar el proyecto fuera de lo académico, debido a la complejidad de estos:

- Conexión directa con cuentas bancarias.
- Transferencias de dinero.
- Pagos en línea.
- Manejo de tarjetas bancarias.
- Préstamos bancarios.
- Inversiones en bolsa.
- Criptomonedas.
- Declaración de impuestos.
- Aplicación móvil nativa.
- Asesoría financiera profesional.
- Envío de dinero entre usuarios..

## **6\. Funcionalidades**

### **Usuario**

El usuario podrá:

1. Crear una cuenta.
2. Iniciar sesión.
3. Cerrar sesión.
4. Registrar ingresos.
5. Registrar gastos.
6. Seleccionar una categoría para cada movimiento.
7. Agregar una descripción a cada movimiento.
8. Indicar la fecha y el valor del movimiento.
9. Consultar sus movimientos financieros.
10. Editar sus movimientos.
11. Eliminar sus movimientos.
12. Crear categorías.
13. Consultar su saldo.
14. Crear presupuestos.
15. Consultar el estado de sus presupuestos.
16. Consultar gráficos de ingresos y gastos.
17. Consultar reportes por periodo y categoría.

### **Administrador**

El administrador podrá:

1. Iniciar sesión.
2. Cerrar sesión.
3. Consultar los usuarios registrados.
4. Crear usuarios.
5. Editar información de usuarios.
6. Desactivar usuarios.
7. Consultar información general de la plataforma.
8. Eliminar usuarios

# **7\. Requerimientos funcionales**

| **ID** | **Requerimiento**                                                                                               | **Rol**       | **Prioridad** |
| ------ | --------------------------------------------------------------------------------------------------------------- | ------------- | ------------- |
| RF-01  | El sistema debe permitir al usuario registrarse creando una cuenta con nombre, correo electrónico y contraseña. | Usuario       | Alta          |
| ---    | ---                                                                                                             | ---           | ---           |
| RF-02  | El sistema debe permitir iniciar sesión mediante correo electrónico y contraseña.                               | Todos         | Alta          |
| ---    | ---                                                                                                             | ---           | ---           |
| RF-03  | El sistema debe identificar el rol del usuario después de iniciar sesión.                                       | Todos         | Alta          |
| ---    | ---                                                                                                             | ---           | ---           |
| RF-04  | El sistema debe permitir al usuario registrar un ingreso especificando monto, fecha, categoría y descripción.   | Usuario       | Alta          |
| ---    | ---                                                                                                             | ---           | ---           |
| RF-05  | El sistema debe permitir al usuario registrar un gasto especificando monto, fecha, categoría y descripción.     | Usuario       | Alta          |
| ---    | ---                                                                                                             | ---           | ---           |
| RF-06  | El sistema debe permitir consultar los movimientos financieros registrados por el usuario.                      | Usuario       | Alta          |
| ---    | ---                                                                                                             | ---           | ---           |
| RF-07  | El sistema debe permitir filtrar los movimientos financieros por rango de fecha, tipo y categoría.              | Usuario       | Media         |
| ---    | ---                                                                                                             | ---           | ---           |
| RF-08  | El sistema debe permitir al usuario editar sus propios movimientos financieros.                                 | Usuario       | Alta          |
| ---    | ---                                                                                                             | ---           | ---           |
| RF-09  | El sistema debe permitir al usuario eliminar sus propios movimientos financieros.                               | Usuario       | Alta          |
| ---    | ---                                                                                                             | ---           | ---           |
| RF-10  | El sistema debe calcular en tiempo real el saldo disponible a partir de los ingresos y gastos registrados.      | Usuario       | Alta          |
| ---    | ---                                                                                                             | ---           | ---           |
| RF-11  | El sistema debe permitir crear categorías para clasificar los movimientos financieros.                          | Usuario       | Media         |
| ---    | ---                                                                                                             | ---           | ---           |
| RF-12  | El sistema debe permitir crear un presupuesto asociado a una categoría y periodo.                               | Usuario       | Alta          |
| ---    | ---                                                                                                             | ---           | ---           |
| RF-13  | El sistema debe mostrar el progreso del presupuesto comparando el valor límite con el total gastado.            | Usuario       | Alta          |
| ---    | ---                                                                                                             | ---           | ---           |
| RF-14  | El sistema debe generar representaciones gráficas interactivas del comportamiento de ingresos y gastos.         | Usuario       | Media         |
| ---    | ---                                                                                                             | ---           | ---           |
| RF-15  | El sistema debe permitir consultar reportes financieros por periodo.                                            | Usuario       | Media         |
| ---    | ---                                                                                                             | ---           | ---           |
| RF-16  | El sistema debe permitir al administrador consultar los usuarios registrados.                                   | Administrador | Alta          |
| ---    | ---                                                                                                             | ---           | ---           |
| RF-17  | El sistema debe permitir al administrador crear usuarios.                                                       | Administrador | Alta          |
| ---    | ---                                                                                                             | ---           | ---           |
| RF-18  | El sistema debe permitir al administrador editar información de los usuarios.                                   | Administrador | Media         |
| ---    | ---                                                                                                             | ---           | ---           |
| RF-19  | El sistema debe permitir al administrador desactivar usuarios.                                                  | Administrador | Alta          |
| ---    | ---                                                                                                             | ---           | ---           |
| RF-20  | El sistema debe impedir que un usuario consulte los movimientos financieros de otro usuario.                    | Usuario       | Alta          |
| ---    | ---                                                                                                             | ---           | ---           |
| RF-21  | El sistema debe permitir cerrar la sesión del usuario.                                                          | Todos         | Alta          |
| ---    | ---                                                                                                             | ---           | ---           |

#

# **8\. Requerimientos no funcionales**

| **ID** | **Categoría**  | **Requerimiento**                                                                                                                 |
| ------ | -------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| RNF-01 | Rendimiento    | Las vistas principales del sistema deben cargarse en un tiempo menor a 3 segundos bajo condiciones normales de red.               |
| ---    | ---            | ---                                                                                                                               |
| RNF-02 | Seguridad      | Las contraseñas deben almacenarse utilizando un mecanismo de cifrado/hash seguro y no como texto plano.                           |
| ---    | ---            | ---                                                                                                                               |
| RNF-03 | Usabilidad     | La interfaz gráfica debe contar con diseño adaptativo (responsive) garantizando su usabilidad en pantallas desde 360 px de ancho. |
| ---    | ---            | ---                                                                                                                               |
| RNF-04 | Compatibilidad | La plataforma debe operar correctamente en los navegadores Google Chrome, Mozilla Firefox, Microsoft Edge y Safari.               |
| ---    | ---            | ---                                                                                                                               |
| RNF-05 | Usabilidad     | La plataforma debe poder utilizarse desde computadores y dispositivos con un ancho mínimo de 360 px.                              |
| ---    | ---            | ---                                                                                                                               |
| RNF-06 | Compatibilidad | La plataforma debe funcionar en las versiones vigentes de Chrome, Edge, Brave, Safari y Firefox durante el periodo de desarrollo. |
| ---    | ---            | ---                                                                                                                               |
| RNF-07 | Disponibilidad | El sistema debe mostrar un mensaje comprensible cuando ocurra un error de conexión con la base de datos.                          |
| ---    | ---            | ---                                                                                                                               |
| RNF-08 | Mantenibilidad | El código debe organizarse separando la interfaz, la lógica de negocio y el acceso a la base de datos.                            |
| ---    | ---            | ---                                                                                                                               |
| RNF-09 | Integridad     | Los valores monetarios registrados deben almacenarse utilizando un tipo de dato apropiado para evitar pérdidas de precisión.      |
| ---    | ---            | ---                                                                                                                               |
| RNF-10 | Usabilidad     | Los formularios deben validar los campos obligatorios antes de guardar información.                                               |
| ---    | ---            | ---                                                                                                                               |

#

# **9\. Reglas de negocio**

- **RN-01.** Cada cuenta de usuario debe ser única e identificada exclusivamente por su dirección de correo electrónico.
- **RN-02.** Un usuario solo tiene autorización para visualizar, modificar o eliminar la información financiera generada por él mismo.
- **RN-03.** Todo registro de ingreso o gasto debe contener un valor numérico estrictamente mayor a cero ().
- **RN-04.** Todo movimiento financiero debe estar asociado obligatoriamente a una fecha válida y a una categoría.
- **RN-05.** El saldo disponible se calcula como la sumatoria de todos los ingresos menos la sumatoria de los gastos en un rango de tiempo.
- **RN-06.** Todo presupuesto debe estar vinculado a una categoría específica y a un periodo temporal definido.
- **RN-07.** El límite fijado en un presupuesto debe ser mayor a cero ().
- **RN-08.** El sistema debe generar un aviso o alerta cuando los gastos acumulados sobrepasen el presupuesto asignado a la categoría.
- **RN-09.** Las categorías con transacciones asociadas no pueden eliminarse del sistema para preservar la integridad del historial.
- **RN-10.** Los usuarios con estado "Desactivado" no podrán iniciar sesión ni realizar operaciones dentro de la plataforma.
- **RN-11.** Al desactivar o eliminar un usuario, sus datos e historial financiero deben conservarse en la base de datos por motivos de auditoría e integridad.
- **RN-12.** El acceso a los paneles y funciones de administración está reservado únicamente para las cuentas con el rol de administrador.

# **10\. Modelo de datos**

La plataforma utilizará una base de datos relacional para almacenar la información de los usuarios y sus movimientos financieros.

### **Entidades principales**

| **Entidad** | **Atributos principales**                                               |
| ----------- | ----------------------------------------------------------------------- |
| Usuario     | id, nombre, correo, contraseña_hash, rol, estado, fecha_registro        |
| ---         | ---                                                                     |
| Categoria   | id, usuario_id, nombre, tipo, estado                                    |
| ---         | ---                                                                     |
| Movimiento  | id, usuario_id, categoria_id, tipo, valor, fecha, descripcion           |
| ---         | ---                                                                     |
| Presupuesto | id, usuario_id, categoria_id, valor_limite, periodo_inicio, periodo_fin |
| ---         | ---                                                                     |
| Rol         | id, nombre                                                              |
| ---         | ---                                                                     |

### **Usuario**

Representa a las personas que tienen una cuenta en la plataforma.

**Atributos:**

- id
- nombre
- correo
- contrasena_hash
- rol_id
- estado
- fecha_registro

### **Rol**

Define los permisos disponibles para cada cuenta.

**Atributos:**

- ID
- Nombre

Los roles principales serán:

- Usuario
- Administrador

### **Categoria**

Permite clasificar los ingresos y gastos.

**Atributos:**

- id
- usuario_id
- nombre
- tipo
- estado

Ejemplos de categorías:

- Alimentación
- Transporte
- Educación
- Entretenimiento
- Salud
- Servicios
- Vivienda
- Salario
- Otros

### **Movimiento**

Representa un ingreso o gasto realizado por el usuario.

**Atributos:**

- id
- usuario_id
- categoria_id
- tipo
- valor
- fecha
- descripcion

El campo tipo permitirá diferenciar entre:

- Ingreso
- Gasto

### **Presupuesto**

Representa el límite de dinero que el usuario establece para una categoría durante un periodo.

**Atributos:**

- id
- usuario_id
- categoria_id
- valor_limite
- periodo_inicio
- periodo_fin

### **Relaciones**

- Un **rol** puede estar asociado a muchos usuarios.
- Un **usuario** puede tener muchos movimientos.
- Un **usuario** puede tener muchas categorías.
- Un **usuario** puede tener muchos presupuestos.
- Una **categoría** puede estar asociada a muchos movimientos.
- Una **categoría** puede estar asociada a muchos presupuestos.
- Cada movimiento pertenece a un único usuario.
- Cada movimiento pertenece a una única categoría.
- Cada presupuesto pertenece a un único usuario y a una única categoría.

# **11\. Pantallas y flujo**

La plataforma tendrá las siguientes pantallas principales:

| **Pantalla**         | **Rol**       | **Para qué sirve**                                                  |
| -------------------- | ------------- | ------------------------------------------------------------------- |
| Inicio de sesión     | Todos         | Permitir el acceso mediante correo y contraseña.                    |
| ---                  | ---           | ---                                                                 |
| Registro             | Usuario       | Crear una nueva cuenta en la plataforma.                            |
| ---                  | ---           | ---                                                                 |
| Dashboard financiero | Usuario       | Mostrar saldo, ingresos, gastos, presupuestos y resumen financiero. |
| ---                  | ---           | ---                                                                 |
| Movimientos          | Usuario       | Consultar, filtrar, editar y eliminar ingresos y gastos.            |
| ---                  | ---           | ---                                                                 |
| Registrar movimiento | Usuario       | Registrar un nuevo ingreso o gasto.                                 |
| ---                  | ---           | ---                                                                 |
| Presupuestos         | Usuario       | Crear y consultar presupuestos por categoría.                       |
| ---                  | ---           | ---                                                                 |
| Reportes             | Usuario       | Consultar gráficos y reportes de ingresos y gastos.                 |
| ---                  | ---           | ---                                                                 |
| Gestión de usuarios  | Administrador | Consultar, crear, editar y desactivar usuarios.                     |
| ---                  | ---           | ---                                                                 |

### **Flujo del usuario**

Registro → Inicio de sesión → Dashboard → Registrar movimiento → Movimientos → Presupuestos → Reportes

### **Flujo del administrador**

Inicio de sesión → Gestión de usuarios → Crear/editar/eliminar/desactivar usuario

### **Dashboard**

El Dashboard será la pantalla principal del usuario después de iniciar sesión.

Mostrará:

- Saldo disponible.
- Total de ingresos.
- Total de gastos.
- Presupuesto utilizado.
- Resumen de movimientos recientes.
- Gráfico de ingresos y gastos.
- Distribución de gastos por categoría.

# **12\. Mockup**

### **01-login.png**

Pantalla de inicio de sesión. Centrado en un formulario y un botón para verificar el inicio

### **02-registro.png**

Pantalla para crear una cuenta. Enfocado en un formulario para ingresar nombre de usuario, email asociado a la cuenta y una contraseña

### **03-dashboard.png**

Pantalla principal del usuario. En el cual se mostrarán las gráficas de cada tipo de movimiento hecho en la cuenta.

### **04-movimientos.png**

Pantalla para consultar los movimientos financieros. Tratará de una tabla donde se muestre que tipo de movimiento y a que horas fue realizado

### **05-registrar-movimiento.png**

Pantalla para registrar un ingreso o gasto. Dará un formulario en el cual se debe llenar con el nombre del movimiento, que tipo de movimiento es, y que tanto fue lo ganado o pagado.

### **06-presupuestos.png**

Pantalla para administrar los presupuestos.

### **07-reportes.png**

Pantalla de reportes financieros. Mostrando una tabla para resumir los movimientos

### **08-gestion-usuarios.png**

Pantalla exclusiva del administrador. En el cual mostrará cada tipo de gestión especial que puede hacer el administrador.

# **13\. Historias de usuario, casos de uso, restricciones y supuestos**

## **Historias de usuario**

### **Historia de usuario 1 – Registrar gasto**

**Como** usuario,  
**quiero** registrar mis gastos indicando su valor, categoría y fecha,  
**para** llevar un control de cuánto dinero estoy utilizando.

### **Historia de usuario 2 – Registrar ingreso**

**Como** usuario,  
**quiero** registrar mis ingresos indicando su valor, categoría y fecha,  
**para** conocer cuánto dinero recibo durante un periodo.

### **Historia de usuario 3 – Consultar movimientos**

**Como** usuario,  
**quiero** consultar mi historial de ingresos y gastos,  
**para** conocer cómo he utilizado mi dinero.

### **Historia de usuario 4 – Crear presupuesto**

**Como** usuario,  
**quiero** establecer un límite de gasto para una categoría,  
**para** controlar cuánto dinero destinó a esa categoría.

### **Historia de usuario 5 – Consultar reportes**

**Como** usuario,  
**quiero** visualizar gráficos de mis ingresos y gastos,  
**para** comprender mejor la distribución de mis movimientos financieros.

### **Historia de usuario 6 – Gestionar usuarios**

**Como** administrador,  
**quiero** gestionar las cuentas de los usuarios,  
**para** mantener actualizada la información de las cuentas de la plataforma.

## **Caso de uso: Registrar un gasto**

**Actor:** Usuario.

**Precondición:** El usuario debe haber iniciado sesión.

**Flujo principal:**

1. El usuario ingresa a la sección "Movimientos".
2. Selecciona la opción "Registrar movimiento".
3. Selecciona el tipo "Gasto".
4. Ingresa el valor del gasto.
5. Selecciona una categoría.
6. Selecciona la fecha.
7. Agrega una descripción opcional.
8. El usuario selecciona "Guardar".
9. El sistema valida los datos.
10. El sistema almacena el movimiento en la base de datos.
11. El sistema actualiza el saldo y los reportes.
12. El sistema muestra un mensaje confirmando el registro.

**Excepciones:**

- Si el valor es menor o igual a cero, el sistema debe indicar que el valor no es válido.
- Si falta un campo obligatorio, el sistema debe solicitar completarlo.
- Si ocurre un error de conexión con la base de datos, el sistema debe informar que no fue posible guardar el movimiento.

## **Caso de uso: Crear presupuesto**

**Actor:** Usuario.

**Precondición:** El usuario debe haber iniciado sesión.

**Flujo principal:**

1. El usuario ingresa a "Presupuestos".
2. Selecciona "Nuevo presupuesto".
3. Selecciona una categoría.
4. Define el valor límite.
5. Define el periodo.
6. Selecciona "Guardar".
7. El sistema valida la información.
8. El sistema almacena el presupuesto.
9. El sistema muestra el nuevo presupuesto.

**Excepción:**

Si el valor del presupuesto es menor o igual a cero, el sistema no permitirá guardarlo y mostrará un mensaje de validación.

## **Caso de uso: Gestionar usuarios**

**Actor:** Administrador.

**Precondición:** El administrador debe haber iniciado sesión y tener permisos administrativos.

**Flujo principal:**

1. El administrador ingresa a "Gestión de usuarios".
2. El sistema muestra la lista de usuarios.
3. El administrador selecciona un usuario.
4. Puede consultar o modificar la información permitida.
5. Puede cambiar el estado de la cuenta.
6. El sistema valida la operación.
7. El sistema actualiza la información en la base de datos.

**Excepción:**

Si una persona que no tiene permisos administrativos intenta acceder a esta sección, el sistema debe rechazar el acceso.

## **Restricciones**

- El proyecto será desarrollado como una aplicación web.
- La plataforma debe utilizar una base de datos para almacenar la información.
- El sistema debe contar con autenticación.
- Deben existir como mínimo dos roles con permisos diferentes.
- Los usuarios solamente podrán acceder a su propia información financiera.
- El proyecto no contempla conexiones directas con entidades bancarias.
- El proyecto no contempla transacciones de dinero reales.
- El sistema dependerá de una conexión a Internet para acceder a la aplicación web.
- El proyecto debe mantener la estructura solicitada para el repositorio de Git.

## **Supuestos**

- Los usuarios cuentan con acceso a Internet.
- Los usuarios proporcionarán información correcta al registrar sus movimientos.
- Los valores ingresados por los usuarios estarán expresados en una única moneda definida para el proyecto.
- La plataforma será utilizada para realizar seguimiento financiero personal y no como sistema contable empresarial.
- El administrador será responsable de gestionar las cuentas de usuario.
- La información almacenada en la base de datos estará disponible para generar los reportes de la plataforma.

# **Historial de cambios**

| **Fecha**  | **Cambio**                                                             | **Responsable**      |
| ---------- | ---------------------------------------------------------------------- | -------------------- |
| 2026-09-25 | Creación inicial de la definición del proyecto de Finanzas Personales. | Equipo de desarrollo |
| ---        | ---                                                                    | ---                  |

# **Referencias**

- Mozilla Developer Network (MDN). Documentación sobre desarrollo web, HTML, CSS, JavaScript y accesibilidad. Disponible en: <https://developer.mozilla.org/>
- OWASP Foundation. _OWASP Application Security Verification Standard (ASVS)_. Utilizada como referencia para aspectos generales de seguridad de aplicaciones web. Disponible en: <https://owasp.org/www-project-application-security-verification-standard/>
- Documentación oficial del sistema gestor de bases de datos seleccionado por el equipo. Se utilizará para respaldar las decisiones relacionadas con almacenamiento y gestión de datos.

# **Declaración de uso de inteligencia artificial**

Durante la elaboración de la definición del proyecto se utilizó un asistente de inteligencia artificial como herramienta de apoyo para organizar ideas, estructurar las secciones del documento y revisar la redacción de algunos requerimientos, tomándola principalmente como apoyo para transformar la idea general de una plataforma de finanzas personales en una estructura compatible con las secciones solicitadas para el proyecto.

El equipo revisará, modificará el contenido generado para adaptarlo a las decisiones reales del proyecto. Las decisiones relacionadas con el alcance definitivo, las funcionalidades que serán implementadas, el diseño de la base de datos, la arquitectura, las tecnologías y la distribución del trabajo serán tomadas y validadas por los integrantes del equipo.