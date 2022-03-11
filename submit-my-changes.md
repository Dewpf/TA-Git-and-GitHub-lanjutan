Jawabannya

1. Fork repository GitHub https://github.com/impactbyte/tech4impact-students-bio.git menggunakan akun Github kamu
    
2. Clone remote repository dari hasil fork tersebut. Jangan clone dari repository originalnya.
   
3. Buatlah branch baru dengan nama lengkap kamu. Misalnya david-winalda. Jangan melakukan perubahan pada branch master.
    - git branch Dewita-PF

4. Checkout ke dalam branch tersebut yang telah kamu buat
    - git checkout Dewita-PF

5. Buatlah 1 file format .md dengan nama lengkap kamu. Contoh davidwinalda.md
    - touch dewitapf.md

6. Isi file tersebut dewitapf.md dengan konten di bawah ini:

Nama Lengkap: Dewita Puja Firdayanti
Umur: 24
Pesan yang ingin disampaikan: Semangat untuk kamu yang disana sedang berjuang

7. Masukkan file .md tersebut ke dalam staging area
    - git add dewitapf.md


8. Commit dengan memberikan pesan nama file .md kamu
    - git commit -m " add dewitapf.md file"
    - git push origin Dewita-PF ---> agar branch muncul di github sebelum di merge/di gabungkan dengan branch master

9. Merge branch yang telah kamu buat ke dalam branch master
    - git merge Dewita-PF

10. Push ke dalam branch master
    - git push origin master

11. Lakukan pull request dari GitHub Repository yang telah kamu fork untuk digabungkan ke dalam branch master pada GitHub Repository aslinya.

    pull request :
    - [link full req](https://github.com/impactbyte/tech4impact-students-bio/pull/104)