# Bootcamp 2017 #3 - GIT & GITHUB

## Version of Control System

Version of control system atau singkatan `VCS` biasanya digunakan untuk memanage version dari suatu file yang biasanya berbasis text khususnya `source code` atau `coding` tapi selain itu juga bisa digunakan untuk memanage file binaary contohnya `.docx`, `.pdf`, `.png`, `.jpeg` dan lain-lain.

VCS ini tujuannya supaya kita sebagai developer dapat bekerja dengan team kita dengan mudah tanpa harus copy-paste, kirim via email `source code` yang kita tulis di komputer kita, selain itu juga dengan version of control system ini bisa menghandle ada conflik ketika `source code` yang kita tulis digabungkan dengan `source code` sesama developer istilahnya menggunakan `merge`

Ada beberapa teknologi version of control system yang beredar di pasaran yaitu:

1. [git](https://git-scm.com/)
2. subversion [SVN](https://subversion.apache.org/)
3. [mercurial](https://www.mercurial-scm.org)
4. [Bazaar](http://bazaar.canonical.com/en/)
5. [monotone](http://www.monotone.ca/)

## git is popular & easy to use

Jaman sekarang banyak developer pindah dari subversion ke git karena reabilitas dan didukung oleh komunitas yang besar yaitu open source.

## Share hosting git

1. [github.com](https://github.com/)
2. [gitlab.com](https://gitlab.com/)
3. [bitbucket.com](https://bitbucket.org/)

## Perintah dasar git

- ```git add file.extension``` atau ```git add .``` untuk melakukan indexing di sistem git
- ```git commit -m "message info"``` untuk menyimpan file secara permanen
- ```git reset stageId``` untuk mereset indexing sebelum commit
- ```git checkout branch/commitId``` untuk melakukan rewind atau switching ke branch yang berbeda
- ```git remote add nama-branch link-repo``` untuk nemanbahkan shared repository ke lokal repository
- ```git remote remove nama-branch``` untuk menghapus shared repository di local repository
- ```git push origin nama-branch``` atau ```git push -u origin master``` melakukan upload ke shared repository 
