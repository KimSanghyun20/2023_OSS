# 3주차 git   
_____________________________________________

## 이미지   
![kau](https://raw.githubusercontent.com/nparkcourage/2023-kau-0504/main/w3/2023_OSS/img/kau/kau.png?token=GHSAT0AAAAAAB7WH52EHHGNFF7HOGZDF5PYZA3CEIA)





## LMS 링크   
[LMS](https://lms.kau.ac.kr/login.ph)   

## Progit링크   
[Progit](https://git-scm.com/book/ko/v2)   

### 주요 git 명령어
- add: 파일을 추적 대상으로 포함시킬 때, 또는 커밋 대상으로 포함시킬 때 사용 ex) git add   
- commit   
- branch   
- merge    
- status   
- log ex) git log   
______________________________________________

## 2주차 숙제   
```bash
 1 #!/bin/bash
 2 Name="김상현"
 3 S_I="2020126012"
 4 F_P=$(find /home/kau2/ -name 'w2_homework.txt' 2>/dev/null)
 5 L_N=$(cat $F_P | wc -l)
 6 L_L=$(cat $F_P |tail -1)
 7
 8
 9 echo "__________"
10 echo "name"
11 echo "$Name"
12 echo "__________"
13 echo "student id"
14 echo "$S_I"
15 echo "__________"
16 echo "file path"
17 echo "$F_P"
18 echo "__________"
19 echo "line number"
20 echo "$L_N"
21 echo "__________"
22 echo "last line"
23 echo "$L_L```
