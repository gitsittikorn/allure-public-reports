# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: main-web/accident/accident-normal-flow.spec.ts >> accident-normal-flow-no-tax-deduction
- Location: tests/main-web/accident/accident-normal-flow.spec.ts:57:5

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
          - generic [ref=e47]: แผนประกัน
          - generic [ref=e48]:
            - img "แผนประกัน" [ref=e50]
            - generic [ref=e52]: ประกันอุบัติเหตุ
            - generic [ref=e54] [cursor=pointer]:
              - img [ref=e55]
              - text: แก้ไข
        - generic [ref=e58]:
          - generic [ref=e59]:
            - img "ทิพยประกันภัย" [ref=e61]
            - generic [ref=e62]:
              - generic [ref=e63]: ทิพยประกันภัย
              - generic [ref=e64]: ประกันภัยอุบัติเหตุระยะสั้น 30 วัน
          - generic [ref=e66]:
            - generic [ref=e67]:
              - paragraph [ref=e68]: จำนวนเงินเอาประกันภัย
              - paragraph [ref=e69]: ฿ 200,000
              - paragraph [ref=e70]: ชดเชยรายได้
              - paragraph [ref=e71]: ฿ 1,900
            - generic [ref=e72]:
              - paragraph [ref=e73]: อายุระหว่าง 1-70 ปี
              - paragraph [ref=e74]: ฿ 18
          - generic [ref=e75]:
            - heading "การเสียชีวิต การสูญเสียมือ เท้า หรือสายตาโดยถาวรสิ้นเชิง หรือการทุพพลภาพถาวรสิ้นเชิง (อ.บ.1)" [level=3] [ref=e76]:
              - button "การเสียชีวิต การสูญเสียมือ เท้า หรือสายตาโดยถาวรสิ้นเชิง หรือการทุพพลภาพถาวรสิ้นเชิง (อ.บ.1)" [expanded] [ref=e77] [cursor=pointer]:
                - generic [ref=e78]: การเสียชีวิต การสูญเสียมือ เท้า หรือสายตาโดยถาวรสิ้นเชิง หรือการทุพพลภาพถาวรสิ้นเชิง (อ.บ.1)
                - img [ref=e80]
            - region [ref=e85]:
              - generic [ref=e87]:
                - generic [ref=e90]:
                  - generic [ref=e91]: "- จากอุบัติเหตุทั่วไป"
                  - generic "จากอุบัติเหตุทั่วไป" [ref=e92]:
                    - img "จากอุบัติเหตุทั่วไป" [ref=e93]
                - generic [ref=e94]: 100,000 บาท
                - generic [ref=e97]:
                  - generic [ref=e98]: "- ขณะขับขี่หรือโดยสารรถจักรยานยนต์"
                  - generic "ขณะขับขี่หรือโดยสารรถจักรยานยนต์" [ref=e99]:
                    - img "ขณะขับขี่หรือโดยสารรถจักรยานยนต์" [ref=e100]
                - generic [ref=e101]: 50,000 บาท
                - generic [ref=e104]:
                  - generic [ref=e105]: "- การถูกฆาตรกรรมหรือถูกทำร้ายร่างกาย"
                  - generic "การถูกฆาตรกรรมหรือถูกทำร้ายร่างกาย" [ref=e106]:
                    - img "การถูกฆาตรกรรมหรือถูกทำร้ายร่างกาย" [ref=e107]
                - generic [ref=e108]: 50,000 บาท
          - generic [ref=e109]:
            - heading "เงินชดเชยรายวันกรณีนอนพักรักษาตัวเป็นผู้ป่วยในของโรงพยาบาลหรือสถานพยาบาลเวชกรรมเนื่องจากอุบัติเหตุ" [level=3] [ref=e110]:
              - button "เงินชดเชยรายวันกรณีนอนพักรักษาตัวเป็นผู้ป่วยในของโรงพยาบาลหรือสถานพยาบาลเวชกรรมเนื่องจากอุบัติเหตุ" [expanded] [ref=e111] [cursor=pointer]:
                - generic [ref=e112]: เงินชดเชยรายวันกรณีนอนพักรักษาตัวเป็นผู้ป่วยในของโรงพยาบาลหรือสถานพยาบาลเวชกรรมเนื่องจากอุบัติเหตุ
                - img [ref=e114]
            - region [ref=e119]:
              - generic [ref=e121]:
                - generic [ref=e124]:
                  - generic [ref=e125]: "- สูงสุด 7 วัน/ครั้ง"
                  - generic "สูงสุด 7 วัน/ครั้ง" [ref=e126]:
                    - img "สูงสุด 7 วัน/ครั้ง" [ref=e127]
                - generic [ref=e128]: 200 บาท
          - generic [ref=e129]:
            - heading "ผลประโยชน์กรณีเป็นผู้ป่วยใน" [level=3] [ref=e130]:
              - button "ผลประโยชน์กรณีเป็นผู้ป่วยใน" [expanded] [ref=e131] [cursor=pointer]:
                - generic [ref=e132]: ผลประโยชน์กรณีเป็นผู้ป่วยใน
                - img [ref=e134]
            - region [ref=e139]:
              - generic [ref=e141]:
                - generic [ref=e144]:
                  - generic [ref=e145]: ผลประโยชน์สูงสุดต่อการรักษาแต่ละครั้ง
                  - generic "ผลประโยชน์สูงสุดต่อการรักษาแต่ละครั้ง" [ref=e146]:
                    - img "ผลประโยชน์สูงสุดต่อการรักษาแต่ละครั้ง" [ref=e147]
                - generic [ref=e148]: 100 บาท
          - generic [ref=e149]:
            - heading "ผลประโยชน์กรณีไม่ต้องเข้าพักรักษาตัวเป็นผู้ป่วยใน" [level=3] [ref=e150]:
              - button "ผลประโยชน์กรณีไม่ต้องเข้าพักรักษาตัวเป็นผู้ป่วยใน" [expanded] [ref=e151] [cursor=pointer]:
                - generic [ref=e152]: ผลประโยชน์กรณีไม่ต้องเข้าพักรักษาตัวเป็นผู้ป่วยใน
                - img [ref=e154]
            - region [ref=e159]:
              - generic [ref=e161]:
                - generic [ref=e162]:
                  - generic [ref=e164]:
                    - generic [ref=e165]: หมวดที่ 6 ค่าบริการทางการแพทย์เพื่อตรวจวินิจฉัยที่เกี่ยวข้องโดยตรงก่อนและหลังการเข้าพักรักษาตัวเป็นผู้ป่วยใน หรือค่ารักษาพยาบาลผู้ป่วยนอกที่ต่อเนื่องที่เกี่ยวข้องโดยตรงหลังการเข้าพักรักษาตัวเป็นผู้ป่วยในต่อการเข้าพักรักษาตัวเป็นผู้ป่วยในครั้งใดครั้งหนึ่ง
                    - generic "หมวดที่ 6 ค่าบริก" [ref=e166]:
                      - img "หมวดที่ 6 ค่าบริก" [ref=e167]
                  - generic [ref=e168] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e169]: 1,000 บาท
          - generic [ref=e170]:
            - heading "ผลประโยชน์ชดเชยรายวัน" [level=3] [ref=e171]:
              - button "ผลประโยชน์ชดเชยรายวัน" [expanded] [ref=e172] [cursor=pointer]:
                - generic [ref=e173]: ผลประโยชน์ชดเชยรายวัน
                - img [ref=e175]
            - region [ref=e180]:
              - generic [ref=e182]:
                - generic [ref=e185]:
                  - generic [ref=e186]: ชดเชยรายได้ระหว่างเข้าพักรักษาตัวในโรงพยาบาลในฐานะผู้ป่วยใน
                  - generic "ชดเชยรายได้ระหว่างเข้าพักรักษาตัวในโรงพยาบาลในฐานะผู้ป่วย" [ref=e187]:
                    - img "ชดเชยรายได้ระหว่างเข้าพักรักษาตัวในโรงพยาบาลในฐานะผู้ป่วย" [ref=e188]
                - generic [ref=e189]: 1,900 บาท
        - generic [ref=e190]:
          - generic [ref=e191]: เงื่อนไขการรับประกัน
          - paragraph [ref=e192]:
            - paragraph [ref=e193]:
              - text: เงื่อนไขการรับประกันนะ นะ นะ
              - text: เงื่อนไขการรับประกันนะ นะ นะ
              - text: เงื่อนไขการรับประกันนะ นะ นะ
            - paragraph [ref=e194]:
              - strong [ref=e195]: เงื่อนไขการรับประกันนะ นะ นะ
              - strong [ref=e196]: เงื่อนไขการรับประกันนะ นะ นะ
              - strong [ref=e197]: เงื่อนไขการรับประกันนะ นะ นะ
            - generic [ref=e199]:
              - paragraph [ref=e200]:
                - emphasis [ref=e201]:
                  - text: เงื่อนไขการรับประกันนะ นะ นะ
                  - text: เงื่อนไขการรับประกันนะ นะ นะ
                - emphasis [ref=e202]: เงื่อนไขการรับประกันนะ นะ นะ
                - strong
              - paragraph [ref=e203]:
                - text: เงื่อนไขการรับประกันนะ นะ นะ
                - text: เงื่อนไขการรับประกันนะ นะ นะ
                - text: เงื่อนไขการรับประกันนะ นะ นะ
              - paragraph [ref=e205]:
                - emphasis [ref=e207]:
                  - strong [ref=e208]: เงื่อนไขการรับประกันนะ นะ นะ
                - emphasis [ref=e210]:
                  - strong [ref=e211]: เงื่อนไขการรับประกันนะ นะ นะ
                - emphasis [ref=e213]:
                  - strong [ref=e214]: เงื่อนไขการรับประกันนะ นะ นะ
              - paragraph [ref=e216]:
                - generic [ref=e217]:
                  - strong [ref=e218]: เงื่อนไขการรับประกันนะ นะ นะ
                  - strong [ref=e219]: เงื่อนไขการรับประกันนะ นะ นะ
                  - strong [ref=e220]: เงื่อนไขการรับประกันนะ นะ นะ
        - generic [ref=e221]:
          - button "ย้อนกลับ" [ref=e222] [cursor=pointer]:
            - img [ref=e224]
            - text: ย้อนกลับ
          - button "เลือกแผนนี้" [ref=e226] [cursor=pointer]:
            - text: เลือกแผนนี้
            - img [ref=e228]
    - contentinfo [ref=e230]:
      - link "TQM Logo" [ref=e232] [cursor=pointer]:
        - /url: /
        - img "TQM Logo" [ref=e233]
      - generic [ref=e234]:
        - button "ผลิตภัณฑ์ประกันภัย" [ref=e237] [cursor=pointer]:
          - generic [ref=e239]: ผลิตภัณฑ์ประกันภัย
          - img [ref=e241]
        - button "บริการลูกค้า" [ref=e245] [cursor=pointer]:
          - generic [ref=e247]: บริการลูกค้า
          - img [ref=e249]
        - button "ติดต่อสอบถาม" [ref=e253] [cursor=pointer]:
          - generic [ref=e255]: ติดต่อสอบถาม
          - img [ref=e257]
        - button "บริษัท" [ref=e261] [cursor=pointer]:
          - generic [ref=e263]: บริษัท
          - img [ref=e265]
        - generic [ref=e267]:
          - generic [ref=e268]:
            - link "line" [ref=e270] [cursor=pointer]:
              - /url: https://lin.ee/Ds7qY7v
              - img "line" [ref=e271]
            - link "facebook" [ref=e273] [cursor=pointer]:
              - /url: https://www.facebook.com/TqmBroker
              - img "facebook" [ref=e274]
            - link "instagram" [ref=e276] [cursor=pointer]:
              - /url: https://www.instagram.com/tqminsurancebroker
              - img "instagram" [ref=e277]
            - link "tiktok" [ref=e279] [cursor=pointer]:
              - /url: http://www.tiktok.com/@tqmmorelove
              - img "tiktok" [ref=e280]
            - link "youtube" [ref=e282] [cursor=pointer]:
              - /url: https://www.youtube.com/@TQMInsuranceBrokerOfficial
              - img "youtube" [ref=e283]
            - link "x" [ref=e285] [cursor=pointer]:
              - /url: https://x.com/Tqmbeside
              - img "x" [ref=e286]
          - link "1737" [ref=e288] [cursor=pointer]:
            - /url: tel:1737
            - img [ref=e289]
            - text: "1737"
        - generic [ref=e292]:
          - link "TQM Application" [ref=e294] [cursor=pointer]:
            - /url: https://tqm.onelink.me/jwZj/fsmrwgvs
            - img "TQM Application" [ref=e295]
          - generic [ref=e296]:
            - link "TQM IOS Application" [ref=e297] [cursor=pointer]:
              - /url: https://apps.apple.com/th/app/tqm24/id1274502784
              - img "TQM IOS Application" [ref=e298]
            - link "TQM Android Application" [ref=e299] [cursor=pointer]:
              - /url: https://play.google.com/store/apps/details?id=com.tqm.tqmapp
              - img "TQM Android Application" [ref=e300]
            - link "TQM APK Download" [ref=e301] [cursor=pointer]:
              - /url: https://storage.googleapis.com/tqm-beta-static/files/APK/tqm24.apk
              - img "TQM APK Download" [ref=e302]
        - generic [ref=e303]:
          - paragraph [ref=e304]: ©Copyright 2026 TQM.co.th All Rights Reserved.
          - generic [ref=e305]:
            - paragraph [ref=e306]:
              - link "แผนผังเว็บไซต์" [ref=e307] [cursor=pointer]:
                - /url: https://devweb.tqm.co.th/sitemap
            - paragraph [ref=e308]:
              - link "ข้อกำหนดและเงื่อนไข" [ref=e309] [cursor=pointer]:
                - /url: /terms-and-conditions
            - paragraph [ref=e310]:
              - link "นโยบายข้อมูลส่วนบุคคล" [ref=e311] [cursor=pointer]:
                - /url: /tqm/privacy
    - generic [ref=e312]:
      - generic:
        - generic:
          - generic:
            - img
        - generic:
          - button "Close notification":
            - img
          - generic:
            - paragraph: สนใจแผนนี้อยู่รึเปล่า? สงสัยถามพี่หมีได้เลย
      - button "Toggle chat" [ref=e313] [cursor=pointer]:
        - img "chat-on-web" [ref=e314]
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
  - alert [ref=e315]: รายละเอียดประกันอุบัติเหตุ | TQM ทีคิวเอ็ม
```

# Test source

```ts
  1  | import { Page, expect } from "@playwright/test";
  2  | import { commonLocator } from "../../../../locator/nmw/nmw-common-locator";
  3  | import { AccidentProductDetailType } from "../../../../types/accident.type";
  4  | import CommonTQM from "../../../../utils/common-tqm";
  5  | 
  6  | export default class AccidentProductDetailPage {
  7  |   constructor(public page: Page) {}
  8  | 
  9  |     async checkProductData(accidentProductDetail: AccidentProductDetailType) {
  10 |       await expect(this.page.getByTestId(commonLocator.TEXT_ID_PRODUCT_DATA)).toBeVisible();
  11 |       const productData = await this.page
  12 |         .getByTestId(commonLocator.TEXT_ID_PRODUCT_DATA)
  13 |         .textContent();
  14 |       expect(productData?.trim()).toBe(accidentProductDetail.productData);
  15 |     }
  16 | 
  17 |   async getInsurePrice(accidentProductDetail: AccidentProductDetailType) {
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
  28 |       accidentProductDetail.insurePrice = await CommonTQM.getInsurePrice(
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
  39 |       accidentProductDetail.insurePrice = await CommonTQM.getInsurePrice(
  40 |         this.page,
  41 |         commonLocator.TEXT_ID_INSURE_PRICE
  42 |       );
  43 |     }
  44 |   }
  45 | 
  46 |   async getInsureName(accidentProductDetail: AccidentProductDetailType) {
  47 |     await expect(this.page.getByTestId(commonLocator.TEXT_ID_COMPANY_NAME)).toBeVisible();
  48 |     const companyNameText = await this.page
  49 |       .getByTestId(commonLocator.TEXT_ID_COMPANY_NAME)
  50 |       .textContent();
  51 |     expect(companyNameText?.trim()).not.toBe("0");
  52 |     accidentProductDetail.insureName = await CommonTQM.getInsureName(
  53 |       this.page,
  54 |       commonLocator.TEXT_ID_COMPANY_NAME
  55 |     );
  56 |     await this.page.getByTestId("nextStepButton").click();
  57 |   }
  58 | }
  59 | 
```