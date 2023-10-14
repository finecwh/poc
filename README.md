# [네트워크 APT 샘플]

## 샘플명:  good [afaj9215].zip.zip  
### 악성코드 설명  
Redaman 또는 RTM 뱅킹 트로이목마 악성코드.  
PDF 아이콘 파일로 위장된 EXE 악성파일로, "Windows Update" 명으로 Task Scheduler에 추가하여 지속성 유지  
소프트웨어나 웹 활동을 정기적으로 검사하고 명령 및 제어(C2) 서버로 데이터 유출 및 추가 악성 페이로드 다운로드를 시도함.  
  
### 감염 호스트로부터 발생되는 통신
		 
     - 104.28.16.33 port 443 - namecha.in / HTTPS/SSL/TLS traffic
	 - 94.156.189.28 port 80 / POST /index.php (Trojan.Redaman CnC Beacon)

### 상세분석 참고 및 샘플 출처 : 
<https://www.malware-traffic-analysis.net/2018/10/02/index.html>
  
  
## 샘플명: guide123^pva23g333.zip  
### 악성코드 설명 
Emotet 다운로더 악성코드   
악성 매크로를 이용하여 Emotet을 다운로드하는 문서 형태 악성코드  
(Emotet : 금융정보 탈취 악성코드의 일종으로, `크리덴셜 탈취, 네트워크 증식, 민감정보 수집' 등의 악성행위 수행.
활성화된 Emotet은 공격자와 통신을 유지하며 정보탈취 멀웨어, 랜섬웨어 등을 추가로 다운로드함)  
Phishing 및 악성사이트를 접속을 통해 추가 악성코드(Emotet)를 다운로드하는 Downloader 악성코드

### 감염 호스트로부터 발생되는 통신
	
	- 34.90.96.46 port 80 - diwafashions.com - GET /wp-admin/mqau6/ (Emotet 악성코드)

### 상세분석 참고 및 샘플 출처
<https://www.malware-traffic-analysis.net/2019/12/20/index.html>
  
  
## 샘플명: guide@pavdf123.zip  
### 악성코드 설명
Trickbot 악성코드 
사용자 PC에서 웹 브라우저 정보 및 금융거래 정보 등 민감한 정보를 탈취하는 악성행위하며, 공격자는 주로 주로 기업을 대상으로 워드프로세서 문서형태(.doc)로 유포함
keylogging 또는 크리덴셜 관련 API를 후킹하는 등의 행위 수행

### 상세분석 참고 및 샘플 출처
<https://www.malware-traffic-analysis.net/2019/12/20/index.html>
  
  
## 샘플명: invoce=(pfj1xytq9).zip  
### 악성코드 설명  
Globeimposter 랜섬웨어  
메두사락커(MedusaLocker)라는 공격자들의 유포되고 있으며 RDP(Remote Desktop Protocol, 원격 데스크톱 프로토콜)를 통해 유포되고 있는 것으로 추정  
랜섬웨어 감염시 ..doc(예를들어, `1<확장자>..doc`) 확장자로 암호화되며, 암호화된 각 폴더에 Read___ME.html 이라는 랜섬 노트 생성  
  
### 상세분석 참고 및 샘플 출처
<https://www.checkmal.com/video/read/735/?p=28&lang=ko>
  
  
## 샘플명: manual+qwerty111+.zip  
### 악성코드 설명
Ursnif 악성코드  
금융 정보 탈취 악성코드, 이메일 관련 프로그램 및 시스템에 설치된 인터넷 브라우져 계정정보를 탈취하는 악성행위 수행  
해당 악성코드는 수행한 후 추가 악성파일을 다운로드 행위를 수행함
  
### 상세분석 참고 및 샘플 충처
<https://www.malware-traffic-analysis.net/2019/07/29/index.html>
  
  
## 샘플명: pwㅤfirst123.zip  
### 악성코드 설명  
Downloader 악성코드  
악성 매크로를 이용해 추가 악성파일 다운로드 시도하는 문서(xls) 악성코드

### 감염 호스트로부터 발생되는 통신
	
	- port 443 (HTTPS) - tinyurl.com - GET /y4cpohnr
	- 217.160.0.242 port 80 - aminsanat.com - GET /wp-content/plugins/tech/LO-06.exe
	

### 상세분석 참고 및 샘플 출처
<https://www.malware-traffic-analysis.net/2021/01/06/index.html>
  
  
## 샘플명: 설계도((tjfrPeh1)).zip  
### 악성코드 설명
Remcos 악성코드  
감염된 시스템에 원격으로 작업을 수행하는 데 사용하는 RATRAT(Remote Access Trojan) 유형 악성 코드  
정보 탈취, PC 모니터링 등 악의적인 목적으로 사용  
지속성 유지를 위해 레지스트리 등록

### 감염 호스트로부터 발생되는 통신
	
	- 79.134.225.92 port 2889 - whatgodcannotdodoestnotexist.duckdns.org
	
### 상세분석 참고 및 샘플 출처
<https://www.malware-traffic-analysis.net/2021/01/06/index.html>
<https://any.run/report/1787f73acf804bff30fe863e077fb5bc9799b3cb39065534198f894757907e79/a2a97018-dbdb-4c55-b693-e7a54ec2291d/>
  
  
## 샘플명: 