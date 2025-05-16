# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 권재현
- 리뷰어 : 김성훈


# PRT(Peer Review Template)
- [x]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - ![image](https://github.com/user-attachments/assets/36a372e2-af39-4f66-a501-3cabc19c2ff4)
    - CAM
    - ![image](https://github.com/user-attachments/assets/6ebb8584-aad3-4232-ba0c-ecd58557668c)
    - Grad-CAM
    - ![image](https://github.com/user-attachments/assets/676b0668-3147-46f4-b7f2-c0cd8985e745)
    - 100개 이미지에 대한 CAM과 Grad-CAM의 Bounding Box IOU값을 기준으로 Object Localization 성능 비교
    
- [x]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 각 코드 블럭마다 소제목으로 해당 코드 블럭의 기능과 존재 이유 등을 기술하였음.
        
- [x]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - CAM, Grad-CAM 각각 100장의 이미지를 기반으로 만들어보고 성능을 비교하여 기록으로 남겨두었음
    - ![image](https://github.com/user-attachments/assets/273551e1-e75a-4840-8bd0-940f48cb1e3b)
    - 시각화를 통해 비교 분석에 활용했으며 수치를 비교하여 객관성을 확보하는 노력을 기록해둠.
        
- [x]  **4. 회고를 잘 작성했나요?**
    - 이번 프로젝트를 진행하며 배운점, 느낀점 아쉬운점 등을 회고에 따로 남겨두었음.

        
- [x]  **5. 코드가 간결하고 효율적인가요?**
    - 여러 함수를 만들고 활용하여 실험을 진행하며 반복되는 내용을 최소화하여 간결한 코드블럭이 되도록 함.


# 회고(참고 링크 및 코드 개선)
```
주어진 내용을 충실히 이행하면서 인사이트를 찾으려는 노력이 좋았습니다. 이런 노력이 중간 중간 코멘트 등 기록되면 나중에 봐도 잘 기억나고 좋을 것 같아요.
실험을 100장을 뽑으시는 코드는 지금보니 For문을 돌면서 매번 새로 뽑으면서 중복이 되는 것으로 보이네요. 이미지 뽑는 코드만 for문 밖으로 빼면 해결이 될 것 같습니다.
첫 시작에 목차를 작성해주셔서 이후 진행 흐름을 알고 보니 더 집중도 되고 좋았던 것 같아요.
 
```
