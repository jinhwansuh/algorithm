 배열과 연결리스트는 메모리에서 차이가 난다.

# 배열
배열은 순차적으로 들어가기에 연속적으로 사용;
- 배열 요소삭제 O(n) - 삭제하고 땡기기 위해
- 추가 O(n) - 추가하고 뒤로 밀기때문에

# 연결리스트
- 연결리스트는 메모리를 알기위해 포인터를 사용.
- 삭제 - 삭제를 골랐다면 이전 요소가 삭제할 요소 다음요소에 연결 (이 로직은 상수시간 소요)
- 추가 - 추가할 요소의 포인터를 추가할 요소 다음 요소에 연결, 이전 요소의 포인터를 추가할 요소 포인터에 연결;
- 찾기 - 헤드포인터에서 시작, 해당 요소가 우리가 찾는게 아니면 다음으로 넘어감 O(n);


# Singly Linked List

Head 에서 Tail까지 단방향으로 이어지는 연결 리스트;

헤드 포인터 (첫번째 출발점) 
포인터 영역 Null (연결 리스트의 끝)



