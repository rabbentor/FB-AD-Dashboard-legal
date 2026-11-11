# นโยบายความเป็นส่วนตัว (Privacy Policy)

อัปเดตล่าสุด: 25 ตุลาคม 2026  
ผู้ดูแลแอป: WhiteRabbit  
ติดต่อ: asdem000@gmail.com

## 1. ภาพรวม (Overview)

แอปพลิเคชันนี้เป็นเครื่องมือส่วนบุคคลสำหรับเจ้าของแอป ใช้จัดการ ตรวจสอบ และวิเคราะห์บัญชีโฆษณา Meta (Facebook) ของตนเองผ่าน Meta Marketing API โดยประกอบด้วยแดชบอร์ดที่ทำงานในเว็บเบราว์เซอร์ของเจ้าของแอป และอาจมีผู้ช่วย AI ที่ทำงานบนบัญชี Cloudflare ของเจ้าของแอป รวมถึงระบบแจ้งเตือนผ่านบัญชี LINE ของเจ้าของแอปเมื่อมีการเปิดใช้ฟีเจอร์ดังกล่าว

แอปนี้ไม่ได้เปิดให้บุคคลทั่วไปสมัครสมาชิก ไม่ได้ให้บริการแก่บุคคลที่สาม และไม่มีวัตถุประสงค์เพื่อรวบรวมข้อมูลของผู้ใช้ Facebook รายอื่น

This application is a personal tool used solely by its owner to manage, monitor, and analyze the owner's own Meta (Facebook) advertising accounts through the Meta Marketing API. It consists of a dashboard running in the owner's web browser and may include an optional AI assistant hosted in the owner's own Cloudflare account, as well as notifications sent to the owner's own LINE account when those features are enabled.

The application is not open for public registration, is not provided as a service to third parties, and is not intended to collect data about other Facebook users.

## 2. ข้อมูลที่แอปเข้าถึง (Information Accessed)

แอปเข้าถึงเฉพาะข้อมูลที่เกี่ยวข้องกับบัญชีโฆษณาและเพจที่เจ้าของแอปมีสิทธิ์เข้าถึง โดยอาจประกอบด้วย:

- ข้อมูลบัญชีโฆษณา เช่น Advertising Account ID และข้อมูลพื้นฐานของบัญชี
- ข้อมูลแคมเปญ (Campaigns)
- ข้อมูลชุดโฆษณา (Ad Sets)
- ข้อมูลโฆษณาและชิ้นงานโฆษณา (Ads and Ad Creatives)
- สถิติและผลการดำเนินงานโฆษณา (Insights) เช่น ยอดใช้จ่าย การแสดงผล การเข้าถึง จำนวนคลิก และผลลัพธ์ตามที่ Meta API อนุญาต
- รายชื่อเพจ Facebook ที่เจ้าของแอปดูแลหรือมีสิทธิ์เข้าถึง เมื่อจำเป็นต่อการทำงานของแอป
- Access Token และข้อมูลการตั้งค่าที่จำเป็นต่อการเชื่อมต่อ Meta API

ข้อมูลกลุ่มเป้าหมาย เช่น อายุ เพศ หรือพื้นที่ อาจปรากฏในรูปแบบสถิติแบบสรุปรวมตามที่ Meta ให้บริการ ข้อมูลดังกล่าวใช้เพื่อวิเคราะห์ผลโฆษณา ไม่ได้มีวัตถุประสงค์เพื่อระบุตัวบุคคล

The application accesses only advertising-account and Page information that the app owner is authorized to access. This may include:

- Advertising account information, such as Advertising Account IDs and basic account details
- Campaigns
- Ad sets
- Ads and ad creatives
- Advertising performance insights, such as spend, impressions, reach, clicks, and other results made available by the Meta API
- Facebook Pages managed by or accessible to the app owner, when needed for the application's functions
- Access tokens and settings required to connect to the Meta API

Audience breakdowns, such as age, gender, or geographic area, may be displayed as aggregated statistics provided by Meta. These statistics are used to analyze advertising performance and are not intended to identify individuals.

## 3. การจัดเก็บและประมวลผลข้อมูล (Data Storage and Processing)

การจัดเก็บข้อมูลขึ้นอยู่กับฟีเจอร์ที่เจ้าของแอปเลือกใช้งาน ดังนี้

### 3.1 แดชบอร์ด (Dashboard)

Access Token และการตั้งค่าที่จำเป็นต่อการใช้งานแดชบอร์ดจะถูกจัดเก็บใน Local Storage ของเว็บเบราว์เซอร์บนอุปกรณ์ของเจ้าของแอป ข้อมูลดังกล่าวไม่ได้ถูกส่งไปจัดเก็บบนเซิร์ฟเวอร์ของผู้ให้บริการแอปโดยอัตโนมัติ

### 3.2 ผู้ช่วย AI (Optional AI Assistant)

หากเปิดใช้งาน ผู้ช่วย AI จะทำงานบน Cloudflare Workers ภายในบัญชี Cloudflare ที่เจ้าของแอปเป็นผู้ควบคุม โดย:

- Access Token ที่จำเป็นจะจัดเก็บเป็นค่าลับ (Secret) ในระบบของ Cloudflare
- การตั้งค่าและประวัติการทำงานที่จำเป็นอาจจัดเก็บใน Cloudflare KV ภายในบัญชีเดียวกัน
- ข้อมูลจะถูกประมวลผลเพื่อให้ผู้ช่วย AI ทำงานตามคำสั่งและวัตถุประสงค์ที่เจ้าของแอปกำหนด

### 3.3 การแจ้งเตือนผ่าน LINE (Optional LINE Notifications)

หากเปิดใช้งาน ระบบอาจส่งสรุปผลโฆษณาและการแจ้งเตือนไปยังบัญชี LINE ของเจ้าของแอปผ่าน LINE Messaging API โดยระบบรับคำสั่งจากบัญชี LINE ที่ได้รับอนุญาตของเจ้าของแอปเท่านั้น

### 3.4 การใช้บริการ AI ภายนอก (Optional Third-Party AI Services)

หากเจ้าของแอปเปิดใช้ฟีเจอร์ AI ข้อมูลที่จำเป็น เช่น ตัวเลขผลการดำเนินงานโฆษณาและข้อความโฆษณา อาจถูกส่งไปยังผู้ให้บริการ AI ที่เจ้าของแอปเลือก เช่น Anthropic หรือ OpenAI เพื่อวิเคราะห์ข้อมูล ให้คำแนะนำ หรือสร้างภาพโฆษณา การเชื่อมต่อดังกล่าวใช้ API Key ของเจ้าของแอปเอง และอยู่ภายใต้ข้อกำหนดและนโยบายความเป็นส่วนตัวของผู้ให้บริการ AI นั้นด้วย

### 3.5 การเปิดเผยข้อมูลแก่ผู้ให้บริการ (Service Providers)

ไม่มีการขายข้อมูลหรือเปิดเผยข้อมูลแก่บุคคลที่สามเพื่อการโฆษณาหรือการตลาดของบุคคลอื่น ข้อมูลอาจถูกส่งไปยัง Meta, Cloudflare, LINE หรือผู้ให้บริการ AI เฉพาะเท่าที่จำเป็นต่อฟีเจอร์ที่เจ้าของแอปเลือกเปิดใช้งาน ตามรายละเอียดข้างต้น

Data storage depends on which features the app owner enables:

### 3.1 Dashboard

Access tokens and dashboard settings are stored in the Local Storage of the web browser on the app owner's device. They are not automatically uploaded to an application operator's server.

### 3.2 AI Assistant (Optional)

If enabled, the AI assistant runs on Cloudflare Workers within the Cloudflare account controlled by the app owner.

- Required access tokens are stored as Cloudflare Secrets.
- Necessary settings and activity history may be stored in Cloudflare KV within the same account.
- Data is processed to perform the assistant's functions as instructed by the app owner.

### 3.3 LINE Notifications (Optional)

If enabled, advertising summaries and alerts may be sent to the app owner's LINE account through the LINE Messaging API. The system accepts commands only from the app owner's authorized LINE account.

### 3.4 Third-Party AI Services (Optional)

If AI features are enabled, necessary information—such as advertising performance figures and ad copy—may be sent to an AI provider selected by the app owner, such as Anthropic or OpenAI, for analysis, recommendations, or ad-image generation. These integrations use the app owner's own API keys and are also subject to the selected provider's terms and privacy policy.

### 3.5 Service Providers

Data is not sold or disclosed to third parties for their advertising or marketing purposes. Data may be transmitted to Meta, Cloudflare, LINE, or an AI provider only as necessary for features that the app owner chooses to enable, as described above.

## 4. ข้อมูลของบุคคลอื่น (Other Individuals' Data)

แอปนี้ไม่มีระบบสมัครสมาชิกหรือเข้าสู่ระบบสำหรับบุคคลทั่วไป และไม่ได้ออกแบบมาเพื่อรวบรวมข้อมูลส่วนบุคคลของผู้ใช้ Facebook รายอื่น ไม่มีการติดตามพฤติกรรมของผู้ใช้ทั่วไป และไม่มีการนำข้อมูลส่วนบุคคลของผู้ใช้ Facebook รายอื่นไปสร้างโปรไฟล์หรือกำหนดกลุ่มเป้าหมาย

This application has no public registration or public user-login system and is not designed to collect personal information about other Facebook users. It does not track the behavior of general users or use other Facebook users' personal information to build profiles or create advertising audiences.

## 5. ความปลอดภัยของข้อมูล (Data Security)

เจ้าของแอปเป็นผู้ควบคุมอุปกรณ์ บัญชี Cloudflare บัญชี LINE และ API Key ที่ใช้กับบริการต่าง ๆ โดยตรง เจ้าของแอปควรเก็บรักษาอุปกรณ์และข้อมูลรับรองการเข้าถึงให้ปลอดภัย ไม่เปิดเผย Access Token หรือ API Key ต่อบุคคลอื่น และถอนสิทธิ์การเข้าถึงเมื่อไม่ต้องการใช้งานแล้ว

มีการใช้กลไกการจัดเก็บตามความสามารถของแต่ละแพลตฟอร์ม เช่น Local Storage, Cloudflare Secrets และ Cloudflare KV อย่างไรก็ตาม ไม่มีวิธีการส่งผ่านหรือจัดเก็บข้อมูลทางอิเล็กทรอนิกส์ใดที่ปลอดภัยสมบูรณ์แบบ จึงไม่สามารถรับประกันความปลอดภัยได้อย่าง абсолют

The app owner directly controls the devices, Cloudflare account, LINE account, and API keys used by the application. The owner should secure their devices and credentials, avoid disclosing access tokens or API keys, and revoke access when it is no longer needed.

The application uses the storage and security mechanisms provided by each platform, such as browser Local Storage, Cloudflare Secrets, and Cloudflare KV. However, no electronic transmission or storage method is completely secure, and absolute security cannot be guaranteed.

## 6. การเก็บรักษาและการลบข้อมูล (Data Retention and Deletion)

ข้อมูลจะถูกเก็บไว้เท่าที่จำเป็นต่อการใช้งานฟีเจอร์ที่เจ้าของแอปเปิดใช้งาน เจ้าของแอปสามารถลบข้อมูลหรือยุติการเชื่อมต่อได้ด้วยตนเองตามขั้นตอนในหน้า [คำแนะนำการลบข้อมูล (Data Deletion)](../data-deletion/)

- ข้อมูลแดชบอร์ด: ลบผ่านปุ่ม “ลบออกจากเครื่อง” ในหน้าตั้งค่า Token หรือล้าง Local Storage ของเว็บไซต์
- ข้อมูลผู้ช่วย AI: ลบ Worker และข้อมูลที่เกี่ยวข้องใน Cloudflare KV จากบัญชี Cloudflare ของเจ้าของแอป
- การเชื่อมต่อ Meta: ถอนสิทธิ์แอปจากการตั้งค่าบัญชี Facebook/Meta

การลบข้อมูลออกจากแอปไม่ได้ลบข้อมูลที่ Meta หรือผู้ให้บริการภายนอกจัดเก็บไว้ตามนโยบายของผู้ให้บริการนั้นโดยอัตโนมัติ

Data is retained only as needed for the features enabled by the app owner. The owner can delete data or disconnect services by following the [Data Deletion instructions](../data-deletion/).

- Dashboard data: use the “ลบออกจากเครื่อง” (Remove from this device) button in the token settings or clear the website's Local Storage.
- AI assistant data: delete the Worker and related Cloudflare KV data from the app owner's Cloudflare account.
- Meta connection: revoke the app's permissions through Facebook/Meta account settings.

Deleting data from this application does not automatically delete data retained by Meta or external providers under their own policies.

## 7. การเปลี่ยนแปลงนโยบาย (Changes to This Policy)

อาจมีการปรับปรุงนโยบายนี้เมื่อมีการเปลี่ยนแปลงฟีเจอร์ วิธีประมวลผลข้อมูล หรือข้อกำหนดที่เกี่ยวข้อง โดยจะระบุวันที่อัปเดตล่าสุดไว้ด้านบน

This policy may be updated when application features, data-processing practices, or relevant requirements change. The latest revision date will be shown at the top of this page.

## 8. ติดต่อ (Contact)

หากมีคำถามเกี่ยวกับนโยบายความเป็นส่วนตัวหรือการจัดการข้อมูล กรุณาติดต่อ:

**อีเมล:** asdem000@gmail.com

For questions about this Privacy Policy or data handling, contact:

**Email:** asdem000@gmail.com

---

เอกสารนี้จัดทำขึ้นเพื่ออธิบายการประมวลผลข้อมูลของแอปพลิเคชันที่ใช้ Meta Marketing API สำหรับการใช้งานส่วนบุคคล ไม่ใช่คำรับรองหรือการรับรองจาก Meta Platforms, Inc.
