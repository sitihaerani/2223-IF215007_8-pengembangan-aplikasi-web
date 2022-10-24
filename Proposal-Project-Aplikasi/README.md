# PROPOSAL PROJECT 
## APLIKASI ACTIVITY REMINDER
******************************************************************
## Permasalahan
* Dalam kehidupan sehari-hari pada umumnya   mahasiswa terkadang kesulitan bahkan ada beberapa orang yang lupa untuk mengatur dan menepati kegiatan hariannya khusunya sering lupa dalam mengingat tugas

## Rancangan Solusi
* Aplikasi yang dapat membantu agenda mahasiswa sekaligus mengingatkan mahasiswa tersebut dimana pun dan kapan pun mereka berada

## Use Case
* User melakukan Registrasi
* User melakukan Login
* User dapat melihat schedule
* User dapat menambah schedule dan menambah keterangan schedule

## Struktur Data

* Data User

| Atribut  | Tipe Data | Contoh                |
| -------- | --------- | --------------------- |
| id_user  | INTEGER   | 1                     |
| username | VARCHAR   | sitihaerani           |
| email    | VARCHAR   | sitihaerani@gmail.com |
| password | VARCHAR   | shaerani              |
| tgl_lahir| DATE TIME | 2002-02-02            |


* Data Schedule

| Atribut       | Tipe Data | Contoh       |
| ------------- | --------- | ------------ |
| id_schedule   | INTEGER   | 1            |
| nama_schedule | VARCHAR   | Prak. Jarkom |
| tanggal       | DATE TIME | 2022-09-15   |

* Data Task

| Atribut    | Tipe Data | Contoh                      |
| ---------- | --------- | --------------------------- |
| id_task    | INTEGER   | 1                           |
| kelas      | VARCHAR   | F-Pengembangan Aplikasi Web |
| nama_tugas | VARCHAR   | Proposal Project            |
| catatan    | VARCHAR   | kumpulkan di GitHub         |  


## UI

![1](https://user-images.githubusercontent.com/112878739/189589451-62a19bd6-a032-4ba8-8ac8-a5c2663a11f2.png)


![2](https://user-images.githubusercontent.com/112878739/189589602-b4b55f8a-625d-4aac-b0ba-ff611dd69b52.png)


![3](https://user-images.githubusercontent.com/112878739/189589635-10cbc6ac-f01e-4cd7-bce2-7118cd0b55d1.png)


![4](https://user-images.githubusercontent.com/112878739/189589673-7ba0c61a-9623-4bf0-940c-5dcb57d14845.png)


![5](https://user-images.githubusercontent.com/112878739/189589694-8642ff17-b96a-4249-afbe-c45142d89fc1.png)
