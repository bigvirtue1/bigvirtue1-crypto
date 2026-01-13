# bigvirtue1/crypto

## 🔐 Crypto

> **Personal encryption with a future-proof key design**  
> 미래 확장을 고려한 개인용 암호화 프로젝트

- 📦 Data is encrypted using a **random symmetric data key per file**
- 🔑 Key protection is **modular and versioned**
- 🔐 **Default**: password-based encryption (no public key input)
- 🗝 **Optional**: encrypted external key file for portability
- 📄 No external metadata files (everything is self-contained)

> Public-key and post-quantum schemes may be added later  
> **without breaking file compatibility**.

## 🔐 Crypto – Design Update (v1)

> **A personal encryption system with future-proof key design**  
> 미래 확장을 고려한 개인용 암호화 시스템

---

### ✨ Core Design Philosophy

**ENGLISH**

This project follows a **hybrid encryption architecture**  
that clearly separates **data encryption** from **key protection**.

- 📦 **Data is always encrypted with a random symmetric data key**  
  (e.g. AES-256-GCM, generated per file)
- 🔑 **Key protection is modular and versioned**  
  (password-based now, public-key based later)

This structure allows future upgrades  
**without breaking file compatibility**.

---

**한국어**

이 프로젝트는 **데이터 암호화와 키 보호를 명확히 분리한  
하이브리드 암호 구조**를 따릅니다.

- 📦 **모든 데이터는 파일마다 생성되는 대칭 데이터 키로 암호화됩니다**
- 🔑 **키 보호 방식은 모듈화되어 있으며 버전별로 확장 가능합니다**

이 구조를 통해  
**파일 호환성을 유지한 채 기능 확장이 가능**합니다.

---

### 🧭 v1 Scope (Current Focus)

- 🔐 **Default**: Password-based encryption  
  → 공개키 입력 없이 사용 가능
- 🗝 **Optional**: Encrypted external key file  
  → 이동성 및 보안 강화
- 📄 **No external metadata files**  
  → 모든 정보는 암호화 파일 내부에 포함

> Public-key encryption (KEM, post-quantum schemes)  
> is **intentionally excluded from v1**,  
> and may be added later without format changes.

---

### 🚧 Project Status

This repository reflects an **evolving v1 design**.  
Details may change as implementation progresses.

> 본 저장소는 v1 설계를 구체화하는 과정에 있으며,  
> 구현 세부 사항은 변경될 수 있습니다.

## 📢 Official Roadmap: Free Release Announcement (Within 6 Months)
I am pleased to announce that a professional-grade version of the **Bigvirtue1 Encryption Program** will be released for free within the next 6 months. This release focuses on the "Self-Extracting EXE" format to ensure that top-tier security is accessible to everyone, anywhere, without complex installations.

### ✨ Key Features of the Upcoming Free Release
* **Self-Extracting EXE:** Encrypt your data into a single executable file that can be decrypted on any machine without the Bigvirtue1 program installed.
* **7-Layer Protection (Auto-Active):** Even in the free version, a 7-layer defense code automatically activates during password entry to prevent plain-text exposure.
* **9-Layer Internal Security:** Managed by 2 passwords and 1 password file, the system internally operates 9 layers of automated seeds, tokens, and keys.
* **Zero-Trace On-Screen Viewing:** Decrypt and view memos or photos **on-screen only**. No traces are left on the hard drive, ensuring absolute privacy.
* **Drag & Drop Simplicity:** Encrypt and manage files instantly with a simple drag-and-drop interface.

### 🤝 A Message to the Developer Community
Bigvirtue1 does not aim to compete with existing encryption tools. Our goal is to contribute to the global security ecosystem by providing a new standard of **"Trace-Free Visibility"** and **"Seamless Security Portability."** We hope this project inspires other developers and enhances the safety of digital information for everyone.

---

## 📢 공식 무료 공개 로드맵 안내 (6개월 이내)
향후 6개월 이내에 상용 프로그램급의 성능을 갖춘 **Bigvirtue1 암호화 프로그램**을 무료로 공개할 예정입니다. 이번 공개는 "EXE 자동 풀림" 형식을 통해 복잡한 설치 없이도 누구나 어디서든 세계 최고 수준의 보안을 누리는 데 중점을 둡니다.

### ✨ 무료 공개 버전의 주요 핵심 기능
* **EXE 자동 풀림:** 프로그램 설치 없이도 단일 실행 파일만으로 원본 데이터를 안전하게 복호화할 수 있습니다.
* **7중 자동 보호막:** 무료 버전임에도 비밀번호 입력 시 7중 보호 코드가 자동 작동하여 단 1글자의 평문 노출도 허용하지 않습니다.
* **9중 내부 레이어:** 2개의 비밀번호와 1개의 비밀번호 파일로 관리되며, 내부적으로는 9개의 자동 난수 및 키 레이어가 입체적으로 작동합니다.
* **화면 전용 무흔적 열람:** 메모와 사진을 오직 **화면상에서만** 복호화하여 볼 수 있습니다. 하드디스크에 흔적을 남기지 않는 완전 무흔적 기술을 구현합니다.
* **드래그 앤 드롭:** 복잡한 과정 없이 드래그 앤 드롭만으로 즉시 암호화 및 관리가 가능합니다.

### 🤝 개발자 커뮤니티에 전하는 메시지
Bigvirtue1은 기존의 암호화 프로그램들과 경쟁하기보다, **"열람 시의 무흔적"**과 **"보안의 연속성"**이라는 새로운 가치를 공유하고자 합니다. 이 프로젝트가 보안 생태계에 긍정적인 영감을 주고, 전 세계 사용자의 정보를 보호하는 데 기여하기를 바랍니다.


