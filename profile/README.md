<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="../images/logo-light.png">
  <source media="(prefers-color-scheme: light)" srcset="../images/logo-dark.png">
  <img src="../images/logo-dark.png" height="60" alt="Agile Robots">
</picture>

**English** | [简体中文](README.zh-CN.md)

### Connecting Artificial Intelligence to the Physical World

[![Website](https://img.shields.io/badge/Website-2C3E50?style=for-the-badge&logo=google-chrome&logoColor=white)](https://www.agile-robots.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/agile-robots-se/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AgileRobots-APAC)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:service.apac@agile-robots.com)

</div>

### 🚀 About Agile Robots

---

Agile Robots is a world-class provider of next-generation automation solutions based in Munich. By combining artificial intelligence and robotics, the company makes industries smarter, more flexible, and more efficient.

Founded in 2018, Agile Robots has built a unique portfolio that covers all areas of AI-driven robotics under one roof, from force-sensitive robotic arms to intelligent automation platforms and mobile robots, and now brings Physical AI to industry with its humanoid robot Agile ONE. As an international company based in Germany with production sites in Europe, America and Asia, Agile Robots serves customers anywhere in the world.

### 🧭 Getting Started

---

1. Read the [development manual](https://agilerobots-apac.github.io/diana_development_manual/en/) to set up your robot and development environment.
2. Pick your integration path: **ROS 2** ([Humble](https://github.com/AgileRobots-APAC/diana_ros2/tree/humble) / Jazzy (coming soon)) or the **SDK** ([C++](https://github.com/AgileRobots-APAC/diana_sdk_cpp) / [Python](https://github.com/AgileRobots-APAC/diana_sdk_python)).
3. Run the examples ([C++](https://github.com/AgileRobots-APAC/diana_examples_cpp) / [Python](https://github.com/AgileRobots-APAC/diana_examples_python)) to verify your setup, then build your own application.

### 📂 Repositories

---

<table width="100%">
  <tr>
    <td rowspan="2" width="120" align="center" valign="middle"><b>ROS 2</b></td>
    <td width="300">
      <a href="https://github.com/AgileRobots-APAC/diana_ros2/tree/humble"><img src="https://img.shields.io/badge/diana__ros2-Humble-22314E?style=flat-square&logo=ros&logoColor=white" alt="diana_ros2"></a>
    </td>
    <td>ROS 2 Humble (Ubuntu 22.04) packages for Diana: drivers, controllers, MoveIt 2 integration and launch files.</td>
  </tr>
  <tr>
    <td>
      <img src="https://img.shields.io/badge/diana__ros2-Jazzy%20(coming%20soon)-22314E?style=flat-square&logo=ros&logoColor=white" alt="diana_ros2 Jazzy">
    </td>
    <td>ROS 2 Jazzy (Ubuntu 24.04) packages for Diana (coming soon).</td>
  </tr>
  <tr>
    <td rowspan="2" width="120" align="center" valign="middle"><b>Developer SDKs</b></td>
    <td>
      <a href="https://github.com/AgileRobots-APAC/diana_sdk_cpp"><img src="https://img.shields.io/badge/diana__sdk__cpp-C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="diana_sdk_cpp"></a>
    </td>
    <td>C++ SDK providing libraries and APIs for integrating Diana and Thor into custom applications.</td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AgileRobots-APAC/diana_sdk_python"><img src="https://img.shields.io/badge/diana__sdk__python-Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="diana_sdk_python"></a>
    </td>
    <td>Python SDK providing libraries and APIs for integrating Diana and Thor into custom applications.</td>
  </tr>
  <tr>
    <td rowspan="2" width="120" align="center" valign="middle"><b>Examples</b></td>
    <td>
      <a href="https://github.com/AgileRobots-APAC/diana_examples_cpp"><img src="https://img.shields.io/badge/diana__examples__cpp-C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="diana_examples_cpp"></a>
    </td>
    <td>C++ example programs for Diana and Thor: connection, motion control, state reading and more.</td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/AgileRobots-APAC/diana_examples_python"><img src="https://img.shields.io/badge/diana__examples__python-Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="diana_examples_python"></a>
    </td>
    <td>Python example programs for Diana and Thor: connection, motion control, state reading and more.</td>
  </tr>
  <tr>
    <td width="120" align="center" valign="middle"><b>Robot Description</b></td>
    <td>
      <a href="https://github.com/AgileRobots-APAC/diana_description"><img src="https://img.shields.io/badge/diana__description-Repo-0E8A7D?style=flat-square&logo=github" alt="diana_description"></a>
    </td>
    <td>Robot description of Diana: URDF/Xacro, meshes and visualization for simulation and planning.</td>
  </tr>
  <tr>
    <td width="120" align="center" valign="middle"><b>Overlay</b></td>
    <td>
      <a href="https://github.com/AgileRobots-APAC/diana_libfranka_overlay"><img src="https://img.shields.io/badge/diana__libfranka__overlay-Repo-0E8A7D?style=flat-square&logo=github" alt="diana_libfranka_overlay"></a>
    </td>
    <td>Patches on top of upstream libfranka for Diana3, Diana7 and Diana7G2 arms, with one branch per arm.</td>
  </tr>
</table>

### 📚 Documentation

---

<table width="100%">
  <tr>
    <td width="120" align="center" valign="middle"><b>Developer Guide</b></td>
    <td width="300">
      <a href="https://agilerobots-apac.github.io/diana_development_manual/en/"><img src="https://img.shields.io/badge/diana__development__manual-Docs-2E7D32?style=flat-square&logo=readthedocs&logoColor=white" alt="diana_development_manual"></a>
    </td>
    <td>Development manual for Diana and Thor: installation guides, tutorials and usage of commonly used APIs.</td>
  </tr>
  <tr>
    <td rowspan="3" width="120" align="center" valign="middle"><b>Feishu (Lark)</b></td>
    <td>
      <img src="https://img.shields.io/badge/Diana%20Technical%20Manual-Docs%20(coming%20soon)-2E7D32?style=flat-square&logo=readthedocs&logoColor=white" alt="Diana Technical Manual">
    </td>
    <td>Diana technical manual (coming soon): product manual (robot arm, control box, teach pendant, compatibility), models and simulation, operation, safety, software development, applications and solutions, and FAQ.</td>
  </tr>
  <tr>
    <td>
      <a href="https://agilerobots.feishu.cn/wiki/space/7604738168612473794"><img src="https://img.shields.io/badge/Diana%20Resources-Docs-2E7D32?style=flat-square&logo=readthedocs&logoColor=white" alt="Diana Resources"></a>
    </td>
    <td>Diana resources and reference materials.</td>
  </tr>
  <tr>
    <td>
      <a href="https://agilerobots.feishu.cn/wiki/space/7620696065129417672"><img src="https://img.shields.io/badge/Thor%20Resources-Docs-2E7D32?style=flat-square&logo=readthedocs&logoColor=white" alt="Thor Resources"></a>
    </td>
    <td>Thor resources and reference materials.</td>
  </tr>
</table>

### 📧 Contact Us

---

For questions or support, email [service.apac@agile-robots.com](mailto:service.apac@agile-robots.com), visit [www.agile-robots.com](https://www.agile-robots.com), or open an issue in the relevant repository.
