# SPRING ADVANCED

작성된 코드를 개선하는 Spring 심화 주차 개인 과제를 진행했습니다.

+ LV1-1에선 불필요한 로직의 실행을 방지하고 성능을 향상시켰습니다.

+ LV1-2에선 불필요한 `if-else`구조를 개선했습니다.

+ LV1-3에선 비밀번호 변경 시 비밀번호 형식 관련 예외 처리를 `UserService` -> `UserChangePasswordRequest`가 처리하도록 개선했습니다.

+ LV2 에선 `Fetch Join`으로 해결하던 `N + 1`문제를 `@EntityGraph` 기반으로 처리하도록 개선하였습니다.
  해당 과정에서 `@EntityGraph`와 `Fetch Join`의 차이점 및, `@EntityGraph`를 사용하는 경우를 블로그에 정리하였습니다.   [정리한 블로그 링크](https://velog.io/@4ou_chan/Spring-EntityGraph-%EC%99%9C-%EC%8D%A8%EC%95%BC%ED%95%A0%EA%B9%8C)

+ LV3 에선 작성되어있는 테스트코드가 정상 작동하지 않는 원인을 파악한 후 정상 작동 할 수 있도록 수정하는 과정을 겪었습니다. 
