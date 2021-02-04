# [webpack]
1. chunkhash
chunkhash 는 변경이 감지된 entry 에 한해서만 hash 값을 변경한다<br>
production 환경에서만 사용한다.<br>
만약 로컬 환경에서 사용하고 싶은 경우 HotModuleReplacementPlugin 함수를 주석 처리한다.
