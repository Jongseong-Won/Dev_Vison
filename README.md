# Dev_Vison

![1](https://user-images.githubusercontent.com/24608378/113106129-5adc9d00-923d-11eb-8ffb-a64a45de18b4.PNG)


|구분|표본수|이미지수|미검|오과검|합계|약검|중복검|합계|총계|미검|검출률|정확도|비고|
|-|-|-|-|-|-|-|-|-|-|-|-|-|-
|4/1||8125|||||||||||특이사항 확인|

* 4/1 정상제품 → 링 미조립 오검 
(Object 검출 오류 개선 실패, 동일 오류 확인, 라벨링 방법 변경을 통한 개선 시도예정)
![over_detection](https://user-images.githubusercontent.com/24608378/113259595-43b6b180-9308-11eb-9830-6a7eabe9f1da.png)
* 4/1 제품 영역 외 라벨링 이슈 → 지정 영역만 검사하도록 프로그램 수정 
![over_detection](https://user-images.githubusercontent.com/24608378/113260390-2df5bc00-9309-11eb-9aa4-6825562fe4ab.png)


-----
-----
-----

|구분|표본수|이미지수|미검|오과검|합계|약검|중복검|합계|총계|미검|검출률|정확도|비고|
|-|-|-|-|-|-|-|-|-|-|-|-|-|-
|3/29|175|425|22|1|23|12|6|18|41|20.5|88.3%|95.3%||
|3/30|85|185|10|50|60|9|0|9|69|34.5|59.4%|83.8%|Edge 과검(48)|
|3/31|29|145|2|1|3|0|0|0|3|1.5|94.8%|97.9%|링없음 오검|
|3/31|||||||||||||합계중|


* 3/31 정상제품 → 링 미조립 오검 (Object 검출 오류 추정)
![1](https://user-images.githubusercontent.com/24608378/113108143-a132fb80-923f-11eb-864c-16a49267bcd4.PNG)
* 3/31 정상제품 투입 → 제전통과 → 먼지로 인한 오검
![1](https://user-images.githubusercontent.com/24608378/113107281-b3606a00-923e-11eb-8a71-46a4c049dc1a.PNG)
* 3/30 Edge과검
![over_detection](https://user-images.githubusercontent.com/24608378/112963615-8484be00-9182-11eb-9c8f-a03dfd522e2c.png)
