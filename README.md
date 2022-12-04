# capston_chorok

구현 코드 : https://github.com/2022-GDSC-Sangmyung-Hackathon/01_chorokmaesil
학교에서 실시한 GDSC 해커톤 대회에 참가하였다. 대회 당일 주제가 주어지는 형식으로 주어진 시간은 24시간으로 그시간 내에 코드를 완성해야 하는 프로젝트이다.

처음으로 디자이너와 협업 하였고, 개발하는 사람이 아닌 다른 업무를 하는 사람과에 의사소통 능력을 기를 수 있었다.

주제는 일상에서의 역발상이였다. 예시로 네비게이션은 빠른길을 가기위해 만들어진 개발품인데 역발상으로 좀 돌아가더라도 이쁜길을 소개해주는 형식이다.

팀이 정한 아이디어로는

일상에서는 알람을 듣고 일어나지만 이것에 관한 역발상으로 알람을 자신이 듣지 않고 자신이 설정한 누군가가 알람을 듣고 깨워주는 방식으로 생각했다.

알람은 듣고 일어나야 하는데 듣지 못하여 깨지 못하는 문제들이 많다. 이 문제에 대하여 "내가 아닌 내 주변의 사람이 나를 깨워주는 것은 어떨까?" 라는 역발상을 하였다.

기존 어플과의 다른 차별성을 가지고있는 핵심기능은 친구추가 선택 기능이다.

알람 어플에 친구추가 기능이 있다는 것이 의아할수도 있지만, 당연히 울릴 알람이 울리지 않고 누군가가 대신 깨워주는 것에 초점을 맞췄다.

그래서 친구 이메일을 입력한 뒤 기본 제공 되는 이미지 중 친구 이미지를 선택할 수 있다.

친구를 선택한 뒤 시간을 설정한다. 이 기능은 친구 입장에서 수락 및 거절을 할 수 있다.

수락한다면 친구에게 설정한 시간에 알람이 울리게 된다.

파이어베이스와 안드로이드 스튜디오를 연동하여 사용하였으며 데이터베이스는 총 3개의 클래스로 구성되어있다.

사용자 데이터, 친구 데이터, 알람 시간 데이터 등을 저장한다.

이 데이터를 통해 원할하게 친구를 추가 할 수 있고, 주요 기능인 알람기능을 구현할 수 있다.

친구 리스트에서 친구를 골라 알람 설정을 하면 그 알람 데이터는 사용자에게 전달되는 것이 아니라 바로 친구에게 전달되어 그시간에 맞게 알람이 울리게 된다.

알람 기능은 알람 리시버라는 함수를 만들어서 백그라운드에서도 알람이 울릴 수 있도록 구현하였다.

전반적으로 파이어베이스 기능 및 안드로이드 개발을 담당했다.

<img width="455" alt="이미지" src="https://user-images.githubusercontent.com/79883776/205481934-b68a06e5-e91e-4120-8536-96ad69b5c74a.png">


<img width="294" alt="image" src="https://user-images.githubusercontent.com/79883776/205481926-8269ae09-67ef-4265-9871-e3ec68e7eaa2.png">

