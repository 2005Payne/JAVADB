### ResultSet
select 문에서 조회한 결과를 저장하는 객체이다.
### rs.next()
다음 행으로 이동하고 행의 존재 여부에 따라 true/false를 반환한다.
조회한 결과는 첫번째 행의 위에서 시작되기 때문에   
첫 rs.next()를 써도 첫번째 행은 생략되지 않는다.
