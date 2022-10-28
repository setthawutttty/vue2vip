<template>
          <div id="topmenu">
        <!-- Button trigger modal -->
        <div class="container">
          <div class="row">
            <div
              class="col-12 col-sm-12 col-md-12 col-lg-12 d-flex flex-row justify-content-center justify-content-sm-center justify-content-md-center justify-content-lg-center align-items-center my-2"
            >
              <a
                type="button"
                class="btn_md"
                data-bs-toggle="modal"
                data-bs-target="#staticBackdrop"
              >
                อัตราจ่าย
              </a>
              <a
                type="button"
                class="btn_md"
                data-bs-toggle="modal"
                data-bs-target="#staticBackdrop"
              >
                กฎกติกา
              </a>
              <a
                type="button"
                class="btn_mdl"
                data-bs-toggle="modal"
                data-bs-target="#staticBackdrop"
                ><i class="bi bi-line"></i>
                ติดต่อเรา
              </a>
            </div>
          </div>
        </div>
      </div>
      
      <div
    class="modal fade"
    id="staticBackdrop"
    data-bs-backdrop="static"
    data-bs-keyboard="false"
    tabindex="-1"
    aria-labelledby="staticBackdropLabel"
    aria-hidden="true"
  >
    <div class="modal-dialog">
      <div class="modal-content">
        <div class="modal-header">
          <h5 class="modal-title" id="staticBackdropLabel">อัตราจ่าย</h5>
          <button
            type="button"
            class="btn-close"
            data-bs-dismiss="modal"
            aria-label="Close"
          ></button>
        </div>
        <div class="modal-body">เเล้วเเต่จะเพิ่ม</div>
        <div class="modal-footer">
          <button type="button" class="btn btn-success" data-bs-dismiss="modal">
            ฉันเข้าใจเเละยอมรับ
          </button>
        </div>
      </div>
    </div>
  </div>
</template>
