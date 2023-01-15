# MySQL

 사용할법한 sql문을 작성해보자.
 &nbsp;
 &nbsp;
 &nbsp;


 기본키가 1~10까지의 고객을 조회하라 
>  SELECT * FROM members WHERE member_id BETWEEN 1 AND 10;

&nbsp;
&nbsp;

 김씨 성을 가진 고객들을 조회하라
>  SELECT * FROM members WHERE name LIKE '김%';

&nbsp;
&nbsp;

 활동중인 고객의 연락처가 변경되어 휴면상태 고객과 중복되는 상황이 발생했다.
 중복된 연락처를 가진 고객의 이름과 연락처 정보의 레코드를 조회하라.
>  SELECT name,phone FROM members WHERE phone like %010-1111-1111%;

&nbsp;
&nbsp;

 자신의 생일인 달에 사용할 수 있는 생일쿠폰을 받을 수 있다 이번 달 생일쿠폰이 지급될 고객들을 조회하라.
>  SELECT * FROM members WHERE birthday like %12%;


