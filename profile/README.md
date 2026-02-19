# HOTSPOT 🔥
## 가족 중심의 스마트 데이터 플랫폼
HOTSPOT은 가족 단위 데이터 사용을 실시간으로 통합 관리하고, 역할(부모·자녀·관리자)에 따라 정책 기반으로 데이터 사용을 제어할 수 있는 플랫폼입니다.
가족 구성원이 동시에 데이터를 사용하더라도 잔여량 소진 시점과 차단 적용이 일관되게 동작하도록 설계했으며, 트래픽 시뮬레이터 기반의 이벤트 처리로 **대용량 실시간 환경(가상 사용자 100만 / 가족 그룹 25만)**을 가정해 구현했습니다.

### ⚙️ 핵심 기능
- 가족 통합 대시보드: 실시간 잔여 데이터 / 구성원별 사용 비중 시각화
- 부모 정책 제어: 사용자별 한도 조절, 즉시 차단, 시간대별 차단 정책 적용
- 알림 시스템: 잔여량 50% / 30% / 10% 구간 소진 알림
- 백오피스 관리: 정책 CRUD, 가족 그룹/구성원 권한 관리, 정책 변경 즉시 반영
- 실시간 트래픽 처리: 데이터 사용 이벤트를 스트리밍으로 처리하고 정책 적용 결과를 검증

### 💾 Repositories
- `HOTSPOT-FE`: [사용자/관리자 클라이언트(웹) 레포지토리](https://github.com/HOTSPOT-pro/HOTSPOT-FE)
- `HOTSPOT-USER-BE`: [사용자 기능 서버 레포지토리](https://github.com/HOTSPOT-pro/HOTSPOT-USER-BE)
- `HOTSPOT-ADMIN-BE`: [관리자 기능 서버(백오피스) 레포지토리](https://github.com/HOTSPOT-pro/HOTSPOT-ADMIN-BE)
- `HOTSPOT-KAFKA`: [트래픽 처리 및 이벤트 스트리밍(Kafka 기반) 레포지토리](https://github.com/HOTSPOT-pro/HOTSPOT-KAFKA)
