kakao-android-sdk-standalone
===========================

kakao-android-sdk에서 외부 의존성을 모두 제거하여, 별도의 의존성 부담 없이  사용할 수 있도록 수정한 버전입니다.

kakao-android-sdk
=================
kakao sdk for android
+ sdk(sources, resources, libraries)
+ samples(sources, resources for each sample)
+ templates(sources, resources for each template)
+ docs(javadoc)
+ intellij, eclipse


apklib
======

sdk만 별도로 apklib으로 다음과 같이 패키징 할 수 있습니다.

    $ mvn clean package -pl sdk
    $ ls -al sdk/target/kakao-android-sdk-standalone-apklib-1.0.6.apklib


credit
======

본 프로젝트는 [Kakao Developers_](https://developers.kakao.com/) 에서 공개하고 있는
`kakao-android-sdk` 를 기반으로 하고 있습니다.

 * Minyoung Jeong (a.k.a. kkung, kkungkkung@gmail.com)
 * Kakao Corp
