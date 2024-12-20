# CC_MF_Success
Must run before sbatch
$ mkdir /scratch/zhang2/ServiceHost
(Generally use the next three lines is fine. as the fold already exists)
$ cd /home/zhang2/.MathWorks
$ rm -rf ServiceHost
$ ln -s /scratch/zhang2/ServiceHost ServiceHost
$ cd current directory

Then if you check with:

$ ls -l
