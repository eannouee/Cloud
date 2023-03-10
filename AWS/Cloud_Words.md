# Cloud 용어 정리 

1. Region
- 물리적으로 위착 다른 나라들을 대상으로 동일 서버를 사용하게 하면 재해 또는 불가항력으로 서버가 정지되었을 때 대처할 수 없어서 서비스를 종료해야 하거나, 물리적 거리로 인해 빠른 속도를 낼 수 없다.
- 이러한 이유로 아마존은 전세계 주요 국가에 리전을 구축하여 해당 위치에서 가장 가까운 곳에서 클라우드 서비스를 이용할 수 있도록 서비스를 제공 

2. Availability Zone
- 데이터 센터(Internet Data Center, IDC)를 의미 
- AWS 하나의 리전에 다수의 AZ을 보유하고 있고 가용 영역이 위치한 IDC는 같은 리전이라도 지리적으로 멀리 떨어져 있다.
- AZ가 떨어져 있는 이유는, 하나의 AZ이 재해, 정전, 테러 화재 등 다양한 이유로 작동불능이 되더라도 다른 AZ에 서비스를 재개할 수 있도록 하기 위함이다. 

3. Edge Location
- Amazon의 CDN 서비스인 CloudFront를 위한 캐시 서버들의 모음을 의미 
- Content Delivery Network의 약자로, 콘텐츠를 서버와 물리적으로 사용자들이 빠르게 받을 수 있도록 전세계 곳곳에 위치한 캐시 서버에 복제해주는 서비스 
- 콘텐츠를 빠르게 받기 위해 물리적으로 멀리 떨어진 서버에서 다운로드 하는 것보다, 가까운 서버에 접속하여 다운로드 받는 것이 속도가 훨씬 빠르기 때문에 CDN 서비스는 전세계 주요 도시에 캐시 서버를 구축해 놓는다.


