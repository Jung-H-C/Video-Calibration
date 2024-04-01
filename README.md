# Video-Calibration
It's a video calibration program equipped with recording system🎥😄

***
웹캠을 이용한 영상 녹화 및 이를 보정해주는 프로그램<br>
<img width="300" alt="original_69" src="https://github.com/Jung-H-C/Video-Calibration/assets/101037538/3e7fbe00-163d-4889-af3e-b99ad349379e">
<img width="300" alt="rectified_68" src="https://github.com/Jung-H-C/Video-Calibration/assets/101037538/89eb2ce2-0600-49b3-b615-0c891410b51e">
<br>
(왼쪽: 원본) (오른쪽: 보정 후)

***
# Program 설명

![image](https://github.com/Jung-H-C/Video-Calibration/assets/101037538/abe7b911-a891-4cc7-aee8-a3c1fe6e434a)
<br>
<b>[space bar]</b>를 눌러 웹캠을 녹화합니다.
<br>
***
![image](https://github.com/Jung-H-C/Video-Calibration/assets/101037538/8124d450-3716-4499-bc48-2fd0d2bd427f)
<br>
<b>[select_img_from_video]</b>함수로 아까 녹화한 영상을 불러와 chess board의 pattern을 인지하는 이미지를 여러장 저장합니다.
<br>
***
![image](https://github.com/Jung-H-C/Video-Calibration/assets/101037538/027dfa61-4a62-4fb7-8939-9dacbf59e0b3)
<br>
<b>저장한 이미지를 바탕으로 다음과 같은 카메라 행렬과 왜곡 계수를 return 합니다.</b>
<br>
***
![image](https://github.com/Jung-H-C/Video-Calibration/assets/101037538/bb59c2bc-5129-4794-becd-97d4ef6e18ee)
<br>
<b>return된 parameter값을 바탕으로 보정된 영상과 원본 영상을 toggle하여 비교합니다.</b>





***
# Camera Calibration 결과:
<br>
<img width="800" alt="original_69" src="https://github.com/Jung-H-C/Video-Calibration/assets/101037538/6010927b-a924-4b6b-8283-c6a25bc82768">
<br>


***
# 보정 Demo:
<img width="300" alt="original_69" src="https://github.com/Jung-H-C/Video-Calibration/assets/101037538/3e7fbe00-163d-4889-af3e-b99ad349379e">
<img width="300" alt="rectified_68" src="https://github.com/Jung-H-C/Video-Calibration/assets/101037538/89eb2ce2-0600-49b3-b615-0c891410b51e">
<br>
(왼쪽: 원본) (오른쪽: 보정 후)
<br>
<img width="300" alt="original_284" src="https://github.com/Jung-H-C/Video-Calibration/assets/101037538/2dedde76-4087-4ac1-87c1-05d9182dc6f2">
<img width="300" alt="rectified_286" src="https://github.com/Jung-H-C/Video-Calibration/assets/101037538/ad415f8f-991a-42d4-82a1-0a47ae749904">
<br>
(왼쪽: 원본) (오른쪽: 보정 후)
<br>
<img width="300" alt="original_367" src="https://github.com/Jung-H-C/Video-Calibration/assets/101037538/eb127fa0-514c-4de3-a84d-8f7a5c5d76a3">
<img width="300" alt="rectified_368" src="https://github.com/Jung-H-C/Video-Calibration/assets/101037538/09795368-6fd3-4fea-9a90-81e158b9c9b8">
<br>
(왼쪽: 원본) (오른쪽: 보정 후)
<br>
