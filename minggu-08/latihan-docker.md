# Docker Compose

## Langkah 1 : Setup


1. membuat sebuah direktori untuk project

![Gambar 1](./docker01.png)

2. membuat file app.py pada direktori project

![Gambar 1](./docker02.png)

3. membuat file requirement.txt

flask
redis


## Langkah 2 : Membuat Dockerfile

membuat file Dockerfile

![Gambar 1](./docker03a.png)

## Langkah 3 : Define services in a Compose file

membuat dile docker-compose.yml

![Gambar 1](./docker03b.png)

## Langkah 4 : Build and run your app with Compose

1. dari direktori project jalankan perintah docker-compose up


![Gambar 1](./docker03.png)


2. jalankan http://localhost:5000 pada browser


![Gambar 1](./docker04.png)


3. refresh halaman tersebut


![Gambar 1](./docker05.png)


4. berpindah terminal window yang lain docker image ls


![Gambar 1](./docker06.png)

5. untuk berhenti dengan perintah docker-compose down atau tekan ctrl+C


## Step 5 : Edit the Compose file to add a bind mount

edit file docker-compose.yml

![Gambar 1](./docker07.png)


## Step 6 : Re-build and run the app with Compose

dari direktori project jalankan perintah docker-compose up

![Gambar 1](./docker08.png)


cekHello World pada browser

![Gambar 1](./docker09.png)


## Step 7 : Update aplikasi

ubah greeting Hello World! di file app.py menjadi Hello from Docker!

![Gambar 1](./docker10.png)


refresh browser


![Gambar 1](./docker11.png)

## Langkah 8 : Experiment with some other commands







![Gambar 1](./docker12.png)


![Gambar 1](./docker13.png)


![Gambar 1](./docker14.png)
