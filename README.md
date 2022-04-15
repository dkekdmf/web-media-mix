# eb-media-mix metadata 개발
웹툰, 웹 소설, 웹드라마 등 웹 콘텐츠 시장이 전 세계적으로 증가하고 있습니다. 만화책을 위한 Comic Book ontology처럼 단일 매체용 정보 모델은 존재했지만, 미디어 믹스로 인해 표현 불가능한 부분이 생겼습니다. 웹툰이 드라마화된 경우 웹툰 캐릭터와 캐릭터를 연기한 배우 간의 관계는 기존 모델로 설명이 불가능합니다. 이런 새로운 관계 및 속성에 대한 정보는 공유/개방 가능한 형태로 모델링 되지 않았었기에, 효과적으로 검색/질의/구독하기 위한 정보 데이터 모델을 만들고자 합니다.

# 미디어 믹스란?
사전적 의미는 신문이나 라디오, 잡지 또는 텔레비전과 같은 서로 다른 성격의 여러 가지 광고 매체를 적절하게 혼용하여 광고 효과를 극대화하려는 전략이다.

# 메타 데이터란?
문자적 의미로는 데이터에 대한 데이터(data about data)라고 정의되나 일반적으로 다양한 업무를 지원하기 위하여 사용되는 정보자원에 대한 구조화된 데이터를 의미하는 것으로 해석된다.

# 현재 단계 및 향후 방향
웹툰 미디어 믹스의 대략적인 구조는 설계되어 있으나, 특정 프로그래밍 언어로 표현되지 않았기 때문에 프로그램에 사용하기가 어렵습니다. 주어진 자료를 Human- and machine- readable 하며 공유 가능한 포맷으로 변환하는 작업을 수행합니다.

# 사용 도구
RDFLib을 사용하여 개념/인스턴스/관계를 모델링하고, networkx/graphviz 등을 이용하여 모델된 데이터를 시각화한다.
rdflib (https://github.com/RDFLib)
networkx (https://github.com/networkx/networkx)
graphviz (https://gitlab.com/graphviz/graphviz)

# 참고
현재 아이디어는 성소정, 최소원으로부터 시작되었습니다.
