# Whack-a-Mole
2015-1학기 모바일서비스플랫폼 3조 팀프로젝트 - 07김낙현, 10김주수, 10윤대현

cocos2D-X 로 만든 두더지 게임입니다.

Tizen IDE 에서는 libcocos2dx와 여기의 cpp-empty-test를 import한 후
libcocos2dx를 먼저 빌드하고 cpp-empty-test를 빌드하고 실행해주면 됩니다.

libcocos2dx가 용량제한으로 업로드 되지 않아 cpp-empty-test만 업로드했습니다.
cocos2D-X는 타이젠용으로 3.5버전이 릴리즈 된 것을 사용했습니다.
참고: http://blog.cocos2d-x.org/2015/04/cocos2d-x-v3-5-for-tizen-released

위 링크글에 댓글처럼 white screen issue가 있어 댓글과 같이 CCApplication-tizen.cpp파일의
elm_config_accel_preference_set(gl_mode); 코드를
elm_config_accel_preference_set(“opengl”); 로 바꿔주었습니다.
