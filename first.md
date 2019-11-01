Task 1

1)	recruit@umuzi-recruit:~$ ls
	Desktop    Downloads         Music     Public     Videos
	Documents  examples.desktop  Pictures  Templates
	recruit@umuzi-recruit:~$ 
	gives a list of files in the directroy

2)	recruit@umuzi-recruit:~$ pwd
	/home/recruit
	recruit@umuzi-recruit:~$ 
	shows the directory im working on

3)	recruit@umuzi-recruit:~$ mkdir workspace
	recruit@umuzi-recruit:~$ cd workspace
	recruit@umuzi-recruit:~/workspace$ 

4)	recruit@umuzi-recruit:~/workspace$ ls
	recruit@umuzi-recruit:~/workspace$ 
	there is nothing in the new directory

5)	recruit@umuzi-recruit:~/workspace$ touch README.md
	recruit@umuzi-recruit:~/workspace$ 

6)	recruit@umuzi-recruit:~/workspace$ cp README.md CHANGELOG.md
	recruit@umuzi-recruit:~/workspace$ 

task 2

1)	recruit@umuzi-recruit:~$ touch exercise.md
	recruit@umuzi-recruit:~$ mv exercise.md temp/
	recruit@umuzi-recruit:~$ cd temp
	recruit@umuzi-recruit:~/temp$ ls
	exercise.md
	recruit@umuzi-recruit:~/temp$ rm temp/exercise.md
	rm: cannot remove 'temp/exercise.md': No such file or directory
	recruit@umuzi-recruit:~/temp$ cd ~
	recruit@umuzi-recruit:~$ rm temp/exercise.md
	recruit@umuzi-recruit:~$ cd temp
	recruit@umuzi-recruit:~/temp$ ls
	recruit@umuzi-recruit:~/temp$ 

task 3

1)	recruit@umuzi-recruit:~$ touch umuzi.md recruits.md cohort.md
	recruit@umuzi-recruit:~$ 

2)	recruit@umuzi-recruit:~$ touch umuzi.md recruits.md cohort.md
	recruit@umuzi-recruit:~$ echo "take me to church" > umuzi.md
	recruit@umuzi-recruit:~$ echo "once i was 7 years old" > recruits.md
	recruit@umuzi-recruit:~$ echo "once i was 20 years old my story got told" > cohort.md

3)	recruit@umuzi-recruit:~$ less umuzi.md
	recruit@umuzi-recruit:~$ less recruits.md
	recruit@umuzi-recruit:~$ less cohort.md

4)	recruit@umuzi-recruit:~$ cat recruits.md > summary.md
	recruit@umuzi-recruit:~$ cat cohort.md >> summary.md
	recruit@umuzi-recruit:~$ cat umuzi.md >> summary.md

5)	recruit@umuzi-recruit:~$ echo " The end " >> summary.md


task 4

1)	recruit@umuzi-recruit:~$ locate umuzi
	/home/recruit/workspace/umuzi.md

2)	recruit@umuzi-recruit:~$ locate umuzi >> search_results.md


task 5

1)	recruit@umuzi-recruit:~$ cd Documents
	recruit@umuzi-recruit:~/Documents$ touch pad.md

2)	recruit@umuzi-recruit:~$ cd Desktop
	recruit@umuzi-recruit:~/Desktop$ mkdir work
	recruit@umuzi-recruit:~/Desktop$ 

3)	recruit@umuzi-recruit:~/Desktop$ cp ../Documents/pad.md pad_copy.md

4)	recruit@umuzi-recruit:~/Desktop$ locate updatedb
	/etc/updatedb.conf
	/etc/alternatives/updatedb
	/etc/alternatives/updatedb.8.gz
	/usr/bin/updatedb
	/usr/bin/updatedb.mlocate
	/usr/share/man/man5/updatedb.conf.5.gz
	/usr/share/man/man8/updatedb.8.gz
	/usr/share/man/man8/updatedb.mlocate.8.gz

5)	recruit@umuzi-recruit:~/Desktop$ locate pad_copy.md
	/home/recruit/Desktop/pad_copy.md

task 6

1)	recruit@umuzi-recruit:~$ find -name *.pdf
	./Documents/Assessment Agreement IT.pdf

2)	recruit@umuzi-recruit:~$ find -name *.pdf >> cohort.md

3)

task 7

1)	
