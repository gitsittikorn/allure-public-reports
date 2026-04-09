# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: main-web/home/home-normal-flow.spec.ts >> Home-NormalFlow-Fullvalue
- Location: tests/main-web/home/home-normal-flow.spec.ts:50:5

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
          - generic [ref=e47]: ข้อมูลบ้าน
          - generic [ref=e48]:
            - img "ข้อมูลบ้าน" [ref=e50]
            - generic [ref=e52]: ประกันบ้าน / บ้านเดี่ยว / ปูนทั้งหมด / 2 ชั้น / ใช้สำหรับที่อยู่อาศัย / กระบี่
            - generic [ref=e54] [cursor=pointer]:
              - img [ref=e55]
              - text: แก้ไข
        - generic [ref=e58]:
          - generic [ref=e59]:
            - img "เมืองไทยประกันชีวิต" [ref=e61]
            - generic [ref=e62]:
              - generic [ref=e63]: เมืองไทยประกันชีวิต
              - generic [ref=e64]: ประกันบ้าน First Lost ประกันบ้าน First Lost 1
              - generic [ref=e65]:
                - generic [ref=e67]:
                  - img "flood_icon" [ref=e69]
                  - generic [ref=e70]: น้ำท่วม
                - generic [ref=e72]:
                  - img "fire_icon" [ref=e74]
                  - generic [ref=e75]: ไฟไหม้
                - generic [ref=e77]:
                  - img "earthquake_icon" [ref=e79]
                  - generic [ref=e80]: แผ่นดินไหว
                - generic [ref=e82]:
                  - img "robbery_icon" [ref=e84]
                  - generic [ref=e85]: โจรกรรม
          - generic [ref=e87]:
            - generic [ref=e88]:
              - paragraph [ref=e89]: ทุนประกันภัย
              - paragraph [ref=e90]: ฿ 150,000
              - paragraph [ref=e91]: แผ่นดินไหว
              - paragraph [ref=e92]: "-"
            - generic [ref=e93]:
              - paragraph [ref=e94]: เบี้ยประกัน/3ปี
              - paragraph [ref=e95]: ฿ 500
              - paragraph [ref=e96]: เฉลี่ยปีละ 166 บาท
          - generic [ref=e97]:
            - heading "การประกันอัคคีภัยและภัยเพิ่ม" [level=3] [ref=e98]:
              - button "การประกันอัคคีภัยและภัยเพิ่ม" [expanded] [ref=e99] [cursor=pointer]:
                - generic [ref=e100]: การประกันอัคคีภัยและภัยเพิ่ม
                - img [ref=e102]
            - region [ref=e107]:
              - generic [ref=e109]:
                - generic [ref=e112]:
                  - generic [ref=e113]: ภัยจากการนัดหยุดงาน การจลาจล หรือการกระทำอันมีเจตนาร้าย
                  - generic "Test" [ref=e114]:
                    - img "Test" [ref=e115]
                - generic [ref=e116]: 500 บาท
                - generic [ref=e119]:
                  - generic [ref=e120]: ความสูญเสียหรือเสียหายจากภัยธรรมชาติ
                  - generic "test" [ref=e121]:
                    - img "test" [ref=e122]
                - generic [ref=e123]: ห้าร้อย
                - generic [ref=e126]:
                  - generic [ref=e127]: ขยายภัยเพิ่มพิเศษ ภัยจากลมพายุ
                  - generic "test" [ref=e128]:
                    - img "test" [ref=e129]
                - generic [ref=e130]: "500"
                - generic [ref=e134]: ขยายภัยเพิ่มพิเศษ ภัยแผ่นดินไหว
                - generic [ref=e135]: ห้าร้อย
                - generic [ref=e139]: ขยายภัยเพิ่มพิเศษ ภัยลูกเห็บ
                - generic [ref=e140]: "500"
                - generic [ref=e144]: ขยายภัยเพิ่มพิเศษ ภัยต่อเครื่องใช้ไฟฟ้า (วงเงินต่อภัย)
                - generic [ref=e145]: ห้าร้อย
                - generic [ref=e149]: ไฟไหม้ ฟ้าผ่า
                - generic [ref=e150]: "500"
                - generic [ref=e154]: ขยายภัยเพิ่มพิเศษ ภัยน้ำท่วม
                - generic [ref=e155]: ห้าร้อย
          - generic [ref=e156]:
            - heading "โจรกรรม ลักทรัพย์ ชิงทรัพย์ ปล้นทรัพย์" [level=3] [ref=e157]:
              - button "โจรกรรม ลักทรัพย์ ชิงทรัพย์ ปล้นทรัพย์" [expanded] [ref=e158] [cursor=pointer]:
                - generic [ref=e159]: โจรกรรม ลักทรัพย์ ชิงทรัพย์ ปล้นทรัพย์
                - img [ref=e161]
            - region [ref=e166]:
              - generic [ref=e168]:
                - generic [ref=e169]:
                  - generic [ref=e172]: ความเสียหายต่ออาคารสิ่งปลูกสร้าง ค่าซ่อมแซมประตู-หน้าต่าง รวมถึงค่าใช้จ่ายในการเปลี่ยนอุปกรณ์ล็อคและกุญแจ(ต่อความเสียหายแต่ละครั้ง และตลอดระยะเวลาเอาประกันภัยต่อปี)
                  - generic [ref=e173] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e174]: "500"
                - generic [ref=e178]: วงเงินจำกัดความคุ้มครองต่อครั้ง
                - generic [ref=e179]: ห้าร้อย
                - generic [ref=e180]:
                  - generic [ref=e183]: ขยายความคุ้มครองความเสียหายต่อทรัพย์สินส่วนบุคคล และค่าซ่อมแซมตัวอาคารจากร่องรอยงัดแงะที่เกิดเหตุ (รวมอยู่ในวงเงินหมวดโจรกรรม)
                  - generic [ref=e184] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e185]: "500"
                - generic [ref=e189]: ความสูญเสียหรือความเสียหาย
                - generic [ref=e190]: ห้าร้อย
          - generic [ref=e191]:
            - heading "ภัยที่เกิดกับกระจก" [level=3] [ref=e192]:
              - button "ภัยที่เกิดกับกระจก" [expanded] [ref=e193] [cursor=pointer]:
                - generic [ref=e194]: ภัยที่เกิดกับกระจก
                - img [ref=e196]
            - region [ref=e201]:
              - generic [ref=e203]:
                - generic [ref=e207]: ความเสียหายต่อกระจกที่ติดตั้งถาวร
                - generic [ref=e208]: "500"
          - generic [ref=e209]:
            - heading "ความรับผิดต่อบุคคลภายนอก" [level=3] [ref=e210]:
              - button "ความรับผิดต่อบุคคลภายนอก" [expanded] [ref=e211] [cursor=pointer]:
                - generic [ref=e212]: ความรับผิดต่อบุคคลภายนอก
                - img [ref=e214]
            - region [ref=e219]:
              - generic [ref=e221]:
                - generic [ref=e225]: ความรับผิดตามกฎหมายต่อบุคคลภายนอกต่อการบาดเจ็บเสียชีวิต และทรัพย์สินของบุคคลภายนอก
                - generic [ref=e226]: ห้าร้อย
          - generic [ref=e227]:
            - heading "ประกันภัยเงินทดแทนแรงงาน" [level=3] [ref=e228]:
              - button "ประกันภัยเงินทดแทนแรงงาน" [expanded] [ref=e229] [cursor=pointer]:
                - generic [ref=e230]: ประกันภัยเงินทดแทนแรงงาน
                - img [ref=e232]
            - region [ref=e237]:
              - generic [ref=e239]:
                - generic [ref=e240]:
                  - generic [ref=e243]: ความรับผิดตามกฎหมายแรงงาน หากลูกจ้างประจำได้รับความบาดเจ็บจากอุบัติเหตุ หรือความเจ็บป่วยในระหว่างการทำงาน
                  - generic [ref=e244] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e245]: "500"
          - generic [ref=e246]:
            - heading "ไฟไหม้ ฟ้าผ่า" [level=3] [ref=e247]:
              - button "ไฟไหม้ ฟ้าผ่า" [expanded] [ref=e248] [cursor=pointer]:
                - generic [ref=e249]: ไฟไหม้ ฟ้าผ่า
                - img [ref=e251]
            - region [ref=e256]:
              - generic [ref=e258]:
                - generic [ref=e262]: ขยายภัยเพิ่มพิเศษ ภัยแผ่นดินไหว
                - generic [ref=e263]: "-"
        - generic [ref=e264]:
          - generic [ref=e265]: เงื่อนไขการรับประกัน
          - paragraph [ref=e266]:
            - list [ref=e267]:
              - listitem [ref=e268]: สิ่งปลูกสร้างเพื่อการอยู่อาศัยเท่านั้น (ไม่มีการประกอบธุรกิจอื่นภายในสิ่งปลูกสร้างนั้นๆ)
              - listitem [ref=e269]: กำหนดจำนวนเงินเอาประกันภัยและชดใช้ค่าสินไหมทดแทนตามวิธีมูลค่าทรัพย์สินที่เป็นของใหม่ (Replacement Cost Value)
              - listitem [ref=e270]: จำกัดซื้อได้ 1 ฉบับต่อ 1 สถานที่เอาประกันภัย
              - listitem [ref=e271]: ความรับผิดของบริษัทรวมกันแล้วสูงสุดไม่เกินจำนวนเงินเอาประกันภัย
            - paragraph [ref=e272]: หมายเหตุ
            - list [ref=e273]:
              - listitem [ref=e274]: รับประกันภัยโดย บริษัท เอฟดับบลิวดีประกันภัย จำกัด (มหาชน)”
              - listitem [ref=e275]: เอกสารนี้ไม่ใช่สัญญาประกันภัย ให้ถือตามเงื่อนไขข้อความที่ระบุไว้ในกรมธรรม์ประกันภัยเป็นสำคัญ
              - listitem [ref=e276]: ผู้ซื้อควรทำความเข้าใจรายละเอียด ความคุ้มครอง และเงื่อนไขก่อนตัดสินใจทำประกันทุกครั้ง
        - generic [ref=e277]:
          - button "ย้อนกลับ" [ref=e278] [cursor=pointer]:
            - img [ref=e280]
            - text: ย้อนกลับ
          - button "เลือกแผนนี้" [ref=e282] [cursor=pointer]:
            - text: เลือกแผนนี้
            - img [ref=e284]
    - contentinfo [ref=e286]:
      - link "TQM Logo" [ref=e288] [cursor=pointer]:
        - /url: /
        - img "TQM Logo" [ref=e289]
      - generic [ref=e290]:
        - button "ผลิตภัณฑ์ประกันภัย" [ref=e293] [cursor=pointer]:
          - generic [ref=e295]: ผลิตภัณฑ์ประกันภัย
          - img [ref=e297]
        - button "บริการลูกค้า" [ref=e301] [cursor=pointer]:
          - generic [ref=e303]: บริการลูกค้า
          - img [ref=e305]
        - button "ติดต่อสอบถาม" [ref=e309] [cursor=pointer]:
          - generic [ref=e311]: ติดต่อสอบถาม
          - img [ref=e313]
        - button "บริษัท" [ref=e317] [cursor=pointer]:
          - generic [ref=e319]: บริษัท
          - img [ref=e321]
        - generic [ref=e323]:
          - generic [ref=e324]:
            - link "line" [ref=e326] [cursor=pointer]:
              - /url: https://lin.ee/Ds7qY7v
              - img "line" [ref=e327]
            - link "facebook" [ref=e329] [cursor=pointer]:
              - /url: https://www.facebook.com/TqmBroker
              - img "facebook" [ref=e330]
            - link "instagram" [ref=e332] [cursor=pointer]:
              - /url: https://www.instagram.com/tqminsurancebroker
              - img "instagram" [ref=e333]
            - link "tiktok" [ref=e335] [cursor=pointer]:
              - /url: http://www.tiktok.com/@tqmmorelove
              - img "tiktok" [ref=e336]
            - link "youtube" [ref=e338] [cursor=pointer]:
              - /url: https://www.youtube.com/@TQMInsuranceBrokerOfficial
              - img "youtube" [ref=e339]
            - link "x" [ref=e341] [cursor=pointer]:
              - /url: https://x.com/Tqmbeside
              - img "x" [ref=e342]
          - link "1737" [ref=e344] [cursor=pointer]:
            - /url: tel:1737
            - img [ref=e345]
            - text: "1737"
        - generic [ref=e348]:
          - link "TQM Application" [ref=e350] [cursor=pointer]:
            - /url: https://tqm.onelink.me/jwZj/fsmrwgvs
            - img "TQM Application" [ref=e351]
          - generic [ref=e352]:
            - link "TQM IOS Application" [ref=e353] [cursor=pointer]:
              - /url: https://apps.apple.com/th/app/tqm24/id1274502784
              - img "TQM IOS Application" [ref=e354]
            - link "TQM Android Application" [ref=e355] [cursor=pointer]:
              - /url: https://play.google.com/store/apps/details?id=com.tqm.tqmapp
              - img "TQM Android Application" [ref=e356]
            - link "TQM APK Download" [ref=e357] [cursor=pointer]:
              - /url: https://storage.googleapis.com/tqm-beta-static/files/APK/tqm24.apk
              - img "TQM APK Download" [ref=e358]
        - generic [ref=e359]:
          - paragraph [ref=e360]: ©Copyright 2026 TQM.co.th All Rights Reserved.
          - generic [ref=e361]:
            - paragraph [ref=e362]:
              - link "แผนผังเว็บไซต์" [ref=e363] [cursor=pointer]:
                - /url: https://devweb.tqm.co.th/sitemap
            - paragraph [ref=e364]:
              - link "ข้อกำหนดและเงื่อนไข" [ref=e365] [cursor=pointer]:
                - /url: /terms-and-conditions
            - paragraph [ref=e366]:
              - link "นโยบายข้อมูลส่วนบุคคล" [ref=e367] [cursor=pointer]:
                - /url: /tqm/privacy
    - generic [ref=e368]:
      - generic:
        - generic:
          - generic:
            - img
        - generic:
          - button "Close notification":
            - img
          - generic:
            - paragraph: สนใจแผนนี้อยู่รึเปล่า? สงสัยถามพี่หมีได้เลย
      - button "Toggle chat" [ref=e369] [cursor=pointer]:
        - img "chat-on-web" [ref=e370]
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
  - alert [ref=e371]: รายละเอียดประกันอัคคีภัย บ้าน | TQM ทีคิวเอ็ม
```

# Test source

```ts
  1  | import { Page, expect } from "@playwright/test";
  2  | import { commonLocator } from "../../../../locator/nmw/nmw-common-locator";
  3  | import { HomeProductDetailType } from "../../../../types/home.type";
  4  | import CommonTQM from "../../../../utils/common-tqm";
  5  | 
  6  | export default class HomeProductDetailTypePage {
  7  |   constructor(public page: Page) {}
  8  | 
  9  |   async checkProductData(homeProductDetail: HomeProductDetailType) {
  10 |     await expect(this.page.getByTestId(commonLocator.TEXT_ID_PRODUCT_DATA)).toBeVisible();
  11 |     const productData = await this.page
  12 |       .getByTestId(commonLocator.TEXT_ID_PRODUCT_DATA)
  13 |       .textContent();
  14 |     expect(productData?.trim()).toBe(homeProductDetail.productData);
  15 |   }
  16 | 
  17 |   async getInsurePrice(homeProductDetail: HomeProductDetailType) {
  18 |     const commonTQM = new CommonTQM(this.page);
  19 |     await commonTQM.initDevice();
  20 | 
  21 |     if (commonTQM.isDeviceMobile()) {
  22 |       await expect(this.page.getByTestId(commonLocator.IMG_ID_COMPANY_LOGO)).toBeVisible();
> 23 |       await expect(this.page.getByTestId(commonLocator.TEXT_ID_PRICE)).toBeVisible();
     |                                                                        ^ Error: expect(locator).toBeVisible() failed
  24 |       const insureNetAmount = await this.page
  25 |         .getByTestId(commonLocator.TEXT_ID_PRICE)
  26 |         .textContent();
  27 |       expect(insureNetAmount?.trim()).not.toBe("");
  28 |       homeProductDetail.insurePrice = await CommonTQM.getInsurePrice(
  29 |         this.page,
  30 |         commonLocator.TEXT_ID_PRICE
  31 |       );
  32 |     } else {
  33 |       await expect(this.page.getByTestId(commonLocator.IMG_ID_COMPANY_LOGO)).toBeVisible();
  34 |       await expect(this.page.getByTestId(commonLocator.TEXT_ID_INSURE_PRICE)).toBeVisible();
  35 |       const insurePrice = await this.page
  36 |         .getByTestId(commonLocator.TEXT_ID_INSURE_PRICE)
  37 |         .textContent();
  38 |       expect(insurePrice?.trim()).not.toBe("");
  39 |       homeProductDetail.insurePrice = await CommonTQM.getInsurePrice(
  40 |         this.page,
  41 |         commonLocator.TEXT_ID_INSURE_PRICE
  42 |       );
  43 |     }
  44 |   }
  45 | 
  46 |   async getInsureName(homeProductDetail: HomeProductDetailType) {
  47 |     await expect(this.page.getByTestId(commonLocator.TEXT_ID_COMPANY_NAME)).toBeVisible();
  48 |     const companyNameText = await this.page
  49 |       .getByTestId(commonLocator.TEXT_ID_COMPANY_NAME)
  50 |       .textContent();
  51 |     expect(companyNameText?.trim()).not.toBe(homeProductDetail.textZero);
  52 |     homeProductDetail.insureName = await CommonTQM.getInsureName(
  53 |       this.page,
  54 |       commonLocator.TEXT_ID_COMPANY_NAME
  55 |     );
  56 |     await this.page.getByTestId(commonLocator.BUTTON_ID_NEXT_STEP).click();
  57 |   }
  58 | }
  59 | 
```