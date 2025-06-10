---
permalink: /projects/autonomous-vehicle/
title: "Autonomous Vehicle in ISLab HCMUTE"
author_profile: true
---

<!-- ---
permalink: /
title: "Autonomous Vehicle in ISLab HCMUTE"
excerpt: ""
author_profile: true
redirect_from: 
  - /projects/autonomous-vehicle/
--- -->

<link rel="stylesheet" href="{{ '/assets/css/main.css' | relative_url }}" />
<!-- <link rel="stylesheet" href="/assets/css/main.css" /> -->
<link rel="stylesheet" href="{{ '/assets/css/academicons.css' | relative_url }}" />
<script src="{{ '/assets/js/main.min.js' | relative_url }}"></script>

<link rel="icon" href="/images/avatar.png" />

<div class="project-container" style="display: flex; gap: 20px; align-items: flex-start; flex-wrap: wrap;">

  <!-- Cột trái: 2 video xếp dọc, có khoảng cách -->
  <div class="project-media" style="flex: 1; min-width: 300px; max-width: 480px;">
    <div style="display: flex; flex-direction: column; gap: 24px;">
      <!-- Video 1 -->
      <iframe width="100%" height="100%" style="border-radius: 8px;"
        src="https://www.youtube.com/embed/LpsxEhBA7x4"
        title="Autonomous Vehicle Demo 1"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen>
      </iframe>

      <!-- Video 2 -->
      <iframe width="100%" height="100%" style="border-radius: 8px;"
        src="https://www.youtube.com/embed/eoENRmZNXMg"
        title="Autonomous Vehicle Demo 2"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen>
      </iframe>
    </div>
  </div>

  <!-- Cột phải: mô tả -->
  <div class="project-description" style="flex: 2; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">
    <h1>Autonomous Vehicle in ISLab HCMUTE</h1>

    <p>
      Developed a real-time autonomous vehicle operating within the campus of Ho Chi Minh City University of Technology and Education (HCMUTE), leveraging artificial intelligence and multi-sensor fusion to perform localization, obstacle avoidance, and autonomous navigation in real-world outdoor environments.
    </p>

    <h3>Goal:</h3>
    <p>
      Develop a real-time autonomous vehicle capable of navigating complex environments within the campus of HCMUTE, using AI-driven perception and multisensor fusion.
    </p>

    <h3>Algorithm:</h3>
    <p>
      The system uses multi-sensor fusion that combines LiDAR, camera, and RTK GPS data to enhance localization accuracy and environmental understanding. Deep learning-based vision algorithms are employed, including YOLO-based object detection, semantic segmentation models such as BiseNet, LiteSeg, and DeepLab, depth estimation using DepthAnything, MiDas, and MonoDepth, along with Ultra-Fast-Lane-Detection for lane marking perception.
    </p>

    <h3>My Role:</h3>
    <p>
      Developed vision algorithms and optimized real-time performance to ensure smooth operation on resource-constrained hardware.
    </p>

  </div>

</div>


<script>
  document.addEventListener("DOMContentLoaded", function () {
    document.querySelectorAll('a[href^="/"]').forEach(function (link) {
      // Nếu là link nội bộ có target _blank thì loại bỏ
      if (link.target === "_blank") {
        link.target = "_self";
      }

      // Hoặc chặn mặc định và thay bằng navigation
      link.addEventListener("click", function (e) {
        e.preventDefault();
        window.location.href = link.href;
      });
    });
  });
</script>