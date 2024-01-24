# Min_MedicalBlind_Spots_Bigdata
2023-1학기 빅데이터 최종 프로젝트: 의료불균형 및 의료 사각지대 최소화 프로젝트
---
<br>

### 🛠️ 프로젝트 실행 방법
```ver1 : Git clone 이용```
1. Jupyter Notebook & Git설치
2. Jupyter Notebook 기본 경로로 이동(ex. C://JupyterProject)
3. 새로운 폴더 생성(다른 파일과 겹치는 것 방지)
4. "Git Bash Here" 클릭해 Git Bash 실행
5. 다음 명령어 입력<br>
   ```git clone https://github.com/hayannn/Min_MedicalBlind_Spots_Bigdata.git```
7. 주피터 노트북 내에서 실행
*주의 : 반드시, 데이터셋과 코드 파일이 같은 디렉터리에 존재해야 합니다.

<br>

```ver2 : ZIP 파일 이용```
1. Jupyter Notebook 설치
2. Jupyter Notebook 기본 경로로 이동(ex. C://JupyterProject)
3. GitHub Repository에서 "Download ZIP" 클릭해 압축 파일 다운로드
   ![스크린샷 2024-01-22 215720](https://github.com/hayannn/Min_MedicalBlind_Spots_Bigdata/assets/102213509/36746590-98c8-4960-a967-572df5144bd5)
4. 파일 압축 해제 및 Jupyter Notebook 기본 경로에 폴더 이동하기
5. 주피터 노트북 내에서 실행
*주의 : 반드시, 데이터셋과 코드 파일이 같은 디렉터리에 존재해야 합니다.
---

<br>

## 💊 프로젝트 설명
### 📚 프로젝트 내용 소개
<br>

[1] 병의원, 약국 데이터 분석
- 병의원 및 약국의 데이터셋을 가져오고, 전처리 후 최종 데이터셋을 지도에 출력해줍니다.
  
<br>

[2] 병의원, 약국 데이터 분석 - 랭킹
- 병의원 및 약국 데이터를 불러오고, 사용자가 특정 지역명을 입력하면 해당 지역의 데이터를 출력하는 방식입니다.
- 랭킹 데이터까지 한꺼번에 함께 보여주며, 그 결과를 이용해 해당 지역에 부족한 진료 과목을 표시해줍니다.
  
<br>

[3] 병의원, 약국 데이터 분석 - 심야 약국 정보
- 전라북도 휴일 약국 데이터를 사용해 특정 지역명을 입력하면, 해당 지역의 약국 운영시간을 파악 할 수 있도록 했습니다.
- 또한, 저녁 6시 이후의 심야 시간에도 영업을 하는 약국 정보를 표시해줍니다.
  
<br>

[4] 병의원, 약국 데이터 분석 - 전라북도 전주시 동물약국 현황 시각화
- 전라북도 전주에 위치한 동물약국 현황 데이터를 가져와 지도에 시각화해줍니다.
  
<br>

[5] 병의원, 약국 데이터 분석 - 동물 약국 현황(인천 미추홀구)
- 인천 미추홀구의 동물 약국 현황 오픈 API를 호출하는 방식을 사용하여, 지도에 시각화해줍니다.

<br>

---

<br>

### 📚 데이터 분석 결과 활용 방안 및 기대효과
[1] 분석 결과 활용 방안
- 분석 결과는 의료 사각지대를 파악하는 데 도움이 되기 때문에, 부족한 진료 과목을 보는 병원이 개설될 수 있도록 도와줄 수 있고, 위치를 기반으로 보았을 때에도 특히 병원이 부족한 곳을 파악해 병원이 개설될 수 있도록 도움을 줄 수 있기 때문에 활용 가능합니다.(약국 역시 동일)

<br>

[2] 기대효과 및 시사점
- 의료 불균형과 의료 사각지대를 최소화해 의료 관련 위협에 처해있는 많은 사람들에게 도움이 될 수 있으며, 병의원 및 약국을 개설하려는 사람에게도 객관적인 정보를 제공해 도움을 줄 수 있는 기대효과가 있습니다.
- 또한, 전국에 있는 많은 지역들이 이 데이터를 적용해 퍼져나간다면 기본적인 의료에 대한 권리를 침해받지 않고 아플 때 도움을 받을 권리를 누리며 편안하게 삶을 살아갈 수 있도록 할 수 있을 것이라는 점을 시사합니다.
  
---

<br>

### 📚 참고문헌 출처

- 기사 자료
   - [수도권 의료사각②  - 약국도 없는 동네가 있다?](https://tbs.seoul.kr/news/newsView.do?seq_800=20443545&amp;typ_800=7)
   - [우리나라 보건의료 체계의 가장 큰 문제는 '지역 간 의료 불균형'](https://www.akomnews.com/bbs/board.php?bo_table=news&wr_id=41055)
   - [늦은 밤 ‘공공심야약국’으로 달려갔습니다](https://www.korea.kr/news/reporterView.do?newsId=148914235)
   - ['우리동네 동물약국은 여기' 펫코팜 약국 찾기 웹사이트 오픈](https://www.getnews.co.kr/news/articleView.html?idxno=598745)

<br>

- 논문
   - 현재, 해당 논문의 URL을 찾을 수 없음.
   - https://hanyang.dcollection.net/public_resource/pdf/200000593576_20230416015003.pdf

<br>

- 데이터 및 API 출처
   - [건강보험심사평가원_전국 병의원 및 약국 현황](https://www.data.go.kr/data/15051059/fileData.do)
   - [전라북도_휴일약국](https://www.data.go.kr/data/15045491/fileData.do)
   - [전라북도 전주시_동물약국 정보 현황](https://www.data.go.kr/data/15058560/openapi.do)
   - [인천광역시 미추홀구_동물약국 현황](https://www.data.go.kr/data/15060767/fileData.do)

---

<br>

# 참고자료
## 📝프로젝트 계획서 및 최종 보고서
- [빅데이터 분석계획서 - 202068001 이하얀.pdf](https://github.com/hayannn/Min_MedicalBlind_Spots_Bigdata/files/14032284/-.202068001.pdf)
- [빅데이터 최종보고서-202068001 이하얀.pdf](https://github.com/hayannn/Min_MedicalBlind_Spots_Bigdata/files/14032285/-202068001.pdf)

---

<br>
<br>

## 💊 최종 발표 영상
https://github.com/hayannn/Min_MedicalBlind_Spots_Bigdata/assets/102213509/4e88da0a-005e-413b-abd0-4d078d9c94e3

---

<br>
<br>

## 💊 최종 자료
- [최종 보고서 코드 내용 설명.pdf](https://github.com/hayannn/Min_MedicalBlind_Spots_Bigdata/files/14032290/default.pdf)
- [빅데이터 최종 프로젝트 - 202068001 이하얀.pdf](https://github.com/hayannn/Min_MedicalBlind_Spots_Bigdata/files/14032292/-.202068001.pdf)

