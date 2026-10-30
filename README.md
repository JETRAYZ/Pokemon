# ⚡ Pokémon Blind Auction (Online Realtime Multiplayer)

เกมประมูลโปเกมอนแบบไม่เปิดเผยตัวตน (Blind Auction) ออนไลน์แบบเรียลไทม์ รองรับการเล่นพร้อมกันหลายคนผ่าน Cloud MQTT และ BroadcastChannel

![Pokémon Blind Auction](https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/items/poke-ball.png)

## ✨ ฟีเจอร์หลัก (Key Features)

- 🌐 **Realtime Cloud Sync**: ซิงค์สถานะห้อง การเสนอราคา และเวลานับถอยหลังตรงกันเป๊ะสำหรับผู้เล่นทุกคนผ่าน Cloud MQTT WebSockets (`broker.emqx.io`)
- 🔒 **Player Seat Security**: ผู้เล่นกดบิดได้เฉพาะที่นั่งของตนเองเท่านั้น ป้องกันการกดเงินแทนกัน
- ⌨️ **Custom Price Bidding**: เสนอราคาได้ทั้งแบบปุ่มด่วน (+2k, +5k, +10k) และพิมพ์ราคาเองตามต้องการ
- 🎲 **Authentic Moves & Abilities**: สุ่มโปเกมอนกว่า 1,000+ ร่างจาก PokéAPI พร้อมท่าต่อสู้และอบิลิตี้จริงตามสายพันธุ์
- 👥 **Multiplayer 4 Seats & Bot Test**: รองรับผู้เล่น 4 คน พร้อมระบบเพิ่มบอทจำลองสำหรับการทดสอบ
- ⏱️ **Synchronized Countdown**: ระบบนับถอยหลัง 5 วินาทีระดับมิลลิวินาที ซิงค์การจบประมูลและเปิดตัวโปเกมอนพร้อมกัน
- 📱 **Responsive Design**: ใช้งานได้สะดวกทั้งบนคอมพิวเตอร์ แท็บเล็ต และสมาร์ตโฟน

## 🚀 วิธีการใช้งาน (Getting Started)

1. เปิดไฟล์ `index.html` หรือเปิดผ่านเว็บโฮสติ้ง (เช่น GitHub Pages)
2. คัดลอกลิงก์ห้องที่มี `?room=...` ส่งให้เพื่อน
3. กดที่นั่งที่ว่างเพื่อใส่ชื่อและเลือกรูปโปรไฟล์
4. เริ่มประมูลโปเกมอนแบบเรียลไทม์ไปด้วยกัน!
