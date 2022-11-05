# Summary Pre-Processing Data

## 1. Data Cleansing :

### A. Handle Missing Values

- Tidak ada data yang bernilai *null*/hilang

### B. Handle Duplicated Data

- Tidak ada data yang duplikat

### C. Handle Outliers

- Pada fitur 'Prior_purchases' dan 'Discount_offered' terdapat *outliers*

- Dilakukan filter *outliers* berdasarkan IQR

### D. Feature Transformation

- Pada fitur 'Discount_offered' distribusi datanya *right-skewed*, dilakukan Log Transformation sehingga distribusinya akan mendekati normal

### E. Feature Encoding

- Label Encoding digunakan pada fitur 'Gender' dan 'Product_importance'

- One Hot Encoding digunakan pada fitur 'Mode_of_Shipment'

### F. Handle Class Imbalance

- Berdasarkan derajat kesetimpangan data, data yang dimiliki tidak termasuk ke dalam kategori *imbalance*

## 2. Feature Engineering :

### A. Feature Selection

- Saat ini semua fitur akan digunakan karena fitur yang ada saat ini tidak banyak

- Tidak ada fitur yang redundan, sehingga tidak perlu ada fitur yang di drop

### B. Feature Extraction

- Dibuat klasifikasi berat berdasarkan fitur 'Weight_in_gms'

### C. Feature Addition

- Shipment Date (Tanggal pengiriman barang)
- Revenue (Cost - Discount offer)
- Order Date (Tanggal pemesanan sekaligus pembayaran)
- Membership status (status customer berdasarkan banyaknya transaksi)







