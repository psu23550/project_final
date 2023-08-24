<template>
  <div class="page">
    <div class="q-my-lg">
      <q-card class="my-card bg-secondary text-white">
        <q-card-section>
          <p class="title text-center">ความผูกพันกับบุตรคืออะไร</p>
        </q-card-section>

        <q-separator dark />

        <q-card-section>
          <p class="text-p">
            “ความผูกพันกับบุตร” คือ พฤติกรรมของมารดาที่แสดงความรักใคร่ ผูกพัน
            การเอาใจใส่ เสียสละที่มีต่อบุตร เกิดขึ้นทีละเล็กละน้อย
            ตั้งแต่ระยะตั้งครรภ์ และ ระยะคลอด และระยะหลังคลอด
            ความผูกพันระหว่างมารดากับบุตรมีความคงทนถาวร
            มีผลต่อความอยู่รอดและพัฒนาการของบุตร
          </p>
        </q-card-section>
      </q-card>

      <div class="img-fluid rounded-pill q-ma-md">
        <div class="row justify-center">
          <img
            class="border-radius-5 image-box-shadow"
            src="~/assets/baby.jpg"
          />
        </div>
      </div>

      <q-card class="my-card bg-secondary text-white">
        <q-card-section>
          <p class="title">การสร้างความผูกพันกับบุตรต้องทำอย่างไร</p>
        </q-card-section>

        <q-separator dark />

        <q-card-section>
          <div class="text-p">
            <ol>
              <li>
                <p>หาสถานที่ฝากครรภ์และคลอดที่ปลอดภัย</p>
              </li>
              <li>
                <p>
                  ฝากครรภ์จากสถานพยาบาลอย่างน้อย 4 ครั้งและมาตรวจครรภ์ตามนัด
                </p>
              </li>
              <li>
                <p>หาความรู้เกี่ยวกับบุตรแรกเกิดและพฤติกรรมที่บุตรแสดงออก</p>
              </li>
              <li><p>ตั้งชื่อ เรียกชื่อบุตร</p></li>
              <li>
                <p>
                  นับและบันทึกการดิ้นของบุตรทุกวัน
                  นับผลรวมของจำนวนการดิ้นของบุตรใน 3
                  เวลาหลังรับประทานอาหารถ้าผลการนับพบว่าน้อยกว่า 10 ครั้งต่อ 12
                  ชั่วโมง ให้รีบมาโรงพยาบาลเพื่อประเมินสุขภาพบุตรในครรภ์ต่อไป
                </p>
              </li>
              <li><p>ลูบหน้าท้องของมารดาเมื่อบุตรในท้องดิ้น</p></li>
              <li>
                <p>
                  ลูบคลำส่วนต่างๆ ของบุตรผ่านหน้าท้อง เช่น
                  เลือกห้องที่เก็บเสียงไม่รบกวน ควรทำหลังอาหารเย็นอย่างน้อย 1
                  ครั้งจนถึงคลอด
                </p>
              </li>
            </ol>
          </div>
        </q-card-section>
      </q-card>

      <q-card class="my-card bg-secondary text-white q-my-md">
        <q-card-section>
          <div class="text-p">
            <table>
              <tr>
                <th>ความสำคัญต่อบุตร</th>
                <th>ความสำคัญต่อมารดา</th>
              </tr>
              <tr>
                <td>
                  ทำให้บุตรมีการเจริญเติบโตและพัฒนาการด้านร่างกาย จิตใจอารมณ์
                  และสติปัญญาที่ดี
                </td>
                <td>
                  <ol>
                    <li>มีความรักใคร่ ผูกพันต่อบุตรมากขึ้น</li>
                    <li>มีความสนใจต่อภาวะสุขภาพของบุตรในครรภ์</li>
                    <li>
                      มีความสนใจที่จะกระตุ้นพัฒนาการของบุตรในครรภ์ด้วยการลูบหรือสัมผัสบุตรผ่านทางหน้าท้อง
                    </li>
                  </ol>
                </td>
              </tr>
              <tr></tr>
            </table>
          </div>
        </q-card-section>
      </q-card>
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
  /* margin-left: 12px; */
  font-family: "Prompt", sans-serif;
  margin-bottom: 0;
}
.text-p {
  padding-left: 55px;
  font-size: 18px;
}

.colum {
  display: flex;
  justify-content: space-between;
  padding: 50px;
}
td,
th {
  border: 1px solid #dddddd;
  text-align: left;
  padding: 8px;
  padding-top: 8px;
}
</style>
