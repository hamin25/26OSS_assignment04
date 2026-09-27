22500354 성하민

1. Key Learning: 이번 주 배운 핵심 내용 3가지
- HTML Form을 활용해 <input>, <select>, <textarea>, <button> 등의 요소를 사용하여 다양한 형태의 입력을 만들 수 있다.
- focus, :hover 등을 활용하면 사용자의 동작에 따라 화면이 달라지도록 만들 수 있다.
- addEventListener()로 submit 이벤트를 처리하고, checkValidity(), focus(), event.preventDefault() 등을 활용하면 사용자가 입력하지 않은 input칸에 대한 상황을 처리할 수 있다.

2. Form Elements: 사용한 Form 요소와 용도
- text : 아이디, 이름 등 텍스트 입력, email: 이메일 형식의 입력, password: 비밀번호 입력, radio : 여러 항목 중 하나 선택, checkbox: 여러 항목 중 여러가지 선택, date : 생년월일 입력, color : 색상 선택, select : 정해진 목록에서 선택, textarea : 여러 줄의 텍스트 입력, button : Form 제출 및 초기화


3. HTML vs CSS: form1.html과 form1_css.html의 차이
- html은 주로 구조를 담당하고 css는 디자인을 담당한다. form1.html에서는 HTML을 이용하여 Form의 구조와 입력 요소를 구성한 반면, form1_css.html에서는 기존 HTML 구조는 유지하면서 CSS를 이용하여 Form의 디자인을 적용해 입력창의 크기, 여백, 테두리, 배경색, 버튼의 모양 등을 설정했다.

4. Validation & JS: 적용한 Validation 조건과 JavaScript 처리 과정
- HTML Validation에서는 사용자가 반드시 입력해야 하는 항목에 required를 적용하였다. 또한 이메일 같이 특정형식을 지켜야하면 type="email"을 사용하여 이메일 형식을 확인하고, 비밀번호에는 minlength="6"을 적용하여 최소 6자 이상 입력하도록 하였다. JavaScript에서는 document.querySelector()를 사용하여 Form과 각 입력 요소를 가져왔고 이후 addEventListener("submit", ...)를 사용하여 Form이 제출될 때 동작하도록 만들었다.

5. Problem & Solution: 문제와 해결 과정
- JavaScript Validation을 구현하는 과정 자체가 어려웠던 것 같다. submit 이벤트가 발생하면 event.preventDefault()를 사용하여 기본적인 Form 제출을 막고, JavaScript에서 입력값을 검사하도록 구현하는 방식을 공부하고 이를 적용해보며 해결하였다. 특히 수업 자료의 Form Submit 및 Validation 예제를 참고하여 addEventListener(), checkValidity(), focus()를 적용하였다.

6. Reflection: 새롭게 알게 된 점 또는 궁금한 점
- 사용자와 상호작용을 위해 form 형식을 활용해서 단순히 이미 입력된 정보 뿐만 아니라 입력값을 통해 웹페이지를 작동시킬 수 있는 점을 새롭게 배웠다.
