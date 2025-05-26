//c.chpater pointer
//포인터란 
int num=10;
int*ptr=&num;

//포인터 변수 선언과 초기화
int *ptr;//int형 데이터를 가리키는 데이터
char*cptr;//char형 데이터를 가리키는 데이터


//초기화 되지 않은 예상치 못한 동작 유발->null값 으로 초기화
int*ptr=NULL;//안전한 포인터 초기화


//포인터 연산자(&&와*)
& 연산자: 변수의 메모리 주소를 바놘
* 연산자: 포인터가 가리키는 변수의 값을 반환
int num=42;
int*ptr=&num;

printf("num의 주소:%p\n",&num);
printf("ptr의 값(num의 주소):%p\n"
