# 문서 인덱스

문서 ID: AG

이 파일에는 문서 인덱스와 공통 응답 규칙만 작성한다. 


- [PO: Project Overview](agents/project_overview.md)
- [CP: Commit Push Rules](agents/commit_push_rules.md)
- [DW: Document Writing Rules](agents/document_writing_rules.md)
- [IP: Information Processing Practical Memorization Rules](agents/information_processing_practical_rules.md)
- [PE: Past Exam Markdown Rules](agents/past_exam_markdown_rules.md)

## 문서 읽기 기준

- 정보처리기사 실기 암기 문서를 작성, 수정, 분리, 정리할 때는 `IP`만 읽음
  - 대상: `노트/정보처리기사_실기_암기/` 하위 파일
  - `DW`, `PE`는 함께 읽지 않음
- 프로젝트 목적이나 자료 분류 기준 확인이 필요할 때는 `PO`를 읽음
- 커밋, 푸시 요청을 받았을 때는 `CP`를 읽음
- 일반 `노트/*.md` 개념 정리 문서를 작성하거나 수정할 때는 `DW`를 읽음
  - 정보처리기사 실기 암기 문서는 제외
- 기출문제 markdown 작성, 변환, 풀이 형식 정리가 필요할 때는 `PE`를 읽음
  - 정보처리기사 실기 암기 문서는 제외

## 공통 응답 규칙

- 요청 처리 시 읽은 문서가 있으면 응답에 문서 ID만 짧게 표시
  - 예: `읽음: DW, PE`
  - 파일명을 길게 나열하지 않음
