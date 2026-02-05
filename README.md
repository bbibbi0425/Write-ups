# 🔍 Forensics Write-ups

[![Dreamhack](https://img.shields.io/badge/Dreamhack-CTF-00ADD8?style=for-the-badge&logo=hackaday&logoColor=white)](https://dreamhack.io)
[![Forensics](https://img.shields.io/badge/Category-Forensics-red?style=for-the-badge)](.)

> 디지털 포렌식 CTF 문제 풀이 모음집  
> Windows Forensics • Registry Analysis • Disk Imaging • Browser Artifacts

## 📚 Table of Contents

- [About](#about)
- [Write-up Structure](#write-up-structure)
- [Tools & Techniques](#tools--techniques)
- [Learning Path](#learning-path)

## 🎯 About

Dreamhack 플랫폼의 포렌식 카테고리 문제들을 풀이한 write-up 저장소입니다.  
실무 포렌식 조사 절차를 기반으로 각 문제의 분석 과정, 사용 도구, 플래그 획득 방법을 체계적으로 기록했습니다.

**주요 특징:**
- 📋 단계별 상세 분석 과정
- 🛠️ 실제 사용한 도구 및 버전 명시
- 🎓 핵심 개념 및 학습 포인트 정리
- 🔍 재현 가능한 명령어 및 경로 제공


## 🛠️ Tools & Techniques

### Forensic Tools

| Tool | Version | Purpose |
|------|---------|---------|
| **FTK Imager** | v4.7.8.31 | 디스크 이미지 마운트 및 파일 추출 |
| **Registry Explorer** | v2.1.0 | Windows 레지스트리 분석 |
| **Autopsy** | Latest | 디스크 이미지 종합 분석 |
| **DB Browser for SQLite** | - | Chrome 히스토리 DB 분석 |
| **HxD / 010 Editor** | - | Hex 분석 및 바이너리 편집 |
| **binwalk** | - | 파일 내 임베디드 데이터 추출 |
| **PowerShell** | v5.1+ | 해시 계산 및 스크립트 |


## 📝 Write-up Structure

모든 write-up은 다음과 같이 일관된 구조로 작성되어 있습니다:

### 1. Challenge Info
- Challenge Name
- Category
- Difficulty Level
- Platform
- Objective (목표 및 플래그 형식)

### 2. Problem Description
- 문제 시나리오
- 제공된 파일 정보

### 3. Provided Files
- 분석 대상 파일 목록 및 형식

### 4. Tools Used
- 사용한 도구 및 버전 정보

### 5. Analysis Steps
- 5.1 초기 조사 및 파일 확인
- 5.2 주요 아티팩트 분석
- 5.3 증거 추출 및 검증
- 5.4 최종 정보 정리

### 6. Flag
- 최종 플래그 제출

## 📁 Repository Structure

```
Write-ups/
├── forensic/
└── README.md
```

---

<div align="center">

**⭐ If you found this helpful, consider starring!**

Made with 🔍 by [bbibbi0425](https://github.com/bbibbi0425)

</div>