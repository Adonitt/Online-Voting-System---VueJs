// TheSideBar.vue
<script setup>

</script>

<template>
  <div class="sidebar">
    <div class="sidebar-logo">
      <!-- Logo Header -->
      <div class="logo-header" data-background-color="white">
        <a href="index.html" class="logo">
          <img
              src="@/assets/img/foto/ks.jpeg"
              alt="navbar brand"
              class="navbar-brand"
              height="50px"
              width="50px"
        </a>
        <button class="topbar-toggler more">
          <i class="gg-more-vertical-alt"></i>
        </button>
      </div>
      <!-- End Logo Header -->
    </div>
    <div class="sidebar-wrapper scrollbar scrollbar-inner">
      <div class="sidebar-content">
        <ul class="nav nav-secondary">
          <li class="nav-item active">
            <a
                data-bs-toggle="collapse"
                href="#dashboard"
                class="collapsed"
                aria-expanded="false"
            >
              <i class="fas fa-home"></i>
              <p>Dashboard</p>
              <span class="caret"></span>
            </a>
            <div class="collapse" id="dashboard">
              <ul class="nav nav-collapse">
                <li>
                  <a href="../demo1/index.html">
                    <span class="sub-item">Dashboard 1</span>
                  </a>
                </li>
              </ul>
            </div>
          </li>
          <li class="nav-section">
                <span class="sidebar-mini-icon">
                  <i class="fa fa-ellipsis-h"></i>
                </span>
            <h4 class="text-section">Components</h4>
          </li>
          <li class="nav-item">
            <a data-bs-toggle="collapse" href="#base">
              <i class="fas fa-layer-group"></i>
              <p>Base</p>
              <span class="caret"></span>
            </a>
            <div class="collapse" id="base">
              <ul class="nav nav-collapse">
                <li>
                  <a href="components/avatars.html">
                    <span class="sub-item">Avatars</span>
                  </a>
                </li>
                <li>
                  <a href="components/buttons.html">
                    <span class="sub-item">Buttons</span>
                  </a>
                </li>
                <li>
                  <a href="components/gridsystem.html">
                    <span class="sub-item">Grid System</span>
                  </a>
                </li>
                <li>
                  <a href="components/panels.html">
                    <span class="sub-item">Panels</span>
                  </a>
                </li>
                <li>
                  <a href="components/notifications.html">
                    <span class="sub-item">Notifications</span>
                  </a>
                </li>
                <li>
                  <a href="components/sweetalert.html">
                    <span class="sub-item">Sweet Alert</span>
                  </a>
                </li>
                <li>
                  <a href="components/font-awesome-icons.html">
                    <span class="sub-item">Font Awesome Icons</span>
                  </a>
                </li>
                <li>
                  <a href="components/simple-line-icons.html">
                    <span class="sub-item">Simple Line Icons</span>
                  </a>
                </li>
                <li>
                  <a href="components/typography.html">
                    <span class="sub-item">Typography</span>
                  </a>
                </li>
              </ul>
            </div>
          </li>
          <li class="nav-item">
            <a data-bs-toggle="collapse" href="#sidebarLayouts">
              <i class="fas fa-th-list"></i>
              <p>Sidebar Layouts</p>
              <span class="caret"></span>
            </a>
            <div class="collapse" id="sidebarLayouts">
              <ul class="nav nav-collapse">
                <li>
                  <a href="sidebar-style-2.html">
                    <span class="sub-item">Sidebar Style 2</span>
                  </a>
                </li>
                <li>
                  <a href="icon-menu.html">
                    <span class="sub-item">Icon Menu</span>
                  </a>
                </li>
              </ul>
            </div>
          </li>

        </ul>
      </div>
    </div>
  </div>
</template>
