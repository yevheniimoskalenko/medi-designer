<template>
  <div class="contant">
    <div class="container">
      <div class="row d-flex ">
        <div class="col-12 col-sm-12 col-md-6">
          <div class="content-middle">
            <div class="content-header">
              <h1 class="h1-header">Stay Productive & Work Remotely</h1>
              <p class="content-text">
                The key to work-from-home success is to create an enviroment
                that allows you to focus on the tasks at hand. Whether you are
                working from home for the first time.
              </p>
              <button type="button" class="btn btn-purple btn-lg">
                Learn More
              </button>
            </div>
          </div>
        </div>
        <div class="col-12 col-sm-12 col-md-6">
          <div class="content-image">
            <img src="@/assets/women.png" alt="girl" class="content-img" />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<style lang="scss" scoped>
.content-header {
  h1 {
    line-height: 76px;
    font-size: 72px;
    color: #1b0a42;
  }
  p {
    padding-bottom: 28px;
  }
}

.content-middle {
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}
@media (max-width: 576px) {
  .btn-purple {
    font-size: 14px;
  }
  .btn-purple:hover {
    color: rgb(241, 241, 241);
  }
  .contant {
    margin: 40px 0;
  }
  .content-image {
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    img {
      width: 100%;
    }
  }
  .content-header {
    h1 {
      font-size: 33px;
      line-height: 36px;
      text-align: center;
    }
    p {
      padding: 0px;
    }
  }
  .content-text {
    font-size: 16px;
    line-height: 25px;
    text-align: center;
  }
  .content-header {
    display: flex;
    height: 100%;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    button {
      margin-bottom: 30px;
    }
  }
}

@media (min-width: 576px) {
  .content-img {
    width: 100%;
  }
  .contant {
    margin: 40px 0;
  }
  .content-header {
    h1 {
      font-size: 45px;
      line-height: 50px;
      text-align: center;
    }
  }
  .content-text {
    text-align: center;
  }
  .content-header {
    display: flex;
    height: 100%;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    button {
      margin-bottom: 30px;
    }
  }
}

// Medium devices (tablets, 768px and up)
@media (min-width: 768px) {
  .content-header {
    h1 {
      font-size: 48px;
      line-height: 40px;
    }
  }
  .content-text {
    font-size: 16px;
    line-height: 22px;
  }
  .content-image {
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .content-img {
    width: 100%;
  }
  .content-middle {
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .contant {
    height: 90vh;
    display: flex;
    justify-content: center;
    align-items: center;
  }
}

// Large devices (desktops, 992px and up)
@media (min-width: 992px) {
  .contant {
    height: 90vh;
    display: flex;
    justify-content: center;
    align-items: center;
  }
}

// Extra large devices (large desktops, 1200px and up)
@media (min-width: 1200px) {
  .content-header {
    h1 {
      line-height: 76px;
      font-size: 72px;
      color: #1b0a42;
    }
  }
  .content-text {
    padding-bottom: 28px;
    font-size: 20px;
    line-height: 28px;
  }
  .contant {
    height: 90vh;
    display: flex;
    justify-content: center;
    align-items: center;
  }
}
</style>
