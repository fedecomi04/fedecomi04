<h1 align="center">Hi, I'm Federico 👋</h1>

<p align="center">
  Mechanical engineer focused on robotics. <br/>
  B.Sc. Mechanical Engineering at <a href="https://www.epfl.ch/">EPFL</a> · exchange year at <a href="https://www.tum.de/">TU München</a> · M.Sc. Mechanical Engineering (Robotics) at <a href="https://ethz.ch/">ETH Zürich</a>.
</p>

<p align="center">
  Currently building a <b>Gaussian-splatting pipeline for teleoperation</b>.
</p>

---

### 🤖 Featured projects

<table>
  <tr>
    <td width="33%" valign="top">
      <h4><a href="https://github.com/fedecomi04/opensource-spinal-quadruped">opensource-spinal-quadruped</a></h4>
      <a href="https://github.com/fedecomi04/opensource-spinal-quadruped">
        <img src="https://raw.githubusercontent.com/fedecomi04/opensource-spinal-quadruped/main/docs/images/hero_quadruped.png" />
      </a>
      <p><b>ASTRA</b> — open-source 9.5 kg quadruped with a 3-DoF active spine. Full mechanical CAD, STM32 firmware, ROS 2 control stack, MuJoCo simulation. Built as my BSc thesis to be reproducible for ~€1.5 k.</p>
      <sub>ROS 2 · STM32 · MuJoCo · Quasi-direct drive · Fusion 360</sub>
    </td>
    <td width="33%" valign="top">
      <h4><a href="https://github.com/fedecomi04/Monocular_VO_pipeline">Monocular_VO_pipeline</a></h4>
      <a href="https://github.com/fedecomi04/Monocular_VO_pipeline">
        <img src="https://raw.githubusercontent.com/fedecomi04/Monocular_VO_pipeline/main/docs/media/kitti_vo_scaledrift.gif" />
      </a>
      <p>Monocular visual SLAM pipeline for ETH's <i>Vision Algorithms for Mobile Robotics</i>. KLT/SIFT tracking, RANSAC PnP, local bundle adjustment, SIFT loop closure with Sim(3) pose-graph optimisation, ground-plane scale recovery.</p>
      <sub>Python · OpenCV · NumPy · KITTI / Malaga</sub>
    </td>
    <td width="33%" valign="top">
      <h4><a href="https://github.com/fedecomi04/pdm4ar-coursework">pdm4ar-coursework</a></h4>
      <a href="https://github.com/fedecomi04/pdm4ar-coursework">
        <img src="https://raw.githubusercontent.com/fedecomi04/pdm4ar-coursework/main/docs/media/ex13_spaceship_docking.gif" />
      </a>
      <p>14 exercises from ETH <i>Planning &amp; Decision Making for Autonomous Robots</i>. Graph search (A*, Dijkstra), MDPs, Dubins/Reeds-Shepp, collision checking, <b>SCvx for spaceship docking</b>, and a multi-agent goal-collection final project.</p>
      <sub>Python · CVXPY · NetworkX · SCvx</sub>
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <h4><a href="https://github.com/fedecomi04/RL_LeRobot_pickandplace">RL_LeRobot_pickandplace</a></h4>
      <a href="https://github.com/fedecomi04/RL_LeRobot_pickandplace">
        <img src="https://raw.githubusercontent.com/fedecomi04/RL_LeRobot_pickandplace/main/docs/media/eval3_sim_early.gif" />
      </a>
      <p>Sim-to-real visual RL for colour-queried cube pick-and-place on the <b>SO-101 arm</b> with a wrist camera. Custom realistic ManiSkill3 env, SAC + split policies, FK/IK place, real-robot eval orchestrators. ETH Robot Learning course.</p>
      <sub>PyTorch · ManiSkill3 · SAC · SO-101 · Sim2Real</sub>
    </td>
    <td width="33%" valign="top">
      <h4><a href="https://github.com/fedecomi04/flappy-bird-with-dynamicprogramming">flappy-bird-with-dynamicprogramming</a></h4>
      <a href="https://github.com/fedecomi04/flappy-bird-with-dynamicprogramming">
        <img src="https://raw.githubusercontent.com/fedecomi04/flappy-bird-with-dynamicprogramming/main/docs/images/optimal_policy_demo.gif" />
      </a>
      <p>Side-scrolling <b>flappy-bird as a stochastic shortest-path problem</b>: 7 770 states, delayed/stochastic flaps, solved offline by value &amp; policy iteration (with a warm-start hyperparameter study). ETH DPOC course.</p>
      <sub>Python · NumPy · SciPy · Pygame · Value/Policy Iteration</sub>
    </td>
    <td width="33%" valign="top">
      <!-- spacer to keep the bottom row visually balanced -->
    </td>
  </tr>
</table>

---

### 🔧 What I work on

- **Gaussian splatting & teleoperation** — current focus: building a 3D-GS pipeline that reconstructs operator environments fast enough to drive a remote robot.
- **Reinforcement learning for manipulation** — visual SAC, sim-to-real, custom realistic envs.
- **Legged robotics** — mechanical design, quasi-direct-drive actuation, MuJoCo-in-the-loop control, ROS 2.
- **Computer vision** — monocular SLAM, feature tracking, bundle adjustment, place recognition.
- **Planning & control** — graph search, MDPs, dynamic programming, trajectory optimisation (SCvx, MPC), multi-agent coordination.
- **Embedded** — STM32 firmware, CAN-FD, low-level motor protocols.

### 🛠️ Tech I reach for

`Python` · `C++` · `ROS 2` · `MuJoCo` · `ManiSkill3` · `PyTorch` · `OpenCV` · `NumPy` · `SciPy` · `STM32CubeIDE` · `Fusion 360` · `CVXPY` · `Bash`

### 📫 Reach out

Open an issue on any of the project repos, or DM me on GitHub.
