# HUD Dashboard Extension for pi-coding-agent

[English](#english) | [한국어](#한국어)

---

## English

An interactive HUD (Heads-Up Display) extension for the [pi coding agent](https://github.com/badlogic/pi-mono) that provides real-time monitoring of agentic workflow status.

### Features

#### 🎯 Real-time Workflow Tracking
- **Status indicators**: Idle, Thinking, Planning, Executing, Error, Completed
- **Animated spinners**: Visual feedback during active states
- **Connection monitoring**: Heartbeat-based provider connectivity check

#### 🔧 Tool Execution Monitoring
- **Live tool call tracking**: See which tools are running, pending, or completed
- **Execution timing**: Track when tools start and finish
- **Error highlighting**: Visual indicators for failed tool executions

#### 📊 Metrics Dashboard
- **Turn count**: Number of agent turns in the session
- **Tools executed**: Total tools run since session start
- **Error rate**: Percentage of failed tool executions
- **Session duration**: Time since the HUD was initialized

#### 🔒 Security & Reliability
- **Secret redaction**: Automatically masks API keys, tokens, and credentials
- **Heartbeat monitoring**: Automatic detection of provider disconnections
- **State synchronization**: Optimistic updates and debounced reconciliation

### Installation

```bash
pi install git:github.com/tmdgusya/hud-dashboard
```

### Commands

| Command | Description |
|---------|-------------|
| `/hud-help` | Show HUD Dashboard help |
| `/hud-status` | Show current HUD status (workflow, tools, errors, heartbeat) |
| `/hud-metrics` | Toggle metrics widget visibility |
| `/hud-tools` | Toggle tool list widget visibility |
| `/hud-minimize` | Minimize or restore the HUD dashboard |
| `/hud-reset` | Reset HUD state to defaults |

---

## 한국어

[pi coding agent](https://github.com/badlogic/pi-mono)를 위한 대화형 HUD(Heads-Up Display) 확장 프로그램입니다. 에이전트의 워크플로우 상태를 실시간으로 모니터링할 수 있는 대시보드를 제공합니다.

### 주요 기능

#### 🎯 실시간 워크플로우 추적
- **상태 표시**: Idle, Thinking, Planning, Executing, Error, Completed 상태 시각화
- **애니메이션 스피너**: 에이전트가 활동 중일 때 시각적 피드백 제공
- **연결 모니터링**: 하트비트(Heartbeat) 기반의 프로바이더 연결 상태 체크

#### 🔧 도구 실행 모니터링
- **실시간 도구 호출 추적**: 실행 중, 대기 중, 완료된 도구 호출 표시
- **실행 시간 기록**: 도구 실행 시작 및 종료 시간 추적
- **에러 하이라이트**: 실패한 도구 실행에 대한 시각적 표시

#### 📊 메트릭 대시보드
- **턴 횟수**: 세션 내 에이전트 턴 수 카운트
- **도구 실행 수**: 세션 시작 이후 실행된 총 도구 수
- **에러율**: 실패한 도구 실행 비율(%) 계산
- **세션 지속 시간**: HUD 초기화 이후 경과 시간 표시

#### 🔒 보안 및 안정성
- **민감 정보 마스킹**: API 키, 토큰, 비밀번호 등을 자동으로 감지하여 가림 처리
- **하트비트 감시**: 프로바이더와의 연결 끊김을 자동으로 감지
- **상태 동기화**: 낙관적 업데이트(Optimistic updates) 및 디바운스된 상태 조정 로직 적용

### 설치 방법

```bash
pi install git:github.com/tmdgusya/hud-dashboard
```

### 명령어 안내

| 명령어 | 설명 |
|---------|-------------|
| `/hud-help` | HUD 대시보드 도움말 표시 |
| `/hud-status` | 현재 HUD 상태(워크플로우, 도구, 에러, 하트비트 등) 요약 표시 |
| `/hud-metrics` | 메트릭 위젯 표시 여부 전환 |
| `/hud-tools` | 도구 목록 위젯 표시 여부 전환 |
| `/hud-minimize` | HUD 대시보드 최소화 또는 복원 |
| `/hud-reset` | HUD 상태를 기본값으로 리셋 |

## License

MIT
