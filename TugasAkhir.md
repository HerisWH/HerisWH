### Heris Warli Huda
### 185150307111014
### Tugas Akhir

## Tugas 1
Buat EC2 Instance di AWS Academy:

•	Name and tags: Tugas Akhir

•	OS Images: Ubuntu Server 22.04 LTS 64 bit

•	Instance type: t2.medium

•	Key pair: vockey

•	Edit Network settings: allow SSH, allow HTTP, allow HTTPS, allow TCP port 8080, allow TCP port 8081

•	Configure storage: 30 GiB, gp3

Setelah EC2 Instance siap, lakukan instalasi Mininet+OpenFlow, Ryu dll.

![Tugas 1](https://user-images.githubusercontent.com/107157273/172842106-4c6340de-6b37-42c3-8dd3-366f053fcb5a.png)

## Tugas 2
Membuat program sederhana untuk custom topology dengan 6 host dan 3 switch, lalu membuat flow nya terhubung ke seluruh host nya dan sekalian diuji koneksi nya.

![Tugas 2](https://user-images.githubusercontent.com/107157273/172842476-035e4ce8-1a69-4b2a-922b-c36f04a82842.png)


## Tugas 3
Membuat load balancer. Load balancing adalah proses pembagian beban traffic sebuah aplikasi atau server. Dengan load balancer, beban traffic tidak akan dibebankan kepada beberapa jalur koneksi. Hal ini mempercepat waktu respons server Anda dan mencegahnya dari overloading. Dengan begini, kinerja server Anda akan lebih maksimal tidak peduli berapa banyak traffic yang Anda dapatkan.

![image](https://user-images.githubusercontent.com/107157273/172842909-2ed09660-fcb9-4ad6-b58b-04966d685187.png)


## Tugas 4
Menggunakan gitclone untuk menyalin repository dari https://github.com/abazh/learn_sdn.git pada terminal satu dan mengganti direktori ke learn_sdf/SPF pada terminal 1.
Menulis kode ‘ryu-manager --observe-links dijkstra_Ryu_controller.py’ pada terminal 1.
Screenshot terminal 1:

Terminal 1:

![Tugas 4 1](https://user-images.githubusercontent.com/107157273/172843697-63d1d921-854f-4749-b3fd-abdd191d7dc3.png)

Mengganti direktori ke learn_sdn/SPF seperti pada terminal 1 dan menuliskan perintah ‘sudo python3 topo-spf_lab.py’ pada terminal 2:

Terminal 2:

![Tugas 4 2](https://user-images.githubusercontent.com/107157273/172843762-32a1c07a-32e5-4439-9a07-4ce4c7839f10.png)

Mengecek konektivitas ping: h1 ping -c 4 h4.

Terminal 1:

![Tugas 4 3](https://user-images.githubusercontent.com/107157273/172843864-87f4707e-fd7d-4a63-9491-3284bda3dd7e.png)

Terminal 2:

![Tugas 4 4](https://user-images.githubusercontent.com/107157273/172843899-12fd17bb-9163-4baa-b2a4-ffa4920ff6b8.png)
