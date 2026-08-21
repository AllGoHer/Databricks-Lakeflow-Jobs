# Databricks-Lakeflow-Jobs
__________________________________________________________________________________________________________________________________________________________________________________________________________________
Primero, en workspacecreamos la carpeta llamada Databricks_Jobs y otra carpeta llamada notebooks.

Luego dentro de notebooks, creamos tres archivos notebook, notebook_02, notebook_03

Y cada uno con un código print distinto. Ejemplo: print(“Allan_Gonzales”).

Ahora, nos vamos Job & Pipeline y, hacemos click  en JOB (Orquestate Notebooks, pipelines, query & more).

![image](https://github.com/user-attachments/assets/664a5ec1-5b99-45a2-8959-e84e1fb820ce)

Luego, damos click en +Add another task type y, seleccionamos notebook

![image](https://github.com/user-attachments/assets/83bf252a-1389-435e-8ca1-10c3106df720)

![image](https://github.com/user-attachments/assets/fb120923-608c-4bc0-ac52-649ed1e7f0c7)

Completamos la información necesaria.

![image](https://github.com/user-attachments/assets/8753ae17-f14a-4fda-a6e0-a1b2b568d82b)

Luego en path hacemos la siguiente configuración.

![image](https://github.com/user-attachments/assets/9ab2f404-8269-4d5b-abfb-470e1242fb94)

![image](https://github.com/user-attachments/assets/88f8c2f1-ff19-402f-86a7-2f11637b4337)

Luego hacemos click en el lapiz de retries y hacemos la siguiente configuración.

![image](https://github.com/user-attachments/assets/b522c907-bad6-491b-a9bb-ca0d10fed78a)

![image](https://github.com/user-attachments/assets/ca1be86f-70f9-4b63-8e0b-e09a814b0a89)

![image](https://github.com/user-attachments/assets/ede98da2-17e6-483a-918c-7a640386e584)

Finalmente le damos crear tarea (Create Task)

Ahora, damos click en +add task

![image](https://github.com/user-attachments/assets/bb767784-00be-4efd-9b19-3f5169c543d3)

![image](https://github.com/user-attachments/assets/ccfb61b1-bd05-4037-bc5f-b2aa5fa93b86)

Ahora, repetimos los mismos pasos anteriores para configurar la tarea 2 (sin configurar retries) y, en la tarea 3 hacemos lo mismo, excepto en dependencias donde la tarea 3 solo depende de la tarea 1.

![image](https://github.com/user-attachments/assets/3beb9322-bfec-4a5e-80e5-6430d5e8282a)

Luego de crear las tres tareas, si gustas, puedes cambiar el nombre del pipeline.

![image](https://github.com/user-attachments/assets/9fc5f8f6-632e-4896-9d94-e56432e8678c)

Luego, ejecutamos el pipeline.

Si queremos ver el estado de ejecución, podemos hacer click en Runs.


![image](https://github.com/user-attachments/assets/8b4ac865-dd39-4750-84ba-f08748283e4b)

También, podemos hacer click en la fecha de start time para ver la gráfica.

![image](https://github.com/user-attachments/assets/7417319f-8db2-432c-8314-ab8a0c74d2cc)

Tambien, puedes hacer click en uno de ellos para ver la ejecución del código.

![image](https://github.com/user-attachments/assets/f525105a-24d4-4e7a-911f-85af4806d624)

![image](https://github.com/user-attachments/assets/51cf7859-3f62-474e-a95a-372a3c71910b)

![image](https://github.com/user-attachments/assets/d366859e-4619-4a5a-bc07-1de85d977912)

Ahora, editaremos la presente tarea, para minimizar el uso de recursos al crear otro trabajo.

Entonces haremos click en task_02 y task_03 para eliminarlos.


![image](https://github.com/user-attachments/assets/f9bee1e6-123d-4221-90af-c5c09f083062)

![image](https://github.com/user-attachments/assets/bbb28a3c-18ce-419a-8eb9-c0d34a3be222)

Ahora, hacemos click +Add Task y,  hacemos click en if/else condition

![image](https://github.com/user-attachments/assets/610ba101-c3e2-4f58-b99b-cd0f378d3321)

![image](https://github.com/user-attachments/assets/b562ad28-1446-49e3-9bad-3f4649e0e488)

![image](https://github.com/user-attachments/assets/13a17125-3d30-48f0-aa74-a09966e35474)

![image](https://github.com/user-attachments/assets/2c3fac4e-e17b-4765-a04b-dde5537412e3)

![image](https://github.com/user-attachments/assets/3997d27f-7951-444f-9ec1-c2b4444fa1a9)

![image](https://github.com/user-attachments/assets/d9de233f-b35b-4aa3-8b56-61f303fac8db)

Ahora, agregare tarea y seleccionare notebook.

![image](https://github.com/user-attachments/assets/d454783a-bf3d-42c7-97bf-2813d520fa4a)

![image](https://github.com/user-attachments/assets/87903918-e920-42db-b213-085ad7d1cfb3)

Indicare que es el task_02 y marcare la ruta o path.

![image](https://github.com/user-attachments/assets/bde92650-d40d-4d59-8d07-d6b5355bae7d)

![image](https://github.com/user-attachments/assets/4eed3233-0e01-4c6f-b906-9edb05818c21)

Y damos click en crear tarea.

Luego, hacemos agregar tarea y hacemos el mismo procedimiento para el task_03 y solo cambiamos la dependencia por IfWeekend(false).


![image](https://github.com/user-attachments/assets/904eea16-e611-47d7-8c5d-275f283d61d8)

![image](https://github.com/user-attachments/assets/1065053c-73bb-47f5-9be7-6235479a063d)

Hago click en crear tarea y, luego, ejecutamos el pipeline.

![image](https://github.com/user-attachments/assets/acaee8b0-9493-4a48-be44-59f27ffb78a6)

![image](https://github.com/user-attachments/assets/3c997aee-789b-4e50-88f5-e7d9d9432b52)

Ahora iremos a job & pipeline y crearemos un nuevo trabajo

![image](https://github.com/user-attachments/assets/ad697179-affe-4c8b-9807-4e2013a7d6cd)

Luego, en la ventana emergente, hacemos click en +Add another task type  y, seleccionamos Notebook.

![image](https://github.com/user-attachments/assets/e430eb3b-ecae-473d-867a-06bc9a1785b2)

![image](https://github.com/user-attachments/assets/edffcf34-6625-43ef-b311-dd76955c2136)

Ahora, seleccionamos la ruta en path

![image](https://github.com/user-attachments/assets/92c45b98-714a-42a5-a0c1-5e6da58009c6)

Finalmente hacemos click en crear tarea.

Ahora, hacemos click en agregar tarea y seleccionamos For Each.


![image](https://github.com/user-attachments/assets/1130b732-0de5-4574-9304-d3cc84c8d9d2)

![image](https://github.com/user-attachments/assets/e2ec5cb2-65ea-4ee4-9f0f-22a5fa3f916b)

![image](https://github.com/user-attachments/assets/30e469a8-90a4-4ddd-b32d-1d3b63bd5d32)

Le asignamos un nombre y un input y, luego, damos click en Add a task to loop over.

![image](https://github.com/user-attachments/assets/df7e65f2-b6ff-4176-89bb-70b72e01fdc8)

![image](https://github.com/user-attachments/assets/d24181ed-b914-428d-9b5c-796499901218)

![image](https://github.com/user-attachments/assets/a2a1a07b-0ed8-474e-9e68-a5c4749e5b62)

Luego hago click en crear tarea.

![image](https://github.com/user-attachments/assets/0b9ecdd6-7366-4af9-9005-47ff96c9812a)

Luego borramos el primer loop por que ya no es necesario.

![image](https://github.com/user-attachments/assets/8d1158c3-2cdc-4b5a-8b87-9c938580821e)

Y luego ejecutamos (Run Now).

![image](https://github.com/user-attachments/assets/6bd27e54-d984-4077-bb43-7ad41654d468)

![image](https://github.com/user-attachments/assets/25f706d1-0baf-4a7a-b502-325b60a6e5d6)

![image](https://github.com/user-attachments/assets/b3e8119b-309d-4e37-8724-99306ff76f93)

____________________________________________________________________________________________________________________________________________________________________________________________________________________________
### VALORES DINAMICOS.

Regresamos a workspace y creamos una carpeta llamada Intermediate.


![image](https://github.com/user-attachments/assets/e77a9a46-db6d-47c6-814b-955f25d1eb7c)

Ahora, crearé un cuaderno notebook X

Y pasaré el siguiente código.


Código:

        df = spark.createDataFrame([("James", "Sales", 3000), ("Michael", "Sales", 4600), ("Robert", "Sales", 4100)], ["name", "department", "salary"])
        display(df)


![image](https://github.com/user-attachments/assets/0778b76d-7dab-4ef9-9370-60cda461d75e)

Ahora, hare un tipo de monitorio para ver cuantos datos estoy procesando diariamente.

Código:

        display(df.count())


![image](https://github.com/user-attachments/assets/dbbb09f2-b4a2-4f4f-a266-6057560df48e)

Código:

        total_records = df.count()
        total_records


![image](https://github.com/user-attachments/assets/717c7cd0-7f59-480d-8a6b-b53e71ff76cd)


Código:

        dbutils.jobs.taskValues.set(key="total_records", value=total_records)


![image](https://github.com/user-attachments/assets/b4e39c52-ea6d-4b3d-bf44-ca4f6266b2e1)

Ahora creamos otro cuaderno llamado notebook-Y

Para crear un parámetro en Databricks empleré el siguiente código.

Código:

        dbutils.widgets.text("para1", “”)

Esto hará que tu código sea modular y, se generará el siguiente recuadro.


![image](https://github.com/user-attachments/assets/e3ee17a1-93f1-45ce-8ea3-77d390444fe7)

Código:

       dbutils.widgets.get("para1")


![image](https://github.com/user-attachments/assets/87f9acc1-f104-4ca3-8956-f36fbb80707f)

Ahora que ya sabemos como funciona, transformaremos el proyecto de la siguiente manera.

![image](https://github.com/user-attachments/assets/767a1b3a-ce85-4835-889d-8d829caade82)

Ahora crearé un duplicado de este trabajo para ver el proceso, así es que, vamos a Job & Pipeline y, creamos un trabajo.

![image](https://github.com/user-attachments/assets/63cc3ec7-3bbe-41f7-b9e7-3d9d46090e80)

Hare click en +Add another task type y añadiré un cuaderno.

![image](https://github.com/user-attachments/assets/6999fb1e-87a9-4985-b30c-e7b8f14aca37)


![image](https://github.com/user-attachments/assets/3d11407f-dcdf-4d47-ad8a-93224ce57a60)

Crearé una tarea y le asignaré el nombre de task-x

![image](https://github.com/user-attachments/assets/8df06b4a-96e1-453c-ac35-b0c08e2c3b03)

Ahora, asignaremos la ruta (path)

![image](https://github.com/user-attachments/assets/cdbc014e-c622-43af-9eb1-37281f109944)

![image](https://github.com/user-attachments/assets/ea06917d-9888-412e-9aa9-49c9c46e55b4)

![image](https://github.com/user-attachments/assets/9c49e26c-7aff-4546-9114-d62d6a3737ec)

Y finalmente damos click create task.

Luego creamos otra tarea llamada Task-Y.


![image](https://github.com/user-attachments/assets/679ea6fd-a3a0-4b73-b975-7757a6e3a26d)

Pero esta vez agregaremos un parámetro, donde la clave será records_processed (del notebook-Y anterior) y el valor será total_records.

![image](https://github.com/user-attachments/assets/a61b90ce-47a0-43ba-9d4b-721e004dade0)

Finalmente, haré click en crear tarea.

![image](https://github.com/user-attachments/assets/93aceff8-00ca-4b55-9cbb-c43bf0540577)

Ahora, crearé otra tarea llamada Task-Z con dependencia en X.

![image](https://github.com/user-attachments/assets/653abb24-f49e-4d65-b0d9-326dcd7118a6)

![image](https://github.com/user-attachments/assets/170a772a-4d69-48cb-b882-afe189aa4b2c)

Luego, hago click en crear tarea y, por último, volvemos al notebook-Z y asignamos el nombre de la tarea faltante “Task-X”.

![image](https://github.com/user-attachments/assets/6c49be6d-f754-48d4-b3fa-4a08483d95e0)

Y ejecuto todo el pipeline.

![image](https://github.com/user-attachments/assets/5a3fe169-9803-48b6-899a-277ff2da1db4)

![image](https://github.com/user-attachments/assets/9310d008-4a35-4510-bb8d-094664cdbc65)

![image](https://github.com/user-attachments/assets/06e1be6d-44ed-4ddf-9ad0-862960cb554a)

![image](https://github.com/user-attachments/assets/26664c51-679e-43cd-9ecb-0a05d2543558)

![image](https://github.com/user-attachments/assets/090e3482-df3f-49fa-9319-2fde2f81bda2)

____________________________________________________________________________________________________________________________________________________________________________________________________________________________

Ahora crearé un nuevo catálogo llamado db_jobs.

![image](https://github.com/user-attachments/assets/5563175e-3281-4de3-92c6-aeb918f3ce38)

Ahora, me dirijo workspace y crearé un archivo.



![image](https://github.com/user-attachments/assets/c42ffdbf-2715-42cb-abdc-71c50c9f8063)

Código:

        CREATE TABLE db_jobs.default.orders
        (
            order_id INT,
            order_date DATE,
            customer_id INT,
            order_status STRING,
            total_price DECIMAL(10,2)
        );

        INSERT INTO db_jobs.default.orders
        VALUES
            (1, '2022-01-01', 101, 'shipped', 50.00),
            (2, '2022-01-02', 102, 'shipped', 75.00),
            (3, '2022-01-03', 103, 'processing', 30.00),
            (4, '2022-01-04', 104, 'shipped', 100.00),
            (5, '2022-01-05', 105, 'shipped', 60.00)


![image](https://github.com/user-attachments/assets/a9492541-bd52-4cfd-b9bf-8abbb7b5b0ec)

Ahora, hacemos la siguiente consulta, el cual activará una caja de consultas.

Código:

        SELECT 
            *
        FROM
            db_jobs.default.orders
        WHERE
            order_id = :var_id


![image](https://github.com/user-attachments/assets/c3f4cc6c-6a49-4194-9148-d4376f0be14c)

Hacemos ahora un duplicado de la pestaña y, nos vamos a Jobs &pipelines y, editaremos la tarea anterior para ahorrar recursos.

![image](https://github.com/user-attachments/assets/1d95b687-db9a-4f82-b84b-b661854eaa61)

Eliminamos las tareas Task-Y y Task-Z y, editamos el Notebook-X.

![image](https://github.com/user-attachments/assets/5c8f0252-61c7-494d-b375-90e5295a8c32)

![image](https://github.com/user-attachments/assets/dea44a2c-11e0-4aac-a358-fec34652f7be)

Regresamos a la pestaña de Jobs & pipelines y, creamos una consulta sql.

![image](https://github.com/user-attachments/assets/7327f3cf-0188-4a91-953c-9970a18b06e4)


![image](https://github.com/user-attachments/assets/cd0a1430-28df-407a-b28b-77f391609cb4)

![image](https://github.com/user-attachments/assets/f6f604bf-1770-4989-a8a5-9f09751444f7)

![image](https://github.com/user-attachments/assets/aba327f6-20d1-4558-83db-5cc7786e88c2)

![image](https://github.com/user-attachments/assets/3a0bdd0a-3d6b-49e0-928a-587c4f283af8)

Finalmente, damos click en create task.

Ahora, creamos un nuevo cuaderno.


![image](https://github.com/user-attachments/assets/717b31da-ff34-4efb-a21e-b4284a22481f)

![image](https://github.com/user-attachments/assets/fa376072-489e-42fd-a280-c20349da400c)

Código:

        dbutils.widgets.text("sql_output", "")
 
El cual genera la siguiente caja.


![image](https://github.com/user-attachments/assets/bd9ff26a-c466-4c91-aab7-6665566ae61f)

Agregaremos una nueva tarea.

![image](https://github.com/user-attachments/assets/39547e3f-bca9-4119-bb09-389798751dc6)

![image](https://github.com/user-attachments/assets/6cf8a7d8-a390-4606-ae22-e90794e8599f)

Ahora, seleccionamos la ruta.

![image](https://github.com/user-attachments/assets/d6339cbb-bd6a-4a5b-bb89-e69ad45536af)


Luego, en parámetros pondremos en key: SQL_Output y clave: {{tsk.SQL_Query.output.rows}}

![image](https://github.com/user-attachments/assets/3a0ccb19-ab54-40ce-9453-0985f195daf9)

Ahora, creamos la tarea y, ejecutamos todo el trabajo.

![image](https://github.com/user-attachments/assets/1d5d1e5c-a917-4bf0-b0dd-e143b58481e2)

![image](https://github.com/user-attachments/assets/e6fb3b7f-b18d-4fac-9e18-024a31b1b9a7)

![image](https://github.com/user-attachments/assets/bf081c4f-da4b-453e-9040-0e4ddf9a3674)

![image](https://github.com/user-attachments/assets/b98bdabd-f97a-4d27-a9b8-0ded2e9e1468)

![image](https://github.com/user-attachments/assets/a118333b-37a6-4380-85a6-cf4ad1d547df)

![image](https://github.com/user-attachments/assets/b21708f6-afb4-4b5a-b541-0132525c7b6c)

____________________________________________________________________________________________________________________________________________________________________________________________________________________________

### AVANCE

Crearemos una carpeta llamada Advanced y dentro un cuaderno llamado Ingestion.


![image](https://github.com/user-attachments/assets/c7d2c154-23cb-4c30-b381-fcc6b2f65c72)

Ahora para cargar datos, nos vamos a catalog – db_jobs

![image](https://github.com/user-attachments/assets/18fa559a-e4b4-4709-97fa-0b0e265a9c67)

Creamos un volumen

![image](https://github.com/user-attachments/assets/b964273d-1765-43df-ba96-d23717d2b7c0)

![image](https://github.com/user-attachments/assets/16e125e8-4f30-4968-a67c-496e662ffe34)

Ahora cargaremos la data a volúmenes (datos parquet en el repositorio).

![image](https://github.com/user-attachments/assets/fb3e3909-5657-4bec-8ff3-f375eccc4001)

![image](https://github.com/user-attachments/assets/98bf9673-dad1-4ed8-a74a-521dd2f908d8)

Ahora crearemos un duplicado de la pestaña de trabajo.

Nos vamos a workspace –> Databricks_jobs –> Advanced –> Ingestion 

Pasamos el siguiente código.

Código:

        dbutils.widgets.text("file_name", "")
        file_name = dbutils.widgets.get("file_name")


y luego, le damos play.


![image](https://github.com/user-attachments/assets/ce65f420-07fc-470c-9980-4bc9577eaa6c)

Código:

        df = spark.read.format("parquet")\
                    .load(f"/Volumes/db_jobs/default/raw_data/{file_name}.parquet")


![image](https://github.com/user-attachments/assets/2279b1d1-c344-4fb6-bda7-80568760496f)

Luego, damos play

Código:

        df.write.format("delta")\
            .mode("overwrite")\
            .save(f"/Volumes/db_jobs/default/raw_data/sink/{file_name}")


![image](https://github.com/user-attachments/assets/27f54373-e818-4388-a8b8-0e7afd0f998b)

Ahora, crearemos otro cuaderno llamado array.

Pasamos el siguiente código.

Código:

        file_names = [

            {"file_name" : "orders"},
            {"file_name" : "products"},
            {"file_name" : "regions"}
    
        ]

Luego, le damos play.


![image](https://github.com/user-attachments/assets/228de53d-d3ba-4d6a-bc64-3cb492b9ccf6)

Código:

dbutils.jobs.taskValues.set(key = "file_names", value = file_names)


![image](https://github.com/user-attachments/assets/15b9b818-fb4c-476c-a00e-5634196bf1f5)

Ahora, vamos a Job & Pipelines y creamos un nuevo trabajo.

![image](https://github.com/user-attachments/assets/14fae0a7-462b-4c78-8d7c-72133e7d834e)

Creamos un Notebook

![image](https://github.com/user-attachments/assets/f6a80589-335d-4175-aeb7-4404f628efa0)

![image](https://github.com/user-attachments/assets/8f27cae6-f3ea-483b-85a1-4fce51b5ffca)

Le damos a guardar tarea y, luego crearemos un bucle.

![image](https://github.com/user-attachments/assets/51796b96-42f6-4f51-b7de-d0d9b0b7b1ee)

![image](https://github.com/user-attachments/assets/3d83e106-4776-498f-8bd2-ae22690e7daf)

![image](https://github.com/user-attachments/assets/6afbab59-6340-4b89-b1d4-f185b1b462aa)

![image](https://github.com/user-attachments/assets/99d019e3-3815-4b8b-99f0-b51a8735a626)

Luego, damos click en Add a task to loop over.

Ahora, en la nueva ventana emergente, cambiaremos el task como Ingestion y direccionamos su path.


![image](https://github.com/user-attachments/assets/39fd0003-90e6-4b2d-a9c8-e4dd5a6635c3)

![image](https://github.com/user-attachments/assets/3f88c5bc-b3bf-41f9-af35-54e8b4ea624d)

Luego, introducimos los siguientes parámetros y, le damos click en create task.

![image](https://github.com/user-attachments/assets/7df344e1-19e5-429e-ac33-f4e4fa6a6c0a)

![image](https://github.com/user-attachments/assets/cc0237ac-792b-4b10-b3de-b0c0033ecb9f)

Le damos en ejecutar (Run Now).

![image](https://github.com/user-attachments/assets/31a7cc6e-2cfd-47ed-8e7b-0bc3bb15a7b2)

![image](https://github.com/user-attachments/assets/99cf70f0-a47d-49ee-8697-a45e9e762191)

![image](https://github.com/user-attachments/assets/ba36f496-6500-4d58-80f3-8729ecd06d78)

![image](https://github.com/user-attachments/assets/a63b1b57-7609-4bb9-b947-257016d891fb)

Asi mismo, ya se puede ver en la carpeta sink de Catalog.

![image](https://github.com/user-attachments/assets/3f4bf333-66d9-43b4-a3f2-cd7876535e18)

Ahora, vamos a workspace y, creamos un query llamado mapping_table.

![image](https://github.com/user-attachments/assets/7eebfe7d-a0c5-4409-9393-36dbd953092d)

![image](https://github.com/user-attachments/assets/6e2e6067-096c-4aab-af62-956c675547bb)

Pasamos la siguiente consulta.

Código:

        CREATE TABLE db_jobs.default.mapping 
        (
           file_name STRING 
        )

        INSERT INTO db_jobs.default.mapping 
        VALUES 
        ('orders'),
        ('regions'),
        ('products')


Y ejecutamos (Run all)


![image](https://github.com/user-attachments/assets/d92024a2-3814-4e0e-ad9f-22eb352f543c)

Para confirmar la creación, haré lo siguiente.

Código:

        SELECT * FROM mapping;


![image](https://github.com/user-attachments/assets/a7d4f4c8-3567-4146-995b-ccefa466582e)

Ahora, guardamos el query y, regresamos a Jobs y, crearemos una nueva tarea.

![image](https://github.com/user-attachments/assets/6de85357-8d58-4401-845b-7521ac8286b3)

![image](https://github.com/user-attachments/assets/0f00daca-1603-4109-b9a8-d1ac7dac8bd7)

Y le damos click en crear tarea.

Ahora, en el grafico hacemos click en Dinamic_Ingestion y cambiamos algunos datos como la concurrencia, el Imput y la dependencia.


![image](https://github.com/user-attachments/assets/a2003c7b-be58-4337-bc5c-0805567d0f61)

Luego, guardamos la tarea y, eliminamos el Array del gráfico.

![image](https://github.com/user-attachments/assets/fd900eb6-b191-479b-8c9c-f367ed56cb0c)

![image](https://github.com/user-attachments/assets/4ba1ac24-9fdc-49a1-b872-3e54964cb30e)

Ahora en el archivo Ingestion hacemos un pequeño cambio y, crearemos la carpeta sinkSQL para guardar los datos.

![image](https://github.com/user-attachments/assets/ca2b7bcc-8977-44aa-9c03-7ebcf7b09800)

![image](https://github.com/user-attachments/assets/100eb380-6a7d-4dbc-87fa-764a90607210)

Ahora sí, volvemos al Job y ejecutamos el trabajo (Run now).

![image](https://github.com/user-attachments/assets/8cf6c17d-c900-4f29-9149-1fa63300701d)

![image](https://github.com/user-attachments/assets/930bb196-a2b6-4119-8193-d1efbc021519)

![image](https://github.com/user-attachments/assets/337caed2-de77-4bc1-a526-93a0bcfb164b)

Ahora, comprobamos en catalog si esta la carpeta SinkSQL.

![image](https://github.com/user-attachments/assets/b7bdd7cd-d53b-41d6-a3b5-78ffd2be7140)

____________________________________________________________________________________________________________________________________________________________________________________________________________________________
### ALERTAS

Ahora, aprenderemos a crear alertas.

Vamos a la cinta lateral izquierda de Databricks y, hacemos click en Alerts.


![image](https://github.com/user-attachments/assets/759f901b-3425-4fd2-9a19-def351bd7cf0)

Luego, damos click en crear alerta.

![image](https://github.com/user-attachments/assets/34f3aecc-a546-42ad-9337-bfe54f2e3fe6)

En el área de SQL pasamos el siguiente código.

Código:

        SELECT * FROM db_jobs.default.orders
 

Y ejecutamos.


![image](https://github.com/user-attachments/assets/5dde8b1d-5bc5-4a6c-b413-d732af606de6)

Luego, hacemos la siguiente consulta.

Código:

        SELECT sum(total_price) as total_revenue FROM db_jobs.default.orders


![image](https://github.com/user-attachments/assets/915fcad8-28cf-436c-b6f8-ee0664d3bf0b)

Ahora, pondremos las condiciones y restricciones de la alerta.

Por ejemplo: cuando el monto total sea mayor o igual a 315.00


![image](https://github.com/user-attachments/assets/2a05db85-6e6e-4159-bbfc-009747cc0596)

Luego, hacemos click en View alert para ajustar el horario o frecuencia de la alerta.

![image](https://github.com/user-attachments/assets/e3628e24-bc0d-4891-bd6a-0027a8780914)

Ahora hacemos click en Schedule 

![image](https://github.com/user-attachments/assets/c5e82ff5-caef-4fe1-af15-017ffd1a0414)

Luego de programarlo, le damos click en guardar y, vuelves a alerts y seleccionas crear.
Listooo!!!

Luego tendrás que activar el trabajo (job) todos los días manualmente.


![image](https://github.com/user-attachments/assets/adb5c25b-0408-4308-b6d4-93d1cb87fc1d)

![image](https://github.com/user-attachments/assets/380e5800-0258-403f-bda6-ad069651c395)

![image](https://github.com/user-attachments/assets/a124d7a1-ad48-4a2e-b40f-d55218e02f32)


