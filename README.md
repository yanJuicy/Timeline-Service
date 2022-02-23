# Timeline Service

타임라인 서비스는 24시간 동안만 기록한 내용이 저장되는 메모장입니다.

![Untitled](https://user-images.githubusercontent.com/43159295/155364953-74c118c4-ed49-4a81-ab2b-b1671b231093.png)

| 기능 | Method | URL | Return |
| --- | --- | --- | --- |
| 메모 생성 | POST | /api/memos | Memo |
| 메모 조회 | GET | /api/memos | List<Memo> |
| 메모 변경 | PUT | /api/memos/{id} | Long |
| 메모 삭제 | DELETE | /api/memos/{id} | Long |