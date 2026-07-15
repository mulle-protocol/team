# Mulle 팀 멤버 소개 — 원알렉스 (Alex Won)

## 멤버 개요

본 프로필은 원알렉스가 백엔드 및 블록체인 코어 개발 역량으로 참여하는 Mulle 팀원 소개서입니다. Substrate 기반 EVM 호환 체인의 노드와 Rust로 작성된 크로스체인 릴레이어를 실제로 설계·구현해 온 경험을 바탕으로, GIWA와 외부 체인을 잇는 코어 인프라 및 브릿지/릴레이어 계층을 빠르게 구축·검증합니다.

| 구분 | 내용 |
| --- | --- |
| 이름 | **원알렉스 (Alex Won)** |
| 역할 | Backend |
| 국적 | 미국 |
| 활동 지역 | 서울, 대한민국 |
| 경력 | 블록체인 개발 6년 |
| 주요 분야 | Substrate/Polkadot SDK, EVM 호환 체인, Cross-chain Relayer, Rust 블록체인 코어 |
| 언어 | 영어(원어민), 한국어(원어민) |

## 빌더 소개

원알렉스는 블록체인의 가장 아래 계층인 노드 코어와 크로스체인 통신 계층을 직접 구현해 온 엔지니어입니다. Rust를 중심으로 Substrate 기반 EVM 호환 체인의 합의·런타임·네트워킹 구성요소를 다루고, 서로 다른 체인 간 트랜잭션과 데이터를 안전하게 전달하는 릴레이어를 설계·운영하는 데 강점이 있습니다.

## 핵심 강점

### 1. 프로덕션 레벨 블록체인 코어 개발 경험

- Substrate/FRAME 프레임워크 기반 EVM 호환 블록체인 노드(bifrost-node) 개발 참여 — libp2p 네트워킹, Aura 블록 생성, GRANDPA 파이널리티, FRAME pallet 아키텍처 등 코어 컴포넌트 전반을 다룸
- Rust, TypeScript, Solidity를 아우르는 멀티 레이어 구현 경험

### 2. 크로스체인 릴레이어 설계·구현 역량

- Bifrost Network의 Cross-Chain Communication Protocol(CCCP)을 구현하는 릴레이어(bifrost-relayer.rs)를 Rust로 직접 개발 — Ethereum, BSC, Polygon, Base, Arbitrum, Bitcoin, Core, Oasys 등 다수 체인과의 크로스체인 트랜잭션 처리 및 가격 정보 등 데이터 전파 경험
- 이 경험은 GIWA ↔ 외부 체인 간 릴레이어·브릿지 신뢰 구조를 실제 코드 레벨에서 구현하는 작업과 직접 연결됨
- BRP(Bitcoin Relay Protocol) 구현 — CCCP를 활용해 Native Bitcoin 브릿지 프로토콜을 직접 구현, BTC와 EVM 호환 체인 간 자산 이동을 지원
- CCCP를 활용한 메시징 프로토콜 설계 및 릴레이어 구현 — 단순 자산 브릿지를 넘어 체인 간 데이터 전달이 가능한 범용 메시징 계층까지 설계·구현

### 3. 이더리움 코어 클라이언트 이해

- Paradigm의 Rust 기반 실행 클라이언트 reth, Sigma Prime의 Rust 기반 컨센서스 클라이언트 lighthouse를 다루며 이더리움 프로토콜 레벨에 대한 이해를 지속적으로 확장

### 4. DPoS 기반 블록체인 네트워크 구현 및 운영 경험

- DPoS(Delegated Proof of Stake) 컨센서스 기반 블록체인 네트워크의 구현 및 실제 운영 경험 보유

## 주요 경력 및 프로젝트 경험

### PILAB Technology, Inc. — Blockchain Software Engineer

**2020.09 – 현재 · 5년 11개월**

대한민국 서울

Bifrost Network(EVM 호환 멀티체인 블록체인)의 코어 인프라를 개발했습니다.

- bifrost-node — Substrate 기반 EVM 호환 블록체인 노드
- bifrost-relayer.rs — Cross-Chain Communication Protocol(CCCP) 기반 릴레이어
- BRP (Bitcoin Relay Protocol) — CCCP를 활용한 Native Bitcoin 브릿지 프로토콜

주요 업무는 블록체인 노드 코어 구현, DPoS 네트워크 구현·운영, 합의·런타임 모듈 개발, 크로스체인 릴레이어 및 메시징 프로토콜 아키텍처 설계, 멀티체인 RPC 연동, 프로토콜 레벨 안정성 확보입니다.

## 기술 역량

| 영역 | 기술 및 경험 |
| --- | --- |
| Blockchain Core | EVM/Solidity, Rust, Substrate, FRAME, libp2p, Aura, GRANDPA, Consensus |
| Cross-chain | Cross-Chain Communication Protocol(CCCP), BRP(Bitcoin Relay Protocol), 크로스체인 메시징 프로토콜, 멀티체인 RPC 연동 (Ethereum, BSC, Polygon, Base, Arbitrum, Bitcoin, Core, Oasys) |
| Ethereum 클라이언트 | reth (실행 클라이언트), lighthouse (컨센서스 클라이언트) |
| Backend | Rust, TypeScript, Node.js |

## 연락처

- Email: [dnjscksdn98@gmail.com](mailto:dnjscksdn98@gmail.com)
- GitHub: [github.com/dnjscksdn98](https://github.com/dnjscksdn98)
- LinkedIn: [linkedin.com/in/alexwon98](https://www.linkedin.com/in/alexwon98/)
