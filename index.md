[ML] Hồi quy logistic (Logistic Regression)


can tinh chuyen dong so voi frame tham chieu
=> can 1 tap diem match giua frame hien tai va frame tham chieu
(cac tap diem can o tren cac vung nen co dinh, neu can thi thiet lap cac vung tren anh)
Op 1: dang lam
- tinh 1 lan tap diem cho frame tham chieu (dung phim Space de thiet lap)
- voi moi frame moi:
  + track bang OF
  + tinh ra ma tran bien doi
=> test tham so cua cac ham

Op 1.5:
khong dung ma tran bien doi ma dung vector chuyen dong cua frame:
  - tru tung diem (hien tai - tham chieu) => vector chuyen dong
  - trung binh cac vector chuyen dong => vector chuyen dong cua frame
  - chuyen dong frame nguoc lai voi vector chuyen dong cua frame

Op 2: mo rong
can 3 tap diem
  - frame tham chieu
  - frame truoc
  - frame hien tai
Ly do: uoc luong chuyen dong cua frame hien tai so voi frame truoc se de hon so frame tham chieu
uoc luong: hien tai --> truoc --> tham chieu
save bien doi hien tai --> tham chieu ==> truoc --> tham chieu

Op 3: idea moi

Op 4:
keypoint khac: ORB, SURF,..


viet 1 doan save video tu cam that, co rung lac => 1 tap video, gam voi tinh huong quay thuc te
test video, save lai ket qua (voi trh Tracker, merge 4 cua so => 1 anh => save video)


goi y:
doc tham so tu 1 file config
doc videos tu 1 thu muc
save video ket qua ra 1 thu muc

dau ra: 1 thu muc file config + videos ket qua
