###### 질의 성능 향샹을 위한 Index
- 보통 조회 성능 향상을 위하여 필요한 column을 index로 등록한다
- index 처리된 column 을 조회할 때 내장함수 등을 통하여 data를 조작할 경우 성능 향상을 기대할 수 없다
- 조건절에서 성능이 느리다면 해당 컬럼을 index에 등록하는것도 하나의 해결책이 될 수 있다
