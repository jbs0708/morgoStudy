# Morgorithm Study
코테를 작살내기위한 스터디 입니다.

- 정기 회의 : 매주 화요일 저녁

- 마감 기한 : 매주 월요일 오후 6시


## 👥 참여자
> DaegiYeo
> 각자 연결해서 적어주삼^^

## 💁‍♂️ 스터디 규칙
### 문제 풀이
- 매주 5문제씩 해결(하루에 몰아서 하지않기), 문제 수준은 본인수준 맞춰서 ^_^
- 리뷰시간에 의견공유 및 코드 설명
- 매주 회의때 시간을 정해놓고 다들 안풀어본 문제를 풀어보도록 해봅시다.



### 리드미 규칙
사용한 알고리즘, 중요 구현 로직 및 설명, 풀이 후기

### 커밋 규칙
1. Repository clone
```
git clone https://github.com/daegi0923/morgoStudy.git
```
2. Repository open
- vscode or Pycharm
3. Branch 생성
branch는 주차별로 생성한다.
```
git checkout -b {본인의 깃허브 이름}/{주차명}
```
ex. git checkout -b daegi0923/1week

4. 문제별 디렉토리 생성 및 코드, README 저장
```
{플랫폼}/[{문제 번호}] {문제명}/본인의 깃허브 이름
```
ex. BOJ/[1759] 암호 만들기/daegi0923

5. Push
```
git add .
git commit -m "{주차명} : {플랫폼}[{문제번호}] {문제명}"
git push origin {생성한 브랜치}
```
ex. git commit -m "1week : BOJ[1759] 암호 만들기"

6. Pull request 생성
- Pull Request Name : {본인의 깃허브 이름} : [{주차명}]
> ex. daegi0923 : [1week]

- Content : 문제명, 시간복잡도
- Label : 플랫폼, 언어
- Assignees : 본인
스터디 회의 후, merge
### 리뷰 규칙
회의 전까지, 타인이 작성한 코드를 보고 평가와 코멘트 plz~
