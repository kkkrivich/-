
# Перед начал ом установки устанавливаем Linux Oracle на VirtualBox
Далее переходим к установке утилитов:

1. sudo yum install wget
   
![image](https://github.com/user-attachments/assets/8db32686-ee0f-409d-ae15-9d660c7d2376)

2. sudo wget -P /etc/yum.repos.d/ https://download.docker.com/linux/centos/docker-ce.repo
   
![image](https://github.com/user-attachments/assets/8b746fad-87a3-4f95-a3ab-4f43f44536a8)


3. Устанавливаем docker:
sudo yum install docker-ce docker-ce-cli containerd.io

![image](https://github.com/user-attachments/assets/279f3044-6975-4572-aacd-f89bb4e61e34)

![image](https://github.com/user-attachments/assets/9ae6f596-47a1-43b0-8ce7-7d2f4304acc1)

4. Запускаем и разрешанем автозапуск 
sudo systemctl enable docker --now

![image](https://github.com/user-attachments/assets/f070063a-30a5-46a1-94ea-e9b753788844)
