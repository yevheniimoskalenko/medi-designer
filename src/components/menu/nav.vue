<template>
  <div class="navbar navbar-expand-lg navbar-light ">
    <div class="container-fluid">
      <div class="logo">
        <a class="navbar-brand" href="#">
          <img src="@/assets/logo.png" alt="logo" loading="lazy" />
        </a>
      </div>

      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNavAltMarkup"
        aria-controls="navbarNavAltMarkup"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div
        class="collapse navbar-collapse align-middle"
        id="navbarNavAltMarkup"
      >
        <div class="navbar-nav">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
          <a class="nav-link" href="#">About</a>
          <a class="nav-link" href="#">Blog</a>
          <a class="nav-link" href="#">Contact</a>
          <div class="sign d-xl-none d-xxl-none d-lg-none">
            <button type="button" class="btn btn-link">Sign in</button>
            <button type="button" class="btn btn-purple btn-lg">Sign up</button>
          </div>
        </div>
      </div>
      <div class="navRight">
        <button type="button" class="btn btn-link d-none d-lg-block">
          Sign in
        </button>
        <button type="button" class="btn btn-purple btn-lg d-none d-lg-block">
          Sign up
        </button>
      </div>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.logo {
  margin-right: 100px;
}
.navbar {
  font-size: 16px;
  .nav-link {
    color: #1b0a42;
  }

  .navRight {
    width: 100%;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-end;
    .btn {
      display: flex;
    }
    .btn-link {
      text-decoration: none;
      display: block;
    }
  }
}
@media (max-width: 576px) {
  .btn-purple {
    font-size: 14px;
    text-decoration: none;
  }
}

@media (min-width: 576px) {
}

// Medium devices (tablets, 768px and up)
@media (min-width: 768px) {
}

// Large devices (desktops, 992px and up)
@media (min-width: 992px) {
}

// Extra large devices (large desktops, 1200px and up)
@media (min-width: 1200px) {
}
</style>
