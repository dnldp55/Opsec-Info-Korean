# -Opsec 백서 한국어판-

---

<img src="Qubesosoverviewv2.jpg" style="width: 70%;">

0. 익명성, 항상 침목과 자신과의 비밀을 존중, 실수 하지 않기, 무감정 상태 유지
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
13. 하드, 등 기억장치를 빠르게 날릴수 있는 버튼 설정 

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

[Bunny CDN | Hop on the Fastest Content Delivery Network!]
(https://bunny.net)
<p>
대용량 CDN 파일 전송 (2주 무료) / 익명 이메일 사용 
  
<p>
[Anonymous File Upload]
(https://anonfiles.com/)
<p>
익명 파일 업로드

<p>
[VirusTotal]
(https://www.virustotal.com/gui/home/upload)
<p>
파일 바이러스 검사 (파일 내려받을때 검사 필수)

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
  
## 저장 매체

Nitrokey Storage 2 <p>
yubikey (오픈소스가 아님) <p>
5 NFC가 활성화된 Bitwarden

---
  
## 이중 인증 

SMS 기반 2FA, Google OTP 금지!! <p>
Authy 또는 Aegis OTP 사용

