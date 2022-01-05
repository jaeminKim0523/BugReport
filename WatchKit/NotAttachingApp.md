# 빌드시 시뮬레이터에서 앱이 설치되지 않던 이슈 해결

이슈: 워치 앱을 빌드시 iPhone 시뮬레이터에서는 설치가 되지만, Watch 시뮬레이터에서는 설치가 되지 않고 디버깅이 안되던 이슈  

해결 방법: Project - Watch Target - General - Supports Running Without iOS App Installation 옵션 true
