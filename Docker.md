# Docker

:컨테이너 기술

- linux 에 최적화 됨 
- GCP(Google Cloud Platform) 사용해 실습 

# 컨테이너 기술
- app이 서로 다른 서버에 배포했을 때 동작이 다른 경우 
- 옛날, 최근 서버의 os, 라이브러리 등 버전일치가 어려움
- 같은 미들웨어를 사용하는데 서버에서 다르게 동작함 

-> app이 의존하는 os, cpu, 언어 런타임, 라이브러리를 일치 시켜줌 
-> 인프라의 가변성, 호환성이 근본적 문제인데 이를 해결 

The Matrix from hell => 도커책에서 명시하는 기존의 다양한 인프라 문제

컨테이너 = 
- 외부환경으로부터 격리된 공간에서 `프로세스`가 동작하는 기술
- app을 표준화된 단위로 패키징해 동일한 방법으로 배포하기 위한 기술 
- app의 실행코드 뿐만 아니라 외부환경을 하나로 패키징 
  (런타임, 라이브러리, configurations, etc...)
- 리눅스의 namespace, cgroups도 리눅스 컨테이너 기술이었음 

도커)
2013년에 발표 
:컨테이너 기반의 오픈소스 가상화 플랫폼 
- 다양한 프로그램, 실행환경을 컨테이너로 추상화하고 동일한 인터페이스 제공
- 프로그램의 배포 & 관리 단순화 

??? 도커 그림 하나 첨부 ??????

------------------------------------------------------------------------------------
가상머신과 차이 

