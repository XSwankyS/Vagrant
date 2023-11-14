# Vagrant изи старт

Скачиваем, устанавливаем Vagrant и VirtualBox, а так же скачиваем образ CentOS_8<br>
Vagrant       <a href="https://www.vagrantup.com/">Тык!<a><br>
VirtualBox    <a href="https://www.virtualbox.org/">Тык!</a><br>
Образ CentOS_8 <a href="https://disk.yandex.ru/d/Py9PYiPZmMzaUA">Тык!</a><br>
  
  
<h2>Открываем CMD</h2>

<h3>Проверяем установку Vagrant</h3>
vagrant -v<br>
  
<h3>Добавляем образ Centos8</h3>
vagrant box add centos/8 file:///C:\Path\to\file\centos_8.box (подставить свой путь)<br>
  
<h3>Создаём и переходим директорию в которой будем работать</h3>
mkdir C:\VMs\ (Свой путь)<br>
cd C:\VMs\ (Свой путь) <br> 


<h3>В созданной директории размещаем Vagrantfile</h3>
Деплоит три виртуальные машины с hostname control, ansible1, ansible2

<h3>Запускаем</h3>
vagrant up<br>
  
<h3>Произойдёт деплой виртуальных машин default<br>
На этом этапе можно подключиться к VM с помощью ssh</h3>
vagrant ssh hostname

  
 

