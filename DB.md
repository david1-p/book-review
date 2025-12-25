select 구에서 정한 별명은 group by에서 사용 못함!

where 구 : 행에 대한 조건 지정
having 구 : 그룹에 대한 조건 지정 

트랜잭션 : 세트(한 묶음)으로 실행돼야 할 하나 이상의 변경 처리 집합이다. 트랜잭션을 사용하면 데이터베이스 변경 처리 확정 및 취소 등을 관리할 수 있다. 
commit, rollback!
트랜잭션의 ACID 특성! : Atomicity(원자성), Consistency(일관성), Isolation(독립성), Durability(지속성) 

DBMS의 종류 : 게층형, 망형, 관계형, 객체지향형, 객체관계형으로 분류 

mysql -> model overview에서 add diagram 더블클릭하면 다이어그램 그릴 수 있음 

order by 절을 사용하면 정렬을 위해 별도의 메모리 공간 필요, 조건에 맞게 순서대로 출력되므로 시간이 많이걸림
with rollup 절 총합 또는 중간합계 계산

alter table testtbl3 auto_invrement=1000;
set @@auto_increment_increment = 3; 1000부터 3씩 증가

