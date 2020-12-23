<template>
  <div class="navbar navbar-expand-lg navbar-light ">
    <div class="container-fluid wrapper-center">
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
.container-fluid {
  padding-left: 0;
  padding-right: 0;
}
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
  .wrapper-center {
    padding: 0px 20px;
  }
  .btn-purple {
    font-size: 14px;
  }
  .btn-link {
    text-decoration: none;
  }
  .sign {
    button {
      display: block;
    }
  }
}

@media (min-width: 576px) {
  .wrapper-center {
    padding: 0px 30px;
  }
  .btn-link {
    text-decoration: none;
  }
  .sign {
    button {
      display: block;
    }
  }
}

@media (min-width: 768px) {
  .btn-link {
    text-decoration: none;
  }
  .sign {
    button {
      display: block;
    }
  }
}

// Large devices (desktops, 992px and up)
@media (min-width: 992px) {
  .btn-link {
    text-decoration: none;
  }
}

// Extra large devices (large desktops, 1200px and up)
@media (min-width: 1200px) {
  .wrapper-center {
    padding: 0px 80px;
  }
}
</style>
