# AplikasiPenambahanDuaAngka
 latihan 1 
 
nama   :Adiyatma saputra

npm    :2210010115

kelas  :5B nonreg banjarmasin

matkul :pemograman berbasis objek 2


1.disini saya membuat aplikasi menghitung dua angka,dengan menggunakan "JFrameform" sebagai tampilan utama aplikasi

2.pada "JFrameform" saya menambahkan komponen "GUI" antara lain:

-"jpanel" sebagai tempat kompunen

-"jlabel" untuk 'angka satu','dua',dan 'hasil'

-"jtextfield" untuk memasukan angka 'satu''dua'dan'hasil'

-"jbutton" untuk tombol 'tambah''hapus'dan'keluar'

3.menambahkan koding pada tumbol "tambah""hapus"dan"keluar"

-tambah
  
   private void jButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                         
      
        try {
    int angka1 = Integer.parseInt(txtAngka1.getText());
   
    int angka2 = Integer.parseInt(txtAngka2.getText());
   
    int hasil = angka1 + angka2;
   
    txtHasil.setText(String.valueOf(hasil));

} catch (NumberFormatException e) {
  
    JOptionPane.showMessageDialog(this, "Masukkan angka yang valid", "Error", JOptionPane.ERROR_MESSAGE);
}


-hapus
  
   private void jButton2ActionPerformed(java.awt.event.ActionEvent evt) {                                         
        
        txtAngka1.setText("");

txtAngka2.setText("");

txtHasil.setText("");

txtAngka1.requestFocus();
    }                 

-keluar

 private void jButton3ActionPerformed(java.awt.event.ActionEvent evt) {                                         
     
        System.exit(0);
    }                                        



