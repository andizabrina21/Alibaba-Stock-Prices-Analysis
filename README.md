# Alibaba-Stock-Prices-Analysis
Alibaba Group Holding Ltd. merupakan salah satu perusahaan teknologi terbesar di Tiongkok yang memainkan peran penting dalam perkembangan ekonomi digital, baik di pasar domestik maupun secara global. Saham Alibaba diperdagangkan di beberapa bursa International salah satunya di New York Stock Exchange (NYSE) dengan kode BABA.

## Project Overview
Project ini bertujuan untuk menganalisis pergerakan harga saham Alibaba menggunakan pendekatan data analytics guna mengidentifikasi pola, tren, volatilitas, serta potensi risiko dan peluang investasi. Hasil analisis diharapkan dapat memberikan insight yang bermanfaat sebagai pendukung pengambilan keputusan bagi investor maupun pihak yang tertarik mempelajari perilaku pasar saham.

## Business Problem
Saham merupakan aset penting bagi perusahaan sebagai sumber pendanaan untuk mendukung ekspansi bisnis, sekaligus menjadi instrumen investasi bagi investor. Saham memiliki pergerakan harga yang dinamis dan dipengaruhi oleh berbagai faktor, seperti kinerja perusahaan, kondisi ekonomi, perubahan regulasi, serta sentimen pasar. Oleh karena itu, analisis pasar saham penting dilakukan untuk memahami pola pergerakan pasar dan mendukung pengambilan keputusan investasi yang lebih baik. Sebagai salah satu perusahaan teknologi terbesar di dunia, harga saham Alibaba (BABA) mengalami fluktuasi yang cukup tinggi dari waktu ke waktu. Analisis terhadap data historis harga saham diperlukan untuk mengidentifikasi tren, mengukur tingkat volatilitas, serta menemukan insight mengenai potensi risiko dan peluang investasi.

## Dataset Description
Data berupa saham Alibaba periode Januari 2014 hingga Februari 2025 yang diambil dari New York Stock Exchange(NYSE). Dataset ini bersumber dari [Kaggle].
(https://www.kaggle.com/datasets/mhassansaboor/alibaba-stock-dataset-2025/data)\
![Deskripsi gambar](images/Datasetpic.png)
Data tersebut berisi informasi mengenai pergerakan saham Alibaba Group yang terdaftar di NYSE yang terdiri dari beberapa variabel yang merepresentasikan aktivitas perdagangan saham, sebagai berikut,
- Date: Menunjukkan tanggal perdagangan saham.
- Adj Close: Harga penutupan yang telah disesuaikan setelah pembagian dividen dan stock split.
- Close: Harga saham pada saat penutupan pasar.
- High: Harga tertinggi yang dicapai saham dalam satu hari perdagangan.
- Low: Harga terendah yang dicapai saham dalam satu hari perdagangan.
- Open: Harga saham pada saat pembukaan pasar.
- Volume: Jumlah saham yang diperdagangkan dalam satu hari.

## Dashboard Overview
![Dashboard](images/1-Dashboard.png)

## Dashboard Insights & Business Recommendation 
### Key Performance Indicator
![KPI](images/2-KPI.png)
- The average closing price was 135.15, with an average daily high of 136.92 and an average daily low of 133.36, indicating a relatively narrow daily trading range.
  - Investors may consider applying a range trading strategy or waiting for a confirmed breakout before entering new positions, as limited price movements generally offer fewer profit opportunities until a clearer market trend emerges.
- The average daily return of 0.04% indicates relatively slow daily growth, suggesting a period of price stagnation.
  - Investors should not rely solely on short-term capital gains but should combine technical and fundamental analysis to generate more reliable investment signals and reduce the risk of making uninformed decisions.
- The average daily trading volume of 18.99 million shares reflects strong market activity and high liquidity.
  - High liquidity enables investors to enter and exit positions more efficiently, typically with lower slippage risk and narrower bid-ask spreads, resulting in smoother trade execution.

### Trend and Moving Average
![MA](images/3-Trend_and_MA.png)\
- Harga saham Alibaba menunjukkan tren naik yang kuat selama 2016–2020, mencerminkan fase pertumbuhan perusahaan dan meningkatnya kepercayaan investor. Namun, pada periode 2021–2022 terjadi pembalikan tren yang signifikan, ditandai dengan MA 50 hari memotong ke bawah MA 200 hari (Death Cross), yang mengindikasikan momentum bearish yang kuat.
  - Investor sebaiknya meningkatkan kewaspadaan selama periode bearish dan menerapkan strategi manajemen risiko, seperti penggunaan stop-loss atau pengurangan eksposur, untuk membatasi potensi kerugian.
- Sejak 2023, harga saham bergerak sideways, menunjukkan fase konsolidasi setelah tren penurunan. Meskipun terdapat indikasi pemulihan pada periode terbaru, momentum tersebut belum cukup kuat untuk mengonfirmasi terbentuknya tren bullish jangka panjang.
  - Investor sebaiknya menunggu konfirmasi breakout atau sinyal bullish yang lebih kuat sebelum menambah posisi, sehingga risiko false breakout dapat diminimalkan.

### Candlestick
![Candlestick](images/4-Candlestick.png)\
- Candlestick bullish dan bearish muncul secara bergantian selama periode 2017-2021, namun di didominasi oleh candlestick bullish, mencerminkan buying pressure lebih kuat sehinggga mendorong harga saham mencapai puncaknya pada tahun 2021. Setelah itu, frekuensi candlestick bearish meningkat dan diikuti penurunan harga yang tajam, menunjukkan perubahan sentimen pasar dari bullish menjadi bearish.
  - Investor sebaiknya memperhatikan perubahan dominasi pola candlestick sebagai sinyal awal perubahan tren, sehingga dapat mengurangi eksposur atau menerapkan strategi manajemen risiko sebelum penurunan harga semakin dalam.
- Pada periode 2023–2025, jumlah candlestick bullish dan bearish menjadi lebih seimbang dengan rentang pergerakan harga yang relatif sempit, menunjukkan fase konsolidasi dan ketidakpastian arah pasar.
  - Investor disarankan menunggu konfirmasi breakout yang didukung oleh peningkatan volume atau pola candlestick bullish yang kuat sebelum membuka posisi baru, guna mengurangi risiko false breakout

### Daily Return, Volatility and Volume
![MA](images/5-chart.png)\
- Return harian berfluktuasi di sekitar nol, menunjukkan tidak adanya arah pergerakan jangka pendek yang konsisten. Beberapa lonjakan return positif maupun negatif mengindikasikan adanya peristiwa pasar yang berdampak signifikan, sementara penurunan tajam mencerminkan periode koreksi pasar atau meningkatnya tekanan jual (panic selling).
  - Investor sebaiknya memperhatikan periode dengan lonjakan return yang ekstrem karena dapat menandakan peningkatan risiko. Mengombinasikan analisis teknikal, fundamental, dan manajemen risiko dapat membantu mengurangi dampak volatilitas yang tinggi.
- Volatilitas relatif rendah dan stabil sebelum 2020, mencerminkan kondisi pasar yang lebih tenang. Volatilitas kemudian meningkat tajam pada periode 2021–2022, menunjukkan ketidakpastian pasar dan risiko yang lebih tinggi. Meskipun volatilitas menurun setelahnya, levelnya masih berada di atas periode sebelum 2020, mengindikasikan bahwa pasar tetap lebih sensitif terhadap faktor eksternal.
  - Investor disarankan menyesuaikan ukuran posisi (position sizing) dan menerapkan strategi manajemen risiko yang lebih ketat selama periode volatilitas tinggi untuk meminimalkan potensi kerugian.
- Volume perdagangan relatif stabil sepanjang periode pengamatan, menunjukkan partisipasi pasar yang konsisten. Lonjakan volume pada 2021–2022 mencerminkan meningkatnya aktivitas investor akibat peristiwa pasar yang signifikan. Setelah itu, volume menurun namun tetap berada di atas level awal, menunjukkan minat investor yang masih cukup kuat terhadap saham Alibaba.
  - Investor dapat menggunakan volume perdagangan sebagai indikator konfirmasi pergerakan harga, karena kenaikan atau penurunan harga yang didukung volume tinggi umumnya memberikan sinyal tren yang lebih kuat dibandingkan perubahan harga dengan volume rendah.

## Conclusion
Overall, Alibaba's stock has gone through a complete market cycle, starting with strong growth during 2016–2020, peaking in 2020–2021, and then experiencing a sharp correction in 2021–2022, marking a shift to a bearish market. Since 2023, the stock has been moving in a consolidation phase with early signs of recovery, although a long-term bullish trend has yet to be confirmed. Therefore, investors are advised to remain cautious, wait for stronger trend confirmation before increasing their positions, and combine technical analysis, fundamental analysis, and sound risk management to make more informed investment decisions.



