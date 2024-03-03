
![67](https://github.com/dino-21/STEP9_Security2/assets/80396471/52d450f0-4854-4910-a541-4887ab705462)

![23](https://github.com/dino-21/STEP9_Security2/assets/80396471/6c983932-8e97-4873-9161-88838ec81775)


1 security-context.xml 수정

2 네임스페이스 확인
내가 만든 로그인 페이지

3 PasswordEncoder 문제해결
CustomNoOpPasswordEncoder.java 파일 만들기


4 security-context.xml 수정

5 기존의 테이블을 이용하는 경우
오라클에서 작업
회원관련 테이블, 
권한 테이블 설계

6 security-context.xml 수정


7 인코딩된 패스워드를 가지는 사용자 추가

8 MemberTests.java 파일 만들기


9 생성된 사용자에 권한 추가하기 

user00~user79  ROLE_USER 권한
manager80~manager89  ROLE_MEMBER 권한
admin90~admin99  ROLE_AdMIN 권한


10 쿼리를 이용하는 인증 
