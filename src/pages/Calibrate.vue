<template>
  <div class="content">
    <div class="container-fluid">
      <div class="row">
        <div class="col-md-8 ml-auto mr-auto">
          <div class="card">
            <div class="header text-center">
              <h4 class="title">Place a checkerboard in the scene</h4>
              <p class="category"><img src="img/calibration/checkerboard-placement.png" /></p>
              <br>
            </div>
            <div class="content table-responsive table-upgrade">
              <table class="table">
                <thead>
                <tr>
                  <th></th>
                  <th class="text-center"></th>
                </tr>
                </thead>
                <tbody>
                <tr>
                  <td><i class="fa fa-check text-success"></i></td>
                  <td style="width: 720px">It should be visible by all cameras (nothing in the way of cameras' view when hitting Calibrate)</td>
                </tr>
                <tr>
                  <td><i class="fa fa-check text-success"></i></td>
                  <td>It should be horizontal (longer side on the floor)</td>
                </tr>
                <tr>
                  <td><i class="fa fa-check text-success"></i></td>
                  <td>It should be perpendicular to the floor (not lying on the floor)</td>
                </tr>

                <tr class="last-row">
                  <td></td>
                  <td>
                    <a href="#" class="upgrade-table-btn btn btn-round btn-fill btn-primary">Start</a>
                  </td>
                </tr>
                </tbody>
              </table>

            </div>
          </div>
        </div>
      </div>

    </div>
  </div>
</template>
<script>
  export default {}
</script>
<style lang="scss">
  .upgrade-table-btn {
    width: 160px;
    &:first-child {
      margin-right: 10px;
    }
  }
</style>
