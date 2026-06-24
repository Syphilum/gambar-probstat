##How to use
- masukkan code ini ke terminal di soal:
  '''
  url <- "https://raw.githubusercontent.com/Syphilum/gambar-probstat/main/nama_file.png"

download.file(url, "graf.png", mode = "wb")

library(IRdisplay)
IRdisplay::display_png(file = "graf.png")
'''
- ganti "nama_file" dengan foto yang sesuai dengan soal
