# [기본과제1]: 실습결과물 업로드
![image](https://user-images.githubusercontent.com/41908152/81331520-ae517400-90dc-11ea-909a-588d923b0c25.png)
![image](https://user-images.githubusercontent.com/41908152/81331536-b6111880-90dc-11ea-9af2-e773d79dfeed.png)
![image](https://user-images.githubusercontent.com/41908152/81331542-b9a49f80-90dc-11ea-8f60-bca76b8aa38a.png)


# [기본과제2]: itemDecoration, clipToPadding공부해보기
## 1) itemDecoration
* RecyclerView에서 item들 사이에 간격을 띄어주는 역할을 한다.
* RecyclerView.ItemDecoration class를 상속받아서 사용한다.
* 적용할곳(이번경우에는 HomeFragment.kt)에 rv_home.addItemDecoration(InstaItemDecoration(10)) 과 같은 형태로 적용한다.
* 구글링 열심히해서 간단한 것으로 찾아썼는데 사실 복잡한것들은 이해하기 어렵다ㅜㅜ 나중에 공부하고 다시 보고싶은부분!

## 2) clipToPadding
* 일반적인 padding을 적용한다면 화면에 보이는 기준으로 위, 아래에 padding이 생기고 스크롤이 동작할 수 있는 크기가 작아진다(clipToPadding=true)
* clipToPadding을 사용한다면 설정에 따라 스크롤의 가장 위 혹은 가장 아래에만 padding이 생기게 된다(clipToPadding=false)

# [성장과제]: 웹툰 뷰 짜보기
-아직 기본과제도 어려워서 조금 더 공부한 후 완성해 보겠습니다.
