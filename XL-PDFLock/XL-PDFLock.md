# XL-PDFLock - 엑셀 PDF 자동 암호화

> 🎯 **XL-DailyPayroll V.1.0**  
> PDF 파일의 암호 상태를 확인하고, 설정한 옵션에 따라 자동으로 암호화·해제·재암호화할 수 있는 Excel 기반 자동화 도구입니다.
> 파일 단위로 원하는 PDF이름으로 암호 설정과 해제를 손쉽게 수행할 수 있어, 대량 PDF 처리에 효율적입니다.
>  
> 🔧 주요 기능
> - 원본 PDF 폴더에서 PDF 파일 리스트 자동 불러오기
> - PDF 파일의 암호화 여부를 검사하고, Locked / Unlocked 상태를 표시
> - 선택옵션(암호, 해제, 변경)과 파일명을 지정해 대량 PDF 처리
> - 에러 감지 및 로그 표시

※ 이 도구는 [qpdf](https://github.com/qpdf/qpdf) 엔진을 기반으로 작동하며, Excel에서 `qpdf.exe`를 호출해 PDF 암호화·해제·재암호화를 수행합니다.

***
## 파일 다운로드
[XL-PDFLock_V0.1.zip 다운로드](https://github.com/vveekzero/AutoHR/raw/refs/heads/main/XL-PDFLock/Files/XL-PDFLock_V1.0.zip)
※ zip 압축 파일입니다. 반드시 압축을 풀고 사용하세요.

## 파일 사용법
| Sheet | Contents |
|:------|:----------|
| Overview | 개요 |
| Regulation | 일용근로자 관련 법령 및 정의 및 내부 운영 지침 |
| 0.Setting | 일용근로자 급여계산설정 |
| 1.EE_List | 일용근로자 인적사항 |
| 2.WorkLog | 일용근로자 근무기록입력 및 급여계산 |
| 3.Payslip | 일용근로자 급여명세서 |
| 4.PaySummary | 일자별 지급내역 정리 |
| 5.Tax_SI | 원천세 신고 & 4대보험 신고를 위한 정리 |
| 6.Accounting | 회계전표 양식으로 변환 |

