# tsm
Travelling Sales Man API
Exampmle:
curl --header "Content-Type: application/json" --request POST --data '[{"bars":[{"lng":"-5.923322","lat":"54.600832"},{"lng":"-5.934308594437078","lat":"54.589271103918136"},{"lng":"-5.9285263607450505","lat":"54.59325364874902"},{"lng":"-5.932592293398167","lat":"54.59209519204566"},{"lng":"-5.931405","lat":"54.593274"}]}]' http://127.0.0.1:5000/tsm


![map_2](https://user-images.githubusercontent.com/52322574/169505805-150c90e4-f71a-46c7-ba95-1a445951fae1.jpg)
![map_3](https://user-images.githubusercontent.com/52322574/169506628-72d4c7d3-80d8-48ad-8976-d34619973aac.jpg)


Should return [0,4,3,1,2]
