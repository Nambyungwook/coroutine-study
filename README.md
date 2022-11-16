Coroutine Study
===================================

https://developer.android.com/codelabs/kotlin-coroutines#0 를 따라서 공부한 내용 정리

Kotlin Coroutine
--------------
* 메인 스레드를 차단하지나 않고 오래걸리는 작업을 수행하는 패턴중에는 콜백 패턴이 있으며 콜백 패턴은 몇가지 단점이 있는데 콜백을 많이 사용하는 코드는 읽기 어렵고 예외와 같은 일부 언어기능을 사용할 수 없음
* Kotlin Coroutine을 사용하면 콜백 기반의 코드를 순차 코드로 변환 할 수 있고 순차적으로 작성된 코드는 일반적으로 읽기 쉽고 예외와 같은 언어 기능을 사용할 수 있음
* suspend 키워드는 코루틴에서 사용할 수 있는 함수를 표시하는 Kotlin의 방식으로 해당 함수를 호출하면 일시 중단 한 다음 결과와 함께 중단된 지점에서 다시 시작함
* Coroutine Scope : 코틀린에서 코루틴은 CoroutineScope 내에서 동작하며 해당 scope의 lifecycle에 의해 제어됨