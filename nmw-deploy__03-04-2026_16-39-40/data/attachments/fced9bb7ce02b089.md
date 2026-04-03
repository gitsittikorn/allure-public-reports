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
            - img "ทิพยประกันภัย" [ref=e61]
            - generic [ref=e62]:
              - generic [ref=e63]: ทิพยประกันภัย
              - generic [ref=e64]: ประกันบ้านแสนรัก ประกันภัยอัคคีภัยบ้านอยู่อาศัย TIPSMILE Phase3 แผน 2 (ราย 1 ปี)
              - generic [ref=e65]:
                - generic [ref=e67]:
                  - img "flood_icon" [ref=e69]
                  - generic [ref=e70]: น้ำท่วม
                - generic [ref=e72]:
                  - img "earthquake_icon" [ref=e74]
                  - generic [ref=e75]: แผ่นดินไหว
                - generic [ref=e77]:
                  - img "fire_icon" [ref=e79]
                  - generic [ref=e80]: ไฟไหม้
                - generic [ref=e82]:
                  - img "robbery_icon" [ref=e84]
                  - generic [ref=e85]: โจรกรรม
          - generic [ref=e87]:
            - generic [ref=e88]:
              - paragraph [ref=e89]: ทุนประกันภัย
              - paragraph [ref=e90]: ฿ 1,500,000
              - paragraph [ref=e91]: แผ่นดินไหว
              - paragraph [ref=e92]: "-"
            - generic [ref=e93]:
              - paragraph [ref=e94]: เบี้ยประกัน/ปี
              - paragraph [ref=e95]: ฿ 2,799.12
              - paragraph [ref=e96]: ต่อปี
          - generic [ref=e97]:
            - heading "การประกันอัคคีภัยและภัยเพิ่ม" [level=3] [ref=e98]:
              - button "การประกันอัคคีภัยและภัยเพิ่ม" [expanded] [ref=e99] [cursor=pointer]:
                - generic [ref=e100]: การประกันอัคคีภัยและภัยเพิ่ม
                - img [ref=e102]
            - region [ref=e107]:
              - generic [ref=e109]:
                - generic [ref=e113]: ภัยจากการนัดหยุดงาน การจลาจล หรือการกระทำอันมีเจตนาร้าย
                - generic [ref=e114]: "-"
                - generic [ref=e118]: ความสูญเสียหรือเสียหายจากภัยธรรมชาติ
                - generic [ref=e119]: "-"
                - generic [ref=e123]: ขยายภัยเพิ่มพิเศษ ภัยจากลมพายุ
                - generic [ref=e124]: "-"
                - generic [ref=e128]: ขยายภัยเพิ่มพิเศษ ภัยแผ่นดินไหว
                - generic [ref=e129]: "-"
                - generic [ref=e133]: ขยายภัยเพิ่มพิเศษ ภัยลูกเห็บ
                - generic [ref=e134]: "-"
                - generic [ref=e138]: ขยายภัยเพิ่มพิเศษ ภัยต่อเครื่องใช้ไฟฟ้า (วงเงินต่อภัย)
                - generic [ref=e139]: "-"
                - generic [ref=e143]: ไฟไหม้ ฟ้าผ่า
                - generic [ref=e144]: "-"
                - generic [ref=e148]: ขยายภัยเพิ่มพิเศษ ภัยน้ำท่วม
                - generic [ref=e149]: "-"
          - generic [ref=e150]:
            - heading "โจรกรรม ลักทรัพย์ ชิงทรัพย์ ปล้นทรัพย์" [level=3] [ref=e151]:
              - button "โจรกรรม ลักทรัพย์ ชิงทรัพย์ ปล้นทรัพย์" [expanded] [ref=e152] [cursor=pointer]:
                - generic [ref=e153]: โจรกรรม ลักทรัพย์ ชิงทรัพย์ ปล้นทรัพย์
                - img [ref=e155]
            - region [ref=e160]:
              - generic [ref=e162]:
                - generic [ref=e163]:
                  - generic [ref=e166]: ความเสียหายต่ออาคารสิ่งปลูกสร้าง ค่าซ่อมแซมประตู-หน้าต่าง รวมถึงค่าใช้จ่ายในการเปลี่ยนอุปกรณ์ล็อคและกุญแจ(ต่อความเสียหายแต่ละครั้ง และตลอดระยะเวลาเอาประกันภัยต่อปี)
                  - generic [ref=e167] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e168]: "-"
                - generic [ref=e172]: วงเงินจำกัดความคุ้มครองต่อครั้ง
                - generic [ref=e173]: "-"
                - generic [ref=e174]:
                  - generic [ref=e177]: ขยายความคุ้มครองความเสียหายต่อทรัพย์สินส่วนบุคคล และค่าซ่อมแซมตัวอาคารจากร่องรอยงัดแงะที่เกิดเหตุ (รวมอยู่ในวงเงินหมวดโจรกรรม)
                  - generic [ref=e178] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e179]: "-"
                - generic [ref=e183]: ความสูญเสียหรือความเสียหาย
                - generic [ref=e184]: "-"
          - generic [ref=e185]:
            - heading "ภัยที่เกิดกับกระจก" [level=3] [ref=e186]:
              - button "ภัยที่เกิดกับกระจก" [expanded] [ref=e187] [cursor=pointer]:
                - generic [ref=e188]: ภัยที่เกิดกับกระจก
                - img [ref=e190]
            - region [ref=e195]:
              - generic [ref=e197]:
                - generic [ref=e201]: ความเสียหายต่อกระจกที่ติดตั้งถาวร
                - generic [ref=e202]: "-"
          - generic [ref=e203]:
            - heading "ความรับผิดต่อบุคคลภายนอก" [level=3] [ref=e204]:
              - button "ความรับผิดต่อบุคคลภายนอก" [expanded] [ref=e205] [cursor=pointer]:
                - generic [ref=e206]: ความรับผิดต่อบุคคลภายนอก
                - img [ref=e208]
            - region [ref=e213]:
              - generic [ref=e215]:
                - generic [ref=e219]: ความรับผิดตามกฎหมายต่อบุคคลภายนอกต่อการบาดเจ็บเสียชีวิต และทรัพย์สินของบุคคลภายนอก
                - generic [ref=e220]: "-"
          - generic [ref=e221]:
            - heading "ประกันภัยเงินทดแทนแรงงาน" [level=3] [ref=e222]:
              - button "ประกันภัยเงินทดแทนแรงงาน" [expanded] [ref=e223] [cursor=pointer]:
                - generic [ref=e224]: ประกันภัยเงินทดแทนแรงงาน
                - img [ref=e226]
            - region [ref=e231]:
              - generic [ref=e233]:
                - generic [ref=e234]:
                  - generic [ref=e237]: ความรับผิดตามกฎหมายแรงงาน หากลูกจ้างประจำได้รับความบาดเจ็บจากอุบัติเหตุ หรือความเจ็บป่วยในระหว่างการทำงาน
                  - generic [ref=e238] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e239]: "-"
          - generic [ref=e240]:
            - heading "ไฟไหม้ ฟ้าผ่า" [level=3] [ref=e241]:
              - button "ไฟไหม้ ฟ้าผ่า" [expanded] [ref=e242] [cursor=pointer]:
                - generic [ref=e243]: ไฟไหม้ ฟ้าผ่า
                - img [ref=e245]
            - region [ref=e250]:
              - generic [ref=e252]:
                - generic [ref=e256]: ขยายภัยเพิ่มพิเศษ ภัยแผ่นดินไหว
                - generic [ref=e257]: "-"
        - generic [ref=e258]:
          - button "ย้อนกลับ" [ref=e259] [cursor=pointer]:
            - img [ref=e261]
            - text: ย้อนกลับ
          - button "เลือกแผนนี้" [ref=e263] [cursor=pointer]:
            - text: เลือกแผนนี้
            - img [ref=e265]
    - contentinfo [ref=e267]:
      - link "TQM Logo" [ref=e269] [cursor=pointer]:
        - /url: /
        - img "TQM Logo" [ref=e270]
      - generic [ref=e271]:
        - button "ผลิตภัณฑ์ประกันภัย" [ref=e274] [cursor=pointer]:
          - generic [ref=e276]: ผลิตภัณฑ์ประกันภัย
          - img [ref=e278]
        - button "บริการลูกค้า" [ref=e282] [cursor=pointer]:
          - generic [ref=e284]: บริการลูกค้า
          - img [ref=e286]
        - button "ติดต่อสอบถาม" [ref=e290] [cursor=pointer]:
          - generic [ref=e292]: ติดต่อสอบถาม
          - img [ref=e294]
        - button "บริษัท" [ref=e298] [cursor=pointer]:
          - generic [ref=e300]: บริษัท
          - img [ref=e302]
        - generic [ref=e304]:
          - generic [ref=e305]:
            - link "line" [ref=e307] [cursor=pointer]:
              - /url: https://lin.ee/Ds7qY7v
              - img "line" [ref=e308]
            - link "facebook" [ref=e310] [cursor=pointer]:
              - /url: https://www.facebook.com/TqmBroker
              - img "facebook" [ref=e311]
            - link "instagram" [ref=e313] [cursor=pointer]:
              - /url: https://www.instagram.com/tqminsurancebroker
              - img "instagram" [ref=e314]
            - link "tiktok" [ref=e316] [cursor=pointer]:
              - /url: http://www.tiktok.com/@tqmmorelove
              - img "tiktok" [ref=e317]
            - link "youtube" [ref=e319] [cursor=pointer]:
              - /url: https://www.youtube.com/@TQMInsuranceBrokerOfficial
              - img "youtube" [ref=e320]
            - link "x" [ref=e322] [cursor=pointer]:
              - /url: https://x.com/Tqmbeside
              - img "x" [ref=e323]
          - link "1737" [ref=e325] [cursor=pointer]:
            - /url: tel:1737
            - img [ref=e326]
            - text: "1737"
        - generic [ref=e329]:
          - link "TQM Application" [ref=e331] [cursor=pointer]:
            - /url: https://tqm.onelink.me/jwZj/fsmrwgvs
            - img "TQM Application" [ref=e332]
          - generic [ref=e333]:
            - link "TQM IOS Application" [ref=e334] [cursor=pointer]:
              - /url: https://apps.apple.com/th/app/tqm24/id1274502784
              - img "TQM IOS Application" [ref=e335]
            - link "TQM Android Application" [ref=e336] [cursor=pointer]:
              - /url: https://play.google.com/store/apps/details?id=com.tqm.tqmapp
              - img "TQM Android Application" [ref=e337]
            - link "TQM APK Download" [ref=e338] [cursor=pointer]:
              - /url: https://storage.googleapis.com/tqm-beta-static/files/APK/tqm24.apk
              - img "TQM APK Download" [ref=e339]
        - generic [ref=e340]:
          - paragraph [ref=e341]: ©Copyright 2026 TQM.co.th All Rights Reserved.
          - generic [ref=e342]:
            - paragraph [ref=e343]:
              - link "แผนผังเว็บไซต์" [ref=e344] [cursor=pointer]:
                - /url: https://devweb.tqm.co.th/sitemap
            - paragraph [ref=e345]:
              - link "ข้อกำหนดและเงื่อนไข" [ref=e346] [cursor=pointer]:
                - /url: /terms-and-conditions
            - paragraph [ref=e347]:
              - link "นโยบายข้อมูลส่วนบุคคล" [ref=e348] [cursor=pointer]:
                - /url: /tqm/privacy
    - generic [ref=e349]:
      - generic:
        - generic:
          - generic:
            - img
        - generic:
          - button "Close notification":
            - img
          - generic:
            - paragraph: สนใจแผนนี้อยู่รึเปล่า? สงสัยถามพี่หมีได้เลย
      - button "Toggle chat" [ref=e350] [cursor=pointer]:
        - img "chat-on-web" [ref=e351]
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
  - alert [ref=e352]: รายละเอียดประกันอัคคีภัย บ้าน | TQM ทีคิวเอ็ม
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