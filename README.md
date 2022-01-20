
<div align="center"> <img width="400" alt="logo_output" src="https://user-images.githubusercontent.com/50979281/150292128-e326e1b8-5d62-4b54-8ced-4a230c8a607e.png"> 
  
  </dim>


<div align=left> 

## Members


[김민규](https://github.com/MinkyuKim26)(School of Electrical and Electronics Engineering)
<br>
[김지민](https://github.com/kjimin0619)(School of Computer Science & Engineering)
<br>
[배병현](https://github.com/bbh-pharm)(School of Pharmacy)
<br>
[이보림](https://github.com/bo-lim) (School of Computer Science & Engineering)
<br>
[장혜진](깃허브 등 프로필 링크) (소속학부)
<br>
[하희정](https://github.com/Heejung-Ha)(School of Pharmacy)

## 모델 테스트 방법

1. 레포지토리를 다운로드 받습니다
2. [학습된 가중피 파일](https://drive.google.com/file/d/1BSQtXElZyzfsNtfCARuOJ-2pfVc6cpNc/view?usp=sharing)을 다운로드 받은 뒤 레포지토리의 'Scalp_model_parameters'폴더 안에 넣습니다.
3. 터미널 혹은 cmd에서 cd '레포지토리 경로'를 입력합니다. ex) cd /Users/minkyukim/Documents/GitHub/OhMyHair
4. 'python scalp_health_minkyuKim (이미지 경로)'를 입력해 테스트 결과를 확인합니다. 


### 검증 데이터셋을 이용해 모델의 mse 구하기 

1. 리포지토리에 있는 dataset_selection()로 데이터셋에서 검증 데이터셋에 사용할 이미지를 샘플링 후 아래와 같이 검증 데이터셋을 구성합니다.

<p float="left">
<img width="400" alt="스크린샷 2022-01-20 오후 4 16 48" src="https://user-images.githubusercontent.com/50979281/150291331-708d49ad-3122-4316-9b65-f079ee055903.png"> 
<img width="400" alt="스크린샷 2022-01-20 오후 4 16 55" src="https://user-images.githubusercontent.com/50979281/150291342-b92cc659-4eca-4a55-8996-75208c1efef6.png">
</p>

2. 터미널 혹은 cmd에서 cd '레포지토리 경로'를 입력합니다. ex) cd /Users/minkyukim/Documents/GitHub/OhMyHair
3. python 'get_mse_scalp_model (검증 데이터셋 경로)'를 입력해 증상별(모낭사이홍반, 비듬 등) mse를 구합니다.
  
</div >
