#########
User Type
#########

#. **Super Administrator**
   
   * Can access all the features

#. **Admin Wilayah**/**Operator** [Not common used / Low level than Super Administrator]
   
   * Access depend on the district (Kabupaten/Kota)

#. **Kordinator Wilayah (EC)**
   
   * Access depend on the district (Kabupaten/Kota)
   * 1 EC can have many district (Kabupaten/Kota)
   * 1 district can have only 1 EC
   * 1 EC can have many Mitra/Sales (Kabupaten/Kota)
   * List of menus in /backoffice:

     - Pelanggan

       - Daftar Pelanggan
       - Belum Order
     - Pesanan

       - Daftar Pesanan
       - Offline
       - Mitra Penjualan

         - List Sekolah
         - List Prospek Mitra
       - Laporan (with selected date range), result only for they district (Kabupaten/Kota) data
       - Mitra

#. **Sales/Mitra (ER)**
   
   * Related to one Korwil (EC)
   * List of menus in /backoffice:
     
     - Pesanan
       
       - Daftar Pesanan
       - Offline
     - Mitra Penjualan
       
       - List Sekolah
       - List Request

#. **Logistik [Not common used]**
   
   * Not used anymore

#. **Finance**
   
   * List of menus in /backoffice:
     
     - Finance
       
       - Sekolah Belum Lunas
       - Sekolah Lunas
         
         - Semua Inputan
         - Laporan Stok
         - Laporan Stok Rupiah

#. **Account Payable (AP)**
   
   * Same access like Finance, but read-only
   * List of menus in /backoffice:
     
     - Finance
       
       - Sekolah Belum Lunas
       - Sekolah Lunas
       - Semua Inputan
       - Laporan Stok
       - Laporan Stok Rupiah

#. **Regional Sales Manager (RSM)**
   
   * Typically same like Kordinator Wilayah (EC)

#. **Admin Supply Chain Management (SCM)**
   
   * Responsible for approval  process in SCM, access through /backmin
   * List of menus in /backmin:
     
     - Pesanan
       
       - Pesanan Masuk
       - Pesanan Diproses
       - Permintaan Stok
         
         - Permintaan Masuk
         - Permintaan Diproses
       - Laporan
         
         - Lihat Summary Stok
         - Lihat Supply Chain

#. **Gudang (Site/Warehouse)**
   
   * Responsible for process the order, start from preparing, packing, until deliver to school
   * List of menus in /backmin:
     
     - Pesanan Sekolah
       
       - Pesanan Masuk
       - Pesanan Diproses
     - Permintaan Stok
       
       - Request Stok
       - Request Intan
       - Barang Masuk
       - Barang Keluar
     - Pengiriman
       
       - Daftar Pengiriman
     - Laporan
       
       - Lihat Stok (only for they warehouse)
