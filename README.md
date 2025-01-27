## Mirai
Mirai는 Python으로 제작된 디스코드 봇 입니다.  
Kuudra Gang 봇 프리미엄을 2달 사용해보고, 요금이 비싸 만들게 되었습니다.

배포하는 봇이 아닌 개인이 사용하기 위한 봇입니다.  
무료로 사용을 원하시면 '[여기](https://discord.gg/JpTdZPBPd2)' 를 클릭하여 디스코드에 참여하세요.  

Mirai는 항상 명령어를 사용한 시점에 최신 경매장 API를 요청합니다.  
실행 속도가 Kuudra Gang보다 1~3초 느리지만, 더욱 저렴한 아이템을 찾는 경우가 있습니다.
  
## Features
 - 'Attribute'를 가장 저렴한 가격에 업그레이드 가능한 조합을 찾아줍니다.
 - 'Attribute 1, 2'가 포함된 아이템을 부위와 종류별로 정렬하여 찾아줍니다.

찾은 아이템들은 uuid를 함께 불러와 '/viewauction' 명령어로 빠르게 엑세스 할 수 있습니다.

## Usage
최저가 조합을 찾을 땐 `/au` 명령어를 사용할 수 있습니다.  
사진처럼 attribute 종류와, 아이템, 시작레벨, 끝레벨 4가지의 인수를 입력하면 됩니다.<br>
![1](https://github.com/user-attachments/assets/8ef5dc78-088b-4fe2-9d61-82dc01d1bf6b)<br>

Mana Pool Chestplate를 7레벨부터 9레벨까지 강화하려 했을 때  
다음과 같이 경로를 찾아줍니다.<br>
![2](https://github.com/user-attachments/assets/2c3dd33f-0b1b-4b46-83e1-72d931994f32)<br>

Magic Find Chestplate를 9레벨에서 10레벨까지 강화하려 했을 때  
다음과 같이 경로를 찾아줍니다.<br>
![3](https://github.com/user-attachments/assets/e0931ec5-9157-4ca8-afff-5a5321303f91)<br>

또한 하단의 복사(Copy) 기능을 통해 `viewauction {uuid}` 부분을
쉽게 복사할 수 있습니다.<br>
![4](https://github.com/user-attachments/assets/3073381a-ab8a-40a3-8160-3c3c1da97ffa)<br>

Attribute가 포함된 아이템을 찾으려 할 땐, `/if` 명령어를 사용할 수 있습니다.  
아이템의 종류와 부위별로 해당 Attribute가 포함된 최저가 아이템을 찾아줍니다.  
<br>
`Mana Pool, Mana Regeneration`두 개가 포함된 갑옷을 다음과 같이 찾았습니다.<br>
![5](https://github.com/user-attachments/assets/a02d4782-737a-40d2-a2eb-ad1efa634d52)


