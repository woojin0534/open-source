# **:computer:서버 저장소란?**
    원격저장소(remote repository)라고 하며,
    로컬저장소(local repository)에 저장된 코드를 복제한 복제본이라고 할 수 있습니다.

## **협업 저장소란?**
깃은 규모가 큰 프로젝트들을 효율적이고, 높은 품질로 개발하기 위해 여러 개발자들이 협업할 수 있도록 만들어진 도구이고, 그렇기 때문에 협업을 위해 만들어진 깃 서버 저장소를 협업 저장소라고 합니다.<br>
>※ 원활한 협업을 위해 깃에서는 각 개발자들이 네트워크로부터  자유로운 환경에서 프로젝트를 이어나갈 수 있도록 로컬저장소와 서버 저장소를 분리하는 방식을 채택하였습니다.<br>

<kbd>

![협업 저장소](https://user-images.githubusercontent.com/45596014/193068297-5ecd2766-6d96-4799-8566-db09cb5685e1.jpg)

</kbd>

<br>

## **연속된 작업**
사무실 PC의 로컬저장소에서 작업한 데이터를 서버 저장소에 저장하면, 개인 PC 로컬저장소에 다운로드해 연속적으로 작업을 이어갈 수 있습니다.
>  ※ 깃은 서버 저장소의 자료를 여러 각 로컬저장소에 복제할 수 있습니다. 또한 자료가 저장된 여러 로컬저장소들에서 자료를 추가로 작업한 후 다시 하나의 서버 저장소에 통합할 수 있습니다. <br>

<kbd>

![연속된 작업](https://user-images.githubusercontent.com/45596014/193068293-931e835f-76ab-41ce-8356-36a62ef3bb7c.jpg)

</kbd>

<br>

## **새 멤버**
기존 프로젝트에 새 멤버가 추가될 경우 해당 시점까지 작업한 소스코드의 최종 버전을 공유해야 하는데 이때, 깃의 원격저장소 주소만 새 멤버에게 알려주면 별도로 파일을 보내줄 필요 없이 프로젝트의 이전 버전부터 최신 버전까지의 소스코드를 확인할 수 있습니다.
>※ 깃 서버 저장소를 통해 프로젝트에 참여한 모든 구성원에게 코드의 최종 결과물을 동기화할 수 있습니다.<br>

<kbd>

![신입](https://user-images.githubusercontent.com/45596014/193068289-b996b2cc-c65c-440a-9713-524915e508cf.jpg)s

</kbd>