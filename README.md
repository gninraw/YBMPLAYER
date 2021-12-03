# YBMPLAYER
## 테스트 배포를 위한 GITHUB
> 우측의 Releases 선택해서 프로그램을 다운로드 받으세요.
> 업데이트가 생기면 프로그램 시작시 업데이트 가능합니다. 


## ybm.config
> 튜토리얼 폼 번호를 변경하거나 서버 정보를 변경 할 수 있습니다.  

> 276 - 1급시험 폼번호
 
> 275 - 2급시험 폼번호
```json
{
  "DEMO_FOMR_CODE": "128",  // 튜토리얼 폼 번호
  "EXAM_FORM_CODE": "275", // 시험 폼번호
  "API_URL_BASE": "https://datadev-api.ybmit.com" // 서버 주소
  
}
```

## 로그파일
> 프로그램 오류 발생시 프로그램 폴더에 생성되는 로그 파일을 보내주시면 수정에 큰 도움이 됩니다. 
```
YbmExamMakerErrorLog.20211115.log // 오류 로그 파일
YbmExamMakerLog.20211115.log // 정보 로그 파일
```
