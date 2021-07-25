<template>
  <div class="row">
    <div class="col px-5">
      <p class="subheader fw-bold mt-5">SKILLS</p>
      <hr />
      <div class="row">
        <div class="col-2">
          <img
            src="https://cdn.pixabay.com/photo/2017/08/05/11/16/logo-2582748_960_720.png"
            width="100%"
          />
        </div>
        <div class="col-2">
          <img
            src="https://cdn.pixabay.com/photo/2017/08/05/11/16/logo-2582747_960_720.png"
            width="100%"
          />
        </div>
        <div class="col-2">
          <img
            src="data:image/png;base64,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"
            width="100%"
          />
        </div>
        <div class="col-2">
          <img
            src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c3/Python-logo-notext.svg/480px-Python-logo-notext.svg.png"
            width="100%"
          />
        </div>
        <div class="col-2">
          <img
            src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/18/ISO_C%2B%2B_Logo.svg/1822px-ISO_C%2B%2B_Logo.svg.png"
            width="100%"
          />
        </div>
        <div class="col-2">
          <img
            src="https://cdn.freelogovectors.net/svg05/java-logo.svg"
            width="100%"
          />
        </div>
      </div>
      <p class="subheader fw-bold mt-5">PROJECTS</p>
      <hr />
      <div class="row">
        <div class="col-6">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title fw-bold">Automatic Fish Feeding</h5>
              <h6 class="card-subtitle mb-2 text-muted">
                เครื่องให้อาหารปลาอัตโนมัติ
              </h6>
              <hr />
              <p class="card-text">
                ทำเครื่องให้อาหารปลาอัตโนมัติ โดยการเขียน
                <b>C++</b> ควบคุมการทำงานของบอร์ด
                <b>ESP8266</b> และใช้แอปพลิเคชัน <b>Blink</b>
                ในการควบคุมหรือตั้งเวลาการให้อาหารปลา
              </p>
              <a
                href="https://github.com/jamettw/Project-Automatic-Fish-Feeding"
                class="btn btn-dark"
                >Github</a
              >
            </div>
          </div>
        </div>
        <div class="col-6">
          <div class="card">
            <div class="card-body">
              <h5 class="card-title fw-bold">
                Queue Reservation System of Medical Centre KMITL
              </h5>
              <h6 class="card-subtitle mb-2 text-muted">
                ระบบจองคิวคลินิกเวชกรรม สจล.
              </h6>
              <hr />
              <p class="card-text">
                เป็นโปรเจ็คที่ทำขึ้นเพื่ออำนวยความสะดวกให้ผู้ใช้บริการคลินิกโดยการลดขั้นตอนการจองคิวให้สะดวกรวดเร็วมากขึ้น
                และยังทำขึ้นเพื่อศึกษาและพัฒนาทักษะการใช้
                <b>Django Framework</b> อีกด้วย
              </p>
              <a
                href="https://github.com/jamettw/Queue-Reservation-System-of-Medical-Centre-KMITL"
                class="btn btn-dark"
                >Github</a
              >
            </div>
          </div>
        </div>
      </div>
      <p class="subheader fw-bold mt-5">CONTACT</p>
      <hr />
      <p>
        89/166 หมู่บ้านเลิศอุบล ซ.ร่วมมิตรพัฒนา 1 ถ.วัชรพล แขวงท่าแร้ง เขตบางเขน
        กทม 10220
      </p>
      <router-link
        :to="{
          name: 'contact',
        }"
      >
        <a href="" class="btn btn-dark">Click For More ...</a>
      </router-link>
    </div>
    <div class="col px-5">
      <p class="subheader fw-bold mt-5">EDUCATION</p>
      <hr />
      <div class="mx-5 px-4">
        <p class="def-txt">
          • <b>ปริญญาตรี</b><br />
          คณะเทคโนโลยีสารสนเทศ สาขาเทคโนโลยีสารสนเทศ แขนง Software Engineering
          สถาบันเทคโนโลยีพระจอมเกล้าเจ้าคุณทหารลาดกระบัง<br />
          2561-ปัจจุบัน<br /><br />
          • <b>มัธยมศึกษาตอนปลาย</b>
          <br />โรงเรียนพรหมานุสรณ์จังหวัดเพชรบุรี<br />
          2559-2561
        </p>
      </div>
      <p class="subheader fw-bold mt-5">EXPERIENCE</p>
      <hr />
      <div class="mx-5 px-4">
        <p class="def-txt">
          • <b>Staff ค่าย IT Camp 15 (IOT)</b><br />
          ดูแลน้องๆในค่าย สอนวิธีการควบคุมบอร์ด Arduino ด้วย C++
          ดูแลโปรเจคของน้องในค่าย<br /><br />
          • <b>TA Pre-Programming</b><br />
          เป็นกิจกรรมที่จะสร้างพื้นฐานสำหรับการเขียนโปรแกรม
          ให้น้องที่กำลังจะเข้าศึกษาในระดับชั้นปีที่ 1 โดยใช้ Python
        </p>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style>
.subheader {
  font-size: 2em;
}
.def-txt {
  text-align: left;
}
</style>