# datapenelitian
Bisa diakses disini: https://drive.google.com/drive/folders/1bTXTyNOZmsjPzK9p0uq--lxlxySPnBhk?usp=sharing 

Merupakan Data penelitian https://github.com/alberanalafean22/Riset-TA , terdiri dari 3 Jenis Citra: Citra False Color (Untuk menlihat visualisasi Kondisi citra pada kombinasi band 7-5-4), citra multiband(sebagai inputan model) dan citra mask(sebagai label)

Citra Multiband (Citra Inputan), Yang Terdiri dari 5 band:
  *  Band 1: NDVI
  *  Band 2: NBR
  *  Band 3: Band 4 Landsat 9 TOA (Interpetasi False Color, Kombinasi 7-5-4)
  *  Band 4: Band 5 Landsat 9 TOA (Interpetasi False Color, Kombinasi 7-5-4)
  *  Band 5: Band 7 Landsat 9 TOA (Interpetasi False Color, Kombinasi 7-5-4)

Citra Mask (Label segmentasi), yang diperoleh dari thresholding DNBR, terdiri dari 2 warna mewakili piksel
 * Putih > Burned Area (Area Terbakar)
 * Hitam > Non-Burned Area (Tidak Area Terbakar)
