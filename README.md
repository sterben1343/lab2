1) Скачал Docker Desktop
2) Создал nginx image
3) Создал проект в vs code
![alt text](image-1.png)
4) Docker file и index.html
![alt text](<Screenshot 2025-10-23 at 14.42.37.png>)
![alt text](<Screenshot 2025-10-23 at 14.42.51.png>)
5) Забилдил контейнер через комманду в терминале:
docker build --no-cache -t nginx:latest .
6) Запустил контейнер через комманду в терминале:
docker run -d -p 8080:80 --name lab2-nginx-container nginx:latest
![alt text](<Screenshot 2025-10-23 at 14.44.44.png>)