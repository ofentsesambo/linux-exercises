Task 1

1) ls
Desktop Downloads Music Public Videos
Documents examples.desktop Pictures Templates
gives a list of files in the directroy

2) pwd
~$ 
shows the directory im working on

3) mkdir workspace
cd workspace 

4) ls 
there is nothing in the new directory

5) touch README.md

6) cp README.md CHANGELOG.md

task 2

1) touch exercise.md
mv exercise.md temp/
cd temp
ls
exercise.md
rm temp/exercise.md
rm: cannot remove 'temp/exercise.md': No such file or directory
cd ~
rm temp/exercise.md
cd temp
ls

task 3

1) touch umuzi.md recruits.md cohort.md

2) touch umuzi.md recruits.md cohort.md
echo "take me to church" > umuzi.md
echo "once i was 7 years old" > recruits.md
echo "once i was 20 years old my story got told" > cohort.md

3) less umuzi.md
less recruits.md
less cohort.md

4) cat recruits.md > summary.md
cat cohort.md >> summary.md
cat umuzi.md >> summary.md

5) echo " The end " >> summary.md

task 4

1) locate umuzi
/home/recruit/workspace/umuzi.md

2) locate umuzi >> search_results.md

task 5

1) cd Documents
touch pad.md

2) cd Desktop
mkdir work

3) cp ../Documents/pad.md pad_copy.md

4) locate updatedb
/etc/updatedb.conf
/etc/alternatives/updatedb
/etc/alternatives/updatedb.8.gz
/usr/bin/updatedb
/usr/bin/updatedb.mlocate
/usr/share/man/man5/updatedb.conf.5.gz
/usr/share/man/man8/updatedb.8.gz
/usr/share/man/man8/updatedb.mlocate.8.gz

5) locate pad_copy.md
/home/recruit/Desktop/pad_copy.md

task 6

1) find -name *.pdf
./Documents/Assessment Agreement IT.pdf

2) find -name *.pdf >> cohort.md


task 7

1) nano my_bio.md
2) control x to close then control y to save
3) mkdir my_file
mv my_bio.md my_file
