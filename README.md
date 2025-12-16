# NEXUS VIRT — MAKUS DevCloud Platform

> **High-performance, multi-architecture virtualization platform for FPGA/GPU-accelerated development**  
> Based on [PXVIRT](https://docs.pxvirt.lierfang.com) • AGPLv3 Licensed • Developed by [MAKUS SYSTEMS](https://www.makus.co.kr)


## 📌 개요

**NEXUS VIRT**는 **MAKUS SYSTEMS**가 개발한 오픈소스 가상화 플랫폼으로,  
**FPGA/GPU 가속 워크로드**, **다중 아키텍처**(ARM64/LoongArch/x86_64),  
그리고 **공유형 개발 인프라**를 위한 통합 솔루션을 제공합니다.

본 제품은 [PXVIRT](https://docs.pxvirt.lierfang.com) — Proxmox VE를 ARM 및 LoongArch 아키텍처로 확장한 커뮤니티 프로젝트 — 의 소스 코드를 **포크**(fork)하여,  
MAKUS의 DevCloud 요구사항에 맞게 최적화·확장한 **AGPLv3 기반 파생물**입니다.

PXVIRT 자체는 Proxmox VE의 변형이며, **Proxmox®는 Proxmox Server Solutions GmbH의 등록 상표**입니다.  
**NEXUS VIRT는 Proxmox Server Solutions GmbH와 무관**합니다.


## 🚀 주요 기능

- ✅ **다중 아키텍처 클러스터 통합 관리**: x86_64, ARM64, LoongArch
- ✅ **FPGA/GPU 장치 직접 통과 **(PCI/USB Passthrough)
- ✅ **고성능 원격 개발 환경 지원**: Nexus VDI 연동 가능
- ✅ **확장된 API 인터페이스**: 자동화 및 DevOps 파이프라인 용이
- ✅ **국산 하드웨어 최적화**: DELL 서버, 국산 메인보드 등 지원
- ✅ **Proxmox VE 기반 웹 UI 유지** + MAKUS 전용 기능 확장


## ⚖️ 라이선스 및 법적 고지

- **기반 프로젝트**: [PXVIRT](https://docs.pxvirt.lierfang.com) (© Lierfang)
- **원본 기반**: Proxmox VE (© Proxmox Server Solutions GmbH)
- **라이선스**: [GNU Affero General Public License v3.0](LICENSE)
- **상표**: Proxmox®는 등록 상표입니다. 본 제품은 이와 무관합니다.

> **Copyright Notices**  
> Copyright © 2025 Lierfang — PXVIRT Authors  
> Copyright © 2025 MAKUS SYSTEMS — NEXUS VIRT Contributors  
> This program is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

> **소스 코드 공개 의무**:  
> AGPLv3에 따라, 본 제품을 제3자에게 배포하거나 네트워크 서비스로 제공하는 경우,  
> 전체 수정된 소스 코드를 사용자에게 제공해야 합니다.


## 📚 문서 및 지원

- 📖 **공식 문서**: [https://docs.makus.co.kr/nexus-virt](https://docs.makus.co.kr/nexus-virt
- 📧 **기술 문의**: dskim1979@makus.co.kr

---

## 🛠️ 빌드 및 배포

- 소스 코드는 내부 Git 저장소에서 관리됩니다.
- 요청 시, AGPLv3 조건에 따라 전체 소스를 제공합니다.
- ISO 이미지 및 deb 패키지는 고객 계약 기반으로 배포됩니다.

---

> **NEXUS VIRT는 오픈소스 정신을 기반으로, 투명하고 확장 가능한 가상화 인프라를 지향합니다**.
