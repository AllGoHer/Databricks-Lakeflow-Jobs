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

