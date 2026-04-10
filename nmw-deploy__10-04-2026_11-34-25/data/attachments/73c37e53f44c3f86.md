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
            - img "เมืองไทยประกันภัย" [ref=e61]
            - generic [ref=e62]:
              - generic [ref=e63]: เมืองไทยประกันภัย
              - generic [ref=e64]: HAPPYTRIP ASIA Daily
          - generic [ref=e65]:
            - generic [ref=e67]:
              - img "coupon" [ref=e68]
              - generic [ref=e69]:
                - paragraph [ref=e70]: ส่วนลด 5%
                - paragraph [ref=e71]: คูปอง (เฉพาะช่องทางออนไลน์เท่านั้น)
            - generic [ref=e72]:
              - generic [ref=e73]:
                - paragraph [ref=e74]: ค่ารักษาพยาบาล
                - paragraph [ref=e75]: ฿ 2,000,000
                - paragraph [ref=e76]: เสียชีวิตจากอุบัติเหตุ
                - paragraph [ref=e77]: ฿ 1,500,000
              - generic [ref=e78]:
                - paragraph [ref=e79]: อายุระหว่าง 1-75 ปี
                - paragraph [ref=e80]:
                  - text: ฿ 201.19
                  - generic [ref=e81]: ฿ 211
                - paragraph [ref=e82]: ราคาต่อคน
          - generic [ref=e83]:
            - heading "ความคุ้มครองชีวิตและค่ารักษาพยาบาล" [level=3] [ref=e84]:
              - button "ความคุ้มครองชีวิตและค่ารักษาพยาบาล" [expanded] [ref=e85] [cursor=pointer]:
                - generic [ref=e86]: ความคุ้มครองชีวิตและค่ารักษาพยาบาล
                - img [ref=e88]
            - region [ref=e93]:
              - generic [ref=e95]:
                - generic [ref=e96]:
                  - generic [ref=e98]:
                    - generic [ref=e99]: การสูญเสียชีวิต หรืออวัยวะ สายตา หรือทุพพลภาพถาวรสิ้นเชิง เนื่องจากการขับขี่หรือโดยสารรถจักรยานยนต์
                    - generic "การสูญเสียชีวิต หรืออวัยวะ สายตา หรือทุพพลภาพถาวรสิ้นเชิง เนื่องจากการขับขี่หรือโดยสารรถจักรยานยนต์" [ref=e100]:
                      - img "การสูญเสียชีวิต หรืออวัยวะ สายตา หรือทุพพลภาพถาวรสิ้นเชิง เนื่องจากการขับขี่หรือโดยสารรถจักรยานยนต์" [ref=e101]
                  - generic [ref=e102] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e103]: "-"
                - generic [ref=e106]:
                  - generic [ref=e107]: ค่ารักษาพยาบาลระหว่างการเดินทาง จ่ายตามจริงสูงสุด
                  - generic "ค่ารักษาพยาบาลระหว่างการเดินทาง จ่ายตามจริงสูงสุด" [ref=e108]:
                    - img "ค่ารักษาพยาบาลระหว่างการเดินทาง จ่ายตามจริงสูงสุด" [ref=e109]
                - generic [ref=e110]: 2,000,000 บาท
                - generic [ref=e113]:
                  - generic [ref=e114]: ค่ารักษาพยาบาลต่อเนื่องหลังจากกลับถึงประเทศไทย จ่ายตามจริงสูงสุด
                  - generic "ค่ารักษาพยาบาลต่อเนื่องหลังจากกลับถึงประเทศไทย จ่ายตามจริงสูงสุด" [ref=e115]:
                    - img "ค่ารักษาพยาบาลต่อเนื่องหลังจากกลับถึงประเทศไทย จ่ายตามจริงสูงสุด" [ref=e116]
                - generic [ref=e117]: 150,000 บาท
                - generic [ref=e120]:
                  - generic [ref=e121]: ค่าเดินทางเพื่อรักษาพยาบาลแบบผู้ป่วยนอกในต่างประเทศ
                  - generic "ค่าเดินทางเพื่อรักษาพยาบาลแบบผู้ป่วยนอกในต่างประเทศ" [ref=e122]:
                    - img "ค่าเดินทางเพื่อรักษาพยาบาลแบบผู้ป่วยนอกในต่างประเทศ" [ref=e123]
                - generic [ref=e124]: "-"
                - generic [ref=e127]:
                  - generic [ref=e128]: ค่ายาผู้ป่วยนอกจากการรักษาผ่านการแพทย์ทางไกล (Telemedicine)
                  - generic "ค่ายาผู้ป่วยนอกจากการรักษาผ่านการแพทย์ทางไกล" [ref=e129]:
                    - img "ค่ายาผู้ป่วยนอกจากการรักษาผ่านการแพทย์ทางไกล" [ref=e130]
                - generic [ref=e131]: "-"
                - generic [ref=e134]:
                  - generic [ref=e135]: การรับการรักษาพยาบาลในประเทศไทย จ่ายตามจริงสูงสุด
                  - generic "การรับการรักษาพยาบาลในประเทศไทย จ่ายตามจริงสูงสุด" [ref=e136]:
                    - img "การรับการรักษาพยาบาลในประเทศไทย จ่ายตามจริงสูงสุด" [ref=e137]
                - generic [ref=e138]: "-"
                - generic [ref=e139]:
                  - generic [ref=e141]:
                    - generic [ref=e142]: การเคลื่อนย้ายเพื่อการรักษาพยาบาลฉุกเฉินหรือการเคลื่อนย้ายกลับสู่ประเทศไทย จ่ายสูงสุดไม่เกิน
                    - generic "การเคลื่อนย้ายเพื่อการรักษาพยาบาลฉุกเฉินหรือการเคลื่อนย้ายกลับสู่ประเทศไทย จ่ายสูงสุดไม่เกิน" [ref=e143]:
                      - img "การเคลื่อนย้ายเพื่อการรักษาพยาบาลฉุกเฉินหรือการเคลื่อนย้ายกลับสู่ประเทศไทย จ่ายสูงสุดไม่เกิน" [ref=e144]
                  - generic [ref=e145] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e146]: 30,000,000 บาท
                - generic [ref=e147]:
                  - generic [ref=e149]:
                    - generic [ref=e150]: กรณีตรวจสอบพบว่าเกิดจากการบาดเจ็บหรือเจ็บป่วยที่ไม่ใช่สภาพที่เป็นมาก่อนการเอาประกันภัย
                    - generic "กรณีตรวจสอบพบว่าเกิดจากการบาดเจ็บหรือเจ็บป่วยที่ไม่ใช่สภาพที่เป็นมาก่อนการเอาประกันภัย" [ref=e151]:
                      - img "กรณีตรวจสอบพบว่าเกิดจากการบาดเจ็บหรือเจ็บป่วยที่ไม่ใช่สภาพที่เป็นมาก่อนการเอาประกันภัย" [ref=e152]
                  - generic [ref=e153] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e154]: "-"
                - generic [ref=e155]:
                  - generic [ref=e157]:
                    - generic [ref=e158]: กรณีตรวจสอบพบว่าเกิดจากการบาดเจ็บหรือเจ็บป่วยจากสภาพที่เป็นมาก่อนการเอาประกันภัย
                    - generic "กรณีตรวจสอบพบว่าเกิดจากการบาดเจ็บหรือเจ็บป่วยจากสภาพที่เป็นมาก่อนการเอาประกันภัย" [ref=e159]:
                      - img "กรณีตรวจสอบพบว่าเกิดจากการบาดเจ็บหรือเจ็บป่วยจากสภาพที่เป็นมาก่อนการเอาประกันภัย" [ref=e160]
                  - generic [ref=e161] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e162]: "-"
                - generic [ref=e165]:
                  - generic [ref=e166]: เงินชดเชยรายวันระหว่างรักษาตัวในโรงพยาบาล ในฐานะผู้ป่วยใน
                  - generic "เงินชดเชยรายวันระหว่างรักษาตัวในโรงพยาบาล ในฐานะผู้ป่วยใน" [ref=e167]:
                    - img "เงินชดเชยรายวันระหว่างรักษาตัวในโรงพยาบาล ในฐานะผู้ป่วยใน" [ref=e168]
                - generic [ref=e169]: "-"
                - generic [ref=e172]:
                  - generic [ref=e173]: ค่าศัลยกรรมอันเนื่องมาจากอุบัติเหตุ
                  - generic "ค่าศัลยกรรมอันเนื่องมาจากอุบัติเหตุ" [ref=e174]:
                    - img "ค่าศัลยกรรมอันเนื่องมาจากอุบัติเหตุ" [ref=e175]
                - generic [ref=e176]: "-"
                - generic [ref=e179]:
                  - generic [ref=e180]: การเคลื่อนย้ายเพื่อการรักษาพยาบาลฉุกเฉิน
                  - generic "การเคลื่อนย้ายเพื่อการรักษาพยาบาลฉุกเฉิน" [ref=e181]:
                    - img "การเคลื่อนย้ายเพื่อการรักษาพยาบาลฉุกเฉิน" [ref=e182]
                - generic [ref=e183]: "-"
                - generic [ref=e184]:
                  - generic [ref=e186]:
                    - generic [ref=e187]: การเสียชีวิต การสูญเสียอวัยวะ และสายตา หรือทุพพลภาพถาวรจาก อุบัติเหตุขณะเข้าร่วมเทศกาล ประจำปี
                    - generic "การเสียชีวิต การสูญเสียอวัยวะ และสายตา หรือทุพพลภาพถาวรจาก อุบัติเหตุขณะเข้าร่วมเทศกาล ประจำปี" [ref=e188]:
                      - img "การเสียชีวิต การสูญเสียอวัยวะ และสายตา หรือทุพพลภาพถาวรจาก อุบัติเหตุขณะเข้าร่วมเทศกาล ประจำปี" [ref=e189]
                  - generic [ref=e190] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e191]: "-"
                - generic [ref=e194]:
                  - generic [ref=e195]: ค่ารักษาพยาบาลเนื่องจากอุบัติเหตุขณะเข้าร่วมเทศกาลประจำปี
                  - generic "ค่ารักษาพยาบาลเนื่องจากอุบัติเหตุขณะเข้าร่วมเทศกาลประจำปี" [ref=e196]:
                    - img "ค่ารักษาพยาบาลเนื่องจากอุบัติเหตุขณะเข้าร่วมเทศกาลประจำปี" [ref=e197]
                - generic [ref=e198]: "-"
                - generic [ref=e201]:
                  - generic [ref=e202]: ค่ารักษาพยาบาล อาหารเป็นพิษขณะเดินทาง (IPD only)
                  - generic "ค่ารักษาพยาบาล อาหารเป็นพิษขณะเดินทาง (IPD only)" [ref=e203]:
                    - img "ค่ารักษาพยาบาล อาหารเป็นพิษขณะเดินทาง (IPD only)" [ref=e204]
                - generic [ref=e205]: "-"
                - generic [ref=e208]:
                  - generic [ref=e209]: ค่ารักษาพยาบาลเนื่องจากอุบัติเหตุ
                  - generic "ค่ารักษาพยาบาลเนื่องจากอุบัติเหตุ" [ref=e210]:
                    - img "ค่ารักษาพยาบาลเนื่องจากอุบัติเหตุ" [ref=e211]
                - generic [ref=e212]: "-"
                - generic [ref=e215]:
                  - generic [ref=e216]: การเสียชีวิต การสูญเสียอวัยวะ สายตา หรือ ทุพพลภาพถาวรสิ้นเชิงเนื่องจากอุบัติเหตุ
                  - generic "การเสียชีวิต การสูญเสียอวัยวะ สายตา หรือ ทุพพลภาพถาวรสิ้นเชิงเนื่องจากอุบัติเหตุ" [ref=e217]:
                    - img "การเสียชีวิต การสูญเสียอวัยวะ สายตา หรือ ทุพพลภาพถาวรสิ้นเชิงเนื่องจากอุบัติเหตุ" [ref=e218]
                - generic [ref=e219]: 1,500,000 บาท
                - generic [ref=e222]:
                  - generic [ref=e223]: การประกันภัยโจรกรรม
                  - generic "การประกันภัยโจรกรรม" [ref=e224]:
                    - img "การประกันภัยโจรกรรม" [ref=e225]
                - generic [ref=e226]: "-"
          - generic [ref=e227]:
            - heading "ความคุ้มครองสัมภาระและทรัพย์สิน" [level=3] [ref=e228]:
              - button "ความคุ้มครองสัมภาระและทรัพย์สิน" [expanded] [ref=e229] [cursor=pointer]:
                - generic [ref=e230]: ความคุ้มครองสัมภาระและทรัพย์สิน
                - img [ref=e232]
            - region [ref=e237]:
              - generic [ref=e239]:
                - generic [ref=e240]:
                  - generic [ref=e242]:
                    - generic [ref=e243]: การสูญหายหรือเสียหายของกระเป๋าเดินทางและ/หรือทรัพย์สินส่วนตัว ภายในกระเป๋าเดินทาง จ่ายตามจริงสูงสุด
                    - generic "การสูญหายหรือเสียหายของกระเป๋าเดินทางและ/หรือทรัพย์สินส่วนตัว ภายในกระเป๋าเดินทาง จ่ายตามจริงสูงสุด" [ref=e244]:
                      - img "การสูญหายหรือเสียหายของกระเป๋าเดินทางและ/หรือทรัพย์สินส่วนตัว ภายในกระเป๋าเดินทาง จ่ายตามจริงสูงสุด" [ref=e245]
                  - generic [ref=e246] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e247]: "-"
                - generic [ref=e250]:
                  - generic [ref=e251]: การล่าช้าของกระเป๋าเดินทาง จ่ายสูงสุดไม่เกิน
                  - generic "การล่าช้าของกระเป๋าเดินทาง จ่ายสูงสุดไม่เกิน" [ref=e252]:
                    - img "การล่าช้าของกระเป๋าเดินทาง จ่ายสูงสุดไม่เกิน" [ref=e253]
                - generic [ref=e254]: "-"
                - generic [ref=e257]:
                  - generic [ref=e258]: การสูญหายหรือเสียหายของเงินสด
                  - generic "การสูญหายหรือเสียหายของเงินสด" [ref=e259]:
                    - img "การสูญหายหรือเสียหายของเงินสด" [ref=e260]
                - generic [ref=e261]: "-"
                - generic [ref=e264]:
                  - generic [ref=e265]: การสูญหายหรือเสียหายของเอกสารที่เกี่ยวข้องกับการเดินทาง จ่ายตามจริงสูงสุด
                  - generic "การสูญหายหรือเสียหายของเอกสารที่เกี่ยวข้องกับการเดินทาง จ่ายตามจริงสูงสุด" [ref=e266]:
                    - img "การสูญหายหรือเสียหายของเอกสารที่เกี่ยวข้องกับการเดินทาง จ่ายตามจริงสูงสุด" [ref=e267]
                - generic [ref=e268]: "-"
                - generic [ref=e271]:
                  - generic [ref=e272]: ความสูญเสียหรือความเสียหายของคอมพิวเตอร์โน้ตบุ๊ค จ่ายตามจริงสูงสุด
                  - generic "ความสูญเสียหรือความเสียหายของคอมพิวเตอร์โน้ตบุ๊ค จ่ายตามจริงสูงสุด" [ref=e273]:
                    - img "ความสูญเสียหรือความเสียหายของคอมพิวเตอร์โน้ตบุ๊ค จ่ายตามจริงสูงสุด" [ref=e274]
                - generic [ref=e275]: "-"
                - generic [ref=e276]:
                  - generic [ref=e278]:
                    - generic [ref=e279]: การสูญเสียหรือความเสียหายของ กระเป๋าเดินทาง ทรัพย์สิน รวมถึงคอมพิวเตอร์โน้ตบุ๊คอันเนื่องมาจากภัยธรรมชาติ จ่ายตามจริงสูงสุด
                    - generic "การสูญเสียหรือความเสียหายของ กระเป๋าเดินทาง ทรัพย์สิน รวมถึงคอมพิวเตอร์โน้ตบุ๊คอันเนื่องมาจากภัยธรรมชาติ จ่ายตามจริงสูงสุด" [ref=e280]:
                      - img "การสูญเสียหรือความเสียหายของ กระเป๋าเดินทาง ทรัพย์สิน รวมถึงคอมพิวเตอร์โน้ตบุ๊คอันเนื่องมาจากภัยธรรมชาติ จ่ายตามจริงสูงสุด" [ref=e281]
                  - generic [ref=e282] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e283]: "-"
          - generic [ref=e284]:
            - heading "ความคุ้มครองในการเดินทาง" [level=3] [ref=e285]:
              - button "ความคุ้มครองในการเดินทาง" [expanded] [ref=e286] [cursor=pointer]:
                - generic [ref=e287]: ความคุ้มครองในการเดินทาง
                - img [ref=e289]
            - region [ref=e294]:
              - generic [ref=e296]:
                - generic [ref=e299]:
                  - generic [ref=e300]: การยกเลิกการเดินทาง จ่ายตามจริงสูงสุด
                  - generic "การยกเลิกการเดินทาง จ่ายตามจริงสูงสุด" [ref=e301]:
                    - img "การยกเลิกการเดินทาง จ่ายตามจริงสูงสุด" [ref=e302]
                - generic [ref=e303]: "-"
                - generic [ref=e306]:
                  - generic [ref=e307]: การลดจำนวนวันเดินทาง จ่ายตามจริงสูงสุด
                  - generic "การลดจำนวนวันเดินทาง จ่ายตามจริงสูงสุด" [ref=e308]:
                    - img "การลดจำนวนวันเดินทาง จ่ายตามจริงสูงสุด" [ref=e309]
                - generic [ref=e310]: "-"
                - generic [ref=e313]:
                  - generic [ref=e314]: ความล่าช้าในการเดินทาง จ่ายสูงสุดไม่เกิน
                  - generic "ความล่าช้าในการเดินทาง จ่ายสูงสุดไม่เกิน" [ref=e315]:
                    - img "ความล่าช้าในการเดินทาง จ่ายสูงสุดไม่เกิน" [ref=e316]
                - generic [ref=e317]: "-"
                - generic [ref=e320]:
                  - generic [ref=e321]: การพลาดการต่อเที่ยวบิน จ่ายสูงสุดไม่เกิน
                  - generic "การพลาดการต่อเที่ยวบิน จ่ายสูงสุดไม่เกิน" [ref=e322]:
                    - img "การพลาดการต่อเที่ยวบิน จ่ายสูงสุดไม่เกิน" [ref=e323]
                - generic [ref=e324]: "-"
                - generic [ref=e327]:
                  - generic [ref=e328]: การจี้เครื่องบิน
                  - generic "การจี้เครื่องบิน" [ref=e329]:
                    - img "การจี้เครื่องบิน" [ref=e330]
                - generic [ref=e331]: "-"
                - generic [ref=e332]:
                  - generic [ref=e334]:
                    - generic [ref=e335]: การล่าช้าของเที่ยวบินแบบออนไทม์การันตี สำหรับเที่ยวบินขาออกจากประเทศไทย (จ่าย ไม่เกิน 1 ครั้ง กรณีขาเข้าหรือขาออก ขาใดขาหนึ่งเท่านั้น)
                    - generic "การล่าช้าของเที่ยวบินแบบออนไทม์การันตี สำหรับเที่ยวบินขาออกจากประเทศไทย (จ่าย ไม่เกิน 1 ครั้ง กรณีขาเข้าหรือขาออก ขาใดขาหนึ่งเท่านั้น)" [ref=e336]:
                      - img "การล่าช้าของเที่ยวบินแบบออนไทม์การันตี สำหรับเที่ยวบินขาออกจากประเทศไทย (จ่าย ไม่เกิน 1 ครั้ง กรณีขาเข้าหรือขาออก ขาใดขาหนึ่งเท่านั้น)" [ref=e337]
                  - generic [ref=e338] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e339]: "-"
                - generic [ref=e340]:
                  - generic [ref=e342]:
                    - generic [ref=e343]: การล่าช้าของเที่ยวบินแบบออนไทม์การันตี สำหรับเที่ยวบินขาเข้าประเทศไทย (จ่าย ไม่เกิน 1 ครั้ง กรณีขาเข้าหรือขาออก ขาใดขาหนึ่งเท่านั้น)
                    - generic "การล่าช้าของเที่ยวบินแบบออนไทม์การันตี สำหรับเที่ยวบินขาเข้าประเทศไทย (จ่าย ไม่เกิน 1 ครั้ง กรณีขาเข้าหรือขาออก ขาใดขาหนึ่งเท่านั้น)" [ref=e344]:
                      - img "การล่าช้าของเที่ยวบินแบบออนไทม์การันตี สำหรับเที่ยวบินขาเข้าประเทศไทย (จ่าย ไม่เกิน 1 ครั้ง กรณีขาเข้าหรือขาออก ขาใดขาหนึ่งเท่านั้น)" [ref=e345]
                  - generic [ref=e346] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e347]: "-"
                - generic [ref=e350]:
                  - generic [ref=e351]: การล่าช้าของระบบขนส่งมวลชน
                  - generic "การล่าช้าของระบบขนส่งมวลชน" [ref=e352]:
                    - img "การล่าช้าของระบบขนส่งมวลชน" [ref=e353]
                - generic [ref=e354]: "-"
          - generic [ref=e355]:
            - heading "ความคุ้มครองเพิ่มเติม" [level=3] [ref=e356]:
              - button "ความคุ้มครองเพิ่มเติม" [expanded] [ref=e357] [cursor=pointer]:
                - generic [ref=e358]: ความคุ้มครองเพิ่มเติม
                - img [ref=e360]
            - region [ref=e365]:
              - generic [ref=e367]:
                - generic [ref=e370]:
                  - generic [ref=e371]: ค่าใช้จ่ายในการส่งศพ หรืออัฐิกลับประเทศ จ่ายสูงสุดไม่เกิน
                  - generic "ค่าใช้จ่ายในการส่งศพ หรืออัฐิกลับประเทศ จ่ายสูงสุดไม่เกิน" [ref=e372]:
                    - img "ค่าใช้จ่ายในการส่งศพ หรืออัฐิกลับประเทศ จ่ายสูงสุดไม่เกิน" [ref=e373]
                - generic [ref=e374]: 30,000,000 บาท
                - generic [ref=e375]:
                  - generic [ref=e377]:
                    - generic [ref=e378]: กรณีตรวจสอบพบว่าเกิดจากการบาดเจ็บหรือเจ็บป่วยที่ไม่ใช่สภาพที่เป็นมาก่อนการเอาประกันภัย
                    - generic "กรณีตรวจสอบพบว่าเกิดจากการบาดเจ็บหรือเจ็บป่วยที่ไม่ใช่สภาพที่เป็นมาก่อนการเอาประกันภัย" [ref=e379]:
                      - img "กรณีตรวจสอบพบว่าเกิดจากการบาดเจ็บหรือเจ็บป่วยที่ไม่ใช่สภาพที่เป็นมาก่อนการเอาประกันภัย" [ref=e380]
                  - generic [ref=e381] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e382]: "-"
                - generic [ref=e383]:
                  - generic [ref=e385]:
                    - generic [ref=e386]: กรณีตรวจสอบพบว่าเกิดจากการบาดเจ็บหรือเจ็บป่วยจากสภาพที่เป็นมาก่อนการเอาประกันภัย
                    - generic "กรณีตรวจสอบพบว่าเกิดจากการบาดเจ็บหรือเจ็บป่วยจากสภาพที่เป็นมาก่อนการเอาประกันภัย" [ref=e387]:
                      - img "กรณีตรวจสอบพบว่าเกิดจากการบาดเจ็บหรือเจ็บป่วยจากสภาพที่เป็นมาก่อนการเอาประกันภัย" [ref=e388]
                  - generic [ref=e389] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e390]: "-"
                - generic [ref=e393]:
                  - generic [ref=e394]: ความรับผิดตามกฏหมายต่อบุคคลภายนอก จ่ายตามจริงสูงสุด
                  - generic "ความรับผิดตามกฏหมายต่อบุคคลภายนอก จ่ายตามจริงสูงสุด" [ref=e395]:
                    - img "ความรับผิดตามกฏหมายต่อบุคคลภายนอก จ่ายตามจริงสูงสุด" [ref=e396]
                - generic [ref=e397]: 500,000 บาท
                - generic [ref=e400]:
                  - generic [ref=e401]: การเดินทางเพื่อเยี่ยมผู้ป่วยที่โรงพยาบาล จ่ายตามจริงสูงสุด
                  - generic "การเดินทางเพื่อเยี่ยมผู้ป่วยที่โรงพยาบาล จ่ายตามจริงสูงสุด" [ref=e402]:
                    - img "การเดินทางเพื่อเยี่ยมผู้ป่วยที่โรงพยาบาล จ่ายตามจริงสูงสุด" [ref=e403]
                - generic [ref=e404]: "-"
                - generic [ref=e407]:
                  - generic [ref=e408]: รางวัลพิเศษสำหรับ โฮล-อิน-วัน
                  - generic "รางวัลพิเศษสำหรับ โฮล-อิน-วัน" [ref=e409]:
                    - img "รางวัลพิเศษสำหรับ โฮล-อิน-วัน" [ref=e410]
                - generic [ref=e411]: "-"
                - generic [ref=e414]:
                  - generic [ref=e415]: ความเสียหายส่วนแรกสำหรับรถเช่า จ่ายตามจริงสูงสุด
                  - generic "ความเสียหายส่วนแรกสำหรับรถเช่า จ่ายตามจริงสูงสุด" [ref=e416]:
                    - img "ความเสียหายส่วนแรกสำหรับรถเช่า จ่ายตามจริงสูงสุด" [ref=e417]
                - generic [ref=e418]: "-"
                - generic [ref=e421]:
                  - generic [ref=e422]: ชดเชยค่าโทรศัพท์ในกรณีฉุกเฉิน จ่ายตามจริงสูงสุด
                  - generic "ชดเชยค่าโทรศัพท์ในกรณีฉุกเฉิน จ่ายตามจริงสูงสุด" [ref=e423]:
                    - img "ชดเชยค่าโทรศัพท์ในกรณีฉุกเฉิน จ่ายตามจริงสูงสุด" [ref=e424]
                - generic [ref=e425]: "-"
                - generic [ref=e428]:
                  - generic [ref=e429]: ผลประโยชน์การขยายระยะเวลาโดยอัตโนมัติ
                  - generic "ผลประโยชน์การขยายระยะเวลาโดยอัตโนมัติ" [ref=e430]:
                    - img "ผลประโยชน์การขยายระยะเวลาโดยอัตโนมัติ" [ref=e431]
                - generic [ref=e432]: 30 วัน
                - generic [ref=e435]:
                  - generic [ref=e436]: ผลประโยชน์การสูญเสียหรือความเสียหายของทรัพย์สินภายในบ้าน
                  - generic "ผลประโยชน์การสูญเสียหรือความเสียหายของทรัพย์สินภายในบ้าน" [ref=e437]:
                    - img "ผลประโยชน์การสูญเสียหรือความเสียหายของทรัพย์สินภายในบ้าน" [ref=e438]
                - generic [ref=e439]: "-"
                - generic [ref=e442]:
                  - generic [ref=e443]: การบริการให้ความช่วยเหลือในการเดินทาง
                  - generic "การบริการให้ความช่วยเหลือในการเดินทาง" [ref=e444]:
                    - img "การบริการให้ความช่วยเหลือในการเดินทาง" [ref=e445]
                - generic [ref=e446]: "-"
                - generic [ref=e449]:
                  - generic [ref=e450]: บริการการปรึกษาแพทย์ทางไกล
                  - generic "บริการการปรึกษาแพทย์ทางไกล" [ref=e451]:
                    - img "บริการการปรึกษาแพทย์ทางไกล" [ref=e452]
                - generic [ref=e453]: "-"
                - generic [ref=e456]:
                  - generic [ref=e457]: การไปเยี่ยมผู้เอาประกันภัย จ่ายตามจริงสูงสุด
                  - generic "การไปเยี่ยมผู้เอาประกันภัย จ่ายตามจริงสูงสุด" [ref=e458]:
                    - img "การไปเยี่ยมผู้เอาประกันภัย จ่ายตามจริงสูงสุด" [ref=e459]
                - generic [ref=e460]: "-"
                - generic [ref=e463]:
                  - generic [ref=e464]: การส่งผู้เยาว์เพื่อเดินทางกลับประเทศ จ่ายตามจริงสูงสุด
                  - generic "การส่งผู้เยาว์เพื่อเดินทางกลับประเทศ จ่ายตามจริงสูงสุด" [ref=e465]:
                    - img "การส่งผู้เยาว์เพื่อเดินทางกลับประเทศ จ่ายตามจริงสูงสุด" [ref=e466]
                - generic [ref=e467]: "-"
                - generic [ref=e470]:
                  - generic [ref=e471]: ผลประโยชน์ความรับผิดต่อบัตรเครดิต
                  - generic "ผลประโยชน์ความรับผิดต่อบัตรเครดิต" [ref=e472]:
                    - img "ผลประโยชน์ความรับผิดต่อบัตรเครดิต" [ref=e473]
                - generic [ref=e474]: "-"
                - generic [ref=e475]:
                  - generic [ref=e477]:
                    - generic [ref=e478]: โฮล-อิน-วัน / การสูญหายหรือ ความเสียหายของอุปกรณ์กอล์ฟ / การชดเชยค่าธรรมเนียมสนามกอล์ฟ
                    - generic "โฮล-อิน-วัน / การสูญหายหรือ ความเสียหายของอุปกรณ์กอล์ฟ / การชดเชยค่าธรรมเนียมสนามกอล์ฟ" [ref=e479]:
                      - img "โฮล-อิน-วัน / การสูญหายหรือ ความเสียหายของอุปกรณ์กอล์ฟ / การชดเชยค่าธรรมเนียมสนามกอล์ฟ" [ref=e480]
                  - generic [ref=e481] [cursor=pointer]: ดูเพิ่มเติม
                - generic [ref=e482]: "-"
                - generic [ref=e485]:
                  - generic [ref=e486]: การค้นหา การช่วยชีวิต และการกู้ภัย
                  - generic "การค้นหา การช่วยชีวิต และการกู้ภัย" [ref=e487]:
                    - img "การค้นหา การช่วยชีวิต และการกู้ภัย" [ref=e488]
                - generic [ref=e489]: "-"
                - generic [ref=e492]:
                  - generic [ref=e493]: การสูญหายของหนังสือเดินทาง จ่ายตามจริงสูงสุด
                  - generic "การสูญหายของหนังสือเดินทาง จ่ายตามจริงสูงสุด" [ref=e494]:
                    - img "การสูญหายของหนังสือเดินทาง จ่ายตามจริงสูงสุด" [ref=e495]
                - generic [ref=e496]: "-"
                - generic [ref=e499]:
                  - generic [ref=e500]: การถูกปฏิเสธการขอวีซ่า (Visa Refusal)
                  - generic "การถูกปฏิเสธการขอวีซ่า (Visa Refusal)" [ref=e501]:
                    - img "การถูกปฏิเสธการขอวีซ่า (Visa Refusal)" [ref=e502]
                - generic [ref=e503]: "-"
                - generic [ref=e506]:
                  - generic [ref=e507]: คุ้มครองอุบัติเหตุจากการเล่นกีฬาเสี่ยงภัย
                  - generic "คุ้มครองอุบัติเหตุจากการเล่นกีฬาเสี่ยงภัย" [ref=e508]:
                    - img "คุ้มครองอุบัติเหตุจากการเล่นกีฬาเสี่ยงภัย" [ref=e509]
                - generic [ref=e510]: "-"
        - generic [ref=e511]:
          - generic [ref=e512]: เงื่อนไขการรับประกัน
          - paragraph [ref=e513]:
            - paragraph [ref=e514]: เงื่อนไขการรับประกัน
            - paragraph [ref=e515]: เงื่อนไขการรับประกัน
            - paragraph [ref=e516]: เงื่อนไขการรับประกัน
        - generic [ref=e517]:
          - button "ย้อนกลับ" [ref=e518] [cursor=pointer]:
            - img [ref=e520]
            - text: ย้อนกลับ
          - button "เลือกแผนนี้" [ref=e522] [cursor=pointer]:
            - text: เลือกแผนนี้
            - img [ref=e524]
    - contentinfo [ref=e526]:
      - link "TQM Logo" [ref=e528] [cursor=pointer]:
        - /url: /
        - img "TQM Logo" [ref=e529]
      - generic [ref=e530]:
        - button "ผลิตภัณฑ์ประกันภัย" [ref=e533] [cursor=pointer]:
          - generic [ref=e535]: ผลิตภัณฑ์ประกันภัย
          - img [ref=e537]
        - button "บริการลูกค้า" [ref=e541] [cursor=pointer]:
          - generic [ref=e543]: บริการลูกค้า
          - img [ref=e545]
        - button "ติดต่อสอบถาม" [ref=e549] [cursor=pointer]:
          - generic [ref=e551]: ติดต่อสอบถาม
          - img [ref=e553]
        - button "บริษัท" [ref=e557] [cursor=pointer]:
          - generic [ref=e559]: บริษัท
          - img [ref=e561]
        - generic [ref=e563]:
          - generic [ref=e564]:
            - link "line" [ref=e566] [cursor=pointer]:
              - /url: https://lin.ee/Ds7qY7v
              - img "line" [ref=e567]
            - link "facebook" [ref=e569] [cursor=pointer]:
              - /url: https://www.facebook.com/TqmBroker
              - img "facebook" [ref=e570]
            - link "instagram" [ref=e572] [cursor=pointer]:
              - /url: https://www.instagram.com/tqminsurancebroker
              - img "instagram" [ref=e573]
            - link "tiktok" [ref=e575] [cursor=pointer]:
              - /url: http://www.tiktok.com/@tqmmorelove
              - img "tiktok" [ref=e576]
            - link "youtube" [ref=e578] [cursor=pointer]:
              - /url: https://www.youtube.com/@TQMInsuranceBrokerOfficial
              - img "youtube" [ref=e579]
            - link "x" [ref=e581] [cursor=pointer]:
              - /url: https://x.com/Tqmbeside
              - img "x" [ref=e582]
          - link "1737" [ref=e584] [cursor=pointer]:
            - /url: tel:1737
            - img [ref=e585]
            - text: "1737"
        - generic [ref=e588]:
          - link "TQM Application" [ref=e590] [cursor=pointer]:
            - /url: https://tqm.onelink.me/jwZj/fsmrwgvs
            - img "TQM Application" [ref=e591]
          - generic [ref=e592]:
            - link "TQM IOS Application" [ref=e593] [cursor=pointer]:
              - /url: https://apps.apple.com/th/app/tqm24/id1274502784
              - img "TQM IOS Application" [ref=e594]
            - link "TQM Android Application" [ref=e595] [cursor=pointer]:
              - /url: https://play.google.com/store/apps/details?id=com.tqm.tqmapp
              - img "TQM Android Application" [ref=e596]
            - link "TQM APK Download" [ref=e597] [cursor=pointer]:
              - /url: https://storage.googleapis.com/tqm-beta-static/files/APK/tqm24.apk
              - img "TQM APK Download" [ref=e598]
        - generic [ref=e599]:
          - paragraph [ref=e600]: ©Copyright 2026 TQM.co.th All Rights Reserved.
          - generic [ref=e601]:
            - paragraph [ref=e602]:
              - link "แผนผังเว็บไซต์" [ref=e603] [cursor=pointer]:
                - /url: https://devweb.tqm.co.th/sitemap
            - paragraph [ref=e604]:
              - link "ข้อกำหนดและเงื่อนไข" [ref=e605] [cursor=pointer]:
                - /url: /terms-and-conditions
            - paragraph [ref=e606]:
              - link "นโยบายข้อมูลส่วนบุคคล" [ref=e607] [cursor=pointer]:
                - /url: /tqm/privacy
    - generic [ref=e608]:
      - generic:
        - generic:
          - generic:
            - img
        - generic:
          - button "Close notification":
            - img
          - generic:
            - paragraph: สนใจแผนนี้อยู่รึเปล่า? สงสัยถามพี่หมีได้เลย
      - button "Toggle chat" [ref=e609] [cursor=pointer]:
        - img "chat-on-web" [ref=e610]
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
  - alert [ref=e611]: รายละเอียดประกันเดินทาง | TQM ทีคิวเอ็ม
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