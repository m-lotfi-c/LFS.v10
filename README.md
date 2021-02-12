# LFS.v10
http://www.linuxfromscratch.org/

$LFS/sources

To create this directory, execute the following command, as user root, before starting the download session:

sudo mkdir -v $LFS/sources

- Make this directory writable and sticky. 
- “Sticky” means that even if multiple users have write permission on a directory, 
- only the owner of a file can delete the file within a sticky directory. 
- The following command will enable the write and sticky modes:

sudo chmod -v a+wt $LFS/sources

