<template>
  <div class="page">
    <div class="q-my-lg">
      <div>
        <q-card class="my-card bg-secondary text-white">
          <q-card-section>
            <p class="q-pl-xl title text-center">การอุ้มบุตร</p>
          </q-card-section>

          <q-separator dark />

          <q-card-section>
            <p class="text-pp">
              การอุ้มลูกน้อยด้วยท่าอุ้มลูกที่ถูกวิธีเป็นอีกเรื่องหนึ่งที่สำคัญมาก
              ๆ สำหรับคุณพ่อคุณแม่ทุกท่าน
              เพราะร่างกายลูกน้อยในขวบปีแรกยังมีการพัฒนาไม่เต็มที่
              กล้ามเนื้อต่าง ๆ โดยเฉพาะกล้ามเนื้อคอยังไม่แข็งแรงเท่าที่ควร
              ดังนั้น
              การอุ้มลูกด้วยท่าอุ้มลูกที่ถูกวิธีจะส่งผลดีต่อพัฒนาการด้านร่างกายและจิตใจของลูก
              ทำให้ลูกน้อยสามารถรู้สึกปลอดภัย สามารถสัมผัสความรัก ความอบอุ่น
              และช่วยสร้างความไว้วางใจระหว่างคุณพ่อคุณแม่และบุคคลใกล้ชิดได้เป็นอย่างดี
              โดยท่าที่ใช้อุ้มทารก โดยเฉพาะวัยแรกเกิดถึง 3 เดือนมีดังนี้
            </p>
          </q-card-section>
        </q-card>

        <q-card class="my-card bg-secondary text-white q-mt-md">
          <q-card-section>
            <p class="title">
              5 วิธีอุ้มทารกแรกเกิดให้ถูกวิธี ท่าไหนดีและปลอดภัยกับลูกน้อย
            </p>
          </q-card-section>

          <q-separator dark />

          <q-card-section
            ><div class="text-p">
              <ol>
                <li>
                  <p>ท่าไกวเปลอุ้มลูก</p>
                  <div class="q-mt-xl content-index">
                    <img
                      class="img-box-shadow"
                      src="~/assets/ท่าไกวเปลอุ้มลูก.jpg"
                    />
                  </div>
                </li>
                <li>
                  <p>ท่าอุ้มลูกนอนคว่ำ</p>
                  <div class="q-mt-xl content-index">
                    <img
                      class="img-box-shadow"
                      src="~/assets/ท่าอุ้มลูกพาดบ่า.jpg"
                    />
                  </div>
                </li>
                <li>
                  <p>ท่าอุ้มลูกพาดบ่า</p>
                  <div class="q-mt-xl content-index">
                    <img
                      class="img-box-shadow"
                      src="~/assets/ท่าอุ้มลูกวางตัก.jpg"
                    />
                  </div>
                </li>
                <li>
                  <p>ท่าอุ้มลูกวางตัก</p>
                  <div class="q-mt-xl content-index">
                    <img
                      class="img-box-shadow"
                      src="~/assets/ท่าอุ้มลูกนอนคว่ำ.jpg"
                    />
                  </div>
                </li>
                <li>
                  <p>ท่าอุ้มลูกหันหน้าเข้าหากัน</p>
                  <div class="q-mt-xl content-index">
                    <img
                      class="img-box-shadow"
                      src="~/assets/ท่าอุ้มลูกหันหน้าเข้าหากัน.jpg"
                    />
                  </div>
                </li>
              </ol>
            </div>
          </q-card-section>
        </q-card>
      </div>
    </div>
  </div>
</template>

<style scoped>
.page {
  /* background-color: red; */
  position: relative;
  padding: 10px;
}
.q-pl-xl {
  margin: 12px;
}
.head-5 {
  padding: 0px;
}
.title {
  font-size: 28px;
  font-weight: bold;
  margin-left: 12px;
  font-family: "Prompt", sans-serif;
}
.text-p {
  padding-left: 55px;
  font-size: 28px;
  font-weight: bold;
}
.text-pp {
  padding: 0 31px;
  font-size: 18px;
  text-indent: 2rem;
}
.content-index {
  padding: 15px;
  margin: 0;
  width: 100%;
  height: auto;
  min-width: 300px;
  max-width: 100%;
  overflow: hidden;
}
.content-index > img {
  width: 100%;
  height: 100%;
  min-height: 300px;
  display: block;
  margin: 0 auto;
  border-radius: 10px;
  object-fit: cover;
}
.img-box-shadow {
  box-shadow: rgba(17, 17, 26, 0.05) 0px 1px 0px,
    rgba(17, 17, 26, 0.1) 0px 0px 8px;
}
</style>
