# Authentication API with firebase

파이어베이스 기반의 인증 API 입니다.



파이어베이스의 API를 사용해 사용자를 인증하고, 해당 파이어베이스 토큰의 유효기간 만큼 레디스에 인증 정보를 저장하여, 파이어베이스의 API의 호출 없이 레디스의 데이터 확인만으로 사용자를 인증할 수 있도록합니다.



자람 학회의 "마쉿는거" 프로젝트에서 사용할 인증 API로 개발되었으며, 아직 실사용은 하지 않아 제대로 동작하지 않는 문제가 발생할 수 있습니다.