# Tarea_Servidor
docker run -d --name dbpsql -e POSTGRES_PASSWORD=admin  -p 5432:5432 postgres

![image](https://user-images.githubusercontent.com/91167267/200972618-4848c99a-0fc6-482d-bd42-b1089ac386f2.png)

docker network create --attachable redsuda

![image](https://user-images.githubusercontent.com/91167267/200972910-c3b540fe-3219-431b-900c-2e990930e9fb.png)

docker network connect redsuda dbpsql

![image](https://user-images.githubusercontent.com/91167267/200973016-a2022524-a654-4b0e-9786-167c2149adfc.png)

docker network connect redsuda pgadmin

![image](https://user-images.githubusercontent.com/91167267/200973155-e1c7e145-f607-4e55-9de3-af9de518304c.png)

docker inspect redsuda

![image](https://user-images.githubusercontent.com/91167267/200973396-07d414b7-591e-4358-8526-791891b3d6fd.png)

