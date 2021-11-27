## 				**UTS Sistem Administrasi**

**Nama : Dewa Nusantara MP**

**NIM  : 1202190053**

**Kelas: IT02-01**


```markdown
1.	Download ISO Installer windows server 2022
```

```markdown
-	Akan ada 4 pilihan yaitu :
**Try Windows Server on Azure**
**Create a Windows Server VM in Azure**
**Download the ISO**
**Download teh VHD**
Dan pilih yang *Download the ISO*
```

```markdown
- Kemudian ikuti sesuai step by stepnya. Jangan lupa isi data dan centang "yes" kemudian continue
```

```markdown
-	Pilih bahasa yang diinginkan dan klik download
```

```markdown
2.	Langkah Langkah instalasi :
```

```markdown
-	Open VirtualBox and go to the “machine – New” Menu


```

![image](https://user-images.githubusercontent.com/74553908/143456620-6c636571-cf9b-4a27-b3c1-a85893860cf8.png)



```markdown
- Enter the name of the machine and type of system to use
```

![image](https://user-images.githubusercontent.com/74553908/143456876-3e1afbb2-d57c-4cbe-bb16-d7a02ee7e472.png)


```markdown
- Define ram, create the disk defining type and size
```

![image](https://user-images.githubusercontent.com/74553908/143457247-c085bde3-ded9-48f5-8167-a4b3ab610e9e.png)

![image](https://user-images.githubusercontent.com/74553908/143457324-5cafca96-7d7d-41d9-9ce9-9fbbc8493832.png)

![image](https://user-images.githubusercontent.com/74553908/143457449-4378eff1-8bfa-493f-8b84-31dea22f00c4.png)

![image](https://user-images.githubusercontent.com/74553908/143457515-4f9be0f5-4d90-4878-bbdf-6064ebf4677c.png)

![image](https://user-images.githubusercontent.com/74553908/143457611-adf6f71f-af7b-4a04-804c-29ab35ee8613.png)

```markdown
- Go to the machine configuration and in the “Network” section set it from "NET" to “Bridge adapter”
```

![image](https://user-images.githubusercontent.com/74553908/143457750-e9b62544-0d09-4107-afb0-ae209094b9b8.png)



```markdown
- Click on “Start” and select the ISO downloaded
```


![image](https://user-images.githubusercontent.com/74553908/143458582-ed1dc1cf-1b60-4db9-a676-04b24a32fee0.png)

![image](https://user-images.githubusercontent.com/74553908/143458651-7545dee1-e58e-48aa-ac65-8040f28a90ef.png)

```markdown
- Click on “Start” and the Windows Server 2022 installation wizard will load
```

![image](https://user-images.githubusercontent.com/74553908/143458902-bb08b8c5-6363-4f4d-b19f-7449a1ffeed6.png)

```markdown
- Click on “Install now”
```

![image](https://user-images.githubusercontent.com/74553908/143459022-64726e2b-3a96-4429-8dc4-2eee3196b14e.png)

```markdown
- Enter the license (if you have on) and then define the edition to use, Accept the license and then proceed with the installation of Windows Server 2022
```

![image](https://user-images.githubusercontent.com/74553908/143459220-0409508c-d1dc-4766-8586-17ed28a33276.png)

![image](https://user-images.githubusercontent.com/74553908/143459329-45f8004e-9db1-45a5-a6f5-190d87bea07b.png)

![image](https://user-images.githubusercontent.com/74553908/143459619-0da598e8-5659-4c45-919a-9ef87fa22489.png)

![image](https://user-images.githubusercontent.com/74553908/143459754-c554fcff-0299-4987-9d21-6a66169db03f.png)


```markdown
- The system will reboot to complete the process
```

```markdown
- Enter the administrator password
```
![image](https://user-images.githubusercontent.com/74553908/143463329-9cc160d8-d9a6-42d4-886a-97218fc8d3c0.png)

```markdown
- Access the menu “Input – Keyboard – Insert Ctrl + Alt + Del”. Enter the password created and wait for the configuration to load
```

![image](https://user-images.githubusercontent.com/74553908/143463827-0a3c156a-401e-4d64-bc0a-bcecaf192650.png)

![image](https://user-images.githubusercontent.com/74553908/143464257-fa80c4e2-a94a-4d53-8106-e78e60ccea25.png)


```markdown
- Go the menu “Devices – Insert Guest Additions CD Image” , From the Explorer run this and follow the steps pf the wizard. Reboot the machine
```

![image](https://user-images.githubusercontent.com/74553908/143464828-797ad72f-4eeb-4425-b12b-62b86a88ca34.png)

![image](https://user-images.githubusercontent.com/74553908/143464963-698f7041-61d1-48a9-bee3-a94116bc44bf.png)

![image](https://user-images.githubusercontent.com/74553908/143465140-729b4afa-0a1b-4fad-9f0b-4ad5c7c16369.png)

![image](https://user-images.githubusercontent.com/74553908/143465222-2fe9f1c7-6708-4470-ab77-45a4e45bcb9b.png)

![image](https://user-images.githubusercontent.com/74553908/143465356-e63438a8-35ae-43e6-ab3f-561295c6d5c8.png)

![image](https://user-images.githubusercontent.com/74553908/143465556-5a1168cc-d257-4e01-8405-dc6b48f182dd.png)


```markdown
- Access the menu “Input – Keyboard – Insert Ctrl + Alt + Del”. Enter the password created and wait for the configuration to load
```
![image](https://user-images.githubusercontent.com/74553908/143466060-ac6d0e3a-db3b-4270-994c-810249f11ee8.png)

```markdown
- Run “winver” to validate the installed edition of Windows Server
```

![image](https://user-images.githubusercontent.com/62064492/143058074-ab6a8d6f-8421-433e-afd9-3d1873a4123c.png)

```markdown
A. Instalasi Active Directory Domain Services
```

```markdown
- Sebelum melakukan instalasi , kita merubah nama computer terlebih dahulu dengan masuk ke windows powershell. Kemudian ketikkan “rename-computer -Newname Server2022”
```

![image](https://user-images.githubusercontent.com/62064492/143058230-c8536ec9-1ac0-4789-9b63-0b592839313d.png)

```markdown
- Masuk ke menu “Server Manager”. Lalu pilih opsi “Manage:,dilanjutkan dengan mengklik “Add Roles and Features”. Kemudian klik “Next”.
```
![image](https://user-images.githubusercontent.com/62064492/143058338-b6117d81-8479-4860-94f9-f4371a630f72.png)

```markdown
- Pilih opsi “Role-based or feature-based installation”. Lalu “Next”
```

![image](https://user-images.githubusercontent.com/62064492/143058402-8450dfce-0c8f-4b3a-b14d-4da3691fd439.png)

```markdown
- Klik “Select a server from the server pool” untuk memilih direktori penyimpanan lokal. Lalu “Next”
```

![image](https://user-images.githubusercontent.com/62064492/143058537-a5d1dc41-1d55-405d-8fea-ce5335b89c61.png)

```markdown
- Selanjutnya, berikan tanda centang di kotak “Active Directory Domain Services”. Saat anda mencentang kotak, disebelah kanan muncul penjelasan singkat tentang ADDS dan cara kerjanya. Lalu klik “Add Features”.
```
![image](https://user-images.githubusercontent.com/62064492/143058626-b950b867-673b-4be0-8644-571d715e5c91.png)

```markdown
- Kemudian centang kotak “Group Policy Management” dan tekan tombol “Next”.
```

![image](https://user-images.githubusercontent.com/62064492/143058709-2e1fce7f-3cf7-4203-9ec1-5aa1600f3e04.png)

```markdown
- Selanjunya klik “Next” lagi.
```
![image](https://user-images.githubusercontent.com/62064492/143058812-7cc2737b-c66a-4d48-bce0-ebab12dfc834.png)

```markdown
- Klik “Install”.
```

![image](https://user-images.githubusercontent.com/62064492/143058927-66049ec4-f165-4ffa-a11f-d3ba398feaef.png)

```markdown
- Tunggu hingga proses instalasi selesai kemudian melakukan konfigurasi ADDS
```
![image](https://user-images.githubusercontent.com/62064492/143059056-4b3a2b2c-c4a3-43c7-bf11-a974412b383e.png)



```markdown
B. Instalasi DNS server
```

```markdown
- Masuk ke menu “Server Manager”. Lalu pilih opsi “Manage:,dilanjutkan dengan mengklik “Add Roles and Features”. Kemudian klik “Next”. Stepnya sama seperti instalasi active directory. Kita perlu menginstal dan mengonfigurasi peran Active Directory dan server DNS untuk bekerja bersama. 
```

![image](https://user-images.githubusercontent.com/62064492/143059169-bc75ab5c-54dc-474f-b9b1-a809f8547103.png)



```markdown
C. Instalasi Net Framework 3.5
```

```markdown
- Centang “.NET Framework 3.5 features”
```

![image](https://user-images.githubusercontent.com/62064492/143059289-ca4aa9b0-e658-445c-b6eb-7b01ddb2192e.png)

```markdown
- Selanjunya klik “Next” lagi.
```

![image](https://user-images.githubusercontent.com/62064492/143059414-e40ac556-cbd2-4192-8fc6-3459d68decd8.png)

```markdown
- Selanjutnya klik “Install”.
```
![image](https://user-images.githubusercontent.com/62064492/143059520-231922be-4757-4c00-bf38-e89398e48da4.png)

```markdown
- Tunggu hingga proses instalasi selesai
```

![image](https://user-images.githubusercontent.com/62064492/143059642-a839d8d3-231c-4f1e-8a5a-fe37c474cb02.png)

```markdown
**Promote Server to a Domain Controller**
```

```markdown
- Seting ke ip static menggunakan cmd, ketik sconfig
```

![image](https://user-images.githubusercontent.com/74553908/143473368-4946e132-3d60-40be-b6d9-1c35c6b4e79c.png)

![image](https://user-images.githubusercontent.com/74553908/143473470-2820fa16-7c16-4c18-9917-558c8e1d3c07.png)

![image](https://user-images.githubusercontent.com/74553908/143473677-4a005d30-d19f-4ea6-8483-a68e0a3fce59.png)

```markdown
- Setting IP Address Server-ADDS dan mengarah DNS ke IP address static yang digunakan.
```

![image](https://user-images.githubusercontent.com/74553908/143474043-d5070d18-0b96-4445-9f91-86407b5dbb75.png)

```markdown
- Klik “Promote this server to a domain controller untuk konfigurasi ADDS
```
![image](https://user-images.githubusercontent.com/74553908/143476294-34c581ca-ac6a-44ab-a3e1-fa16ffb6b5e3.png)

```markdown
- Pilih “Add a new forest” dan masukkan nama domain yang akan digunakan pada Root Domain Name. Misalnya disini saya menggunakan domain “Boi.com”
```
![image](https://user-images.githubusercontent.com/74553908/143476457-a735bd86-1fde-44ca-a152-97b79d56b54b.png)

```markdown
- Pilih “Windows Server 2016” pada functional level, beri tanda centang pada “Domain Name System (DNS) server” dan ”Global Catalog (GC)”. Serta mengisi password Directory Services Restore Mode dengan kriteria strong password.
```

![image](https://user-images.githubusercontent.com/74553908/143476608-c90d0ceb-cdf2-493b-aca7-2a43a22a5ba8.png)

```markdown
- Lewati bagian DNS Options, lalu klik “Next”.
```

![image](https://user-images.githubusercontent.com/62064492/143064837-a5dd8d07-d77c-4cbe-a96d-eb6b2a120c6e.png)

```markdown
- Mengisi “The NetBIOS domain name” sesuai dengan nama domain yang digunakan.
```

![image](https://user-images.githubusercontent.com/74553908/143476773-2e6dc08b-82f4-4276-8e92-91ddd3325eb8.png)

```markdown
- Lewati bagian Paths, klik “Next”.
```

![image](https://user-images.githubusercontent.com/62064492/143062494-2c7a08ce-49f3-40db-ad12-4490ec112b99.png)

```markdown
- Cek konfigurasi yang ditentukan pada Review Options, jika suda ok. Klik “Next”.
```
![image](https://user-images.githubusercontent.com/74553908/143476945-8c339382-aa18-4c83-bf4f-4c26e294ace9.png)

```markdown
- Jika sudah ada tulisan All prerequisite checks passed successfully. Klik “Install” untuk apply konfigurasi yang sudah ditentukan.
```
![image](https://user-images.githubusercontent.com/62064492/143062766-88e37beb-aa83-4b18-ba2d-b20fec2e6c8f.png)

```markdown
- Tunggu hingga proses instalasi selesai.
```

![image](https://user-images.githubusercontent.com/62064492/143062877-c7a3a0e7-cdd8-404a-9ac2-a4204c5bfd46.png)

```markdown
- Setelah selesai menginstal, maka laptop akan ke restart otomatis. Kemudian login menggunakan password administrator
```
![image](https://user-images.githubusercontent.com/74553908/143481426-fa971aaf-9308-443b-89b4-8580bee00c84.png)

```markdown
- Untuk mengecek hasil konfigurasi, buka cmd dan ketikkan “netdom query fsmo”
```

![image](https://user-images.githubusercontent.com/74553908/143481750-03c044b7-e29f-453c-b89a-b9186cac1b3a.png)

```markdown
- Setelah login dengan Active Directory Domain Controller, buka properti TCP/IP koneksi jaringan Anda. Anda dapat melihat Alamat IP server DNS yang disukai
```

![image](https://user-images.githubusercontent.com/74553908/143481934-26f29b60-2e8d-4c30-842a-c98d2fdac8ed.png)

![image](https://user-images.githubusercontent.com/74553908/143482066-6f4a6e83-771c-4772-a46c-edb5f161a8d8.png)


















