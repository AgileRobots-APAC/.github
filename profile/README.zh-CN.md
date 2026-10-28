<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="../images/logo-light.png">
  <source media="(prefers-color-scheme: light)" srcset="../images/logo-dark.png">
  <img src="../images/logo-dark.png" height="60" alt="Agile Robots 思灵机器人">
</picture>

[English](README.md) | **简体中文**

### 链接人工智能和物理世界

[![Website](https://img.shields.io/badge/Website-2C3E50?style=for-the-badge&logo=google-chrome&logoColor=white)](https://www.agile-robots.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/agile-robots-se/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AgileRobots-APAC)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:service.apac@agile-robots.com)

</div>

### 🚀 关于 Agile Robots

---

思灵机器人（Agile Robots）是一家全球领先的智能机器人明星企业。公司以“链接人工智能与物理世界”为愿景，致力于推动AI与机器人前沿技术的深度融合及创新。围绕机器人感知、决策、力控、视觉、操作系统及人工智能深度学习等核心技术，思灵构建起全栈技术能力，形成世界级的领先优势，并已在 AI、医疗、汽车以及上下游、消费电子、工业、农业等多元场景中落地。

### 🧭 快速开始

---

1. 阅读[开发手册](https://agilerobots-apac.github.io/diana_development_manual/)，完成机器人和开发环境的配置。
2. 选择集成方式：**ROS 2**（[Humble](https://github.com/AgileRobots-APAC/diana_ros2/tree/humble) / Jazzy（即将推出）），或 **SDK**（[C++](https://github.com/AgileRobots-APAC/diana_sdk_cpp) / [Python](https://github.com/AgileRobots-APAC/diana_sdk_python)）。
3. 运行示例（[C++](https://github.com/AgileRobots-APAC/diana_examples_cpp) / [Python](https://github.com/AgileRobots-APAC/diana_examples_python)）验证环境，然后开发你自己的应用。

### 📂 代码仓库

---

<table width="100%">
  <tr>
    <td rowspan="2" width="120" align="center" valign="middle"><b>ROS 2</b></td>
    <td width="300">
      <a href="https://github.com/AgileRobots-APAC/diana_ros2/tree/humble"><img src="https://img.shields.io/badge/diana__ros2-Humble-22314E?style=flat-square&logo=ros&logoColor=white" alt="diana_ros2"></a>
    </td>
    <td>Diana 的 ROS 2 Humble（Ubuntu 22.04）软件包：驱动、控制器、MoveIt 2 集成和 launch 文件。</td>
  </tr>
  <tr>
    <td>
      <img src="https://img.shields.io/badge/diana__ros2-Jazzy%EF%BC%88%E5%8D%B3%E5%B0%86%E6%8E%A8%E5%87%BA%EF%BC%89-22314E?style=flat-square&logo=ros&logoColor=white" alt="diana_ros2 Jazzy">
    </td>
    <td>Diana 的 ROS 2 Jazzy（Ubuntu 24.04）软件包（即将推出）。</td>
  </tr>
  <tr>
    <td rowspan="2" width="120" align="center" valign="middle"><b>开发者 SDK</b></td>
    <td>
      <a href="https://github.com/AgileRobots-APAC/diana_sdk_cpp"><img src="https://img.shields.io/badge/diana__sdk__cpp-C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="diana_sdk_cpp"></a>
    </td>
    <td>C++ SDK，提供将 Diana 和 Thor 集成到自定义应用的库和 API。</td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AgileRobots-APAC/diana_sdk_python"><img src="https://img.shields.io/badge/diana__sdk__python-Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="diana_sdk_python"></a>
    </td>
    <td>Python SDK，提供将 Diana 和 Thor 集成到自定义应用的库和 API。</td>
  </tr>
  <tr>
    <td rowspan="2" width="120" align="center" valign="middle"><b>示例</b></td>
    <td>
      <a href="https://github.com/AgileRobots-APAC/diana_examples_cpp"><img src="https://img.shields.io/badge/diana__examples__cpp-C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="diana_examples_cpp"></a>
    </td>
    <td>Diana 和 Thor 的 C++ 示例程序：连接、运动控制、状态读取等。</td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AgileRobots-APAC/diana_examples_python"><img src="https://img.shields.io/badge/diana__examples__python-Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="diana_examples_python"></a>
    </td>
    <td>Diana 和 Thor 的 Python 示例程序：连接、运动控制、状态读取等。</td>
  </tr>
  <tr>
    <td width="120" align="center" valign="middle"><b>机器人描述</b></td>
    <td>
      <a href="https://github.com/AgileRobots-APAC/diana_description"><img src="https://img.shields.io/badge/diana__description-Repo-0E8A7D?style=flat-square&logo=github" alt="diana_description"></a>
    </td>
    <td>Diana 机器人描述：URDF/Xacro、网格模型，用于仿真、规划和可视化。</td>
  </tr>
  <tr>
    <td width="120" align="center" valign="middle"><b>补丁（Overlay）</b></td>
    <td>
      <a href="https://github.com/AgileRobots-APAC/diana_libfranka_overlay"><img src="https://img.shields.io/badge/diana__libfranka__overlay-Repo-0E8A7D?style=flat-square&logo=github" alt="diana_libfranka_overlay"></a>
    </td>
    <td>基于上游 libfranka 的机械臂补丁，支持 Diana3、Diana7 和 Diana7G2，每款机械臂一个分支。</td>
  </tr>
</table>

### 📚 文档

---

<table width="100%">
  <tr>
    <td width="120" align="center" valign="middle"><b>开发指南</b></td>
    <td width="300">
      <a href="https://agilerobots-apac.github.io/diana_development_manual/"><img src="https://img.shields.io/badge/diana__development__manual-Docs-2E7D32?style=flat-square&logo=readthedocs&logoColor=white" alt="diana_development_manual"></a>
    </td>
    <td>Diana 和 Thor 的开发手册：安装指南、教程和常用 API 的使用说明。</td>
  </tr>
  <tr>
    <td rowspan="3" width="120" align="center" valign="middle"><b>飞书</b></td>
    <td>
      <img src="https://img.shields.io/badge/Diana%20%E6%8A%80%E6%9C%AF%E6%89%8B%E5%86%8C-Docs%EF%BC%88%E5%8D%B3%E5%B0%86%E6%8E%A8%E5%87%BA%EF%BC%89-2E7D32?style=flat-square&logo=readthedocs&logoColor=white" alt="Diana 技术手册">
    </td>
    <td>Diana 技术手册（即将推出）：产品手册（机械臂、控制箱、示教器、产品兼容性）、模型与仿真、使用与操作、安全、软件开发技术文档、应用与解决方案、常见问题。</td>
  </tr>
  <tr>
    <td>
      <a href="https://agilerobots.feishu.cn/wiki/space/7604738168612473794"><img src="https://img.shields.io/badge/Diana%20%E8%B5%84%E6%96%99-Docs-2E7D32?style=flat-square&logo=readthedocs&logoColor=white" alt="Diana 资料"></a>
    </td>
    <td>Diana 资料与参考文档。</td>
  </tr>
  <tr>
    <td>
      <a href="https://agilerobots.feishu.cn/wiki/space/7620696065129417672"><img src="https://img.shields.io/badge/Thor%20%E8%B5%84%E6%96%99-Docs-2E7D32?style=flat-square&logo=readthedocs&logoColor=white" alt="Thor 资料"></a>
    </td>
    <td>Thor 资料与参考文档。</td>
  </tr>
</table>

### 📧 联系我们

---

如有问题或需要支持，请发送邮件至 [service.apac@agile-robots.com](mailto:service.apac@agile-robots.com)，访问 [www.agile-robots.com](https://www.agile-robots.com)，或在相关仓库中提交 issue。
