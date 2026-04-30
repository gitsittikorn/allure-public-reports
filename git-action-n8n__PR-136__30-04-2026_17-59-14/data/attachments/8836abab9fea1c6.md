# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: main-web/health/health-normal-flow.spec.ts >> health-normal-flow-with-tax-deduction
- Location: tests/main-web/health/health-normal-flow.spec.ts:8:5

# Error details

```
Error: expect(locator).toBeVisible() failed

Locator: getByTestId('acceptCookieButton')
Expected: visible
Timeout: 18000ms
Error: element(s) not found

Call log:
  - Expect "toBeVisible" with timeout 18000ms
  - waiting for getByTestId('acceptCookieButton')

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
      - article [ref=e18]:
        - generic [ref=e19]:
          - generic [ref=e20]:
            - heading "ประกันสุขภาพ คุ้มครองค่ารักษาพยาบาล IPD OPD" [level=1] [ref=e21]
            - paragraph [ref=e23]: ทำประกันสุขภาพที่ไหนดี? ประกันสุขภาพกับ TQM ให้คุณเลือกแผนที่เหมาะสมในราคาที่เข้าถึงได้ หมดกังวลเรื่องค่าใช้จ่ายยามเจ็บป่วย เช่น ค่าห้อง ค่ายา ค่ารักษาพยาบาล ค่าบริการทางการแพทย์ ด้วยการซื้อประกันสุขภาพที่มอบความคุ้มครองครอบคลุม โดยที่คุณไม่ต้องสำรองจ่าย และยังสามารถลดหย่อนภาษีได้ ช่วยให้คุณดูแลสุขภาพและการเงินได้อย่างมีประสิทธิภาพ
          - generic [ref=e24]:
            - list [ref=e26]:
              - listitem [ref=e27]:
                - img [ref=e29] [cursor=pointer]
              - listitem [ref=e30]:
                - img [ref=e32] [cursor=pointer]
              - listitem [ref=e33]:
                - img [ref=e35] [cursor=pointer]
              - listitem [ref=e36]:
                - img [ref=e38] [cursor=pointer]
              - listitem [ref=e39]:
                - generic [ref=e40]:
                  - link "automate health flow1 title":
                    - /url: /health-insurance/packages/%E0%B9%82%E0%B8%9B%E0%B8%A3%E0%B9%82%E0%B8%A1%E0%B8%8A%E0%B8%B1%E0%B8%99%E0%B9%81%E0%B8%99%E0%B8%B0%E0%B8%99%E0%B8%B3_automate%20health%20flow1
                    - img "automate health flow1 title" [ref=e41] [cursor=pointer]
              - listitem [ref=e42]:
                - img [ref=e44] [cursor=pointer]
              - listitem [ref=e45]:
                - img [ref=e47] [cursor=pointer]
            - list [ref=e48]:
              - listitem [ref=e49]:
                - button "paginate-dots" [ref=e50] [cursor=pointer]
              - listitem [ref=e51]:
                - button "paginate-dots" [ref=e52] [cursor=pointer]
              - listitem [ref=e53]:
                - button "paginate-dots" [ref=e54] [cursor=pointer]
      - article [ref=e55]:
        - heading "เช็คราคาแผนประกันสุขภาพตรงใจ" [level=2] [ref=e56]
        - article [ref=e57]:
          - paragraph [ref=e59]: กรอกข้อมูลเพื่อค้นหาแผนประกัน
          - generic [ref=e60]:
            - paragraph [ref=e61]: ข้อมูลสุขภาพ
            - generic [ref=e62]:
              - generic [ref=e65]:
                - img "สุขภาพ" [ref=e66]
                - generic [ref=e67]: สุขภาพ
              - generic [ref=e70]:
                - img "มะเร็ง" [ref=e71]
                - generic [ref=e72]: มะเร็ง
              - generic [ref=e75]:
                - img "ลดหย่อนภาษี" [ref=e76]
                - generic [ref=e77]: ลดหย่อนภาษี
            - generic [ref=e78]:
              - generic [ref=e80]:
                - paragraph [ref=e81]: เพศ *
                - generic [ref=e83]:
                  - combobox [ref=e84] [cursor=pointer]:
                    - generic [ref=e85]: เพศ
                  - textbox
                  - img
                  - group
              - generic [ref=e86]:
                - paragraph [ref=e87]: วัน/เดือน/ปีเกิด *
                - generic [ref=e93]:
                  - textbox "Choose date" [ref=e94]:
                    - /placeholder: DD/MM/YYYY
                  - button [ref=e95] [cursor=pointer]:
                    - img [ref=e96]
                  - group
          - generic [ref=e98]:
            - button "ให้เจ้าหน้าที่ติดต่อกลับ" [ref=e99] [cursor=pointer]
            - button "ค้นหาแผนประกัน" [disabled] [ref=e100]:
              - img [ref=e102]
              - text: ค้นหาแผนประกัน
        - img "TQM Bear" [ref=e105]
      - article [ref=e106]:
        - heading "โปรโมชันประกันสุขภาพ แนะนำโดย TQM" [level=2] [ref=e108]:
          - img [ref=e109]
          - text: โปรโมชันประกันสุขภาพ แนะนำโดย TQM
        - generic [ref=e111]:
          - tablist "promotion_tabs" [ref=e116]:
            - tab "โปรโมชันทั้งหมด" [selected] [ref=e117] [cursor=pointer]
            - tab "สุขภาพ" [ref=e118] [cursor=pointer]
            - tab "มะเร็ง" [ref=e119] [cursor=pointer]
            - tab "ลดหย่อนภาษี" [ref=e120] [cursor=pointer]
          - tabpanel "โปรโมชันทั้งหมด" [ref=e121]:
            - generic [ref=e124]:
              - list [ref=e125]:
                - listitem [ref=e126]:
                  - link "Health flow2O สุขภาพ, มะเร็ง, ลดหย่อนภาษี Health flow2O Health flow2O" [ref=e129] [cursor=pointer]:
                    - /url: /health-insurance/packages/%E0%B9%82%E0%B8%9B%E0%B8%A3%E0%B9%82%E0%B8%A1%E0%B8%8A%E0%B8%B1%E0%B8%99%E0%B8%9E%E0%B8%B4%E0%B9%80%E0%B8%A8%E0%B8%A9_Health2O
                    - generic [ref=e130]:
                      - generic [ref=e131]:
                        - img "Health flow2O" [ref=e132]
                        - generic [ref=e133]: สุขภาพ, มะเร็ง, ลดหย่อนภาษี
                      - generic [ref=e134]:
                        - paragraph [ref=e135]: Health flow2O
                        - paragraph [ref=e136]: Health flow2O
                - listitem [ref=e137]:
                  - link [ref=e140] [cursor=pointer]:
                    - /url: /health-insurance/packages/%E0%B9%82%E0%B8%9B%E0%B8%A3%E0%B9%82%E0%B8%A1%E0%B8%8A%E0%B8%B1%E0%B8%99%E0%B8%9E%E0%B8%B4%E0%B9%80%E0%B8%A8%E0%B8%A9_Health3O
                    - generic [ref=e141]:
                      - generic [ref=e142]:
                        - img [ref=e143]
                        - generic [ref=e144]: สุขภาพ
                      - generic [ref=e145]:
                        - paragraph [ref=e146]: Health flow3O
                        - paragraph [ref=e147]: Health flow3O
                - listitem [ref=e148]:
                  - link [ref=e151] [cursor=pointer]:
                    - /url: /health-insurance/packages/%E0%B9%82%E0%B8%9B%E0%B8%A3%E0%B9%82%E0%B8%A1%E0%B8%8A%E0%B8%B1%E0%B8%99%E0%B8%9E%E0%B8%B4%E0%B9%80%E0%B8%A8%E0%B8%A9_Health4O
                    - generic [ref=e152]:
                      - generic [ref=e153]:
                        - img [ref=e154]
                        - generic [ref=e155]: สุขภาพ
                      - generic [ref=e156]:
                        - paragraph [ref=e157]: Health flow4O
                        - paragraph [ref=e158]: Health flow4O
                - listitem [ref=e159]:
                  - link [ref=e162] [cursor=pointer]:
                    - /url: /health-insurance/packages/%E0%B9%82%E0%B8%9B%E0%B8%A3%E0%B9%82%E0%B8%A1%E0%B8%8A%E0%B8%B1%E0%B8%99%E0%B8%9E%E0%B8%B4%E0%B9%80%E0%B8%A8%E0%B8%A9_automate%20health%20flow1
                    - generic [ref=e163]:
                      - generic [ref=e164]:
                        - img [ref=e165]
                        - generic [ref=e166]: ลดหย่อนภาษี, สุขภาพ, มะเร็ง
                      - generic [ref=e167]:
                        - paragraph [ref=e168]: automate health flow1 title
                        - paragraph [ref=e169]: automate health flow1
                - listitem [ref=e170]:
                  - link [ref=e173] [cursor=pointer]:
                    - /url: /health-insurance/packages/%E0%B9%82%E0%B8%9B%E0%B8%A3%E0%B9%82%E0%B8%A1%E0%B8%8A%E0%B8%B1%E0%B8%99%E0%B8%9E%E0%B8%B4%E0%B9%80%E0%B8%A8%E0%B8%A9_%E0%B8%9B%E0%B8%A3%E0%B8%B0%E0%B8%81%E0%B8%B1%E0%B8%99%E0%B8%AA%E0%B8%B8%E0%B8%82%E0%B8%A0%E0%B8%B2%E0%B8%9E%20Health%20Top%20Up
                    - generic [ref=e174]:
                      - generic [ref=e175]:
                        - img [ref=e176]
                        - generic [ref=e177]: มะเร็ง, สุขภาพ, ลดหย่อนภาษี
                      - generic [ref=e178]:
                        - paragraph [ref=e179]: ประกันสุขภาพ Health Top Up (ห้ามแก้ ทดสอบ Health Flow 4)
                        - paragraph [ref=e180]: (ห้ามแก้ ทดสอบ Health Flow 4)
                - listitem [ref=e181]:
                  - link [ref=e184] [cursor=pointer]:
                    - /url: /health-insurance/packages/%E0%B9%82%E0%B8%9B%E0%B8%A3%E0%B9%82%E0%B8%A1%E0%B8%8A%E0%B8%B1%E0%B8%99%E0%B8%9E%E0%B8%B4%E0%B9%80%E0%B8%A8%E0%B8%A9_healthpondflow2
                    - generic [ref=e185]:
                      - generic [ref=e186]:
                        - img [ref=e187]
                        - generic [ref=e188]: สุขภาพ, มะเร็ง, ลดหย่อนภาษี,
                      - generic [ref=e189]:
                        - paragraph [ref=e190]: health pond flow2
                        - paragraph [ref=e191]: health pond flow2
                - listitem [ref=e192]:
                  - link [ref=e195] [cursor=pointer]:
                    - /url: /health-insurance/packages/%E0%B9%82%E0%B8%9B%E0%B8%A3%E0%B9%82%E0%B8%A1%E0%B8%8A%E0%B8%B1%E0%B8%99%E0%B8%9E%E0%B8%B4%E0%B9%80%E0%B8%A8%E0%B8%A9_automate%20health%20flow2
                    - generic [ref=e196]:
                      - generic [ref=e197]:
                        - img [ref=e198]
                        - generic [ref=e199]: ลดหย่อนภาษี, มะเร็ง, สุขภาพ
                      - generic [ref=e200]:
                        - paragraph [ref=e201]: automate health flow2
                        - paragraph [ref=e202]: automate health flow2
                - listitem [ref=e203]:
                  - link [ref=e206] [cursor=pointer]:
                    - /url: /health-insurance/packages/%E0%B9%82%E0%B8%9B%E0%B8%A3%E0%B9%82%E0%B8%A1%E0%B8%8A%E0%B8%B1%E0%B8%99%E0%B8%9E%E0%B8%B4%E0%B9%80%E0%B8%A8%E0%B8%A9_automate%20health%20flow3
                    - generic [ref=e207]:
                      - generic [ref=e208]:
                        - img [ref=e209]
                        - generic [ref=e210]: สุขภาพ, มะเร็ง, , ลดหย่อนภาษี
                      - generic [ref=e211]:
                        - paragraph [ref=e212]: automate health flow3
                        - paragraph [ref=e213]: automate health flow3
                - listitem [ref=e214]:
                  - link [ref=e217] [cursor=pointer]:
                    - /url: /health-insurance/packages/%E0%B9%82%E0%B8%9B%E0%B8%A3%E0%B9%82%E0%B8%A1%E0%B8%8A%E0%B8%B1%E0%B8%99%E0%B8%9E%E0%B8%B4%E0%B9%80%E0%B8%A8%E0%B8%A9_automate%20health%20flow4
                    - generic [ref=e218]:
                      - generic [ref=e219]:
                        - img [ref=e220]
                        - generic [ref=e221]: มะเร็ง, สุขภาพ, ลดหย่อนภาษี
                      - generic [ref=e222]:
                        - paragraph [ref=e223]: automate health flow4
                        - paragraph [ref=e224]: automate health flow4
                - listitem [ref=e225]:
                  - link [ref=e228] [cursor=pointer]:
                    - /url: /health-insurance/packages/%E0%B9%82%E0%B8%9B%E0%B8%A3%E0%B9%82%E0%B8%A1%E0%B8%8A%E0%B8%B1%E0%B8%99%E0%B8%9E%E0%B8%B4%E0%B9%80%E0%B8%A8%E0%B8%A9_Health%20flow3
                    - generic [ref=e229]:
                      - generic [ref=e230]:
                        - img [ref=e231]
                        - generic [ref=e232]: สุขภาพ, ลดหย่อนภาษี, มะเร็ง
                      - generic [ref=e233]:
                        - paragraph [ref=e234]: Health flow3
                        - paragraph [ref=e235]: Health flow3
              - list [ref=e236]:
                - listitem [ref=e237]:
                  - button "paginate-dots" [ref=e238] [cursor=pointer]
                - listitem [ref=e239]:
                  - button "paginate-dots" [ref=e240] [cursor=pointer]
                - listitem [ref=e241]:
                  - button "paginate-dots" [ref=e242] [cursor=pointer]
                - listitem [ref=e243]:
                  - button "paginate-dots" [ref=e244] [cursor=pointer]
                - listitem [ref=e245]:
                  - button "paginate-dots" [ref=e246] [cursor=pointer]
                - listitem [ref=e247]:
                  - button "paginate-dots" [ref=e248] [cursor=pointer]
                - listitem [ref=e249]:
                  - button "paginate-dots" [ref=e250] [cursor=pointer]
                - listitem [ref=e251]:
                  - button "paginate-dots" [ref=e252] [cursor=pointer]
                - listitem [ref=e253]:
                  - button "paginate-dots" [ref=e254] [cursor=pointer]
                - listitem [ref=e255]:
                  - button "paginate-dots" [ref=e256] [cursor=pointer]
        - button "ดูโปรโมชันประกันสุขภาพทั้งหมด" [ref=e258] [cursor=pointer]
      - article [ref=e260]:
        - heading "เลือกแผนประกันสุขภาพตามไลฟ์สไตล์" [level=2] [ref=e261]:
          - generic [ref=e262]: เลือกแผนประกันสุขภาพตามไลฟ์สไตล์
        - generic [ref=e263]:
          - generic [ref=e264]:
            - heading "pond ทั้งหมด" [level=3] [ref=e265]
            - paragraph
            - generic [ref=e266]:
              - link "pond ทั้งหมด":
                - /url: /health-insurance/collections/%E0%B9%80%E0%B8%A5%E0%B8%B7%E0%B8%AD%E0%B8%81%E0%B8%95%E0%B8%B2%E0%B8%A1%E0%B8%AA%E0%B9%84%E0%B8%95%E0%B8%A5%E0%B9%8C_pond
                - img "pond ทั้งหมด" [ref=e267] [cursor=pointer]
          - generic [ref=e268]:
            - heading "เอาใจคนห่วง OPD" [level=3] [ref=e269]
            - paragraph [ref=e270]: ป่วยเบาๆ แต่ป่วยบ่อยก็อุ่นใจ เพราะมีความคุ้มครอง OPD
            - generic [ref=e271]:
              - link "เอาใจคนห่วง OPD":
                - /url: /health-insurance/collections/%E0%B9%80%E0%B8%A5%E0%B8%B7%E0%B8%AD%E0%B8%81%E0%B8%95%E0%B8%B2%E0%B8%A1%E0%B8%AA%E0%B9%84%E0%B8%95%E0%B8%A5%E0%B9%8C_%E0%B9%80%E0%B8%AD%E0%B8%B2%E0%B9%83%E0%B8%88%E0%B8%84%E0%B8%99%E0%B8%AB%E0%B9%88%E0%B8%A7%E0%B8%87%20OPD
                - img "เอาใจคนห่วง OPD" [ref=e272] [cursor=pointer]
          - generic [ref=e273]:
            - heading "HealthSet7" [level=3] [ref=e274]
            - paragraph
            - generic [ref=e275]:
              - link "HealthSet7":
                - /url: /health-insurance/collections/%E0%B9%80%E0%B8%A5%E0%B8%B7%E0%B8%AD%E0%B8%81%E0%B8%95%E0%B8%B2%E0%B8%A1%E0%B8%AA%E0%B9%84%E0%B8%95%E0%B8%A5%E0%B9%8C_HealthSet7
                - img "HealthSet7" [ref=e276] [cursor=pointer]
          - generic [ref=e277]:
            - heading "เอาใจคนห่วง IPD" [level=3] [ref=e278]
            - paragraph [ref=e279]: หมดห่วงเรื่องค่ารักษา เมื่อต้องนอนโรงพยาบาล
            - generic [ref=e280]:
              - link "เอาใจคนห่วง IPD":
                - /url: /health-insurance/collections/%E0%B9%80%E0%B8%A5%E0%B8%B7%E0%B8%AD%E0%B8%81%E0%B8%95%E0%B8%B2%E0%B8%A1%E0%B8%AA%E0%B9%84%E0%B8%95%E0%B8%A5%E0%B9%8C_%E0%B9%80%E0%B8%AD%E0%B8%B2%E0%B9%83%E0%B8%88%E0%B8%84%E0%B8%99%E0%B8%AB%E0%B9%88%E0%B8%A7%E0%B8%87%20IPD
                - img "เอาใจคนห่วง IPD" [ref=e281] [cursor=pointer]
          - generic [ref=e282]:
            - heading "Health 8" [level=3] [ref=e283]
            - paragraph
            - generic [ref=e284]:
              - link "Health 8":
                - /url: /health-insurance/collections/%E0%B9%80%E0%B8%A5%E0%B8%B7%E0%B8%AD%E0%B8%81%E0%B8%95%E0%B8%B2%E0%B8%A1%E0%B8%AA%E0%B9%84%E0%B8%95%E0%B8%A5%E0%B9%8C_Health8
                - img "Health 8" [ref=e285] [cursor=pointer]
          - generic [ref=e286]:
            - heading "Test" [level=3] [ref=e287]
            - paragraph
            - generic [ref=e288]:
              - link "Test":
                - /url: /health-insurance/collections/%E0%B9%80%E0%B8%A5%E0%B8%B7%E0%B8%AD%E0%B8%81%E0%B8%95%E0%B8%B2%E0%B8%A1%E0%B8%AA%E0%B9%84%E0%B8%95%E0%B8%A5%E0%B9%8C_Test
                - img "Test" [ref=e289] [cursor=pointer]
      - article [ref=e290]:
        - generic [ref=e291]:
          - heading "ประกันสุขภาพ คืออะไร" [level=2] [ref=e292]
          - paragraph [ref=e294]: ประกันสุขภาพ คือเครื่องมือวางแผนการเงินที่ช่วยแบ่งเบาค่าใช้จ่ายด้านการรักษาพยาบาล ทั้งในกรณีผู้ป่วยใน (IPD) และผู้ป่วยนอก (OPD) โดยเฉพาะในช่วงเวลาที่คุณต้องเผชิญกับโรคภัยต่าง ๆ เช่น หัวใจ หลอดเลือดสมอง ซึ่งอาจต้องใช้เงินจำนวนมากในการรักษา
        - heading "ทำไมประกันสุขภาพจึงสำคัญ" [level=2] [ref=e295]
        - generic [ref=e296]:
          - generic [ref=e297]:
            - img "deceased" [ref=e298]
            - heading "โรคใหม่เกิดขึ้นเสมอ" [level=3] [ref=e299]
            - paragraph [ref=e300]: โรคติดต่อและโรคไม่ติดต่อในยุคนี้เกิดขึ้นได้ตลอดเวลา เช่น COVID-19 หรือโรคเรื้อรังใหม่ ๆ
          - generic [ref=e301]:
            - img "environment" [ref=e302]
            - heading "สิ่งแวดล้อมแย่ลง" [level=3] [ref=e303]
            - paragraph [ref=e304]: ฝุ่น PM2.5, มลพิษ, อาหารแปรรูป ล้วนเพิ่มความเสี่ยงเจ็บป่วย
          - generic [ref=e305]:
            - img "welfare" [ref=e306]
            - heading "สวัสดิการไม่เพียงพอ" [level=3] [ref=e307]
            - paragraph [ref=e308]: สวัสดิการบริษัทหรือรัฐอาจครอบคลุมไม่ครบ โดยเฉพาะหากต้องเข้ารักษาที่โรงพยาบาลเอกชน
          - generic [ref=e309]:
            - img "prices" [ref=e310]
            - heading "จ่ายน้อย คุ้มครองสูง" [level=3] [ref=e311]
            - paragraph [ref=e312]: ประกันสุขภาพบางแบบเหมาจ่าย มีวงเงินคุ้มครองสูง ครอบคลุมค่ารักษาพยาบาลเกือบทุกอย่าง
      - article [ref=e313]:
        - generic [ref=e314]:
          - heading "ประกันสุขภาพคุ้มครองอะไรบ้าง?" [level=2] [ref=e315]
          - paragraph [ref=e316]: แผนประกันสุขภาพในปัจจุบันมีหลายแบบ เพื่อรองรับความต้องการที่แตกต่างกัน โดยสามารถเลือกให้เหมาะกับช่วงวัยและไลฟ์สไตล์ของคุณ
        - generic [ref=e318]:
          - list [ref=e319]:
            - listitem [ref=e320]:
              - generic [ref=e321]:
                - img [ref=e323]
                - heading "ประกันสุขภาพผู้ป่วยใน (IPD)" [level=3] [ref=e325]
                - paragraph [ref=e326]: คุ้มครองเมื่อคุณต้องนอนพักรักษาตัวในโรงพยาบาล เช่น ค่าห้อง ค่าบริการโรงพยาบาล ค่ารักษาพยาบาล ค่าผ่าตัด ค่ายา ค่าตรวจทางห้องแล็บ
            - listitem [ref=e327]:
              - generic [ref=e328]:
                - img [ref=e330]
                - heading [level=3] [ref=e332]: ประกันสุขภาพผู้ป่วยนอก (OPD)
                - paragraph [ref=e333]: เหมาะสำหรับคนที่ต้องไปหาหมอบ่อย แต่ไม่ต้องนอนโรงพยาบาล เช่น ค่าปรึกษาแพทย์ทั่วไป ค่าตรวจวินิจฉัยเบื้องต้น ค่ายา หรือค่าบริการทางแพทย์ทั่วไป
            - listitem [ref=e334]:
              - generic [ref=e335]:
                - img [ref=e337]
                - heading [level=3] [ref=e339]: ประกันสุขภาพเหมาจ่าย
                - paragraph [ref=e340]: เป็นประกันสุขภาพที่ให้ความคุ้มครองแบบไม่จำกัดประเภทค่าใช้จ่าย แต่จะกำหนดเป็นวงเงินต่อปี เช่น ค่ารักษาทุกประเภทในวงเงินเดียว เหมาะกับผู้ที่ต้องการความยืดหยุ่นและไม่อยากกังวลเรื่องข้อจำกัด
            - listitem [ref=e341]:
              - generic [ref=e342]:
                - img [ref=e344]
                - heading [level=3] [ref=e346]: ประกันสุขภาพโรคร้ายแรง
                - paragraph [ref=e347]: จ่ายเงินก้อนหากตรวจพบว่าเป็นโรคร้ายแรง เช่น โรคมะเร็ง โรคหัวใจ โรคหลอดเลือดสมอง ฯลฯ
            - listitem [ref=e348]:
              - generic [ref=e349]:
                - img [ref=e351]
                - heading [level=3] [ref=e353]: ประกันสุขภาพเด็ก
                - paragraph [ref=e354]: คุ้มครองค่าใช้จ่ายเกี่ยวกับการรักษาเด็ก เช่น ค่าวัคซีน ค่ารักษาโรคทั่วไป โรคเฉพาะทางในวัยเด็ก
            - listitem [ref=e355]:
              - generic [ref=e356]:
                - img [ref=e358]
                - heading [level=3] [ref=e360]: ประกันสุขภาพผู้สูงอายุ
                - paragraph [ref=e361]: คุ้มครองผู้ที่มีอายุ 50 ปีขึ้นไป หรือวัยเกษียณ เช่น ค่ารักษาโรคเรื้อรัง ค่ารักษาทั่วไปในโรงพยาบาล
          - list [ref=e362]:
            - listitem [ref=e363]:
              - button "paginate-dots" [ref=e364] [cursor=pointer]
            - listitem [ref=e365]:
              - button "paginate-dots" [ref=e366] [cursor=pointer]
            - listitem [ref=e367]:
              - button "paginate-dots" [ref=e368] [cursor=pointer]
            - listitem [ref=e369]:
              - button "paginate-dots" [ref=e370] [cursor=pointer]
            - listitem [ref=e371]:
              - button "paginate-dots" [ref=e372] [cursor=pointer]
            - listitem [ref=e373]:
              - button "paginate-dots" [ref=e374] [cursor=pointer]
      - article [ref=e375]:
        - generic [ref=e376]:
          - img "คุณกัญญ์ปภัส วัฒนพสิษฐ์" [ref=e378]
          - generic [ref=e379]:
            - img "quote-start" [ref=e380]
            - paragraph [ref=e381]: ตั้งแต่มีประกันสุขภาพ เจ็บป่วยแค่ไหนก็ไม่กังวลอีกแล้วค่ะ ความคุ้มครองครอบคลุมค่ารักษาพยาบาลทั้งหมดและไม่ต้องสำรองจ่ายไปก่อนด้วย
            - img "quote-end" [ref=e382]
            - generic [ref=e383]: คุณกัญญ์ปภัส วัฒนพสิษฐ์
      - article [ref=e384]:
        - heading "แชร์ประสบการณ์จากผู้ใช้บริการ TQM" [level=2] [ref=e385]
        - list [ref=e389]:
          - listitem [ref=e390]:
            - generic [ref=e392]:
              - img "คุณธนภัทร เลิศกุลธรรม" [ref=e394]
              - paragraph [ref=e395]: คุณธนภัทร เลิศกุลธรรม
              - generic [ref=e396]:
                - img [ref=e398]
                - img [ref=e401]
                - img [ref=e404]
                - img [ref=e407]
                - img [ref=e410]
              - paragraph [ref=e413]: ประทับใจพนักงานให้คำแนะนำดีครับ มีแผนประกันสุขภาพให้เลือกเยอะ ทำแล้วก็รู้สึกหมดกังวัลครับ ไม่ต้องควักเงินเองตอนป่วยเข้า รพ.
          - listitem [ref=e414]:
            - generic [ref=e416]:
              - img [ref=e418]
              - paragraph [ref=e419]: คุณขรินทิพย์ งบกระโทก
              - generic [ref=e420]:
                - img [ref=e422]
                - img [ref=e425]
                - img [ref=e428]
                - img [ref=e431]
                - img [ref=e434]
              - paragraph [ref=e437]: แค่ได้ทำประกันสุขภาพไว้ก็รู้สึกเบาใจมากค่ะ ไม่ต้องห่วงเรื่องค่ารักษาเวลาป่วย เพราะรู้ว่ามีคนช่วยดูแล
          - listitem [ref=e438]:
            - generic [ref=e440]:
              - img [ref=e442]
              - paragraph [ref=e443]: คุณเอกชัย จูฉิม
              - generic [ref=e444]:
                - img [ref=e446]
                - img [ref=e449]
                - img [ref=e452]
                - img [ref=e455]
                - img [ref=e458]
              - paragraph [ref=e461]: ตอนแอดมิท โชคดีที่มีประกันของ TQM เคลมง่ายมาก รพ.แจ้งปุ๊บก็จัดการให้เลย ไม่ต้องสำรองจ่ายเอง สบายใจจริง ๆ ครับ
      - article [ref=e462]:
        - heading "คำถามที่พบบ่อยเกี่ยวกับประกันสุขภาพ" [level=2] [ref=e463]
        - generic [ref=e464]:
          - button "ประกันสุขภาพกับประกันโรคร้ายแรง ต่างกันอย่างไร?" [ref=e468] [cursor=pointer]:
            - heading "ประกันสุขภาพกับประกันโรคร้ายแรง ต่างกันอย่างไร?" [level=3] [ref=e470]
            - img [ref=e472]
          - button "ประกันสุขภาพสามารถเคลมค่ารักษาผู้ป่วยนอกได้หรือไม่?" [ref=e477] [cursor=pointer]:
            - heading "ประกันสุขภาพสามารถเคลมค่ารักษาผู้ป่วยนอกได้หรือไม่?" [level=3] [ref=e479]
            - img [ref=e481]
          - button "ทําประกันสุขภาพต้องตรวจสุขภาพก่อนทําไหม?" [ref=e486] [cursor=pointer]:
            - heading "ทําประกันสุขภาพต้องตรวจสุขภาพก่อนทําไหม?" [level=3] [ref=e488]
            - img [ref=e490]
          - button "ทําประกันสุขภาพต้องรอกี่วันถึงจะคุ้มครอง?" [ref=e495] [cursor=pointer]:
            - heading "ทําประกันสุขภาพต้องรอกี่วันถึงจะคุ้มครอง?" [level=3] [ref=e497]
            - img [ref=e499]
          - button "มีประกันสุขภาพกลุ่มของบริษัทอยู่แล้ว ควรซื้อประกันสุขภาพเพิ่มอีกหรือไม่?" [ref=e504] [cursor=pointer]:
            - heading "มีประกันสุขภาพกลุ่มของบริษัทอยู่แล้ว ควรซื้อประกันสุขภาพเพิ่มอีกหรือไม่?" [level=3] [ref=e506]
            - img [ref=e508]
          - button "ประกันสุขภาพเหมาจ่ายคืออะไร?" [ref=e513] [cursor=pointer]:
            - heading "ประกันสุขภาพเหมาจ่ายคืออะไร?" [level=3] [ref=e515]
            - img [ref=e517]
          - button "ทําประกันสุขภาพควบคู่ประกันอุบัติเหตุแบบไม่ต้องสำรองจ่ายได้ไหม?" [ref=e522] [cursor=pointer]:
            - heading "ทําประกันสุขภาพควบคู่ประกันอุบัติเหตุแบบไม่ต้องสำรองจ่ายได้ไหม?" [level=3] [ref=e524]
            - img [ref=e526]
          - button "เบี้ยประกันสุขภาพสามารถนำไปลดหย่อนภาษีได้หรือไม่?" [ref=e531] [cursor=pointer]:
            - heading "เบี้ยประกันสุขภาพสามารถนำไปลดหย่อนภาษีได้หรือไม่?" [level=3] [ref=e533]
            - img [ref=e535]
          - button "ทําประกันสุขภาพให้พ่อแม่ ลดหย่อนภาษีได้ไหม?" [ref=e540] [cursor=pointer]:
            - heading "ทําประกันสุขภาพให้พ่อแม่ ลดหย่อนภาษีได้ไหม?" [level=3] [ref=e542]
            - img [ref=e544]
          - button "ทําประกันสุขภาพแผนไหนดี?" [ref=e549] [cursor=pointer]:
            - heading "ทําประกันสุขภาพแผนไหนดี?" [level=3] [ref=e551]
            - img [ref=e553]
      - generic [ref=e555]:
        - heading "คำศัพท์ทั่วไปเกี่ยวกับประกันสุขภาพที่คุณควรรู้" [level=2] [ref=e556]
        - generic [ref=e557]:
          - generic [ref=e558]:
            - img "Vocabulary Info" [ref=e560]
            - generic [ref=e561]:
              - paragraph [ref=e562]: ผู้ป่วยใน (IPD)
              - paragraph [ref=e563]: คือ ผู้ป่วยที่ต้องเข้ารับการรักษาและนอนพักค้างคืนในโรงพยาบาลอย่างน้อย 6 ชั่วโมงขึ้นไป ตามคำวินิจฉัยของแพทย์ เพื่อรับการรักษาหรือรอดูอาการ
          - generic [ref=e564]:
            - img "Vocabulary Info" [ref=e566]
            - generic [ref=e567]:
              - paragraph [ref=e568]: ผู้ป่วยนอก (OPD)
              - paragraph [ref=e569]: คือ ผู้ป่วยที่เข้ารับการรักษาในโรงพยาบาล แต่ไม่ต้องนอนพักค้างคืน เมื่อตรวจและรักษาเรียบร้อย สามารถกลับบ้านได้เลยในวันที่เข้ารับการรักษา
          - generic [ref=e570]:
            - img "Vocabulary Info" [ref=e572]
            - generic [ref=e573]:
              - paragraph [ref=e574]: ระยะเวลารอคอย (Waiting Period)
              - paragraph [ref=e575]: คือ ช่วงเวลาที่ประกันยังไม่คุ้มครอง หลังจากวันที่สัญญาประกันมีผลบังคับใช้ โดยทั่วไปมักกำหนดไว้ตั้งแต่ 30 วัน 90 วัน หรือ 120 วัน ขึ้นอยู่กับประกันแต่ละประเภทหรือแต่ละโรค
          - generic [ref=e576]:
            - img "Vocabulary Info" [ref=e578]
            - generic [ref=e579]:
              - paragraph [ref=e580]: การสำรองจ่ายแบบ Fax Claim
              - paragraph [ref=e581]: คือ บริการพิเศษที่ผู้เอาประกันไม่ต้องควักเงินจ่ายค่ารักษาเองล่วงหน้า หากโรงพยาบาลนั้นอยู่ในเครือข่ายคู่สัญญาของบริษัทประกัน
      - article [ref=e582]:
        - heading "เคลมประกันสุขภาพ" [level=2] [ref=e583]
        - paragraph [ref=e584]: เจ็บป่วยหากมีประกันสุขภาพ ความคุ้มครองครอบคลุมค่ารักษาพยาบาลทั้งหมดและไม่ต้องสำรองจ่ายไปก่อนด้วย
        - generic [ref=e585]:
          - generic [ref=e586]:
            - img "เคลมเงินชดเชยรายวัน" [ref=e588]
            - generic [ref=e589]:
              - heading "เคลมเงินชดเชยรายวัน" [level=3] [ref=e590]
              - paragraph [ref=e591]: เคลมเงินชดเชยรายวันกรณีนอนโรงพยาบาล รวบรวมเอกสารใบรับรองแพทย์ ประวัติการรักษา และใบเสร็จรับเงิน นำเอกสาร เพื่อขอรับสินไหม
          - generic [ref=e592]:
            - img "เคลมสินไหมผู้ป่วยนอก (OPD)" [ref=e594]
            - generic [ref=e595]:
              - heading "เคลมสินไหมผู้ป่วยนอก (OPD)" [level=3] [ref=e596]
              - paragraph [ref=e597]: ก่อนเข้าใช้บริการสามารถแจ้งบริษัทประกัน ณ โรงพยาบาลที่ท่านเข้าใช้บริการ ให้ตรวจเช็คสิทธิ์ในการเบิกเคลมประกันสุขภาพได้ เพื่อความสะดวกในการเข้าใช้บริการที่โรงพยาบาล สะดวก และไม่ต้องสำรองจ่าย
          - generic [ref=e598]:
            - img "เคลมสินไหมผู้ป่วยใน (IPD)" [ref=e600]
            - generic [ref=e601]:
              - heading "เคลมสินไหมผู้ป่วยใน (IPD)" [level=3] [ref=e602]
              - paragraph [ref=e603]: เมื่อเข้ารับรักษาตัวเป็นผู้ป่วยใน (IPD) สามารถแจ้งเคลมสินไหมสุขภาพโดยการแจ้งชื่อบริษัทประกันที่ท่านทำอยู่ เพื่อเช็คสิทธิ์ในการเบิกเคลมตรงกับทางโรงพยาบาล โดยลูกค้าไม่ต้องสำรองจ่ายค่ารักษาพยาบาล
        - generic [ref=e604]: "หมายเหตุ : เป็นไปตามเงื่อนไขกรมธรรม์"
        - generic [ref=e606]:
          - heading "ช่องทางการเคลมประกันสุขภาพ" [level=2] [ref=e607]
          - generic [ref=e608]:
            - generic [ref=e609] [cursor=pointer]:
              - img "app" [ref=e610]
              - generic [ref=e611]: สายด่วน 1737
            - generic [ref=e612] [cursor=pointer]:
              - img "app" [ref=e613]
              - generic [ref=e614]: App TQM24
            - generic [ref=e615] [cursor=pointer]:
              - img "app" [ref=e616]
              - generic [ref=e617]: Line TQM
        - button "ดูข้อมูลการเคลมเพิ่มเติม" [ref=e619] [cursor=pointer]
    - contentinfo [ref=e620]:
      - link "TQM Logo" [ref=e622] [cursor=pointer]:
        - /url: /
        - img "TQM Logo" [ref=e623]
      - generic [ref=e624]:
        - button "ผลิตภัณฑ์ประกันภัย" [ref=e627] [cursor=pointer]:
          - generic [ref=e629]: ผลิตภัณฑ์ประกันภัย
          - img [ref=e631]
        - button "บริการลูกค้า" [ref=e635] [cursor=pointer]:
          - generic [ref=e637]: บริการลูกค้า
          - img [ref=e639]
        - button "ติดต่อสอบถาม" [ref=e643] [cursor=pointer]:
          - generic [ref=e645]: ติดต่อสอบถาม
          - img [ref=e647]
        - button "บริษัท" [ref=e651] [cursor=pointer]:
          - generic [ref=e653]: บริษัท
          - img [ref=e655]
        - generic [ref=e657]:
          - generic [ref=e658]:
            - link "line" [ref=e660] [cursor=pointer]:
              - /url: https://lin.ee/Ds7qY7v
              - img "line" [ref=e661]
            - link "facebook" [ref=e663] [cursor=pointer]:
              - /url: https://www.facebook.com/TqmBroker
              - img "facebook" [ref=e664]
            - link "instagram" [ref=e666] [cursor=pointer]:
              - /url: https://www.instagram.com/tqminsurancebroker
              - img "instagram" [ref=e667]
            - link "tiktok" [ref=e669] [cursor=pointer]:
              - /url: http://www.tiktok.com/@tqmmorelove
              - img "tiktok" [ref=e670]
            - link "youtube" [ref=e672] [cursor=pointer]:
              - /url: https://www.youtube.com/@TQMInsuranceBrokerOfficial
              - img "youtube" [ref=e673]
            - link "x" [ref=e675] [cursor=pointer]:
              - /url: https://x.com/Tqmbeside
              - img "x" [ref=e676]
          - link "1737" [ref=e678] [cursor=pointer]:
            - /url: tel:1737
            - img [ref=e679]
            - text: "1737"
        - generic [ref=e682]:
          - link "TQM Application" [ref=e684] [cursor=pointer]:
            - /url: https://tqm.onelink.me/jwZj/fsmrwgvs
            - img "TQM Application" [ref=e685]
          - generic [ref=e686]:
            - link "TQM IOS Application" [ref=e687] [cursor=pointer]:
              - /url: https://apps.apple.com/th/app/tqm24/id1274502784
              - img "TQM IOS Application" [ref=e688]
            - link "TQM Android Application" [ref=e689] [cursor=pointer]:
              - /url: https://play.google.com/store/apps/details?id=com.tqm.tqmapp
              - img "TQM Android Application" [ref=e690]
            - link "TQM APK Download" [ref=e691] [cursor=pointer]:
              - /url: https://storage.googleapis.com/tqm-beta-static/files/APK/tqm24.apk
              - img "TQM APK Download" [ref=e692]
        - generic [ref=e693]:
          - paragraph [ref=e694]: ©Copyright 2026 TQM.co.th All Rights Reserved.
          - generic [ref=e695]:
            - paragraph [ref=e696]:
              - link "แผนผังเว็บไซต์" [ref=e697] [cursor=pointer]:
                - /url: https://devweb.tqm.co.th/sitemap
            - paragraph [ref=e698]:
              - link "ข้อกำหนดและเงื่อนไข" [ref=e699] [cursor=pointer]:
                - /url: /terms-and-conditions
            - paragraph [ref=e700]:
              - link "นโยบายข้อมูลส่วนบุคคล" [ref=e701] [cursor=pointer]:
                - /url: /tqm/privacy
    - generic [ref=e702]:
      - generic [ref=e703] [cursor=pointer]:
        - img [ref=e706]
        - generic [ref=e714]:
          - button "Close notification" [ref=e715]:
            - img [ref=e716]
          - paragraph [ref=e719]: มองหาประกันสุขภาพที่ตรงใจ ปรึกษาพี่หมีได้เลยครับ
      - button "Toggle chat" [ref=e721] [cursor=pointer]:
        - img "chat-on-web" [ref=e722]
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
  - alert [ref=e723]
```

# Test source

```ts
  1   | import { Locator, Page, expect } from '@playwright/test';
  2   | import dayjs, { Dayjs } from 'dayjs';
  3   | import 'dayjs/locale/th';
  4   | import localizedFormat from 'dayjs/plugin/localizedFormat';
  5   | import { commonData } from '../data/common.data';
  6   | import { commonLocator } from '../locator/nmw/nmw-common-locator';
  7   | import { ViewObjective } from '../types/common.type';
  8   | 
  9   | dayjs.extend(localizedFormat);
  10  | dayjs.locale('th');
  11  | 
  12  | export default class CommonTQM {
  13  |   constructor(
  14  |     public page: Page,
  15  |     private isMobile: boolean = false,
  16  |   ) {}
  17  | 
  18  |   async initDevice() {
  19  |     this.isMobile = await this.detectIsMobile();
  20  |   }
  21  | 
  22  |   private async detectIsMobile(): Promise<boolean> {
  23  |     return await this.page.evaluate(() => window.innerWidth <= 768);
  24  |   }
  25  | 
  26  |   public isDeviceMobile(): boolean {
  27  |     return this.isMobile;
  28  |   }
  29  | 
  30  |   async waitUntil(objective: ViewObjective, locator: any) {
  31  |     const startTime = performance.now();
  32  |     console.debug(`Start time: "${startTime}"`);
  33  |     for (let i = 0; i < 20; i++) {
  34  |       const element = locator;
  35  |       try {
  36  |         if (objective == ViewObjective.Visible && (await element.isVisible())) {
  37  |           const endTime = performance.now();
  38  |           console.debug(`Wait for visible is success found locator "${locator}" at ${endTime} ms.`);
  39  |           return true;
  40  |         } else if (objective == ViewObjective.Hidden && !(await element.isVisible())) {
  41  |           const endTime = performance.now();
  42  |           console.debug(`Wait for invisible is success NOT found locator "${locator}" at ${endTime} ms.`);
  43  |           return true;
  44  |         }
  45  |       } catch (error) {
  46  |         console.debug(`Catch error: locator "${locator}" - ${error}`);
  47  |         return false;
  48  |       }
  49  |       await new Promise((resolve) => setTimeout(resolve, 500)); // Wait for 0.5 second before checking again
  50  |     }
  51  |     return false; // Return false if the element is out of scope within the timeout
  52  |   }
  53  | 
  54  |   async acceptCookies() {
  55  |     await this.page.waitForTimeout(1000);
  56  |     if (this.isDeviceMobile()) {
  57  |       await this.page.evaluate(() => {
  58  |         window.scrollBy(0, 350);
  59  |       });
  60  |       await this.page.waitForTimeout(500);
  61  |       await this.page.evaluate(() => {
  62  |         window.scrollBy(0, 350);
  63  |       });
  64  |     } else {
  65  |       await this.page.mouse.wheel(0, 400);
  66  |       await this.page.waitForTimeout(500);
  67  |       await this.page.mouse.wheel(0, 400);
  68  |     }
> 69  |     await expect(this.page.getByTestId(commonLocator.BUTTON_ID_ACCEPT_COOKIES)).toBeVisible({ timeout: 18000 });
      |                                                                                 ^ Error: expect(locator).toBeVisible() failed
  70  | 
  71  |     await expect(this.page.getByTestId(commonLocator.BUTTON_ID_ACCEPT_COOKIES)).toBeVisible();
  72  |     await this.page.getByTestId(commonLocator.BUTTON_ID_ACCEPT_COOKIES).click();
  73  |     await expect(this.page.getByTestId(commonLocator.BUTTON_ID_ACCEPT_COOKIES)).toBeHidden();
  74  |   }
  75  | 
  76  |   async acceptConsent() {
  77  |     await this.page.waitForTimeout(1000);
  78  |     const acceptConsentCheckBox = this.page.getByTestId(commonLocator.CHECKBOX_ID_ACCEPT_PRIVACY);
  79  |     const agreeButton = this.page.getByTestId(commonLocator.BUTTON_ID_AGREE_CONSENT);
  80  | 
  81  |     const isVisible = await agreeButton.isVisible().catch(() => false);
  82  |     if (!isVisible) return;
  83  | 
  84  |     await acceptConsentCheckBox.check();
  85  |     await expect(agreeButton).toBeEnabled();
  86  |     await agreeButton.click();
  87  |     await expect(agreeButton).toBeHidden();
  88  |   }
  89  | 
  90  |   async selectDatePicker(page: Page, dataTestId: string, date: Date | Dayjs | string, isBirthday: boolean) {
  91  |     const day = dayjs(date).date();
  92  |     const month = dayjs(date).month();
  93  |     const year = dayjs(date).year();
  94  | 
  95  |     const newDate = dayjs(new Date(year, month, day));
  96  |     const yearEN = newDate.format('YYYY'); // "2025"
  97  |     const monthTH = newDate.format('MMM'); // "เม.ย."
  98  | 
  99  |     const dateLocator = page.getByTestId(dataTestId).locator('button');
  100 | 
  101 |     if (isBirthday) {
  102 |       await dateLocator.filter({ hasText: new RegExp(`^${yearEN}$`) }).click();
  103 |       await this.page.waitForTimeout(500);
  104 | 
  105 |       await dateLocator.filter({ hasText: new RegExp(`^${monthTH}$`) }).click();
  106 |       await this.page.waitForTimeout(500);
  107 | 
  108 |       await dateLocator.filter({ hasText: new RegExp(`^${day}$`) }).click();
  109 |       await this.page.waitForTimeout(500);
  110 |     } else {
  111 |       const currentMonth = dayjs().month();
  112 |       const nextMonth = Math.abs(currentMonth - month);
  113 |       await expect(this.page.getByTestId(commonLocator.ICON_ID_ARROW_RIGHT)).toBeVisible();
  114 | 
  115 |       for (let i = 0; i < nextMonth; i++) {
  116 |         await this.page.getByTestId(commonLocator.ICON_ID_ARROW_RIGHT).click();
  117 |         await this.page.waitForTimeout(500);
  118 |       }
  119 | 
  120 |       await dateLocator.filter({ hasText: new RegExp(`^${day}$`) }).click();
  121 |       await this.page.waitForTimeout(500);
  122 |     }
  123 | 
  124 |     await this.page.getByTestId(dataTestId).locator('button', { hasText: 'OK' }).click();
  125 |   }
  126 | 
  127 |   static async getProductData(page: Page, dataTestId: string): Promise<string> {
  128 |     const productData: string | null = await page.getByTestId(dataTestId).evaluate((el: Element) => el.textContent);
  129 | 
  130 |     // ถ้า textContent เป็น null ให้ fallback เป็น empty string
  131 |     return productData ?? '';
  132 |   }
  133 | 
  134 |   static async getInsureName(page: Page, dataTestId: string): Promise<string> {
  135 |     const insureName: string | null = await page.getByTestId(dataTestId).evaluate((el: Element) => el.textContent);
  136 | 
  137 |     // ถ้า textContent เป็น null ให้ fallback เป็น empty string
  138 |     return insureName ?? '';
  139 |   }
  140 | 
  141 |   static async getInsurePrice(page: Page, dataTestId: string): Promise<number> {
  142 |     const insurePriceText: string = await page
  143 |       .getByTestId(dataTestId)
  144 |       .first()
  145 |       .evaluate((el: Element) => (el as HTMLElement).innerText);
  146 | 
  147 |     // ตรวจสอบว่าเป็น "ฟรี" (Free) หรือไม่
  148 |     if (insurePriceText.trim() === 'ฟรี') {
  149 |       return 0;
  150 |     }
  151 | 
  152 |     // ลบ "฿", "บาท", และช่องว่างที่ไม่จำเป็นออก
  153 |     const cleanedText = insurePriceText.replace('฿', '').replace('บาท', '').trim();
  154 | 
  155 |     // แปลงเป็น number โดย parseFloat (รองรับ "," อยู่ใน string)
  156 |     const numericValue = parseFloat(cleanedText.replace(/,/g, ''));
  157 | 
  158 |     // ตรวจสอบว่าเป็น number จริงหรือไม่
  159 |     if (isNaN(numericValue)) {
  160 |       throw new Error(`Invalid insurance price format: "${insurePriceText}"`);
  161 |     }
  162 |     return numericValue;
  163 |   }
  164 | 
  165 |   // สร้างเลขบัตรประชาชนไทย 13 หลัก
  166 |   static async randomCitizenId(): Promise<string> {
  167 |     let id12 = '';
  168 |     for (let i = 0; i < 12; i++) {
  169 |       id12 += Math.floor(Math.random() * 10).toString();
```