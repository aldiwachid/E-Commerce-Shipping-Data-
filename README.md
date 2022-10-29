# Summary EDA (Exploratory Data Analytic)

## 1. Berdasarkan Descriptive Statistics didapat :

- Tipe data di setiap kolom terlihat sudah sesuai 

- Tidak ada nilai kosong (null) disetiap kolomnya

- Nilai max dan min dari setiap feature, secara umum terlihat normal. Pada 'Discount_offered' dan 'Prior_purchases' perlu diperhatikan karena nilai maxnya sangat jauh dari Q3nya.

- Semua feature terkecuali 'Discount_offered' dan 'Weight_in_gms' terdistribusi normal dilihat dari mean dan median yang bernilai dekat.

- Feature 'Discount_offered' dan 'Weight_in_gms' distribusinya kemungkinan skewed.

## 2. Berdasarkan Univariate Analysis didapat :

### Boxplot

- Dapat dilihat pada plot 'Discount_offered' dan 'Prior_purchases' terdapat *outlier* dan cukup jauh dari nilai distribusi normalnya

- Feature lainnya terlihat tidak memiliki *outlier*

### Distplot

- Terdapat 2 feature yaitu 'Prior_purchase' dan 'Discount_offered' terdistribusi *negatively skewed*

- Feature 'Reached.on.Time_Y.N' memiliki distribusi *bimodal*

### Countplot

- Warehouse : Block A, B, C, D memiliki nilai yang serupa sedangkan block F mendominasi hingga 2x lipat nilai block lainnya.

- Shipment : Transportasi udara dan darat memiliki nilai yang serupa sedangkan transportasi laut(menggunakan kapal) mendominasi sekitar 4x lipat lebih banyak.

- Importance : Secara keseluruhan mayoritas *Importance* produk ada pada *low* dan *medium*, sedangkan *High importances* menjadi minoritas.

- Genders   : Kedua gender memiliki nilai yang serupa.


## 3. Berdasarkan Multivariate Analysis didapat :

- Tidak ada 2 feature yang redundan (>0.7)
- Terdapat korelasi positif antara feature 'Discount_offered' dan 'Reached.on.Time_Y.N' (0.40)
- Terdapat korelasi positif antara feature 'Customer_care_calls' dan 'Cost_of_the_Product' (0.32)
- Terdapat korelasi negatif antara feature 'Weight_in_gms' dan 'Discount_offered' (-0.38)
- Terdapat korelasi negatif antara feature 'Reached.on.Time_Y.N' dan 'Weight_in_gms' (-0.27)







