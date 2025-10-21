# test
BuildOnBASE

# clone repo มาก่อน
git clone https://github.com/ชื่อผู้ใช้/ชื่อrepo.git

cd ชื่อrepo

# แก้ไฟล์ / สร้างไฟล์
echo "Hello World" > test.txt

# สั่งให้ git จำไฟล์นี้
git add test.txt

# commit ครั้งแรก
git commit -m "add hello world file"

# ส่งขึ้น GitHub
git push origin main
