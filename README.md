# -Opsec 백서 한국어판-

---

<img src="Qubesosoverviewv2.jpg" style="width: 70%;">

<b>0. 익명성, 항상 침목과 자신과의 비밀을 존중, 실수 하지 않기, 무감정 상태 유지 
1. 노트북 또는 라즈베리파이, 기타 서브 컴퓨터 사용 (자신의 컴퓨터 절대 사용금지)
2. 공용 와이파이 사용 또는 유료 VPN 이용
3. Windows 사용 금지 (Qubes, Whonix + Kali, Tails 사용)
4. "영어대소문자, 숫자, 특수기호"가 모두 포함된 16자리 이상 패스워드 사용
5. 무료 VPN 사용 금지, 유료 VPN 사용 (Mullvad, Proton, Tor)
6. 불법 행위를 하는 경우 소셜 미디어에 게시하거나 사진, 등을 찍는 흔적을 남지 않기.
7. 파일 내려 받을때 반드시 VirusTotal로 의심스러운 파일을 검사
8. 암호화 알고리즘이 사용된 VeraCrypt로 하드 암호화 (BitLocker 절대 사용 금지)
9. 프로그램 실행전 sandboxie 통한 가상화 사전 프로그램 실행
10. OS, VM 설치 할땐 암호화된 저장매체에 이용 (Nitrokey, Yubikey)
11. 2FA/MTA 구글 OTP 사용 금지 Authy 또는 Aegis OTP 사용
12. 암호 기록시 BitWarden 이용 
13. 하드, 등 기억장치를 빠르게 날릴수 있는 버튼 설정</b>

## Opsec 백서 2022 한국어 

---

## 기기 및 운영체제

자신의 컴퓨터는 절대 사용하면 안될것<p>
노트북 또는 X86 지원되는 SBC 사용한다.<p> 
<br>
ODYSSEY - X86J4105 (이 제품은 실제로 Qubes를 구현해낸 x86 SBC이다.)<p>
(https://www.seeedstudio.com/blog/2020/05/26/qubes-os-security-oriented-operating-system-and-run-qubes-os-on-odyssey-x86j4105/)<p>
ODROID - H3+ (이 제품은 최근이 나온 x86모델중 사양이 가장 좋다.)<p>
이외에도 라떼판다, RockPI 등이 있다.
<br>
노트북은 중고 제품 써도 된다. 그리 좋은 사양은 필요 없다.<p>
일반적으로 공용 와이파이를 사용하거나 AirCard 사용하는것이 좋다.<p> 
<br>
권장 OS는 Whonix, Qubes, Tails 이렇게 3가지 이다.<p>
보통 VM를 통해서 Whonix+Kali 환경을 사용하는 것을 추천한다.<p>
추가적으로 MAC주소 노출에 민감하다면 Qubes+Whonix 환경을 세팅하면된다.<p>
Qubes가 유일하게 MAC 주소 익명화를 제공하기 때문이다.<p>
</br>

---
## 저장 매체

Nitrokey Storage 2 (오픈소스 : 개인정보 수집을 하지 않기 때문) <p>
yubikey (오픈소스가 아님) <p>
5 NFC가 활성화된 Bitwarden

---
  
## 유료 VPN

mullvad VPN, Protonvpn  사용 (타 VPN 소유중 이라면 VPN + Tor)<p>
<br>
(무료 VPN은 절대금지!!)<p>
(mullvad VPN 경우 제 3자를 통해 구입 XMR 지불 하는것이 안전)<p>
<br>
https://digitalgoods.proxysto.re/
https://mullvad.net/en/blog/2022/6/22/vpn-server-audit-found-no-information-leakage-or-logging-of-customer-data/

---


## 파일 업로드
<br>
대용량 CDN 파일 전송 (2주 무료) / 익명 이메일 사용<p>
[Bunny CDN | Hop on the Fastest Content Delivery Network!]
(https://bunny.net)
<br>
  
익명 파일 업로더
[Anonymous File Upload]
(https://anonfiles.com/)<p>
<br>
  
파일 바이러스 검사 (파일 내려받을때 검사 필수)<p>
[VirusTotal]
(https://www.virustotal.com/gui/home/upload)<p>


---
  
## 비트코인 거래시

XHV 또는 XMR(모네로) 사용

[온라인 지갑]<p>
Railgun Aztec(zk.money)와 SCRT
[Overview - Safe](https://gnosis-safe.io/)<p>
[하드웨어 지갑]<p>
[Ledger](https://shop.ledger.com/products/ledger-nano-x?r=8b49b9c6f1fe&tracker=checklist),
[Trezor](https://shop.trezor.io/?offer_id=10&aff_id=1181)
  
---
  
## 대화 매체

Nicegram (텔레그램) 이용<p>
https://my.nicegram.app/login?lng=ko <p>
자기 번호 절대 금지<p>

---
  
## 1회성 혹은 임시 이메일

Tutanota <p>
https://tutanota.com/ <p>
Protonmail <p>
https://proton.me/ <p>
랜덤 아이디/패스워드 이용 <p>

---
  
## 이중 인증 

SMS 기반 2FA, Google OTP 금지!! <p>
Authy 또는 Aegis OTP 사용

---
  
## 압수 수색 영장
  > 만약 경찰이 압수수색 영장을 들고 집에 들어온다면
> 

위에 안티포렌식 글에 있는 암호화 부터 정독 후 암호화 설정을 전부 끝마치고 오길 바랍니다.

안드로이드

- 전원을 내립니다.
- 만약 화면을 보기 힘든 상황일 때 "전원 버튼 + 볼륨 내림 버튼 길게 홀드"하면 기기가 재부팅 되면서 비밀번호 없이 접근이 불가능해집니다.

아이폰

- 전원을 내립니다.
- 아이폰6s 까지: 전원 버튼 + 홈 버튼 홀드
- 아이폰7: 전원 버튼 + 볼륨 다운 버튼 홀드
- 아이폰8,X 이후: 볼륨 버튼 위 아래 한 번씩 짧게 누른 후 전원 버튼 홀드 (이해 안되면 검색)

윈도우

- 전원을 내립니다 (전원 버튼 홀드)
- (베라크립트 사용 시) 베라크립트 > 설정 > 단축키(Hot keys) > "강제 모두 제거, 캐시 지우기, 끝내기(Force Dismount All, Wipe Cache & Exit)" 단축키 미리 설정한 후 컴퓨터 켜져 있는 상태에서 들이닥치면 단축키 바로 사용하기!!!
랩톱(노트북)같은 경우 단순히 덮는 것만으로 제대로 락이 걸리지 않습니다. 시스템 종료를 습관화 합시다.

전원 꺼진 후 시간을 끌 수록 더 복구가 힘들어집니다.

법 지식도 알고 있어야 경찰의 편법에 넘어가 걸레될일 없습니다.

디지털 포렌식 당할 때
[https://youtu.be/f6rWwRVrRFo](https://youtu.be/f6rWwRVrRFo)

묵비권 행사하기
[https://youtu.be/oy41Q2VqrNw](https://youtu.be/oy41Q2VqrNw)

---
## 수사 시나리오

**최악의 시나리오: 경찰 수사**

경찰이 당신에게 연락하는 경우, 웬만해서는 경찰은 당신의 전화번호를 알지라도,

당신이 텔레그램이란 메신저를 통해

직접 아동청소년 음란물을 주고받았다는 증거, 아동청소년 음란물을 소지하고 있다는 증거 같이,
  
당신을 **유죄판결 내릴 수 있는 효력 있는 증거는 연락 당시 경찰이 가지고 있지 않을 가능성이 큽니다.**

이 상황에서 경찰 조무래기한태 쫄아서 다 자백해버린다면, 당신이 증거를 만들어준겁니다.

풀릴 수도 있는게 대부분인데...

그러니 다 자백해서 형량 낮출 생각 섣부른 판단 하지 마세요. 없었던 형량를 만들어낼 수 있습니다.

**대한민국 사법에는 무죄추정의 원칙, 증거재판주의가 있습니다.**

당신이 범죄를 저질렀다는 증거가 있어야 범죄자가 되지, 저지른 증거가 없다면 증거불충분으로 풀려나옵니다.

아래 유튜브 강의 영상 잘 숙지하고, 경찰에 대한 침착한 대응 기대합니다.

경찰서에서 전화가 온다면

[https://youtu.be/Oo0VF4tiL5A](https://youtu.be/Oo0VF4tiL5A)

디지털 포렌식을 당한다면

[https://youtu.be/f6rWwRVrRFo](https://youtu.be/f6rWwRVrRFo)

묵비권 행사

[https://youtu.be/oy41Q2VqrNw](https://youtu.be/oy41Q2VqrNw)

불법 수사 대비

[https://youtu.be/GPeEin-QIDI](https://youtu.be/GPeEin-QIDI)

[https://youtu.be/FI6Mhu48XuQ](https://youtu.be/FI6Mhu48XuQ)

[https://youtu.be/g9-3dy70I_M](https://youtu.be/g9-3dy70I_M)

[https://youtu.be/sg_1oPYAnUc](https://youtu.be/sg_1oPYAnUc)

나홀로 경찰•검찰 수사

[https://youtu.be/0CSki7kS80M](https://youtu.be/0CSki7kS80M)
