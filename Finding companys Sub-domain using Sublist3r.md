1. langkah pertama yaitu login ke kali linux bisa menggunakan virtual machine atau yang lainnya
2. jika sudah login masuk ke terminal dan pastikan untuk melakukan update
3. lalu langsung install Sublist3r dengan command `sudo apt install sublist3r`
   ![Screenshot 2024-09-04 211211](https://github.com/user-attachments/assets/43fad9a0-4ed8-41b2-ab25-0a88d7459653)
   
4. Untuk panduan pengunaan sublist3r bisa dengan menggunakan command `sublist3r -h`
   ![Screenshot 2024-09-04 211309](https://github.com/user-attachments/assets/0e5a43e4-9f64-4658-a85d-2133869448eb)
   
5. Kita bisa mencoba mencari sub-domain pada suatu website dengan menggunakan opsi `-d`, contohnya `sublist3r -d youtube.com`
   ![Screenshot 2024-09-04 211427](https://github.com/user-attachments/assets/f1ec2bee-f948-4654-9e00-c79b42280fc9)
   
6. Dari contoh command di atas bisa di kombinasikan dengan opsi lain, misalnya `-t` untuk melihat threads. contohnya seperti ini `sublist3r -d youtube.com -t 5` dengan menggunakan `-t 5` berfungsi untuk melihat threads sebanyak 5
   ![Screenshot 2024-09-04 212259](https://github.com/user-attachments/assets/74531e83-2485-4238-8f8a-06f7bb96bf89)
   
7. Opsi yang bisa dicoba selanjutnya yaitu `-p` befungsi untuk melihat port yang aktif, contohnya `sublist3r -d youtube.com -p 443,80` disini kita ingin mengecek port 443 , dan 80
   ![Screenshot 2024-09-04 212431](https://github.com/user-attachments/assets/3046fe82-fb47-4b19-855e-074db42accd7)
