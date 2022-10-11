# 🧬 Cancer Data Analysis
 LUAD와 LUSC 암을 잘 구분하는 유전자를 머신러닝을 이용해 추출하는 연구
 
## 📃 Analysis Resutls
**LUAD** : 폐암, **LUSC** : 폐편평상피암
LUAD와 LUSC로 예로 분석하여 결과를 나타냄


본 코드에서는 [firebrowse](http://firebrowse.org/)에 있는 암 데이터(mRNAseq)를 다운로드할 수 있음        
본 코드에서는 5가지의 모델을 사용할 수 있음

✅ **RandomForest와 LightGBM 모델에서의 암 구분 유전자**               
RandomFest : BNC1|646, C10orf99|387695, CSTA|1475, DDAH1|23576, GNA14|9630, KRT74|121391, PARD6G|84552, PRR15L|79170, PVRL1|5818            
LightGBM : BNC1|646,C10orf99|387695, CSTA|1475, DDAH1|23576, GNA14|9630, KRT74|121391, PARD6G|84552, PRR15L|79170, PVRL1|5818, TMPRSS11A|339967              

✅ **RandomForest의 중요도**                  
![image](https://user-images.githubusercontent.com/72390138/195006677-6bc92ce6-8345-4516-a8a7-a6f8625d4b55.png)                

✅ **LightGBM의 중요도**                      
![image](https://user-images.githubusercontent.com/72390138/195007262-8e10df9e-f82e-444e-bb46-a7f5f098fc81.png)             

