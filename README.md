1. React-hook-form
form을 구현할 때 필요한 다양한 기능의 제공.
1) register 함수
<input {...register("Name")} /> 과 같은 구조로 사용된다.
register의 반환값은 {name: "", onChange:func, onBlur:func, ref: func} 이다.

2) watch 함수

3) handleSubmit 함수
validation 검사

2. onBlur 이벤트란?
input의 focus상태가 사라지는 순간 트리거되는 이벤트이다.