#[네트워크 APT 샘플]

## 샘플명:  good [afaj9215].zip.zip  
악성 매크로가 첨부된 doc 파일, 매크로 동작시 Hancitor Loader라 불리는 Backdoor 악성코드 작동 개시,  
C2 서버: '11.116.43.91', 상세분석 *<https://malware.news/t/lets-learn-in-depth-reversing-of-hancitor-dropper-loader-2016-vs-2018-malware-progression/24179>

	Command   Description  
	"r"   Download and execute .DLL or .EXE  
	"l"   Download and execute .EXE in separate thread (arg=1)  
	"e"   Download and execute .EXE in separate thread (arg=0)  
	"b"   Download and inject code into svchost.exe  
	"d"   N/A (not implemented; used to delete itself in older version)  
	"c"   N/A (not implemented)  
	"n"   N/A (not implemented)  


## 샘플명: guide123^pva23g333.zip  
Polymorphic Autorun Worm 악성코드로, 실행 이후 이동식 드라이브등에 감염 시도하여 지속적으로 번식.   
감염시 ns1.thepicturehut.net에 접속 시도. 시그니쳐 문자열은 <PATCH2>로 Registry에 등록되는 이름. Microsoft Defender에선 Vofus로 검출중  
링크 *<https://bbs.kafan.cn/thread-2254329-1-1.html>


## 샘플명: guide@pavdf123.zip  
XClient로 알려진 백도어로, .net으로 작성되었으며 알려지지 않은 패커로 팩 되어있음. 백도어 자가삭제 및 업데이트, EXE 파일 다운로드 및 실행, 특정 URL 접속, PC 강제 종료, DDOS 공격 지시, 키로깅, 화면 캡쳐등의 기능 제공


## 샘플명:  invoce=(pfj1xytq9).zip  
GlobeImposter 랜섬웨어. Nullsoft Installer로 랜섬웨어 작동 코드를 팩해두었다


## 샘플명:  manual+qwerty111+.zip  
LoaderBot으로 명명된 백도어 악성코드. .Net으로 작성되었으며 CMD 명령실행, 파일 다운로드 및 실행, 자가 업데이트, 작업 스케쥴러 제어, 웹페이지 단축 아이콘 생성, 폴더 생성 등의 파일 작업 수행 가능. C2 서버란은 공란으로 설정 되어있음
	
	
## 샘플명:  * pwㅤfirst123.zip  
ASPack + ReflectiveLoader로 2중 팩 된 GandCrab 랜섬웨어  
링크 *<https://medium.com/@comodo_labs/in-the-crabs-claws-the-new-version-of-ransomware-hits-everyone-but-russians-111f866f2bdc>


## 샘플명:  * 설계도((tjfrPeh1)).zip  
xls 문서, 악성 매크로를 이용해 Powershell 명령을 실행.  
Powershell 명령은 특정 C2로부터 파일을 다운로드 받아서 실행하는 명령이나 현재 C2 서버 죽음
https://u.lewd.se/Q1Ftjx_yi3gf.jpg


## 샘플명:  이력서 마케팅 password market123 지원자 지원번호 12123.zip  
UPX 팩 된 백도어 악성코드. 북한의 해킹그룹 Lazarus에서 사용한것으로 추정. C2는 http://emsystec.com/include/inc.asp  
상세 기술 분석 *<https://securelist.com/lazarus-trojanized-defi-app/106195/
https://tria.ge/s?q=d65509f10b432f9bbeacfc39a3506e23&offset=2023-10-13T12%3A25%3A46.992219429Z&limit=50&button=>