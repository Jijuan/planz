# planz

[Summary]
우리는 신뢰속에서 다양한 제품들을 소비한다. 친구가 좋다고 했던 전자제품, 아버지가 물려준 시계, 셀럽이 신었던 신발을 구매하며 물건 자체의 기능과 가치를 넘어 자신이 신뢰하는 사람과 연결된 그 가치를 얻는다. 사무실 근처 김치찌개보다 어머니의 김치찌개가 맛있는 이유는 비단 맛의 차이라기보단 누가 만들었냐가 중요하지 않는가. 우리가 마시는 음료는 어떠할까, 누구는 싸고 맛있으면 된다고 하지만 내가 오늘 커피한잔 마시기 위해 발걸음을 옮기는 곳은 이전에 즐거운 미소와 함께 하루를 힘차게 시작하게 해줬던 메니져가 있던 카페가 아니었나. 플랜즈는 다양한 음료 전문가(Author)들이 직접 만든 음료(Beverage)를 밀폐용기(Keg)에 담아 사용자(User)에게 전달하는 가치를 제공한다. 제품을 제공하는 형태는 무인 자동판매기(Vending machine)이며 해당 자동판매기에는 구매 및 픽업을 돕는 키오스크(Kiosk)가 설치되어 운용된다. 자동판매기에는 총 6개의 밀폐용기(Keg)가 장착(Mount)되며 각 가격 및 기타 정보를 포함한 메뉴(Menu)로 화면에 출력된다. 제품의 노즐에 유사시 생길 수 있는 위생문제를 해결하기 위해, 노즐(Nozzle) 세척(Cleaning) 시스템이 구축되어 있으며 이는 전체 노즐을 한번에 세척할 수 도 있고 각각 노즐을 세척할 수 도 있다. 음료를 구매하는 사용자는 키오스크 화면을 통해 각 메뉴의 제작자(Author), 가공방법, 원산지, 제품 신선도등을 시각적으로 확인할 수 있으며 신용카드(Magnetic, rf, ic)와 플랜즈 머니(planz-money)를 통해 결제할 수 있다. 플랜즈 머니(planz-money)는 사용자 어플리케이션(userApp)을 통해 미리등록된 카드를 사용하여 충전할 수 있는 전자화폐이다. 사용자 어플리케이션을 통해 전자화폐 충전, 자주가는 자동판매기 등록 및 쿠폰(Coupon)을 구매 및 관리할 수 있다. 사용자 어플리케이션을 통해 상시 또는 일시로 이루어지는 다양한 이벤트(Event)에 참여할 수 있고, 쿠폰을 통해 음료 할인, 음료 사이즈 업 등 다양한 혜택을 얻을 수 있다. 이러한 서비스가 원활하게 동작하게 하기 위해 관리자(Admin)은 관리자 어플리케이션(adminApp)을 이용하여 케그 세척 및 장착 관리, 자판기를 관리할 수 있으며 이는 모든 플랜즈의 요소들은 전산화되어 관리된다는 것을 의미한다. 마지막으로 키오스크와 사용자 및 관리자 어플리케이션은 메인 서버인 파이어베이스와 통신하여 이러한 모든 작업을 수행 및 기록한다.

플랜즈 시스템은 총 5 개(Kiosk-order, Kiosk-pickUp, firebase, userApp, adminApp)로 구성된다.

