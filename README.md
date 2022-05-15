# CI/CD Guide
#. CI/CD 적용하기
CI: 지속적인 통합, 소프트웨어의 지속적인 업데이트 발생한다면, 지속적으로 테스트와, Merge(코드 병합)을 통해서 코드의 충돌을 보완할 수 있다
CD: 지속적인 배포, 
지속적인 업데이트를 통해서, 지속적으로 Deploy(배포하는 것)

## 목표: 자동 테스트 및 자동 배포.

### React.js 통한 CI/CD 구축하기

### Required 장치들
- JTest <Testing purpose>
- Firebase Deploy Tool
- Github Action <Automation WorkFlow>

# React.js
React Coponent란?
- 리엑트를 앱을 구성하고 있는 가장 최소한의 단위.
- 컴포넌트는 독자적 데이터 (props)를 입력받아, View(State)에 따라 Dom Node를 출력
- UI를 재사용 가능한 여러조각으로 나누고, 상태에 따라 Dome Node를 출력한다

컴포넌트 종류: 
- 함수형 컴포넌트
- 클래스형 컴포넌트

Render란?
맨 처음 어떻게 화면에 보여질 지 다루는 Render() 함수가 존재한다.
html 요소(element), 또는 React 요소 등의 코드가 눈으로 볼 수 있도록 그려지는 것을 렌더링(Rendering) 이라고 말합니다.
React 요소가 DOM Node에 추가되어 화면에 렌더되려면, ReactDom.Render 함수를 사용합니다.

  
