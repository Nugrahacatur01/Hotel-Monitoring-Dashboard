# **Hotel Monitoring Dashboard**

## **📉 Business Insights: Cancellation Profile & Revenue Loss Analysis (Januari)**
Analisis ini berfokus pada pembedahan pola pembatalan reservasi untuk mengidentifikasi area risiko dan peluang mitigasi pendapatan (Revenue Recovery).

### **1. Identifikasi Kerugian Pendapatan Berdasarkan Tipe Kamar**
**Insight:** *Grafik "Potential Revenue by Market Segment Type" menunjukkan bahwa Room_Type 2 merupakan kontributor kerugian terbesar akibat pembatalan, yaitu mencapai 73.13% (175K). Sementara Room_Type 1 menyumbang 25.17% (60K).*

**Strategi:** *Hotel perlu mengevaluasi kebijakan pembatalan khusus untuk Room_Type 2. Mempertimbangkan skema non-refundable rate untuk tipe kamar populer ini dapat membantu mengamankan pendapatan.*

### **2. Titik Kritis Lead Time (31-90 Hari)**
**Insight:** *Lonjakan pembatalan pada bulan january paling signifikan terjadi pada reservasi dengan Lead Time 31-90 hari (tercatat sebanyak 20 pembatalan). Ini jauh lebih tinggi dibandingkan pembatalan last-minute (0-30 hari) yang hanya berjumlah 4.*

**Strategi:** *Tamu yang memesan jauh-jauh hari memiliki tingkat ketidakpastian lebih tinggi. Tim reservasi disarankan melakukan re-confirmation otomatis pada H-14 kedatangan untuk memvalidasi status pesanan atau menawarkan opsi perubahan tanggal.*

### **3. Karakteristik Tamu: Segmentasi Online & Corporate**
**Insight:** *Segmen Online tetap menjadi penyumbang volume pembatalan tertinggi (0.0100K), diikuti oleh segmen Corporate (0.0060K).*

**Strategi:** *Mengingat segmen korporasi juga memiliki tingkat pembatalan yang muncul secara signifikan, hotel perlu meninjau kembali perjanjian kontrak korporasi (SLA) terkait batas waktu pembatalan tanpa penalti untuk menjaga stabilitas okupansi.*

### **4. Dampak Durasi Menginap (Avg Length of Stay)**
**Insight:** *Nilai Avg Length of Stay pada data pembatalan menunjukkan angka 57 (akumulasi). Hal ini mengindikasikan bahwa pembatalan sering terjadi pada rencana kunjungan berdurasi panjang (long-stay).*

**Strategi:** *Kehilangan satu pesanan long-stay berdampak besar pada ketersediaan inventaris jangka panjang. Penerapan deposit di awal untuk reservasi di atas 7 malam sangat direkomendasikan untuk meminimalkan dampak finansial.*

### **5. Pola Pembatalan Harian (Daily Revenue Loss)**
**Insight:** *Grafik "Daily Revenue" menunjukkan fluktuasi pembatalan yang mencapai puncaknya pada hari ke-25 bulan Januari.*

**Strategi:** *Analisis lebih lanjut diperlukan untuk melihat apakah lonjakan pembatalan di tanggal tersebut terkait dengan faktor eksternal (cuaca, kebijakan maskapai, atau event tertentu) guna mempersiapkan strategi waiting list yang lebih efektif.*

### **🛠️ Tech Stack & Analytical Focus**
**Tool:** Microsoft Power BI

**Metric Focus:** Cancellation Behavior, Lead Time Analysis, Revenue at Risk.

**Objective:** Menyediakan data pendukung bagi manajemen untuk menurunkan angka pembatalan melalui kebijakan reservasi yang berbasis data.
