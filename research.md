---
layout: landing
title: Research
description: Blockchain & Security
image: assets/images/research01.png
nav-menu: true
---

<!-- Main -->
<div id="main" class="alt">
<!-- One -->
    <section id="one">
        <div class="inner">
            <header class="major">
                <h2>2020 ~ ing</h2>
            </header>
            <p>2020년부터 진행한 연구 목록을 정리하였습니다. 각 연구에 대한 자세한 설명은 논문을 참고해 주시면 감사하겠습니다.</p>
            <hr />
            <div class="row">
                <div class="4u 12u$(small)" style="text-align: center;">
                    <img src="assets/images/research01.png" style="width: 65%">
                </div>
                <div class="8u 12u$(small)">
                    <h3>DCSN: 블록체인과 데이터베이스 연동을 위한 데이터 콘텐츠 선택 네트워크</h3>
                    <p>
                    본 연구는 ICT 분야에서 중요한 플랫폼으로 사용되고 있는 블록체인을 활용한다. 기존의 레거시 시스템을
    블록체인으로 이식하는 것은 까다로운 작업이다. 따라서 DCSN은 플랫폼으로 제공되는 블록체인을 보다 폭넓고
    확장성 및 사용성 측면에서 유용하게 활용하기 위해 필요한 핵심 정보를 레거시 시스템에서 테이블 형식으로 전달받아
    블록체인 네트워크에 전파한다. 기존의 레거시 시스템을 수정하지 않고, 기존의 체계를 유지하며 필요한 정보를
    전달받아 오버레이 네트워크를 구성할 수 있다. 레거시 시스템과 블록체인 사이에 연결자 노드를 두고 라우팅 테이블을
    활용하여 필요한 데이터를 주고받는다. 또한 합리적인 의사결정 방식을 통해 검증 노드를 선택하고 합의를 도출한다.
    이를 통해 기존 시스템의 확장성, 보안성을 향상시키고 블록체인을 활용하여 무결성을 보장하며, 네트워크에 데이터
    전파 시 라우팅 테이블을 활용해 데이터의 전파속도를 향상시킬 수 있다.
                    </p>
                </div>
            </div>
            <hr />
            <div class="row">
                <div class="4u 12u$(small)" style="text-align: center;">
                    <img src="assets/images/research02.png" style="width: 65%">
                </div>
                <div class="8u 12u$(small)">
                    <h3>블록체인 및 DID 기반 교내 학생증 발급 및 서비스</h3>
                    <p>
                    In this study, we intend to explain the issuance and service of student ID cards based on blockchain and DID
    (Decentralized Identifier). Blockchain is a very superior technology in terms of security by ensuring the integrity and
    transparency of data handled compared to existing legacy systems. This study used a system that applied DID and
    blockchain for the expected security effect. Establish a distributed identity authentication system through DID, use
    Docker to store student information in a distributed form, and use hashing to store information. The system can
    conveniently use various authentication procedures within the school, and can provide user-friendly UI and services.
                    </p>
                </div>
            </div>
            <hr class="major" />
            <div class="row">
                <div class="4u 12u$(small)" style="text-align: center;">
                    <img src="assets/images/research03.png" style="width: 65%">
                </div>
                <div class="8u 12u$(small)">
                    <h3>블록체인 및 DID 기반 학내 신분증 발급 Eco-System</h3>
                    <p>
                    본 연구에서는 블록체인과 DID(Decentralized Identifier) 기반 학내 신분증 발급 Eco-System을 설명하고
    자 한다. 기존 블록체인과 DID를 활용한 다양한 서비스 플랫폼이 등장하고 있다. 블록체인은 기존의 사
    용 중인 여러 Legacy System보다 다루는 데이터에 대한 무결성과 투명성을 보장하여 보안 측면에서 매우
    우수한 기술이다. 그러나 기존에 쓰이고 있는 학내 신분증 발급 관련 Eco-System은 단순하게 데이터베이
    스를 사용하여 다수의 교내 사용자들의 개인 정보를 관리한다. 이러한 정보들은 그 시스템 자체보다는
    추가적인 보안 시스템에 의존하여 관리하고 있으며 그렇기에 관련 위협이 많다. 그렇기에 해당 시스템에
    블록체인의 기술을 접목하게 되면 이전보다 매우 안전하게 관리될 것으로 기대된다. 본 연구는 이러한
    기대 효과를 위해 DID 시스템을 사용하였다. DID를 통한 분산 신원 인증 체계를 구축하여 교내 이용자들
    의 정보를 안전하게 보관하고 교내의 다양한 인증 절차를 간편하게 이용할 수 있다. 이때 중앙화를 피하
    고자 도커 컨테이너 시스템을 이용하여 모든 서비스를 분산화하여 관리하게 된다.
                    </p>
                </div>
            </div>
            <hr />
            <div class="row">
                <div class="4u 12u$(small)" style="text-align: center;">
                    <img src="assets/images/research04.png" style="width: 65%">
                </div>
                <div class="8u 12u$(small)">
                    <h3>Linked Network: Linking Another Blockchain using Integrated Interface
                    </h3>
                    <p>
                    블록체인은 ICT 분야에서 중요한 플랫폼으로 사용되고 있다. 하지만 다양한 블록체인이 존재함에 따라 상호 연동성이 부족해지고 통합된 서비스를 제공하는 것은 어려운 작업이다. Linked Network는 각 Network 사이에 Integrated Interface를 두어 필요한 정보를 JSON의 형태로 편리하게 받아오며, Hash 함수를 활용하여 무결성을 보장한다. 본 연구는 플랫폼으로 제공되는 블록체인을 확장성 및 사용성 측면에서 유용하게 활용하기 위해 필요한 핵심 정보를 Mainchain에 전파하며, 서로 다른 도메인의 서비스에서 상호 연동성이 있는 서비스를 제공할 수 있는 방법을 제시한다. 서로 다른 블록체인 네트워크 사이에 Connector Node를 두어 정보의 전달을 용이하게 하고, JSON-RPC와 라우팅 테이블을 활용한다. 이를 통해 블록체인의 확장성, 보안성, 무결성을 보장할 수 있다.
                    </p>
                </div>
            </div>
            </div>
        </section>
    
</div>
