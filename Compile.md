# Compile
Compile은 프로그래밍 언어를 [Runtime](Runtime.md)하기 이전에 기계어로 해석하는 작업 방식이다.  
이때 원래의 소스를 **원시코드**, 바뀐 코드를 **목적코드**(Object Code)라고 한다.
런타임 이전에 [Assembly 언어](AssemblyLanguage.md)로 변환하기 때문에 구동 시간이 오래걸리지만, 구동된 이후는 하나의 패키지로 매우 빠르게 작동하게 된다.

---
+ Compiler에 의해 실행된다.
+ [런타임](Runtime.md) 이전에 이미 해석을 마치고 대게 컴파일 결과물이 바로 기계어로 전환되기 때문에 OS 및 빌드 환경에 종속적이다.
+ Compile 언어의 대표격으로 C / C++ 같은 언러들을 들 수 있으며, Java 역시 Byte Code 로 바꾸기 위한 과정에 컴파일을 수행한다.
+ 틀린게 있으면 빌드과정에서 실행이 안된다.

### 함께보기
+ [언어 번역 프로그램](언어번역프로그램.md)     
+ [Interpret](Interpret.md)
+ [Assembler](Assembler.md)