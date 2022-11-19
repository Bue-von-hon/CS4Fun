<details>
<summary>메소드 시그니쳐</summary>
<div>
메소드의 이름과 파라미터
</div>
</details>
<hr>

<details>
<summary>추상클래스와 인터페이스의 차이</summary>
<div>
인터페이스에 디폴트 메소드 기능이 추가된 이후 둘 사이의 동작 차이는 적어졌다.

그럼에도 아래와 같은 몇가지 차이가 존재한다.

사용성에서 추상클래스는 is a, 인터페이스는 has a라는 차이가 존재한다.

</div>
</details>
<hr>

solid
<hr>

<details>
<summary>객체의 동등과 동일</summary>
<div>
동등은 두 객체의 상태가 같음을 의미, equals

동일은 두 객체과 완전히 동일함을 의미, 그냥 주소가 같은것, ==
</div>
</details>
<hr>

<details>
<summary>해시맵의 해시충돌</summary>
<div>
해시 충돌은 새로 저장하려는 값과 이미 같은 해시값에 해당하는 값이 저장되어 있는 것.

자바의 해시맵에서는 링크드 리스트를 이용하여 충돌을 해결한다.(값 두개를 링크드 리스트를 이용해 연결)
</div>
</details>
<hr>

어레이 리스트가 사이즈를 늘리는 방법
<hr>

<details>
<summary>체크드, 언체크드 익셉션의 차이</summary>
<div>
자바 예외는 복구, 회피, 전환이 가능하다.

언체크드, 런타임 익셉션은 복구 불가능한 친구다. 그래서 애초에 이걸 catch하려 시도하면 안된다.

체크드, 이건 복구 가능한 애다. catch해서 복구하던지(보통 재시도를 한다) 회피하던지, 다른 친구로(전환) 잡아서 던져야한다.

</div>
</details>
<hr>

<details>
<summary>enum</summary>
<div>
자바에서 상수를 표현하는 방식이다.

주의사항으로는 ordinal 요거로 값을 비교하면 안된다.(이건 그냥 선언된 순서다)
</div>
</details>

<hr>
<details>
<summary>제너릭</summary>
<div>
컴파일 시 타입 이레이즈된다.

클래스나 메소드에서 사용할 타입을 외부에서 지정해주는것.

PECS : 값을 제공하면 extends, 값을 사용하면 super
</div>
</details>
<hr>

date, localDate의 차이

io stream 주의 사항

<details>
<summary>테스트 더블</summary>
<div>
테스트를 위해 만드는 여러가지 객체 이름이다.(mock이랑 혼용해서 부르기도...)

더미 : 어떤 객체 생성으로만 필요한 친구

스터브 : 객체 생성에 필요한 친구 + 특정한 상태가 설정된 친구

스파이 : 실행 되었는지 아닌지 체크

</div>
</details>

jpa와 마이바티스의 차이

dto란