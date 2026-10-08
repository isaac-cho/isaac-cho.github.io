
---
title: Research
type: landing

sections:

  # ============================================================
  # LANGUAGE MENU
  # ============================================================

  - block: markdown
    id: language-menu
    content:
      text: |
        <div class="text-center my-6">
          <a href="#korean">한국어</a>
          &nbsp; | &nbsp;
          <a href="#english">English</a>
        </div>
    design:
      spacing:
        padding: [1rem, 0, 0, 0]

  # ============================================================
  # KOREAN - OVERVIEW
  # ============================================================

  - block: markdown
    id: korean
    content:
      title: 연구 소개
      text: |
        저는 **확장현실(XR), 공간 컴퓨팅 및 인터랙티브 시각화 환경에서 인간의 지각, 인지 및 의사결정**을 연구합니다.

        인터랙션을 단순히 컴퓨터를 제어하는 수단이 아니라, 사람들이 **불확실성을 탐색하고, 지식을 형성하며, 의사결정을 수행하는 매개체**로 바라봅니다. 이러한 관점에서 제 연구는 다음과 같은 공통된 질문을 다룹니다.

        **인간의 지각, 인지 및 의사결정을 효과적으로 지원하기 위해 인터랙티브 시스템은 어떻게 설계되어야 하는가?**

        제 연구는 컴퓨팅 시스템의 설계 및 구현과 인간 행동에 대한 실증적 연구를 결합하며, 서로 밀접하게 연결된 세 가지 연구 방향을 중심으로 진행됩니다. **인간 중심 XR 및 공간 컴퓨팅**, **인터랙티브 시각화 및 비주얼 컴퓨팅**, **XR 환경에서의 다감각 인터랙션**입니다.

    design:
      css_class: research-page research-overview
      spacing:
        padding: [2rem, 0, 2rem, 0]

  # ============================================================
  # KOREAN - XR / SPATIAL COMPUTING
  # ============================================================

  - block: markdown
    id: korean-xr
    content:
      title: 인간 중심 XR 및 공간 컴퓨팅
      text: |
        ![Human-Centered XR and Spatial Computing](/image/research/xr-spatial-computing.png)

        컴퓨팅 환경이 기존의 2차원 디스플레이를 넘어 확장되면서, 사용자들은 신체 움직임, 공간적 조작 및 3차원 데이터와의 직접적인 상호작용을 통해 정보를 다루고 있습니다.

        저는 몰입형 인터랙션 기법이 **공간 인지와 신체화된 지각(embodied perception)**을 어떻게 활용할 수 있는지, 그리고 이러한 과정에서 인지적·신체적 부담을 어떻게 줄일 수 있는지 연구합니다. 기존 시각화 및 인터랙션 원리가 몰입형 환경에도 그대로 적용된다고 가정하기보다는, XR 환경이 주의집중, 공간 기억, 지각, 작업부하 및 분석 수행 능력에 미치는 영향을 실증적으로 분석합니다.

        이 분야의 주요 연구 주제로는 **3D 사용자 인터페이스, 몰입형 분석(Immersive Analytics), 대형 가상 디스플레이, 가상 디스플레이 인터랙션, 포털 기반 인터랙션 및 공간적 객체 조작** 등이 있습니다.

        **대표 논문**

        - [Beyond Arm’s Reach: Revisiting 3D Interaction Techniques for Virtual Display Management in Immersive Workspaces](/publications/han-2026/)
        - [PORTAL: Portal Widget for Remote Target Acquisition and Control in Immersive Virtual Environments](/publications/han-2022-portal/)
        - [Evaluating Preattentive Features for Detecting Changes in Virtual Environments](/publications/kim-2026-evaluating/)

    design:
      css_class: research-page research-direction
      spacing:
        padding: [2rem, 0, 2rem, 0]

  # ============================================================
  # KOREAN - VISUALIZATION
  # ============================================================

  - block: markdown
    id: korean-visualization
    content:
      title: 인터랙티브 시각화 및 비주얼 컴퓨팅
      text: |
        ![Interactive Visualization and Visual Computing](/image/research/interactive-visualization.png)

        저는 복잡하고 이질적이며 불확실성을 포함하는 정보를 사람들이 효과적으로 이해하고 해석할 수 있도록 지원하는 **인터랙티브 시각화 및 비주얼 컴퓨팅 기술**을 연구합니다.

        인공지능과 머신러닝이 데이터 분석 과정에 점차 깊이 통합됨에 따라, 사용자에게는 계산 결과를 단순히 받아들이는 것을 넘어 이를 해석하고, 검증하며, 맥락화하고, 비판적으로 검토할 수 있는 인터페이스가 필요합니다. 저는 사용자를 자동화된 분석 결과의 수동적인 소비자가 아닌, 분석 과정에 능동적으로 참여하는 주체로 유지하는 비주얼 애널리틱스 시스템을 설계합니다.

        이러한 연구는 **소셜미디어 분석, 디지털 인문학, 정책 분석, 환경 모니터링, 지구과학, 핵심 인프라 및 분산 에너지 시스템** 등 다양한 응용 분야에 걸쳐 있습니다. 궁극적으로는 사용자가 불확실성을 탐색하고, 가설을 형성하며, 복잡한 데이터를 실질적인 지식과 의사결정으로 연결할 수 있도록 지원하는 일반화 가능한 인터랙션 설계 원리를 도출하는 것을 목표로 합니다.

        **대표 논문**

        - [PDViz: A Visual Analytics Approach for State Policy Data](/publications/han-2022/)
        - [HisVA: A Visual Analytics System for Learning History](/publications/han-2021-hisva/)
        - [Investigating Effects of Visual Anchors on Decision-Making about Misinformation](/publications/wesslen-2019-investigating/)

    design:
      css_class: research-page research-direction
      spacing:
        padding: [2rem, 0, 2rem, 0]

  # ============================================================
  # KOREAN - MULTIMODAL INTERACTION
  # ============================================================

  - block: markdown
    id: korean-multimodal
    content:
      title: XR 환경에서의 다감각 인터랙션
      text: |
        ![Multimodal Interaction in XR](/image/research/multimodal-interaction.png)

        저는 다양한 감각 정보를 몰입형 환경에 통합하여 **사용자의 지각, 상호작용 및 공간 이해**를 향상시키는 방법을 연구합니다.

        특히 **후각, 촉각, 시각, 청각 및 기류 자극**이 가상현실과 확장현실 환경에서 사용자 경험, 내비게이션, 객체 조작 및 공간 인지에 미치는 영향을 탐구합니다. 이러한 감각 자극을 서로 독립적인 피드백 채널로 다루기보다는, 다감각 단서들이 인간의 지각 및 인지 과정과 어떻게 상호작용하는지 분석하고, 이를 바탕으로 효과적이고 자연스러운 몰입형 경험을 설계하는 방법을 연구합니다.

        **대표 논문**

        - [Smelling the Way: Olfactory Modulation of Spatial Estimation and Path Integration in Virtual Reality](/publications/bak-2026/)
        - [Exploring the Effects of Olfactory Cues and Ventilation on Teleportation-Based Navigation in VR](/publications/han-2026-olf/)
        - [Beyond the Portal: Enhancing Recognition in VR Through Multisensory Cues](/publications/bak-2025-beyond/)

    design:
      css_class: research-page research-direction
      spacing:
        padding: [2rem, 0, 2rem, 0]

  # ============================================================
  # KOREAN - COLLABORATION
  # ============================================================

  - block: markdown
    id: korean-collaboration
    content:
      title: 공동연구
      text: |
        제 연구는 본질적으로 학제적인 성격을 가지며, **컴퓨터과학, 공학, 에너지 시스템, 의료 및 자연과학** 등 다양한 분야의 연구자 및 실무자들과 협력해 왔습니다.

        **NASA Jet Propulsion Laboratory (JPL), Lawrence Berkeley National Laboratory (LBNL), Electric Power Research Institute (EPRI)** 등 여러 연구기관과 관련된 공동연구에 참여했으며, 다양한 대학의 연구자들과도 협력해 왔습니다.

        특히 **데이터 시각화, 비주얼 애널리틱스, XR 및 공간 컴퓨팅, 다감각 인터랙션, 인간 중심 AI** 분야에서 새로운 공동연구 기회를 모색하고 있습니다.

        **공동연구에 관심이 있으시면** [이메일로 연락해 주세요](mailto:drisaaccho@gmail.com).

    design:
      css_class: research-page research-collaboration
      spacing:
        padding: [2rem, 0, 4rem, 0]

  # ============================================================
  # ENGLISH - OVERVIEW
  # ============================================================

  - block: markdown
    id: english
    content:
      title: Research
      text: |
        My research investigates **human perception, cognition, and decision-making** across XR, spatial computing, and interactive visualization environments.

        I view interaction not merely as a mechanism for controlling computers, but as the medium through which people **explore uncertainty, construct knowledge, and make decisions**. Across my work, I address a common question:

        **How should interactive systems be designed to better support human perception, cognition, and decision-making?**

        My research combines computational system design with empirical studies of human behavior and is organized around three closely connected directions: **human-centered XR and spatial computing**, **interactive visualization and visual computing**, and **multimodal interaction in XR**.

    design:
      css_class: research-page research-overview
      spacing:
        padding: [2rem, 0, 2rem, 0]

  # ============================================================
  # ENGLISH - XR / SPATIAL COMPUTING
  # ============================================================

  - block: markdown
    id: xr-spatial
    content:
      title: Human-Centered XR & Spatial Computing
      text: |
        ![Human-Centered XR and Spatial Computing](/image/research/xr-spatial-computing.png)

        As computing moves beyond two-dimensional displays, users increasingly interact with information through embodied movement, spatial manipulation, and direct engagement with three-dimensional data.

        My research investigates how immersive interaction techniques can leverage **spatial cognition and embodied perception** while minimizing cognitive and physical demands. Rather than assuming that traditional visualization and interaction principles transfer directly to immersive environments, I empirically study how XR affects attention, spatial memory, perception, workload, and analytical performance.

        My work in this area includes **3D user interfaces, immersive analytics, wall-sized virtual displays, virtual display interaction, portal-based interaction, and spatial manipulation**.

        **Selected papers**

        - [Beyond Arm’s Reach: Revisiting 3D Interaction Techniques for Virtual Display Management in Immersive Workspaces](/publications/han-2026/)
        - [PORTAL: Portal Widget for Remote Target Acquisition and Control in Immersive Virtual Environments](/publications/han-2022-portal/)
        - [Evaluating Preattentive Features for Detecting Changes in Virtual Environments](/publications/kim-2026-evaluating/)

    design:
      css_class: research-page research-direction
      spacing:
        padding: [2rem, 0, 2rem, 0]

  # ============================================================
  # ENGLISH - VISUALIZATION
  # ============================================================

  - block: markdown
    id: visualization
    content:
      title: Interactive Visualization & Visual Computing
      text: |
        ![Interactive Visualization and Visual Computing](/image/research/interactive-visualization.png)

        My research investigates how interactive visualization and visual computing can support **human sensemaking across complex, heterogeneous, and uncertain information**.

        As analytical workflows increasingly incorporate artificial intelligence and machine learning, people need interfaces that allow them to interpret, verify, contextualize, and question computational results. I design visual analytics systems that keep users actively involved in the analytical process rather than treating them as passive consumers of automated outputs.

        This work spans applications including **social media analysis, digital humanities, policy analytics, environmental monitoring, earth science, critical infrastructure, and distributed energy systems**. Across these domains, my goal is to identify general interaction principles that help users explore uncertainty, formulate hypotheses, and transform complex data into actionable knowledge.

        **Selected papers**

        - [PDViz: A Visual Analytics Approach for State Policy Data](/publications/han-2022/)
        - [HisVA: A Visual Analytics System for Learning History](/publications/han-2021-hisva/)
        - [Investigating Effects of Visual Anchors on Decision-Making about Misinformation](/publications/wesslen-2019-investigating/)

    design:
      css_class: research-page research-direction
      spacing:
        padding: [2rem, 0, 2rem, 0]

  # ============================================================
  # ENGLISH - MULTIMODAL INTERACTION
  # ============================================================

  - block: markdown
    id: multimodal
    content:
      title: Multimodal Interaction in XR
      text: |
        ![Multimodal Interaction in XR](/image/research/multimodal-interaction.png)

        My research investigates how multiple sensory modalities can be integrated into immersive environments to enhance **perception, interaction, and spatial understanding**.

        I explore how **olfactory, haptic, visual, auditory, and airflow cues** influence user experience, navigation, object interaction, and spatial cognition in virtual and extended reality. Rather than treating these modalities as independent feedback channels, my work examines how multimodal cues interact with human perceptual and cognitive processes and how they can be designed to provide effective and natural immersive experiences.

        **Selected papers**

        - [Smelling the Way: Olfactory Modulation of Spatial Estimation and Path Integration in Virtual Reality](/publications/bak-2026/)
        - [Exploring the Effects of Olfactory Cues and Ventilation on Teleportation-Based Navigation in VR](/publications/han-2026-olf/)
        - [Beyond the Portal: Enhancing Recognition in VR Through Multisensory Cues](/publications/bak-2025-beyond/)

    design:
      css_class: research-page research-direction
      spacing:
        padding: [2rem, 0, 4rem, 0]

  # ============================================================
  # ENGLISH - COLLABORATION
  # ============================================================

  - block: markdown
    id: collaboration
    content:
      title: Research Collaboration
      text: |
        My research is inherently interdisciplinary and has involved collaborations with researchers and practitioners across **computer science, engineering, energy systems, healthcare, and the sciences**.

        I have collaborated on research involving organizations and institutions including **NASA Jet Propulsion Laboratory (JPL), Lawrence Berkeley National Laboratory (LBNL), and the Electric Power Research Institute (EPRI)**, as well as academic collaborators across multiple universities.

        I am particularly interested in new collaborations in **data visualization, visual analytics, XR and spatial computing, multimodal interaction, and human-centered AI**.

        **Interested in collaborating?** Please feel free to [contact me](mailto:drisaaccho@gmail.com).

    design:
      css_class: research-page research-collaboration
      spacing:
        padding: [2rem, 0, 4rem, 0]
---
