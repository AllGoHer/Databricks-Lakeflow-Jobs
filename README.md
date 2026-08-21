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

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

![image]()

