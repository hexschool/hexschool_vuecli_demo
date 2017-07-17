<template>
  <div class="chatroom mt-3">
    <div class="container-fluid">
      <div class="row">
        <div class="col-9">
          <div class="card card-outline-primary">
            <div class="card-block">
              <div class="input-group">
                <input type="text" class="form-control" placeholder="輸入對話">
                <span class="input-group-btn">
                  <button class="btn btn-primary" type="button">送出</button>
                </span>
              </div>
              <ul class="list-unstyled row">
                <li class="media mt-3 col-9">
                  <img class="d-flex mr-3" width="50" height="50" src="http://lorempixel.com/50/50/sports" alt=""> Î
                  <div class="media-body">
                    <h5 class="mt-0 mb-1">List-based media object</h5>
                    Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante sollicitudin. Cras purus odio, vestibulum in vulputate at, tempus viverra turpis. Fusce condimentum nunc ac nisi vulputate fringilla. Donec lacinia congue felis in faucibus.
                  </div>
                </li>
                <li class="media mt-3 col-9">
                  <img class="d-flex mr-3" width="50" height="50" src="http://lorempixel.com/50/50/sports" alt=""> Î
                  <div class="media-body">
                    <h5 class="mt-0 mb-1">List-based media object</h5>
                    Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante sollicitudin. Cras purus odio, vestibulum in vulputate at, tempus viverra turpis. Fusce condimentum nunc ac nisi vulputate fringilla. Donec lacinia congue felis in faucibus.
                  </div>
                </li>
                <li class="media mt-3 col-9 offset-3 text-success">
                  <div class="media-body">
                    <h5 class="mt-0 mb-1">List-based media object</h5>
                    Cras sit amet nibh libero, in gravida nulla. Nulla vel metus scelerisque ante sollicitudin. Cras purus odio, vestibulum in vulputate at, tempus viverra turpis. Fusce condimentum nunc ac nisi vulputate fringilla. Donec lacinia congue felis in faucibus.
                  </div>
                  <img class="d-flex ml-3" width="50" height="50" src="http://lorempixel.com/50/50/sports" alt="">
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="col-3">
          <div class="card">
            <div class="card-header">
              你的資料
            </div>
            <div class="card-block">
              <div class="form-group">
                <label for="username">姓名</label>
                <input type="text" class="form-control" id="username" placeholder="輸入姓名">
                <small class="form-text text-muted">請輸入個人姓名開始使用聊天室</small>
              </div>
              <button type="button" class="btn btn-primary">送出</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  
  </div>
</template>

<script>
export default {
  name: 'hello',
  data() {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>

</style>
