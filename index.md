# Zhicheng Song

I am a Ph.D. student in Robotics and Autonomous Systems at [The Hong Kong University of Science and Technology (Guangzhou)](https://www.hkust-gz.edu.cn/), advised by [Prof. Jun Ma](https://personal.hkust-gz.edu.cn/junma/index.html). I am affiliated with the [Intelligent Autonomous Driving Center (IADC)](https://personal.hkust-gz.edu.cn/junma/Join.html) and the [Robot Motion Planning and Control Lab](https://personal.hkust-gz.edu.cn/junma/index.html).

My research focuses on robotic motion planning, safe autonomy, and robot design, with an emphasis on enabling robots to operate reliably in complex, cluttered, and partially unknown environments. I am broadly interested in safe motion planning, robot perception, mobile manipulation, legged and wheeled-legged robots, and learning-based robot control.

Before joining HKUST(GZ), I received my M.S. degree in Mechanical Engineering with a Robotics Track from [Columbia University](https://www.columbia.edu/), where I worked with [Prof. Hod Lipson](https://www.me.columbia.edu/faculty/hod-lipson) at the [Creative Machines Lab](https://www.creativemachineslab.com/). I received my B.S. degree in Marine Engineering from [Huazhong University of Science and Technology](https://english.hust.edu.cn/).

---

## Publications

<!-- Please see my [Google Scholar](#) for a full list of publications. -->

<style>
.pub {
  display: flex;
  align-items: flex-start;
  margin-bottom: 34px;
}

.pub-img {
  width: 210px;
  min-width: 210px;
  margin-right: 28px;
}

.pub-img img {
  width: 200px;
  border-radius: 3px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.18);
}

.pub-content {
  flex: 1;
}

.pub-title {
  font-size: 16px;
  font-weight: 600;
  color: #000000;
  line-height: 1.35;
  margin-bottom: 3px;
}

.pub-authors {
  font-size: 14px;
  line-height: 1.35;
  margin-bottom: 2px;
}

.pub-authors strong {
  font-weight: 700;
  text-decoration: underline;
}

.pub-venue {
  font-size: 14px;
  font-style: italic;
  line-height: 1.35;
  margin-bottom: 8px;
}

.pub-tags {
  margin-bottom: 10px;
}

.pub-tag {
  display: inline-block;
  background-color: #b81bb3;
  color: white;
  font-size: 11px;
  font-weight: 600;
  padding: 3px 9px;
  border-radius: 4px;
  margin-right: 6px;
  margin-bottom: 5px;
}

.pub-links a {
  display: inline-block;
  border: 1px solid #000;
  color: #000;
  padding: 3px 14px;
  font-size: 12px;
  margin-right: 8px;
  margin-bottom: 4px;
  text-decoration: none;
}

.pub-links a:hover {
  background-color: #f0f0f0;
}

@media screen and (max-width: 700px) {
  .pub {
    display: block;
  }

  .pub-img {
    width: 100%;
    min-width: 0;
    margin-right: 0;
    margin-bottom: 12px;
  }

  .pub-img img {
    width: 100%;
  }
}
</style>

<div class="pub">
  <div class="pub-img">
    <img src="./assets/safe_navigation.png" alt="Safe Navigation">
  </div>
  <div class="pub-content">
    <div class="pub-title">Safe Navigation in Unknown and Cluttered Environments via Direction-Aware Convex Free-Region Generation</div>
    <div class="pub-authors"><strong>Zhicheng Song</strong>, Yongjian Li, Kai Chen, Yulin Li, Fan Shi, and Jun Ma</div>
    <div class="pub-venue">arXiv preprint arXiv:2604.23648, 2026</div>
    <div class="pub-tags">
      <span class="pub-tag">safe navigation</span>
      <span class="pub-tag">motion planning</span>
      <span class="pub-tag">convex free region</span>
    </div>
    <div class="pub-links">
      <a href="https://arxiv.org/pdf/2604.23648">PDF</a>
      <a href="https://github.com/ZhichengSong6/FRGraph">WEBSITE</a>
    </div>
  </div>
</div>

<div class="pub">
  <div class="pub-img">
    <img src="./assets/ncdf.png" alt="Neural Configuration Space Distance Field">
  </div>
  <div class="pub-content">
    <div class="pub-title">Fast and Safe Trajectory Optimization for Mobile Manipulators With Neural Configuration Space Distance Field</div>
    <div class="pub-authors">Yulin Li, Zhiyuan Song, Yiming Li, <strong>Zhicheng Song</strong>, Kai Chen, Chunxin Zheng, Zhihai Bi, Jiahang Cao, Sylvain Calinon, Fan Shi, and Jun Ma</div>
    <div class="pub-venue">arXiv preprint arXiv:2601.18548, 2026</div>
    <div class="pub-tags">
      <span class="pub-tag">mobile manipulator</span>
      <span class="pub-tag">trajectory optimization</span>
      <span class="pub-tag">collision avoidance</span>
      <span class="pub-tag">neural distance field</span>
    </div>
    <div class="pub-links">
      <a href="https://arxiv.org/pdf/2601.18548">PDF</a>
      <a href="https://yulinli0.github.io/GCDF/">WEBSITE</a>
    </div>
  </div>
</div>

<div class="pub">
  <div class="pub-img">
    <img src="./assets/flores.jpg" alt="A Reconfigured Wheel-Legged Robot">
  </div>
  <div class="pub-content">
    <div class="pub-title">A Reconfigured Wheel-Legged Robot for Enhanced Steering and Adaptability</div>
    <div class="pub-authors"><strong>Zhicheng Song</strong>, Jinglan Xu, Chunxin Zheng, Yulin Li, Zhihai Bi, and Jun Ma</div>
    <div class="pub-venue">IEEE Robotics and Automation Letters, 2026</div>
    <div class="pub-tags">
      <span class="pub-tag">wheel-legged robot</span>
      <span class="pub-tag">robot design</span>
      <span class="pub-tag">locomotion</span>
    </div>
    <div class="pub-links">
      <a href="https://ieeexplore.ieee.org/document/11495517">PDF</a>
      <a href="https://github.com/ZhichengSong6/FLORES">WEBSITE</a>
    </div>
  </div>
</div>

<div class="pub">
  <div class="pub-img">
    <img src="./assets/frtree.png" alt="FRTree Planner">
  </div>
  <div class="pub-content">
    <div class="pub-title">FRTree Planner: Robot Navigation in Cluttered and Unknown Environments with Tree of Free Regions</div>
    <div class="pub-authors">Yulin Li, <strong>Zhicheng Song(Co-first)</strong>, Chunxin Zheng, Zhihai Bi, Kai Chen, Michael Yu Wang, and Jun Ma</div>
    <div class="pub-venue">IEEE Robotics and Automation Letters, 2025</div>
    <div class="pub-tags">
      <span class="pub-tag">robot navigation</span>
      <span class="pub-tag">free region</span>
      <span class="pub-tag">unknown environments</span>
    </div>
    <div class="pub-links">
      <a href="https://ieeexplore.ieee.org/document/10897898/">PDF</a>
      <a href="https://github.com/YulinLi0/navigation_with_tree_of_free_regions">WEBSITE</a>
    </div>
  </div>
</div>

<div class="pub">
  <div class="pub-img">
    <img src="./assets/slip_detection.png" alt="State Estimation for Wheeled-Legged Robot with Slip Detection">
  </div>
  <div class="pub-content">
    <div class="pub-title">State Estimation for Wheeled-Legged Robot with Slip Detection</div>
    <div class="pub-authors">Jinglan Xu, <strong>Zhicheng Song</strong>, Chunxin Zheng, and Jun Ma</div>
    <div class="pub-venue">IEEE International Conference on Robotics and Biomimetics (ROBIO), 2024</div>
    <div class="pub-tags">
      <span class="pub-tag">wheeled-legged robot</span>
      <span class="pub-tag">state estimation</span>
      <span class="pub-tag">slip detection</span>
    </div>
    <div class="pub-links">
      <a href="https://ieeexplore.ieee.org/abstract/document/10907492">PDF</a>
    </div>
  </div>
</div>

<div class="pub">
  <div class="pub-img">
    <img src="./assets/flexipod.jpg" alt="A Legged Soft Robot Platform for Dynamic Locomotion">
  </div>
  <div class="pub-content">
    <div class="pub-title">A Legged Soft Robot Platform for Dynamic Locomotion</div>
    <div class="pub-authors">Boxi Xia, Jiaming Fu, Hongbo Zhu, <strong>Zhicheng Song</strong>, Yibo Jiang, and Hod Lipson</div>
    <div class="pub-venue">IEEE International Conference on Robotics and Automation (ICRA), 2021</div>
    <div class="pub-tags">
      <span class="pub-tag">soft robot</span>
      <span class="pub-tag">dynamic locomotion</span>
      <span class="pub-tag">robot design</span>
    </div>
    <div class="pub-links">
      <a href="https://ieeexplore.ieee.org/document/9561018">PDF</a>
      <a href="https://boxixia.github.io/Flexipod/">WEBSITE</a>
    </div>
  </div>
</div>

---

## Contact

Email: [zsong469@connect.hkust-gz.edu.cn](mailto:zsong469@connect.hkust-gz.edu.cn)  
<!-- Google Scholar: [Google Scholar](#)   -->
GitHub: [GitHub](https://github.com/ZhichengSong6)