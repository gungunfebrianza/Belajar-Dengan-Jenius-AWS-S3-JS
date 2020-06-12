# Belajar Dengan Jenius AWS S3 & Node.js

## Penulis : Gun Gun Febrianza

## *Subchapter* 2 - *AWS CLI V1 & V2*

### 2. AWS CLI V2

Saat ini **AWS CLI** sedang dalam tahap upgrade dengan menyediakan **AWS CLI** Versi ke 2, versi pertama tidak akan dikembangkan lagi namun masih tetap dapat digunakan. Saat ini versi ke 2 disarankan tidak digunakan untuk production, **AWS CLI** Versi ke 2 disediakan khusus untuk uji coba. 

Pada **AWS CLI** Versi ke 2, program sudah tidak lagi menggunakan **dependencies** dari **software package** lainnya. Sebelumnya pada versi pertama terdapat **dependency** yaitu keharusan untuk instalasi **python** terlebih dahulu.

Pada **AWS CLI** Versi ke 2 sudah disediakan dukungan untuk **Linux Distribution** seperti **CentOS, Fedora, Ubuntu, Amazon Linux 1**, dan **Amazon Linux 2**. Untuk **MacOS, AWS CLI** Versi ke 2 sudah disediakan dukungan untuk **High Sierra (10.13), Mojave (10.14),** dan **Catalina (10.15).**

#### Install AWS CLI V2 on Linux

Eksekusi perintah di bawah ini :

```bash
$ curl "https://d1vvhvl2y92vvt.cloudfront.net/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip" unzip awscliv2.zip
```

Kemudian :

```bash
$ sudo ./aws/install
```

#### Install AWS CLI V2 on MacOS

Eksekusi perintah di bawah ini :

```bash
$ curl "https://d1vvhvl2y92vvt.cloudfront.net/awscli-exe-macos.zip" -o "awscliv2.zip"
unzip awscliv2.zip
```

Kemudian :

```bash
$ sudo ./aws/install
```

#### Install AWS CLI V2 on Windows

Pada sistem Operasi **Windows**, **download MSI Installer** untuk **AWS CLI V2** disini :
https://d1vvhvl2y92vvt.cloudfront.net/AWSCLIV2.msi

atau anda dapat mengunjungi halaman di bawah ini :

https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2-windows.html

Setelah selesai **download**, lakukan instalasi kemudian eksekusi perintah di bawah ini :

```
C:\> aws2 --version
aws-cli/2.0.0dev3 Python/3.7.5 Windows/10 botocore/2.0.0dev2
```



---------------------

