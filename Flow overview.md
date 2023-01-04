# Flowchart

1. Purchase order lewat portal HSO
2. Lihat DO masuk
3. Rekap manual untuk dibagikan unitnya
4. Validasi kacab
5. Validasi nomor rangka nomor mesin
6. Penginputan data oleh sales di aplikasi Asist ketika ada penjualan
   - Status hot untuk indent, hanya input tipe motor
   - Status deal jika unit tersedia
7. Admin create faktur di PSS agar data dapat di tarik
8. Pengecekan motor yang datang dari HSO sesuai shipping list
9. Input stok get data dari Asist hari kemaren yang di PO melalui Portal HSO
   - Date
   - Warehouse
   - Supplier
   - SAP No
   - Courier
   - Delivered by
   - Phone
   - Data vehicle (count)
     - SKU
     - Item
     - Variant
     - Engine No
     - Frame No
     - Year
     - Shipping In
     - Status
10. Input Sales get data dari Asist hari kemaren yang di PO melalui Portal HSO
    - Input data customer
    - Input data indent (jika ada)
    - Input transaksi sales
      Berkas yang tersedia setelah input sales/penjualan:
      - Cover buku servis
      - Ceklis manual
      - Sales database manual
      - Sales database
      - Kwitansi penjualan (kasir)
      - BSTK (hanya bisa dicetak ketika mendapat approve dari ADH)
      Berkas leasing:
      - Kwitansi tagihan leasing
      - Cetak database dibalik surat persetujuan Pembiayaan dan pemesanan barang
      Berkas yang tersedia setelah stnk/bpkb jadi:
      - STNK
      - BPKB
        nb: data indent akan terload otomatis jika sepeda motor sudah datang

11. Kasir
    - Terima uang dari konsumen sesuai data sales database
    - Tipe pembayaran (langsung/kirim tagih)
    - Jenis pembayaran
      - Kas besar kendal
      - Kas kecil kendal
      - Deposito
      - BCA Kendal
      - BRI - GIRO
      - BRI Tab - Cab/Ahass
      - Permata
      - BCA HO
      - BCA unit kendal
      - BRI tampungan
    - Payment
      - Paid
      - Sub total
      - Plus
      - Discount
      - Amount due
    - Uang yang tercetak di kwitansi ***(sub total)*** belum termasuk diskon
12. BSTK
    - Hanya bisa dicetak sesudah mendapat approval dari ADH (status *outstanding* berubah menjadi *deliver*)
13. STNK dan BPKB
    - Input faktur astra
    - Data STNK di input
    - Memilih data sales/tx yang akan di buatkan STNK dan BPKB
    - Membuat rekapan untuk Biro Jasa pembuat STNK dan BPKB
      - Biro Jasa
      - Tanggal
      - Customer
      - Unit/motor
      - Kode unit
      - No mesin
      - No rangka
      - BBN (Notice)
      - Administrasi (Unotice)
      - Total
      - Tanggal jual
      - No sales
      STNK dan BPKB jadi
      - hanya di input di Assist
