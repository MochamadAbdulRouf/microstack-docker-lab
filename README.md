# microstack-docker-lab
Mini project modul untuk mempelajari Docker dan Docker Compose dengan membuat sebuah lingkungan sederhana yang terdiri dari API Service dan Database, dihubungkan melalui custom network.

⚡ Cara Menjalankan

Clone repo ini

git clone [https://github.com/MochamadAbdulRouf/microstack-docker-lab.git](https://github.com/MochamadAbdulRouf/microstack-docker-lab.git)
cd microstack-docker-lab


Jalankan container dengan Docker Compose

docker compose up -d


Akses API service di browser atau menggunakan curl:

curl http://localhost:8080


Untuk mematikan container + network + volume:

docker compose down -v

Project ini dibuat untuk tujuan pembelajaran. Feel free to fork, modify, and experiment 🚀
