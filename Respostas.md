p1-b:

tar -xzvf challenges.tar.gz

p2-b:

cd challenges

p3-b:
ls

p4-b:
mkdir foo

p5-i:
mkdir -p foo/bar/1/2/3

p6-b:
rm -r foo

p7-b:
echo "Hello World"

p8-b:
echo "Hello World" > hello.txt

p9-b:
touch empty.txt

p10-b:
rm empty.txt

p11-i:
> empty.txt

p12-i:
echo -n > empty.txt

p13-b:
cp hello.txt goodbye.txt

p14-b:
mv goodbye.txt hello_copy.txt

p15-i:
diff hello.txt hello_copy.txt

p16-b:
cat hello.txt hello_copy.txt > 2_hellos.txt

p17-b:
pwd

p18-b:
ls -l

p19-b:
chmod 666 restricted.txt
echo "Algum texto" >> restricted.txt

p20-b:
./hello_executable

p21-b:
chmod +x challenge_20
./challenge_20

p22-b:
gcc compile_me.c -o compile_me
./compile_me

p23-a:
./redirect > output.txt

p24-b:
date

p25-b:
ps all

p26-b:
lscpu 

p27-b:
uname -r

p28-b:
grep -r "You found the needle in the haystack!" bunch_of_files/

p29-b:
head -n 25 people.csv