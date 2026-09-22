```bash
    9  sudo apt update
   10  sudo apt install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
   11  sudo apt install mysql-client -y 
   12  mysql -h database-1.c18ci2w0g7fa.ap-northeast-1.rds.amazonaws.com -u admin -predhat123
   13  ls
   14  git clone https://github.com/mukundDeo9325/student-app-k8s.git
   15  ls
   16  cd student-app-k8s/
   17  ls
   18  cd backend/
   19  ls
   20  vim src/main/resources/application.properties 
   21  ls
   22  cat Dockerfile 
   23  sudo docker build -t mukunddeo9325/backend:latest .
   24  docker images
   25  sudo docker images
   26  docker run -d -p 8080:8080 --name backend b6694f24061e
   27  sudo docker run -d -p 8080:8080 --name backend b6694f24061e
   28  sudo docker ps 
   29  cat Dockerfile 
   30  ls
   31  cd ../frontend/
   32  ls
   33  vim .env 
   34  ls
   35  sudo docker build -t mukunddeo9325/frontend:latest 
   36  sudo docker build -t mukunddeo9325/frontend:latest Dockerfile 
   37  sudo docker build -t mukunddeo9325/frontend:latest . 
   38  docker ps
   39  sudo docker ps 
   40  sudo docker images 
   41  sudo docker run -d -p 80:80 --name frontend ea5c7588a93c
   42  sudo docker ps
   43  ls
   44  history 
   45  mysql -h database-1.c18ci2w0g7fa.ap-northeast-1.rds.amazonaws.com -u admin -predhat123
   46  history 
```
