# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: main-web/travel/travel-normal-flow.spec.ts >> travel-normal-ต่างประเทศ-รายเที่ยว-เครื่องบิน 2 คน
- Location: tests/main-web/travel/travel-normal-flow.spec.ts:65:5

# Error details

```
Error: expect(locator).toBeVisible() failed

Locator: getByTestId('price')
Expected: visible
Timeout: 30000ms
Error: element(s) not found

Call log:
  - Expect "toBeVisible" with timeout 30000ms
  - waiting for getByTestId('price')

```

# Page snapshot

```yaml
- generic [active] [ref=e1]:
  - generic [ref=e3]:
    - banner [ref=e5]:
      - generic [ref=e6]:
        - navigation [ref=e7]:
          - button "open drawer" [ref=e8] [cursor=pointer]:
            - img [ref=e9]
        - generic [ref=e11]:
          - link "TQM Logo" [ref=e12] [cursor=pointer]:
            - /url: /
            - img "TQM Logo" [ref=e13]
          - button "login เข้าสู่ระบบ/สมัครสมาชิก" [ref=e14] [cursor=pointer]:
            - img "login" [ref=e16]
            - text: เข้าสู่ระบบ/สมัครสมาชิก
    - main [ref=e17]:
      - generic [ref=e19]:
        - generic [ref=e20]:
          - img "step0" [ref=e21]
          - generic [ref=e22]: ค้นหา แผนประกัน
        - progressbar [ref=e24]
        - generic [ref=e26]:
          - img "step1" [ref=e27]
          - generic [ref=e28]: เลือก แผนประกัน
        - progressbar [ref=e30]
        - generic [ref=e32]:
          - img "step2" [ref=e33]
          - generic [ref=e34]: ข้อมูล กรมธรรม์
        - progressbar [ref=e36]
        - generic [ref=e38]:
          - img "step3" [ref=e39]
          - generic [ref=e40]: ชำระเงิน
      - generic [ref=e42]:
        - generic [ref=e46]:
          - generic [ref=e47]: ข้อมูลการเดินทาง
          - generic [ref=e48]:
            - img "ข้อมูลการเดินทาง" [ref=e50]
            - generic [ref=e52]: Japan / เครื่องบิน / 6 วัน
            - generic [ref=e54] [cursor=pointer]:
              - img [ref=e55]
              - text: แก้ไข
        - generic [ref=e58]:
          - generic [ref=e59]:
            - img "ทูนประกันภัย" [ref=e61]
            - generic [ref=e62]:
              - generic [ref=e63]: ทูนประกันภัย
              - generic [ref=e64]: ITravel ASIA Daily
          - generic [ref=e66]:
            - generic [ref=e67]:
              - paragraph [ref=e68]: ค่ารักษาพยาบาล
              - paragraph [ref=e69]: ฿ 600,000
              - paragraph [ref=e70]: เสียชีวิตจากอุบัติเหตุ
              - paragraph [ref=e71]: ฿ 1,000,000
            - generic [ref=e72]:
              - paragraph [ref=e73]: อายุระหว่าง 1-85 ปี
              - paragraph [ref=e74]: ฿ 232
              - paragraph [ref=e75]: ราคาต่อคน
          - generic [ref=e76]:
            - heading "ความคุ้มครองชีวิตและค่ารักษาพยาบาล" [level=3] [ref=e77]:
              - button "ความคุ้มครองชีวิตและค่ารักษาพยาบาล" [expanded] [ref=e78] [cursor=pointer]:
                - generic [ref=e79]: ความคุ้มครองชีวิตและค่ารักษาพยาบาล
                - img [ref=e81]
            - region [ref=e86]:
              - generic [ref=e88]:
                - generic [ref=e89]:
                  - generic [ref=e91]:
                    - generic [ref=e92]: การสูญเสียชีวิต หรืออวัยวะ สายตา หรือทุพพลภาพถาวรสิ้นเชิง เนื่องจากการขับขี่หรือโดยสารรถจักรยานยนต์
                    - generic "Testttt" [ref=e93]:
                      - img "Testttt" [ref=e94]
                  - generic [ref=e95] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e96]: "-"
                - generic [ref=e100]: ค่ารักษาพยาบาลระหว่างการเดินทาง จ่ายตามจริงสูงสุด
                - generic [ref=e101]: 600,000 บาท
                - generic [ref=e105]: ค่ารักษาพยาบาลต่อเนื่องหลังจากกลับถึงประเทศไทย จ่ายตามจริงสูงสุด
                - generic [ref=e106]: 40,000 บาท
                - generic [ref=e110]: ค่าเดินทางเพื่อรักษาพยาบาลแบบผู้ป่วยนอกในต่างประเทศ
                - generic [ref=e111]: "-"
                - generic [ref=e115]: ค่ายาผู้ป่วยนอกจากการรักษาผ่านการแพทย์ทางไกล (Telemedicine)
                - generic [ref=e116]: "-"
                - generic [ref=e120]: การรับการรักษาพยาบาลในประเทศไทย จ่ายตามจริงสูงสุด
                - generic [ref=e121]: "-"
                - generic [ref=e125]: การเคลื่อนย้ายเพื่อการรักษาพยาบาลฉุกเฉินหรือการเคลื่อนย้ายกลับสู่ประเทศไทย จ่ายสูงสุดไม่เกิน
                - generic [ref=e126]: "-"
                - generic [ref=e130]: กรณีตรวจสอบพบว่าเกิดจากการบาดเจ็บหรือเจ็บป่วยที่ไม่ใช่สภาพที่เป็นมาก่อนการเอาประกันภัย
                - generic [ref=e131]: "-"
                - generic [ref=e135]: กรณีตรวจสอบพบว่าเกิดจากการบาดเจ็บหรือเจ็บป่วยจากสภาพที่เป็นมาก่อนการเอาประกันภัย
                - generic [ref=e136]: "-"
                - generic [ref=e140]: เงินชดเชยรายวันระหว่างรักษาตัวในโรงพยาบาล ในฐานะผู้ป่วยใน
                - generic [ref=e141]: "1000"
                - generic [ref=e145]: ค่าศัลยกรรมอันเนื่องมาจากอุบัติเหตุ
                - generic [ref=e146]: "-"
                - generic [ref=e150]: การเคลื่อนย้ายเพื่อการรักษาพยาบาลฉุกเฉิน
                - generic [ref=e151]: 1,500,000 บาท
                - generic [ref=e152]:
                  - generic [ref=e155]: การเสียชีวิต การสูญเสียอวัยวะ และสายตา หรือทุพพลภาพถาวรจาก อุบัติเหตุขณะเข้าร่วมเทศกาล ประจำปี
                  - generic [ref=e156] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e157]: "-"
                - generic [ref=e161]: ค่ารักษาพยาบาลเนื่องจากอุบัติเหตุขณะเข้าร่วมเทศกาลประจำปี
                - generic [ref=e162]: "-"
                - generic [ref=e166]: ค่ารักษาพยาบาล อาหารเป็นพิษขณะเดินทาง (IPD only)
                - generic [ref=e167]: "-"
                - generic [ref=e171]: ค่ารักษาพยาบาลเนื่องจากอุบัติเหตุ
                - generic [ref=e172]: "-"
                - generic [ref=e175]:
                  - generic [ref=e176]: การเสียชีวิต การสูญเสียอวัยวะ สายตา หรือ ทุพพลภาพถาวรสิ้นเชิงเนื่องจากอุบัติเหตุ
                  - generic "Testtest" [ref=e177]:
                    - img "Testtest" [ref=e178]
                - generic [ref=e179]: 1,000,000 บาท
                - generic [ref=e183]: การประกันภัยโจรกรรม
                - generic [ref=e184]: "-"
          - generic [ref=e185]:
            - heading "ความคุ้มครองสัมภาระและทรัพย์สิน" [level=3] [ref=e186]:
              - button "ความคุ้มครองสัมภาระและทรัพย์สิน" [expanded] [ref=e187] [cursor=pointer]:
                - generic [ref=e188]: ความคุ้มครองสัมภาระและทรัพย์สิน
                - img [ref=e190]
            - region [ref=e195]:
              - generic [ref=e197]:
                - generic [ref=e198]:
                  - generic [ref=e201]: การสูญหายหรือเสียหายของกระเป๋าเดินทางและ/หรือทรัพย์สินส่วนตัว ภายในกระเป๋าเดินทาง จ่ายตามจริงสูงสุด
                  - generic [ref=e202] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e203]: 10,000 บาท
                - generic [ref=e207]: การล่าช้าของกระเป๋าเดินทาง จ่ายสูงสุดไม่เกิน
                - generic [ref=e208]: 5,000 บาท
                - generic [ref=e212]: การสูญหายหรือเสียหายของเงินสด
                - generic [ref=e213]: 5,000 บาท
                - generic [ref=e217]: การสูญหายหรือเสียหายของเอกสารที่เกี่ยวข้องกับการเดินทาง จ่ายตามจริงสูงสุด
                - generic [ref=e218]: "-"
                - generic [ref=e222]: ความสูญเสียหรือความเสียหายของคอมพิวเตอร์โน้ตบุ๊ค จ่ายตามจริงสูงสุด
                - generic [ref=e223]: "-"
                - generic [ref=e224]:
                  - generic [ref=e227]: การสูญเสียหรือความเสียหายของ กระเป๋าเดินทาง ทรัพย์สิน รวมถึงคอมพิวเตอร์โน้ตบุ๊คอันเนื่องมาจากภัยธรรมชาติ จ่ายตามจริงสูงสุด
                  - generic [ref=e228] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e229]: 10,000 บาท
          - generic [ref=e230]:
            - heading "ความคุ้มครองในการเดินทาง" [level=3] [ref=e231]:
              - button "ความคุ้มครองในการเดินทาง" [expanded] [ref=e232] [cursor=pointer]:
                - generic [ref=e233]: ความคุ้มครองในการเดินทาง
                - img [ref=e235]
            - region [ref=e240]:
              - generic [ref=e242]:
                - generic [ref=e246]: การยกเลิกการเดินทาง จ่ายตามจริงสูงสุด
                - generic [ref=e247]: 5,000 บาท
                - generic [ref=e251]: การลดจำนวนวันเดินทาง จ่ายตามจริงสูงสุด
                - generic [ref=e252]: 10,000 บาท
                - generic [ref=e256]: ความล่าช้าในการเดินทาง จ่ายสูงสุดไม่เกิน
                - generic [ref=e257]: 10,000 บาท
                - generic [ref=e261]: การพลาดการต่อเที่ยวบิน จ่ายสูงสุดไม่เกิน
                - generic [ref=e262]: 10,000 บาท
                - generic [ref=e266]: การจี้เครื่องบิน
                - generic [ref=e267]: "-"
                - generic [ref=e268]:
                  - generic [ref=e271]: การล่าช้าของเที่ยวบินแบบออนไทม์การันตี สำหรับเที่ยวบินขาออกจากประเทศไทย (จ่าย ไม่เกิน 1 ครั้ง กรณีขาเข้าหรือขาออก ขาใดขาหนึ่งเท่านั้น)
                  - generic [ref=e272] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e273]: "-"
                - generic [ref=e274]:
                  - generic [ref=e277]: การล่าช้าของเที่ยวบินแบบออนไทม์การันตี สำหรับเที่ยวบินขาเข้าประเทศไทย (จ่าย ไม่เกิน 1 ครั้ง กรณีขาเข้าหรือขาออก ขาใดขาหนึ่งเท่านั้น)
                  - generic [ref=e278] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e279]: "-"
                - generic [ref=e283]: การล่าช้าของระบบขนส่งมวลชน
                - generic [ref=e284]: "-"
          - generic [ref=e285]:
            - heading "ความคุ้มครองเพิ่มเติม" [level=3] [ref=e286]:
              - button "ความคุ้มครองเพิ่มเติม" [expanded] [ref=e287] [cursor=pointer]:
                - generic [ref=e288]: ความคุ้มครองเพิ่มเติม
                - img [ref=e290]
            - region [ref=e295]:
              - generic [ref=e297]:
                - generic [ref=e301]: ค่าใช้จ่ายในการส่งศพ หรืออัฐิกลับประเทศ จ่ายสูงสุดไม่เกิน
                - generic [ref=e302]: 1,000,000 บาท
                - generic [ref=e306]: กรณีตรวจสอบพบว่าเกิดจากการบาดเจ็บหรือเจ็บป่วยที่ไม่ใช่สภาพที่เป็นมาก่อนการเอาประกันภัย
                - generic [ref=e307]: "-"
                - generic [ref=e311]: กรณีตรวจสอบพบว่าเกิดจากการบาดเจ็บหรือเจ็บป่วยจากสภาพที่เป็นมาก่อนการเอาประกันภัย
                - generic [ref=e312]: "-"
                - generic [ref=e316]: ความรับผิดตามกฏหมายต่อบุคคลภายนอก จ่ายตามจริงสูงสุด
                - generic [ref=e317]: 500,000 บาท
                - generic [ref=e321]: การเดินทางเพื่อเยี่ยมผู้ป่วยที่โรงพยาบาล จ่ายตามจริงสูงสุด
                - generic [ref=e322]: "-"
                - generic [ref=e326]: รางวัลพิเศษสำหรับ โฮล-อิน-วัน
                - generic [ref=e327]: "-"
                - generic [ref=e331]: ความเสียหายส่วนแรกสำหรับรถเช่า จ่ายตามจริงสูงสุด
                - generic [ref=e332]: "-"
                - generic [ref=e336]: ชดเชยค่าโทรศัพท์ในกรณีฉุกเฉิน จ่ายตามจริงสูงสุด
                - generic [ref=e337]: 1,000 บาท
                - generic [ref=e341]: ผลประโยชน์การขยายระยะเวลาโดยอัตโนมัติ
                - generic [ref=e342]: "-"
                - generic [ref=e346]: ผลประโยชน์การสูญเสียหรือความเสียหายของทรัพย์สินภายในบ้าน
                - generic [ref=e347]: 35,000 บาท
                - generic [ref=e351]: การบริการให้ความช่วยเหลือในการเดินทาง
                - generic [ref=e352]: คุ้มครอง
                - generic [ref=e356]: บริการการปรึกษาแพทย์ทางไกล
                - generic [ref=e357]: "-"
                - generic [ref=e361]: การไปเยี่ยมผู้เอาประกันภัย จ่ายตามจริงสูงสุด
                - generic [ref=e362]: "-"
                - generic [ref=e366]: การส่งผู้เยาว์เพื่อเดินทางกลับประเทศ จ่ายตามจริงสูงสุด
                - generic [ref=e367]: "-"
                - generic [ref=e371]: ผลประโยชน์ความรับผิดต่อบัตรเครดิต
                - generic [ref=e372]: "-"
                - generic [ref=e376]: โฮล-อิน-วัน / การสูญหายหรือ ความเสียหายของอุปกรณ์กอล์ฟ / การชดเชยค่าธรรมเนียมสนามกอล์ฟ
                - generic [ref=e377]: 5,000 บาท
                - generic [ref=e381]: การค้นหา การช่วยชีวิต และการกู้ภัย
                - generic [ref=e382]: "-"
                - generic [ref=e386]: การสูญหายของหนังสือเดินทาง จ่ายตามจริงสูงสุด
                - generic [ref=e387]: "-"
                - generic [ref=e391]: การถูกปฏิเสธการขอวีซ่า (Visa Refusal)
                - generic [ref=e392]: "-"
                - generic [ref=e396]: คุ้มครองอุบัติเหตุจากการเล่นกีฬาเสี่ยงภัย
                - generic [ref=e397]: "-"
        - generic [ref=e398]:
          - button "ย้อนกลับ" [ref=e399] [cursor=pointer]:
            - img [ref=e401]
            - text: ย้อนกลับ
          - button "เลือกแผนนี้" [ref=e403] [cursor=pointer]:
            - text: เลือกแผนนี้
            - img [ref=e405]
    - contentinfo [ref=e407]:
      - link "TQM Logo" [ref=e409] [cursor=pointer]:
        - /url: /
        - img "TQM Logo" [ref=e410]
      - generic [ref=e411]:
        - button "ผลิตภัณฑ์ประกันภัย" [ref=e414] [cursor=pointer]:
          - generic [ref=e416]: ผลิตภัณฑ์ประกันภัย
          - img [ref=e418]
        - button "บริการลูกค้า" [ref=e422] [cursor=pointer]:
          - generic [ref=e424]: บริการลูกค้า
          - img [ref=e426]
        - button "ติดต่อสอบถาม" [ref=e430] [cursor=pointer]:
          - generic [ref=e432]: ติดต่อสอบถาม
          - img [ref=e434]
        - button "บริษัท" [ref=e438] [cursor=pointer]:
          - generic [ref=e440]: บริษัท
          - img [ref=e442]
        - generic [ref=e444]:
          - generic [ref=e445]:
            - link "line" [ref=e447] [cursor=pointer]:
              - /url: https://lin.ee/Ds7qY7v
              - img "line" [ref=e448]
            - link "facebook" [ref=e450] [cursor=pointer]:
              - /url: https://www.facebook.com/TqmBroker
              - img "facebook" [ref=e451]
            - link "instagram" [ref=e453] [cursor=pointer]:
              - /url: https://www.instagram.com/tqminsurancebroker
              - img "instagram" [ref=e454]
            - link "tiktok" [ref=e456] [cursor=pointer]:
              - /url: http://www.tiktok.com/@tqmmorelove
              - img "tiktok" [ref=e457]
            - link "youtube" [ref=e459] [cursor=pointer]:
              - /url: https://www.youtube.com/@TQMInsuranceBrokerOfficial
              - img "youtube" [ref=e460]
            - link "x" [ref=e462] [cursor=pointer]:
              - /url: https://x.com/Tqmbeside
              - img "x" [ref=e463]
          - link "1737" [ref=e465] [cursor=pointer]:
            - /url: tel:1737
            - img [ref=e466]
            - text: "1737"
        - generic [ref=e469]:
          - link "TQM Application" [ref=e471] [cursor=pointer]:
            - /url: https://tqm.onelink.me/jwZj/fsmrwgvs
            - img "TQM Application" [ref=e472]
          - generic [ref=e473]:
            - link "TQM IOS Application" [ref=e474] [cursor=pointer]:
              - /url: https://apps.apple.com/th/app/tqm24/id1274502784
              - img "TQM IOS Application" [ref=e475]
            - link "TQM Android Application" [ref=e476] [cursor=pointer]:
              - /url: https://play.google.com/store/apps/details?id=com.tqm.tqmapp
              - img "TQM Android Application" [ref=e477]
            - link "TQM APK Download" [ref=e478] [cursor=pointer]:
              - /url: https://storage.googleapis.com/tqm-beta-static/files/APK/tqm24.apk
              - img "TQM APK Download" [ref=e479]
        - generic [ref=e480]:
          - paragraph [ref=e481]: ©Copyright 2026 TQM.co.th All Rights Reserved.
          - generic [ref=e482]:
            - paragraph [ref=e483]:
              - link "แผนผังเว็บไซต์" [ref=e484] [cursor=pointer]:
                - /url: https://devweb.tqm.co.th/sitemap
            - paragraph [ref=e485]:
              - link "ข้อกำหนดและเงื่อนไข" [ref=e486] [cursor=pointer]:
                - /url: /terms-and-conditions
            - paragraph [ref=e487]:
              - link "นโยบายข้อมูลส่วนบุคคล" [ref=e488] [cursor=pointer]:
                - /url: /tqm/privacy
    - generic [ref=e489]:
      - generic:
        - generic:
          - generic:
            - img
        - generic:
          - button "Close notification":
            - img
          - generic:
            - paragraph: สนใจแผนนี้อยู่รึเปล่า? สงสัยถามพี่หมีได้เลย
      - button "Toggle chat" [ref=e490] [cursor=pointer]:
        - img "chat-on-web" [ref=e491]
      - generic:
        - generic:
          - generic:
            - img "chat-admin"
            - generic:
              - generic: TQM Chats
              - generic: พร้อมดูแลคุณ 24 ชั่วโมง
          - button "Close chat":
            - img
        - generic:
          - status
          - generic:
            - generic:
              - generic:
                - button "chat-plus-file":
                  - img "chat-plus-file"
            - generic:
              - generic:
                - generic:
                  - textbox "พิมพ์เรื่องที่อยากให้พี่หมีช่วยได้เลย..."
            - button "ส่งข้อความ" [disabled]:
              - img "send"
  - alert [ref=e492]: รายละเอียดประกันเดินทาง | TQM ทีคิวเอ็ม
```

# Test source

```ts
  1  | import { Page, expect } from "@playwright/test";
  2  | import { travelSearchWizardData } from "../../../../data/travel/travel-normal-flow.data";
  3  | import { commonLocator } from "../../../../locator/nmw/nmw-common-locator";
  4  | import { TravelProductDetailType } from "../../../../types/travel.type";
  5  | import CommonTQM from "../../../../utils/common-tqm";
  6  | 
  7  | export default class TravelProductDetailPage {
  8  |   constructor(public page: Page) {}
  9  |   async checkProductData(travelProductDetail: TravelProductDetailType) {
  10 |     await expect(
  11 |       this.page.getByTestId(commonLocator.TEXT_ID_PRODUCT_DATA)
  12 |     ).toBeVisible();
  13 |     const productData = await this.page
  14 |       .getByTestId(commonLocator.TEXT_ID_PRODUCT_DATA)
  15 |       .textContent();
  16 |     if (travelSearchWizardData.travelRouteSelect == travelSearchWizardData.domestic) {
  17 |       // ในประเทศ รายเที่ยว 1 คน
  18 |       expect(productData?.trim()).toBe(
  19 |         travelProductDetail.productDataDomestic
  20 |       );
  21 |     } else if (
  22 |       travelSearchWizardData.travelRouteSelect == travelSearchWizardData.aboard // ต่างประเทศ รายเที่ยว 2 คน
  23 |     ) {
  24 |       expect(productData?.trim()).toBe(travelProductDetail.productDataAboard);
  25 |     }
  26 |   }
  27 | 
  28 |   async getInsurePrice(travelProductDetail: TravelProductDetailType) {
  29 |     const commonTQM = new CommonTQM(this.page);
  30 |     await commonTQM.initDevice();
  31 | 
  32 |     if (commonTQM.isDeviceMobile()) {
  33 |       await expect(
  34 |         this.page.getByTestId(commonLocator.IMG_ID_COMPANY_LOGO)
  35 |       ).toBeVisible();
  36 |       await expect(
  37 |         this.page.getByTestId(commonLocator.TEXT_ID_INSURE_PRICE_MOBILE)
> 38 |       ).toBeVisible();
     |         ^ Error: expect(locator).toBeVisible() failed
  39 |       const insureNetAmount = await this.page
  40 |         .getByTestId(commonLocator.TEXT_ID_INSURE_PRICE_MOBILE)
  41 |         .textContent();
  42 |       expect(insureNetAmount?.trim()).not.toBe("");
  43 |       travelProductDetail.insurePrice = await CommonTQM.getInsurePrice(
  44 |         this.page,
  45 |         commonLocator.TEXT_ID_INSURE_PRICE_MOBILE
  46 |       );
  47 |     } else {
  48 |       await expect(
  49 |         this.page.getByTestId(commonLocator.IMG_ID_COMPANY_LOGO)
  50 |       ).toBeVisible();
  51 |       await expect(
  52 |         this.page.getByTestId(commonLocator.TEXT_ID_INSURE_PRICE)
  53 |       ).toBeVisible();
  54 |       const insurePrice = await this.page
  55 |         .getByTestId(commonLocator.TEXT_ID_INSURE_PRICE)
  56 |         .textContent();
  57 |       expect(insurePrice?.trim()).not.toBe("");
  58 |       travelProductDetail.insurePrice = await CommonTQM.getInsurePrice(
  59 |         this.page,
  60 |         commonLocator.TEXT_ID_INSURE_PRICE
  61 |       );
  62 |     }
  63 |     travelProductDetail.insurePriceAllTraveler =
  64 |       travelProductDetail.insurePrice * travelSearchWizardData.totalTraveler;
  65 |   }
  66 | 
  67 |   async getInsureName(travelProductDetail: TravelProductDetailType) {
  68 |     await expect(
  69 |       this.page.getByTestId(commonLocator.TEXT_ID_COMPANY_NAME)
  70 |     ).toBeVisible();
  71 |     const companyNameText = await this.page
  72 |       .getByTestId(commonLocator.TEXT_ID_COMPANY_NAME)
  73 |       .textContent();
  74 |     expect(companyNameText?.trim()).not.toBe("0");
  75 |     travelProductDetail.insureName = await CommonTQM.getInsureName(
  76 |       this.page,
  77 |       commonLocator.TEXT_ID_COMPANY_NAME
  78 |     );
  79 |     await this.page.getByTestId(commonLocator.BUTTON_ID_NEXT_STEP).click();
  80 |   }
  81 | }
  82 | 
```