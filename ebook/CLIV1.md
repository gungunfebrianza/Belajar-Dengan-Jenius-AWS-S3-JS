# Belajar Dengan Jenius AWS S3 & Node.js

## Penulis : Gun Gun Febrianza

## *Subchapter* 2 - *AWS CLI V1 & V2*

### 3. AWS CLI V1

Sebelum melakukan instalasi **AWS CLI**, pastikan sistem operasi anda sudah melakukan installasi bahasa pemrograman **python** versi 3.7 ke atas, kita akan melakukan instalasi **AWS CLI** melalui **python package manage**r yang bernama **pip**. 

#### Install AWS CLI 

Untuk memulai instalasi eksekusi perintah di bawah ini :

```python
pip install awscli
```

#### Upgrade AWS CLI

Jika sebelumnya anda sudah memiliki **AWS CLI**, direkomendasikan untuk melakukan upgrade ke versi yang terakhir untuk alasan keamanan. Untuk upgrade **AWS CLI,** eksekusi perintah di bawah ini :

```
 pip install --upgrade awscli
```

#### Verify AWS CLI

Lakkan verifikasi untuk memastikan **AWS CLI** sudah terpasang dalam sistem operasi anda :

```
aws --version
aws-cli/1.18.56 Python/3.8.2 Windows/10 botocore/1.16.6
```

Eksekusi perintah di atas untuk mendapatkan informasi versi **AWS CLI** yang kita miliki. 
Saat menggunakan **AWS CLI**, kita memerlukan **AWS Credentials** untuk melakukan **authentication** pada layanan **AWS**. 

Terdapat beberapa cara diantaranya adalah :

1.	**Environment Credentials** berupa :
**AWS_ACCESS_KEY_ID** dan **AWS_SECRET_KEY**
2.	**The Shared Credentials File**
3.	**IAM Roles**, jika anda menggunakan **AWS CLI** di sebuah mesin **EC2** maka kita tidak perlu lagi mengatur **credential files** di **production**.

---------------------

