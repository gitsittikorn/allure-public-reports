# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: main-web/pet/pet-normal-flow.spec.ts >> pet-normal-flow
- Location: tests/main-web/pet/pet-normal-flow.spec.ts:12:5

# Error details

```
TimeoutError: locator.click: Timeout 10000ms exceeded.
Call log:
  - waiting for getByTestId('buyNow717Button').first()

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
            - generic [ref=e52]: ประกันสัตว์เลี้ยง
            - generic [ref=e54] [cursor=pointer]:
              - img [ref=e55]
              - text: แก้ไข
        - generic [ref=e58]:
          - generic [ref=e59]:
            - img "ทิพยประกันภัย" [ref=e61]
            - generic [ref=e62]:
              - generic [ref=e63]: ทิพยประกันภัย
              - generic [ref=e64]: ประกันภัยสัตว์เลี้ยง
          - table [ref=e66]:
            - rowgroup [ref=e67]:
              - row "แผนประกันภัย Standard Advanced 🔥Premium (Hot) Ultimate" [ref=e68]:
                - columnheader "แผนประกันภัย" [ref=e69]:
                  - generic [ref=e70]: แผนประกันภัย
                - columnheader "Standard" [ref=e71]:
                  - generic [ref=e72]: Standard
                - columnheader "Advanced" [ref=e73]:
                  - generic [ref=e74]: Advanced
                - columnheader "🔥Premium (Hot)" [ref=e75]:
                  - generic [ref=e76]: 🔥Premium (Hot)
                - columnheader "Ultimate" [ref=e77]:
                  - generic [ref=e78]: Ultimate
            - rowgroup [ref=e79]:
              - row "เบี้ยประกันภัย ฿ 2,050 ฿ 4,800 ฿ 7,000 ฿ 14,800" [ref=e80]:
                - cell "เบี้ยประกันภัย" [ref=e81]:
                  - generic [ref=e82]: เบี้ยประกันภัย
                - cell "฿ 2,050" [ref=e83]:
                  - paragraph [ref=e85]: ฿ 2,050
                - cell "฿ 4,800" [ref=e86]:
                  - paragraph [ref=e88]: ฿ 4,800
                - cell "฿ 7,000" [ref=e89]:
                  - paragraph [ref=e91]: ฿ 7,000
                - cell "฿ 14,800" [ref=e92]:
                  - paragraph [ref=e94]: ฿ 14,800
              - row "ซื้อเลย ซื้อเลย ซื้อเลย ซื้อเลย" [ref=e95]:
                - cell [ref=e96]
                - cell "ซื้อเลย" [ref=e98]:
                  - button "ซื้อเลย" [ref=e100] [cursor=pointer]
                - cell "ซื้อเลย" [ref=e101]:
                  - button "ซื้อเลย" [ref=e103] [cursor=pointer]
                - cell "ซื้อเลย" [ref=e104]:
                  - button "ซื้อเลย" [ref=e106] [cursor=pointer]
                - cell "ซื้อเลย" [ref=e107]:
                  - button "ซื้อเลย" [ref=e109] [cursor=pointer]
              - row "ระยะความคุ้มครอง 1 ปี 1 ปี 1 ปี 1 ปี" [ref=e110]:
                - cell "ระยะความคุ้มครอง" [ref=e111]:
                  - generic [ref=e112]: ระยะความคุ้มครอง
                - cell "1 ปี" [ref=e113]:
                  - generic [ref=e114]: 1 ปี
                - cell "1 ปี" [ref=e115]:
                  - generic [ref=e116]: 1 ปี
                - cell "1 ปี" [ref=e117]:
                  - generic [ref=e118]: 1 ปี
                - cell "1 ปี" [ref=e119]:
                  - generic [ref=e120]: 1 ปี
              - row "จำนวนเงินเอาประกันภัย 5,000 บาท 10,000 บาท 10,000 บาท 20,000 บาท" [ref=e121]:
                - cell "จำนวนเงินเอาประกันภัย" [ref=e122]:
                  - generic [ref=e123]: จำนวนเงินเอาประกันภัย
                - cell "5,000 บาท" [ref=e124]:
                  - generic [ref=e125]: 5,000 บาท
                - cell "10,000 บาท" [ref=e126]:
                  - generic [ref=e127]: 10,000 บาท
                - cell "10,000 บาท" [ref=e128]:
                  - generic [ref=e129]: 10,000 บาท
                - cell "20,000 บาท" [ref=e130]:
                  - generic [ref=e131]: 20,000 บาท
              - row "ค่ารักษาพยาบาล 2,000 บาท 1 ครั้ง/ปี 1,000 บาท 5 ครั้ง/ปี 1,000 บาท 3 ครั้ง/ปี 20,000 บาท 2 ครั้ง/ปี" [ref=e132]:
                - cell "ค่ารักษาพยาบาล" [ref=e133]:
                  - generic [ref=e134]: ค่ารักษาพยาบาล
                - cell "2,000 บาท 1 ครั้ง/ปี" [ref=e135]:
                  - generic [ref=e136]: 2,000 บาท 1 ครั้ง/ปี
                - cell "1,000 บาท 5 ครั้ง/ปี" [ref=e137]:
                  - generic [ref=e138]: 1,000 บาท 5 ครั้ง/ปี
                - cell "1,000 บาท 3 ครั้ง/ปี" [ref=e139]:
                  - generic [ref=e140]: 1,000 บาท 3 ครั้ง/ปี
                - cell "20,000 บาท 2 ครั้ง/ปี" [ref=e141]:
                  - generic [ref=e142]: 20,000 บาท 2 ครั้ง/ปี
              - row "การรักษาพยาบาลเนื่องจากการบาดเจ็บจากอุบัติเหตุหรือการเจ็บป่วยของสัตว์เลี้ยงที่เอาประกันภัย การรักษาพยาบาลเนื่องจากการบาดเจ็บจากอุบัติเหตุหรือการเจ็บป่วยของสัตว์เลี้ยงที่เอาประกันภัย" [ref=e143]:
                - rowheader "การรักษาพยาบาลเนื่องจากการบาดเจ็บจากอุบัติเหตุหรือการเจ็บป่วยของสัตว์เลี้ยงที่เอาประกันภัย การรักษาพยาบาลเนื่องจากการบาดเจ็บจากอุบัติเหตุหรือการเจ็บป่วยของสัตว์เลี้ยงที่เอาประกันภัย" [ref=e144]:
                  - generic [ref=e146]:
                    - generic [ref=e147]: การรักษาพยาบาลเนื่องจากการบาดเจ็บจากอุบัติเหตุหรือการเจ็บป่วยของสัตว์เลี้ยงที่เอาประกันภัย
                    - generic "การรักษาพยาบาลเนื่องจากการบาดเจ็บจากอุบัติเหตุหรือการเจ็บป่วยของสัตว์เลี้ยงที่เอาประกันภัย" [ref=e148]:
                      - img "การรักษาพยาบาลเนื่องจากการบาดเจ็บจากอุบัติเหตุหรือการเจ็บป่วยของสัตว์เลี้ยงที่เอาประกันภัย" [ref=e149]
                - cell [ref=e150]
                - cell [ref=e152]
                - cell [ref=e154]
                - cell [ref=e156]
              - row "การรักษาพยาบาลจากการบาดเจ็บจากอุบัติเหตุ (ต่อการบาดเจ็บแต่ละครั้ง) การรักษาพยาบาลจากการบาดเจ็บจากอุบัติเหตุ (ต่อการบาดเจ็บแต่ละครั้ง) 2,000 บาท 1 ครั้ง/ปี 1,000 บาท 5 ครั้ง/ปี 1,000 บาท 3 ครั้ง/ปี 20,000 บาท 2 ครั้ง/ปี" [ref=e158]:
                - cell "การรักษาพยาบาลจากการบาดเจ็บจากอุบัติเหตุ (ต่อการบาดเจ็บแต่ละครั้ง) การรักษาพยาบาลจากการบาดเจ็บจากอุบัติเหตุ (ต่อการบาดเจ็บแต่ละครั้ง)" [ref=e159]:
                  - generic [ref=e163]:
                    - generic [ref=e164]: การรักษาพยาบาลจากการบาดเจ็บจากอุบัติเหตุ (ต่อการบาดเจ็บแต่ละครั้ง)
                    - generic "การรักษาพยาบาลจากการบาดเจ็บจากอุบัติเหตุ (ต่อการบาดเจ็บแต่ละครั้ง)" [ref=e165]:
                      - img "การรักษาพยาบาลจากการบาดเจ็บจากอุบัติเหตุ (ต่อการบาดเจ็บแต่ละครั้ง)" [ref=e166]
                - cell "2,000 บาท 1 ครั้ง/ปี" [ref=e167]:
                  - generic [ref=e168]: 2,000 บาท 1 ครั้ง/ปี
                - cell "1,000 บาท 5 ครั้ง/ปี" [ref=e169]:
                  - generic [ref=e170]: 1,000 บาท 5 ครั้ง/ปี
                - cell "1,000 บาท 3 ครั้ง/ปี" [ref=e171]:
                  - generic [ref=e172]: 1,000 บาท 3 ครั้ง/ปี
                - cell "20,000 บาท 2 ครั้ง/ปี" [ref=e173]:
                  - generic [ref=e174]: 20,000 บาท 2 ครั้ง/ปี
              - row "การรักษาพยาบาลจากการเจ็บป่วย (ต่อการเจ็บป่วยแต่ละครั้ง) การรักษาพยาบาลจากการเจ็บป่วย (ต่อการเจ็บป่วยแต่ละครั้ง) 500 บาท 3 ครั้ง/ปี 1,000 บาท 3 ครั้ง/ปี 2,500 บาท 4 ครั้ง/ปี 2,000 บาท 10 ครั้ง/ปี" [ref=e175]:
                - cell "การรักษาพยาบาลจากการเจ็บป่วย (ต่อการเจ็บป่วยแต่ละครั้ง) การรักษาพยาบาลจากการเจ็บป่วย (ต่อการเจ็บป่วยแต่ละครั้ง)" [ref=e176]:
                  - generic [ref=e180]:
                    - generic [ref=e181]: การรักษาพยาบาลจากการเจ็บป่วย (ต่อการเจ็บป่วยแต่ละครั้ง)
                    - generic "การรักษาพยาบาลจากการเจ็บป่วย (ต่อการเจ็บป่วยแต่ละครั้ง)" [ref=e182]:
                      - img "การรักษาพยาบาลจากการเจ็บป่วย (ต่อการเจ็บป่วยแต่ละครั้ง)" [ref=e183]
                - cell "500 บาท 3 ครั้ง/ปี" [ref=e184]:
                  - generic [ref=e185]: 500 บาท 3 ครั้ง/ปี
                - cell "1,000 บาท 3 ครั้ง/ปี" [ref=e186]:
                  - generic [ref=e187]: 1,000 บาท 3 ครั้ง/ปี
                - cell "2,500 บาท 4 ครั้ง/ปี" [ref=e188]:
                  - generic [ref=e189]: 2,500 บาท 4 ครั้ง/ปี
                - cell "2,000 บาท 10 ครั้ง/ปี" [ref=e190]:
                  - generic [ref=e191]: 2,000 บาท 10 ครั้ง/ปี
              - row "ความรับผิดต่อบุคคลภายนอกอันเนื่องมาจากสัตว์เลี้ยงที่เอาประกันภัย ความรับผิดต่อบุคคลภายนอกอันเนื่องมาจากสัตว์เลี้ยงที่เอาประกันภัย" [ref=e192]:
                - rowheader "ความรับผิดต่อบุคคลภายนอกอันเนื่องมาจากสัตว์เลี้ยงที่เอาประกันภัย ความรับผิดต่อบุคคลภายนอกอันเนื่องมาจากสัตว์เลี้ยงที่เอาประกันภัย" [ref=e193]:
                  - generic [ref=e195]:
                    - generic [ref=e196]: ความรับผิดต่อบุคคลภายนอกอันเนื่องมาจากสัตว์เลี้ยงที่เอาประกันภัย
                    - generic "ความรับผิดต่อบุคคลภายนอกอันเนื่องมาจากสัตว์เลี้ยงที่เอาประกันภัย" [ref=e197]:
                      - img "ความรับผิดต่อบุคคลภายนอกอันเนื่องมาจากสัตว์เลี้ยงที่เอาประกันภัย" [ref=e198]
                - cell [ref=e199]
                - cell [ref=e201]
                - cell [ref=e203]
                - cell [ref=e205]
              - row "การสูญเสียต่อชีวิต ร่างกาย การบาดเจ็บของบุคคลภายนอก (ต่อปีกรมธรรม์ประกันภัย) การสูญเสียต่อชีวิต ร่างกาย การบาดเจ็บของบุคคลภายนอก (ต่อปีกรมธรรม์ประกันภัย) ดูเพิ่มเติม 5,000 บาท 10,000 บาท ไม่คุ้มครอง 20,000 บาท" [ref=e207]:
                - cell "การสูญเสียต่อชีวิต ร่างกาย การบาดเจ็บของบุคคลภายนอก (ต่อปีกรมธรรม์ประกันภัย) การสูญเสียต่อชีวิต ร่างกาย การบาดเจ็บของบุคคลภายนอก (ต่อปีกรมธรรม์ประกันภัย) ดูเพิ่มเติม" [ref=e208]:
                  - generic [ref=e210]:
                    - generic [ref=e212]:
                      - generic [ref=e213]: การสูญเสียต่อชีวิต ร่างกาย การบาดเจ็บของบุคคลภายนอก (ต่อปีกรมธรรม์ประกันภัย)
                      - generic "การสูญเสียต่อชีวิต ร่างกาย การบาดเจ็บของบุคคลภายนอก (ต่อปีกรมธรรม์ประกันภัย)" [ref=e214]:
                        - img "การสูญเสียต่อชีวิต ร่างกาย การบาดเจ็บของบุคคลภายนอก (ต่อปีกรมธรรม์ประกันภัย)" [ref=e215]
                    - generic [ref=e216] [cursor=pointer]: ดูเพิ่มเติม
                - cell "5,000 บาท" [ref=e217]:
                  - generic [ref=e218]: 5,000 บาท
                - cell "10,000 บาท" [ref=e219]:
                  - generic [ref=e220]: 10,000 บาท
                - cell "ไม่คุ้มครอง" [ref=e221]:
                  - generic [ref=e222]: ไม่คุ้มครอง
                - cell "20,000 บาท" [ref=e223]:
                  - generic [ref=e224]: 20,000 บาท
              - row "การสูญเสีย หรือเสียหายต่อทรัพย์สินของบุคคลภายนอก (ต่อปีกรมธรรม์ประกันภัย) การสูญเสีย หรือเสียหายต่อทรัพย์สินของบุคคลภายนอก (ต่อปีกรมธรรม์ประกันภัย) ดูเพิ่มเติม 1,000 บาท 5,000 บาท ไม่คุ้มครอง 10,000 บาท" [ref=e225]:
                - cell "การสูญเสีย หรือเสียหายต่อทรัพย์สินของบุคคลภายนอก (ต่อปีกรมธรรม์ประกันภัย) การสูญเสีย หรือเสียหายต่อทรัพย์สินของบุคคลภายนอก (ต่อปีกรมธรรม์ประกันภัย) ดูเพิ่มเติม" [ref=e226]:
                  - generic [ref=e228]:
                    - generic [ref=e230]:
                      - generic [ref=e231]: การสูญเสีย หรือเสียหายต่อทรัพย์สินของบุคคลภายนอก (ต่อปีกรมธรรม์ประกันภัย)
                      - generic "การสูญเสีย หรือเสียหายต่อทรัพย์สินของบุคคลภายนอก (ต่อปีกรมธรรม์ประกันภัย)" [ref=e232]:
                        - img "การสูญเสีย หรือเสียหายต่อทรัพย์สินของบุคคลภายนอก (ต่อปีกรมธรรม์ประกันภัย)" [ref=e233]
                    - generic [ref=e234] [cursor=pointer]: ดูเพิ่มเติม
                - cell "1,000 บาท" [ref=e235]:
                  - generic [ref=e236]: 1,000 บาท
                - cell "5,000 บาท" [ref=e237]:
                  - generic [ref=e238]: 5,000 บาท
                - cell "ไม่คุ้มครอง" [ref=e239]:
                  - generic [ref=e240]: ไม่คุ้มครอง
                - cell "10,000 บาท" [ref=e241]:
                  - generic [ref=e242]: 10,000 บาท
              - row "ความคุ้มครอง เพิ่มเติม ความคุ้มครอง เพิ่มเติม" [ref=e243]:
                - rowheader "ความคุ้มครอง เพิ่มเติม ความคุ้มครอง เพิ่มเติม" [ref=e244]:
                  - generic [ref=e246]:
                    - generic [ref=e247]: ความคุ้มครอง เพิ่มเติม
                    - generic "ความคุ้มครอง เพิ่มเติม" [ref=e248]:
                      - img "ความคุ้มครอง เพิ่มเติม" [ref=e249]
                - cell [ref=e250]
                - cell [ref=e252]
                - cell [ref=e254]
                - cell [ref=e256]
              - row "ค่าใช้จ่ายในการจัดการเผาศพหรือการฝังศพให้กับสัตว์เลี้ยงที่ตายจากการบาดเจ็บหรือการเจ็บป่วย (ต่อปีกรมธรรม์ประกันภัย) ค่าใช้จ่ายในการจัดการเผาศพหรือการฝังศพให้กับสัตว์เลี้ยงที่ตายจากการบาดเจ็บหรือการเจ็บป่วย (ต่อปีกรมธรรม์ประกันภัย) ดูเพิ่มเติม 1,000 บาท 2,000 บาท ไม่คุ้มครอง 10,000 บาท" [ref=e258]:
                - cell "ค่าใช้จ่ายในการจัดการเผาศพหรือการฝังศพให้กับสัตว์เลี้ยงที่ตายจากการบาดเจ็บหรือการเจ็บป่วย (ต่อปีกรมธรรม์ประกันภัย) ค่าใช้จ่ายในการจัดการเผาศพหรือการฝังศพให้กับสัตว์เลี้ยงที่ตายจากการบาดเจ็บหรือการเจ็บป่วย (ต่อปีกรมธรรม์ประกันภัย) ดูเพิ่มเติม" [ref=e259]:
                  - generic [ref=e261]:
                    - generic [ref=e263]:
                      - generic [ref=e264]: ค่าใช้จ่ายในการจัดการเผาศพหรือการฝังศพให้กับสัตว์เลี้ยงที่ตายจากการบาดเจ็บหรือการเจ็บป่วย (ต่อปีกรมธรรม์ประกันภัย)
                      - generic "ค่าใช้จ่ายในการจัดการเผาศพหรือการฝังศพให้กับสัตว์เลี้ยงที่ตายจากการบาดเจ็บหรือการเจ็บป่วย (ต่อปีกรมธรรม์ประกันภัย)" [ref=e265]:
                        - img "ค่าใช้จ่ายในการจัดการเผาศพหรือการฝังศพให้กับสัตว์เลี้ยงที่ตายจากการบาดเจ็บหรือการเจ็บป่วย (ต่อปีกรมธรรม์ประกันภัย)" [ref=e266]
                    - generic [ref=e267] [cursor=pointer]: ดูเพิ่มเติม
                - cell "1,000 บาท" [ref=e268]:
                  - generic [ref=e269]: 1,000 บาท
                - cell "2,000 บาท" [ref=e270]:
                  - generic [ref=e271]: 2,000 บาท
                - cell "ไม่คุ้มครอง" [ref=e272]:
                  - generic [ref=e273]: ไม่คุ้มครอง
                - cell "10,000 บาท" [ref=e274]:
                  - generic [ref=e275]: 10,000 บาท
              - row "การตายเนื่องจากการบาดเจ็บจากอุบัติเหตุหรือการเจ็บป่วยของสัตว์เลี้ยงที่เอาประกันภัย (ต่อปีกรมธรรม์ประกันภัย) การตายเนื่องจากการบาดเจ็บจากอุบัติเหตุหรือการเจ็บป่วยของสัตว์เลี้ยงที่เอาประกันภัย (ต่อปีกรมธรรม์ประกันภัย) ดูเพิ่มเติม ไม่คุ้มครอง ไม่คุ้มครอง ไม่คุ้มครอง 20,000 บาท" [ref=e276]:
                - cell "การตายเนื่องจากการบาดเจ็บจากอุบัติเหตุหรือการเจ็บป่วยของสัตว์เลี้ยงที่เอาประกันภัย (ต่อปีกรมธรรม์ประกันภัย) การตายเนื่องจากการบาดเจ็บจากอุบัติเหตุหรือการเจ็บป่วยของสัตว์เลี้ยงที่เอาประกันภัย (ต่อปีกรมธรรม์ประกันภัย) ดูเพิ่มเติม" [ref=e277]:
                  - generic [ref=e279]:
                    - generic [ref=e281]:
                      - generic [ref=e282]: การตายเนื่องจากการบาดเจ็บจากอุบัติเหตุหรือการเจ็บป่วยของสัตว์เลี้ยงที่เอาประกันภัย (ต่อปีกรมธรรม์ประกันภัย)
                      - generic "การตายเนื่องจากการบาดเจ็บจากอุบัติเหตุหรือการเจ็บป่วยของสัตว์เลี้ยงที่เอาประกันภัย (ต่อปีกรมธรรม์ประกันภัย)" [ref=e283]:
                        - img "การตายเนื่องจากการบาดเจ็บจากอุบัติเหตุหรือการเจ็บป่วยของสัตว์เลี้ยงที่เอาประกันภัย (ต่อปีกรมธรรม์ประกันภัย)" [ref=e284]
                    - generic [ref=e285] [cursor=pointer]: ดูเพิ่มเติม
                - cell "ไม่คุ้มครอง" [ref=e286]:
                  - generic [ref=e287]: ไม่คุ้มครอง
                - cell "ไม่คุ้มครอง" [ref=e288]:
                  - generic [ref=e289]: ไม่คุ้มครอง
                - cell "ไม่คุ้มครอง" [ref=e290]:
                  - generic [ref=e291]: ไม่คุ้มครอง
                - cell "20,000 บาท" [ref=e292]:
                  - generic [ref=e293]: 20,000 บาท
              - row "ค่าฉีดวัคซีนป้องกันโรคในสัตว์เลี้ยงที่เอาประกันภัย (ต่อปีกรมธรรม์ประกันภัย) ค่าฉีดวัคซีนป้องกันโรคในสัตว์เลี้ยงที่เอาประกันภัย (ต่อปีกรมธรรม์ประกันภัย) ไม่คุ้มครอง 500 บาท ไม่คุ้มครอง 2,000 บาท" [ref=e294]:
                - cell "ค่าฉีดวัคซีนป้องกันโรคในสัตว์เลี้ยงที่เอาประกันภัย (ต่อปีกรมธรรม์ประกันภัย) ค่าฉีดวัคซีนป้องกันโรคในสัตว์เลี้ยงที่เอาประกันภัย (ต่อปีกรมธรรม์ประกันภัย)" [ref=e295]:
                  - generic [ref=e299]:
                    - generic [ref=e300]: ค่าฉีดวัคซีนป้องกันโรคในสัตว์เลี้ยงที่เอาประกันภัย (ต่อปีกรมธรรม์ประกันภัย)
                    - generic "ค่าฉีดวัคซีนป้องกันโรคในสัตว์เลี้ยงที่เอาประกันภัย (ต่อปีกรมธรรม์ประกันภัย)" [ref=e301]:
                      - img "ค่าฉีดวัคซีนป้องกันโรคในสัตว์เลี้ยงที่เอาประกันภัย (ต่อปีกรมธรรม์ประกันภัย)" [ref=e302]
                - cell "ไม่คุ้มครอง" [ref=e303]:
                  - generic [ref=e304]: ไม่คุ้มครอง
                - cell "500 บาท" [ref=e305]:
                  - generic [ref=e306]: 500 บาท
                - cell "ไม่คุ้มครอง" [ref=e307]:
                  - generic [ref=e308]: ไม่คุ้มครอง
                - cell "2,000 บาท" [ref=e309]:
                  - generic [ref=e310]: 2,000 บาท
              - row "ค่าใช้จ่ายในการโฆษณา การประกาศเพื่อติดตามสัตว์เลี้ยงที่สูญหาย (ต่อปีกรมธรรม์ประกันภัย) ค่าใช้จ่ายในการโฆษณา การประกาศเพื่อติดตามสัตว์เลี้ยงที่สูญหาย (ต่อปีกรมธรรม์ประกันภัย) ดูเพิ่มเติม ไม่คุ้มครอง 5,000 บาท ไม่คุ้มครอง 5,000 บาท" [ref=e311]:
                - cell "ค่าใช้จ่ายในการโฆษณา การประกาศเพื่อติดตามสัตว์เลี้ยงที่สูญหาย (ต่อปีกรมธรรม์ประกันภัย) ค่าใช้จ่ายในการโฆษณา การประกาศเพื่อติดตามสัตว์เลี้ยงที่สูญหาย (ต่อปีกรมธรรม์ประกันภัย) ดูเพิ่มเติม" [ref=e312]:
                  - generic [ref=e314]:
                    - generic [ref=e316]:
                      - generic [ref=e317]: ค่าใช้จ่ายในการโฆษณา การประกาศเพื่อติดตามสัตว์เลี้ยงที่สูญหาย (ต่อปีกรมธรรม์ประกันภัย)
                      - generic "ค่าใช้จ่ายในการโฆษณา การประกาศเพื่อติดตามสัตว์เลี้ยงที่สูญหาย (ต่อปีกรมธรรม์ประกันภัย)" [ref=e318]:
                        - img "ค่าใช้จ่ายในการโฆษณา การประกาศเพื่อติดตามสัตว์เลี้ยงที่สูญหาย (ต่อปีกรมธรรม์ประกันภัย)" [ref=e319]
                    - generic [ref=e320] [cursor=pointer]: ดูเพิ่มเติม
                - cell "ไม่คุ้มครอง" [ref=e321]:
                  - generic [ref=e322]: ไม่คุ้มครอง
                - cell "5,000 บาท" [ref=e323]:
                  - generic [ref=e324]: 5,000 บาท
                - cell "ไม่คุ้มครอง" [ref=e325]:
                  - generic [ref=e326]: ไม่คุ้มครอง
                - cell "5,000 บาท" [ref=e327]:
                  - generic [ref=e328]: 5,000 บาท
              - row "ค่าบริการรับฝากสัตว์เลี้ยงที่เอาประกันภัย กรณีผู้เอาประกันภัยเดินทางไปต่างประเทศ (ต่อปีกรมธรรม์ประกันภัย) ค่าบริการรับฝากสัตว์เลี้ยงที่เอาประกันภัย กรณีผู้เอาประกันภัยเดินทางไปต่างประเทศ (ต่อปีกรมธรรม์ประกันภัย) ดูเพิ่มเติม ไม่คุ้มครอง 500 บาท ไม่คุ้มครอง 2,000 บาท" [ref=e329]:
                - cell "ค่าบริการรับฝากสัตว์เลี้ยงที่เอาประกันภัย กรณีผู้เอาประกันภัยเดินทางไปต่างประเทศ (ต่อปีกรมธรรม์ประกันภัย) ค่าบริการรับฝากสัตว์เลี้ยงที่เอาประกันภัย กรณีผู้เอาประกันภัยเดินทางไปต่างประเทศ (ต่อปีกรมธรรม์ประกันภัย) ดูเพิ่มเติม" [ref=e330]:
                  - generic [ref=e332]:
                    - generic [ref=e334]:
                      - generic [ref=e335]: ค่าบริการรับฝากสัตว์เลี้ยงที่เอาประกันภัย กรณีผู้เอาประกันภัยเดินทางไปต่างประเทศ (ต่อปีกรมธรรม์ประกันภัย)
                      - generic "ค่าบริการรับฝากสัตว์เลี้ยงที่เอาประกันภัย กรณีผู้เอาประกันภัยเดินทางไปต่างประเทศ (ต่อปีกรมธรรม์ประกันภัย)" [ref=e336]:
                        - img "ค่าบริการรับฝากสัตว์เลี้ยงที่เอาประกันภัย กรณีผู้เอาประกันภัยเดินทางไปต่างประเทศ (ต่อปีกรมธรรม์ประกันภัย)" [ref=e337]
                    - generic [ref=e338] [cursor=pointer]: ดูเพิ่มเติม
                - cell "ไม่คุ้มครอง" [ref=e339]:
                  - generic [ref=e340]: ไม่คุ้มครอง
                - cell "500 บาท" [ref=e341]:
                  - generic [ref=e342]: 500 บาท
                - cell "ไม่คุ้มครอง" [ref=e343]:
                  - generic [ref=e344]: ไม่คุ้มครอง
                - cell "2,000 บาท" [ref=e345]:
                  - generic [ref=e346]: 2,000 บาท
              - row "สิทธิพิเศษเพิ่มเติม ภายหลังสั่งซื้อสำเร็จและลงทะเบียนรับสิทธิกับ PADI สิทธิพิเศษเพิ่มเติม ภายหลังสั่งซื้อสำเร็จและลงทะเบียนรับสิทธิกับ PADI" [ref=e347]:
                - rowheader "สิทธิพิเศษเพิ่มเติม ภายหลังสั่งซื้อสำเร็จและลงทะเบียนรับสิทธิกับ PADI สิทธิพิเศษเพิ่มเติม ภายหลังสั่งซื้อสำเร็จและลงทะเบียนรับสิทธิกับ PADI" [ref=e348]:
                  - generic [ref=e350]:
                    - generic [ref=e351]: สิทธิพิเศษเพิ่มเติม ภายหลังสั่งซื้อสำเร็จและลงทะเบียนรับสิทธิกับ PADI
                    - generic "สิทธิพิเศษเพิ่มเติม ภายหลังสั่งซื้อสำเร็จและลงทะเบียนรับสิทธิกับ PADI" [ref=e352]:
                      - img "สิทธิพิเศษเพิ่มเติม ภายหลังสั่งซื้อสำเร็จและลงทะเบียนรับสิทธิกับ PADI" [ref=e353]
                - cell [ref=e354]
                - cell [ref=e356]
                - cell [ref=e358]
                - cell [ref=e360]
              - row "PADI Set ผลิตภัณฑ์ดูแลสัตว์เลี้ยง พร้อมคูปองส่วนลดสินค้าและบริการราคาพิเศษ (เฉพาะร้านค้าที่ร่วมรายงการ) PADI Set ผลิตภัณฑ์ดูแลสัตว์เลี้ยง พร้อมคูปองส่วนลดสินค้าและบริการราคาพิเศษ (เฉพาะร้านค้าที่ร่วมรายงการ) ดูเพิ่มเติม ฿ 500 ฿ 1,000 ฿ 1,500 ฿ 2,500" [ref=e362]:
                - cell "PADI Set ผลิตภัณฑ์ดูแลสัตว์เลี้ยง พร้อมคูปองส่วนลดสินค้าและบริการราคาพิเศษ (เฉพาะร้านค้าที่ร่วมรายงการ) PADI Set ผลิตภัณฑ์ดูแลสัตว์เลี้ยง พร้อมคูปองส่วนลดสินค้าและบริการราคาพิเศษ (เฉพาะร้านค้าที่ร่วมรายงการ) ดูเพิ่มเติม" [ref=e363]:
                  - generic [ref=e365]:
                    - generic [ref=e367]:
                      - generic [ref=e368]: PADI Set ผลิตภัณฑ์ดูแลสัตว์เลี้ยง พร้อมคูปองส่วนลดสินค้าและบริการราคาพิเศษ (เฉพาะร้านค้าที่ร่วมรายงการ)
                      - generic "PADI Set ผลิตภัณฑ์ดูแลสัตว์เลี้ยง พร้อมคูปองส่วนลดสินค้าและบริการราคาพิเศษ (เฉพาะร้านค้าที่ร่วมรายงการ)" [ref=e369]:
                        - img "PADI Set ผลิตภัณฑ์ดูแลสัตว์เลี้ยง พร้อมคูปองส่วนลดสินค้าและบริการราคาพิเศษ (เฉพาะร้านค้าที่ร่วมรายงการ)" [ref=e370]
                    - generic [ref=e371] [cursor=pointer]: ดูเพิ่มเติม
                - cell "฿ 500" [ref=e372]:
                  - generic [ref=e373]: ฿ 500
                - cell "฿ 1,000" [ref=e374]:
                  - generic [ref=e375]: ฿ 1,000
                - cell "฿ 1,500" [ref=e376]:
                  - generic [ref=e377]: ฿ 1,500
                - cell "฿ 2,500" [ref=e378]:
                  - generic [ref=e379]: ฿ 2,500
              - row "รับสิทธิ์ซื้อสินค้าราคาสมาชิกในร้านค้าและโรงพยาบาลสัตว์ที่ร่วมรายการ รับสิทธิ์ซื้อสินค้าราคาสมาชิกในร้านค้าและโรงพยาบาลสัตว์ที่ร่วมรายการ ได้รับสิทธิ์ ได้รับสิทธิ์ ได้รับสิทธิ์ ได้รับสิทธิ์" [ref=e380]:
                - cell "รับสิทธิ์ซื้อสินค้าราคาสมาชิกในร้านค้าและโรงพยาบาลสัตว์ที่ร่วมรายการ รับสิทธิ์ซื้อสินค้าราคาสมาชิกในร้านค้าและโรงพยาบาลสัตว์ที่ร่วมรายการ" [ref=e381]:
                  - generic [ref=e385]:
                    - generic [ref=e386]: รับสิทธิ์ซื้อสินค้าราคาสมาชิกในร้านค้าและโรงพยาบาลสัตว์ที่ร่วมรายการ
                    - generic "รับสิทธิ์ซื้อสินค้าราคาสมาชิกในร้านค้าและโรงพยาบาลสัตว์ที่ร่วมรายการ" [ref=e387]:
                      - img "รับสิทธิ์ซื้อสินค้าราคาสมาชิกในร้านค้าและโรงพยาบาลสัตว์ที่ร่วมรายการ" [ref=e388]
                - cell "ได้รับสิทธิ์" [ref=e389]:
                  - generic [ref=e390]: ได้รับสิทธิ์
                - cell "ได้รับสิทธิ์" [ref=e391]:
                  - generic [ref=e392]: ได้รับสิทธิ์
                - cell "ได้รับสิทธิ์" [ref=e393]:
                  - generic [ref=e394]: ได้รับสิทธิ์
                - cell "ได้รับสิทธิ์" [ref=e395]:
                  - generic [ref=e396]: ได้รับสิทธิ์
              - row "บริการส่งสินค้าฟรี (เฉพาะร้านค้าที่ร่วมรายการ) บริการส่งสินค้าฟรี (เฉพาะร้านค้าที่ร่วมรายการ) ไม่มี 2 ครั้ง 4 ครั้ง 6 ครั้ง" [ref=e397]:
                - cell "บริการส่งสินค้าฟรี (เฉพาะร้านค้าที่ร่วมรายการ) บริการส่งสินค้าฟรี (เฉพาะร้านค้าที่ร่วมรายการ)" [ref=e398]:
                  - generic [ref=e402]:
                    - generic [ref=e403]: บริการส่งสินค้าฟรี (เฉพาะร้านค้าที่ร่วมรายการ)
                    - generic "บริการส่งสินค้าฟรี (เฉพาะร้านค้าที่ร่วมรายการ)" [ref=e404]:
                      - img "บริการส่งสินค้าฟรี (เฉพาะร้านค้าที่ร่วมรายการ)" [ref=e405]
                - cell "ไม่มี" [ref=e406]:
                  - generic [ref=e407]: ไม่มี
                - cell "2 ครั้ง" [ref=e408]:
                  - generic [ref=e409]: 2 ครั้ง
                - cell "4 ครั้ง" [ref=e410]:
                  - generic [ref=e411]: 4 ครั้ง
                - cell "6 ครั้ง" [ref=e412]:
                  - generic [ref=e413]: 6 ครั้ง
              - row "เบี้ยประกันภัย ฿ 2,050 ฿ 4,800 ฿ 7,000 ฿ 14,800" [ref=e414]:
                - cell "เบี้ยประกันภัย" [ref=e415]:
                  - generic [ref=e416]: เบี้ยประกันภัย
                - cell "฿ 2,050" [ref=e417]:
                  - paragraph [ref=e419]: ฿ 2,050
                - cell "฿ 4,800" [ref=e420]:
                  - paragraph [ref=e422]: ฿ 4,800
                - cell "฿ 7,000" [ref=e423]:
                  - paragraph [ref=e425]: ฿ 7,000
                - cell "฿ 14,800" [ref=e426]:
                  - paragraph [ref=e428]: ฿ 14,800
              - row "ซื้อเลย ซื้อเลย ซื้อเลย ซื้อเลย" [ref=e429]:
                - cell [ref=e430]
                - cell "ซื้อเลย" [ref=e432]:
                  - button "ซื้อเลย" [ref=e434] [cursor=pointer]
                - cell "ซื้อเลย" [ref=e435]:
                  - button "ซื้อเลย" [ref=e437] [cursor=pointer]
                - cell "ซื้อเลย" [ref=e438]:
                  - button "ซื้อเลย" [ref=e440] [cursor=pointer]
                - cell "ซื้อเลย" [ref=e441]:
                  - button "ซื้อเลย" [ref=e443] [cursor=pointer]
        - generic [ref=e444]:
          - generic [ref=e445]: เงื่อนไขการรับประกัน
          - paragraph [ref=e446]:
            - paragraph [ref=e447]:
              - text: 1.สัตว์เลี้ยงอายุ 3 เดือน - 9 ปี
              - text: 1.1 อายุ 3 เดือน - 7 ปี ไม่ต้องตรวจสุขภาพ (ต่ออายุได้ถึง 9 ปี)
              - text: 1.2 อายุ 8 - 9 ปี ต้องตรวจสุขภาพ (ยกเว้นแผน 1)
              - text: 2. มีเอกสารใบวัคซีนครบถ้วนตามที่สัตวแพทย์กำหนดและนัดหมาย หากไม่มีเอกสารวัคซีนต้องทำการตรวจสุขภาพ
              - text: 3. สัตว์เลี้ยงต้องไม่มีการผ่าตัดจากการเจ็บป่วยมาก่อนการรับประกันภัย
              - text: 4.สัตว์เลี้ยงต้องมีสุขภาพสมบูรณ์ ไม่มีอาการบาดเจ็บ พิการ หรือเจ็บป่วย
              - text: 5.สัตว์เลี้ยงต้องอยู่ในประเทศไทยเท่านั้น
              - text: 6.กรมธรรม์สูงสุด 1 ฉบับ / สัตว์เลี้ยง 1 ตัว
              - text: 7.รับประกันภัยเฉพาะสัตว์เลี้ยงที่มีเจ้าของ ไม่รับสัตว์เลี้ยงเพื่อการค้า
        - button "ย้อนกลับ" [ref=e448] [cursor=pointer]:
          - img [ref=e450]
          - text: ย้อนกลับ
    - contentinfo [ref=e452]:
      - link "TQM Logo" [ref=e454] [cursor=pointer]:
        - /url: /
        - img "TQM Logo" [ref=e455]
      - generic [ref=e456]:
        - button "ผลิตภัณฑ์ประกันภัย" [ref=e459] [cursor=pointer]:
          - generic [ref=e461]: ผลิตภัณฑ์ประกันภัย
          - img [ref=e463]
        - button "บริการลูกค้า" [ref=e467] [cursor=pointer]:
          - generic [ref=e469]: บริการลูกค้า
          - img [ref=e471]
        - button "ติดต่อสอบถาม" [ref=e475] [cursor=pointer]:
          - generic [ref=e477]: ติดต่อสอบถาม
          - img [ref=e479]
        - button "บริษัท" [ref=e483] [cursor=pointer]:
          - generic [ref=e485]: บริษัท
          - img [ref=e487]
        - generic [ref=e489]:
          - generic [ref=e490]:
            - link "line" [ref=e492] [cursor=pointer]:
              - /url: https://lin.ee/Ds7qY7v
              - img "line" [ref=e493]
            - link "facebook" [ref=e495] [cursor=pointer]:
              - /url: https://www.facebook.com/TqmBroker
              - img "facebook" [ref=e496]
            - link "instagram" [ref=e498] [cursor=pointer]:
              - /url: https://www.instagram.com/tqminsurancebroker
              - img "instagram" [ref=e499]
            - link "tiktok" [ref=e501] [cursor=pointer]:
              - /url: http://www.tiktok.com/@tqmmorelove
              - img "tiktok" [ref=e502]
            - link "youtube" [ref=e504] [cursor=pointer]:
              - /url: https://www.youtube.com/@TQMInsuranceBrokerOfficial
              - img "youtube" [ref=e505]
            - link "x" [ref=e507] [cursor=pointer]:
              - /url: https://x.com/Tqmbeside
              - img "x" [ref=e508]
          - link "1737" [ref=e510] [cursor=pointer]:
            - /url: tel:1737
            - img [ref=e511]
            - text: "1737"
        - generic [ref=e514]:
          - link "TQM Application" [ref=e516] [cursor=pointer]:
            - /url: https://tqm.onelink.me/jwZj/fsmrwgvs
            - img "TQM Application" [ref=e517]
          - generic [ref=e518]:
            - link "TQM IOS Application" [ref=e519] [cursor=pointer]:
              - /url: https://apps.apple.com/th/app/tqm24/id1274502784
              - img "TQM IOS Application" [ref=e520]
            - link "TQM Android Application" [ref=e521] [cursor=pointer]:
              - /url: https://play.google.com/store/apps/details?id=com.tqm.tqmapp
              - img "TQM Android Application" [ref=e522]
            - link "TQM APK Download" [ref=e523] [cursor=pointer]:
              - /url: https://storage.googleapis.com/tqm-beta-static/files/APK/tqm24.apk
              - img "TQM APK Download" [ref=e524]
        - generic [ref=e525]:
          - paragraph [ref=e526]: ©Copyright 2026 TQM.co.th All Rights Reserved.
          - generic [ref=e527]:
            - paragraph [ref=e528]:
              - link "แผนผังเว็บไซต์" [ref=e529] [cursor=pointer]:
                - /url: https://devweb.tqm.co.th/sitemap
            - paragraph [ref=e530]:
              - link "ข้อกำหนดและเงื่อนไข" [ref=e531] [cursor=pointer]:
                - /url: /terms-and-conditions
            - paragraph [ref=e532]:
              - link "นโยบายข้อมูลส่วนบุคคล" [ref=e533] [cursor=pointer]:
                - /url: /tqm/privacy
    - generic [ref=e534]:
      - generic:
        - generic:
          - generic:
            - img
        - generic:
          - button "Close notification":
            - img
          - generic:
            - paragraph: พี่หมีช่วยเปรียบเทียบแผนที่เหมาะสมที่สุดดีไหมครับ
      - button "Toggle chat" [ref=e535] [cursor=pointer]:
        - img "chat-on-web" [ref=e536]
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
  - alert [ref=e537]: TQM ทีคิวเอ็ม
```

# Test source

```ts
  1  | import { Page, expect } from "@playwright/test";
  2  | import { petProductPlanDetailLocator } from "../../../../locator/nmw/pet/pet-plan-product-detail";
  3  | import { PetProductPlanDetailType } from "../../../../types/pet.type";
  4  | import CommonTQM from "../../../../utils/common-tqm";
  5  | 
  6  | export default class PetProductPlanDetailPage {
  7  |   constructor(public page: Page) {}
  8  | 
  9  |   async getProductData(petProductPlanDetail: PetProductPlanDetailType) {
  10 |     await expect(
  11 |       this.page.getByTestId(petProductPlanDetailLocator.PET_COMPANY_LOGO_ID)
  12 |     ).toBeVisible();
  13 | 
  14 |     await expect(
  15 |       this.page.getByTestId(petProductPlanDetailLocator.PRODUCT_NAME_ID)
  16 |     ).toBeVisible();
  17 | 
  18 |     await expect(
  19 |       this.page.getByTestId(petProductPlanDetailLocator.PRODUCT_NAME_ID)
  20 |     ).toHaveText(petProductPlanDetail.productName);
  21 |   }
  22 | 
  23 |   async getInsurePrice(petProductPlanDetail: PetProductPlanDetailType) {
  24 |     const commonTQM = new CommonTQM(this.page);
  25 |     await commonTQM.initDevice();
  26 | 
  27 |     await expect(
  28 |       this.page
  29 |         .getByTestId(petProductPlanDetailLocator.PET_INSURE_PRICE_ID)
  30 |         .first()
  31 |     ).toBeVisible();
  32 | 
  33 |     const insurePrice = await CommonTQM.getInsurePrice(
  34 |       this.page,
  35 |       petProductPlanDetailLocator.PET_INSURE_PRICE_ID
  36 |     );
  37 |     expect(insurePrice).toEqual(petProductPlanDetail.insurePrice);
  38 |   }
  39 | 
  40 |   async getInsureName(petProductPlanDetail: PetProductPlanDetailType) {
  41 |     await expect(
  42 |       this.page.getByTestId(
  43 |         petProductPlanDetailLocator.PET_COMPANY_NAME_TEXT_ID
  44 |       )
  45 |     ).toBeVisible();
  46 | 
  47 |     const companyNameText = await this.page
  48 |       .getByTestId(petProductPlanDetailLocator.PET_COMPANY_NAME_TEXT_ID)
  49 |       .textContent();
  50 |     expect(companyNameText).toEqual(petProductPlanDetail.companyNameText);
  51 |     await this.page
  52 |       .getByTestId(petProductPlanDetailLocator.PET_BUY_NOW_717_BUTTON_ID)
  53 |       .first()
> 54 |       .click();
     |        ^ TimeoutError: locator.click: Timeout 10000ms exceeded.
  55 |   }
  56 | }
  57 | 
```