# 💎 Extreme-Diamond-Challenge  - Minecraft Plugin

> **Minecraft plugin ที่ผสมผสานระบบเกมเพลย์ที่ท้าทายเข้ากับความสนุกของ TikTok live streaming**

[![Minecraft](https://img.shields.io/badge/Minecraft-1.20.1-brightgreen.svg)](https://www.minecraft.net/)
[![Java](https://img.shields.io/badge/Java-17+-blue.svg)](https://openjdk.java.net/)
[![Kotlin](https://img.shields.io/badge/Kotlin-2.2.0-purple.svg)](https://kotlinlang.org/)
[![Paper](https://img.shields.io/badge/Paper-API-orange.svg)](https://papermc.io/)

## 📖 เกี่ยวกับโปรเจค

**DiamondxTiktok** เป็น Minecraft plugin ที่ออกแบบมาเพื่อสร้างประสบการณ์การเล่นที่ท้าทายและสนุก โดยผสมผสานระบบการติดตามเพชร การขุดแบบพิเศษ และการแสดงผลแบบเรียลไทม์ผ่านเว็บอินเตอร์เฟส เหมาะสำหรับเซิร์ฟเวอร์ที่ต้องการเพิ่มความน่าสนใจให้กับการเล่น Minecraft

### ✨ ฟีเจอร์หลัก

#### 🎯 **ระบบติดตามเพชร**

- **Diamond Goal System**: ตั้งเป้าหมายจำนวนเพชรที่ต้องเก็บ
- **Countdown Timer**: นับถอยหลังเมื่อถึงเป้าหมาย
- **Real-time Tracking**: ติดตามจำนวนเพชรแบบเรียลไทม์
- **Victory Celebration**: ฉลองเมื่อบรรลุเป้าหมาย

#### ⛏️ **Power Dig System**

- **3x3 Mining**: ขุดได้ครั้งละ 3x3 บล็อก
- **Smart Drop Logic**: เพชรดรอปได้ปกติ แต่บล็อกอื่นๆ หายไป
- **Pickaxe-specific Rules**: กติกาต่างกันตามประเภทของ pickaxe
- **Treasure Effects**: เสียงและอนุภาคพิเศษเมื่อขุดพบเพชร

#### 🌐 **Web Overlay System**

- **Real-time Display**: แสดงจำนวนเพชรและเป้าหมายผ่านเว็บ
- **Live Dashboard**: ดูสถิติผู้เล่นแบบเรียลไทม์
- **Customizable UI**: อินเตอร์เฟสที่ปรับแต่งได้
- **Multi-client Support**: รองรับการเชื่อมต่อหลายเครื่องพร้อมกัน

#### 🎪 **Portal Effects**

- **Teleport Effects**: เอฟเฟคพิเศษเมื่อวาร์ป
- **Particle System**: อนุภาคและเสียงที่สมจริง
- **Atmospheric Sounds**: เสียงบรรยากาศที่เพิ่ม immersion

#### 🔧 **Management Commands**

- `/ttdiamond start` - เริ่มเกม
- `/ttdiamond stop` - หยุดเกม
- `/ttdiamond setgoal <amount>` - ตั้งเป้าหมายเพชร
- `/ttdiamond randomtp` - วาร์ปแบบสุ่มพร้อมเอฟเฟค

## 🚀 การติดตั้ง

### 📋 ข้อกำหนดระบบ

- **Minecraft Version**: 1.20.1
- **Java Version**: 17 หรือสูงกว่า
- **Server Software**: PaperMC หรือ Spigot

### 📦 การติดตั้ง Plugin

1. **ติดตั้ง Plugin**

   - คัดลอกไฟล์ `target/diamonxtiktok-{version}.jar`
   - วางในโฟลเดอร์ `plugins/` ของเซิร์ฟเวอร์
   - รีสตาร์ทเซิร์ฟเวอร์

2. **ตั้งค่า Plugin**
   - แก้ไขไฟล์ `config.yml` ตามต้องการ
   - ตั้งค่าเป้าหมายและพารามิเตอร์ต่างๆ

## 🎮 วิธีการเล่น

### เริ่มต้นเกม

```bash
/ttdiamond start
```

### ตั้งเป้าหมาย

```bash
/ttdiamond setgoal 100
```

### วาร์ปแบบสุ่ม

```bash
/ttdiamond randomtp
```

### ดู Web Overlay

- เปิดเบราว์เซอร์ไปที่ `http://localhost:3001/overlay.html` หรือ `http://localhost:3001/`

## 🙏 Credits

- **PaperMC Team** - สำหรับ Paper API ที่ยอดเยี่ยม
- **Minecraft Community** - สำหรับแรงบันดาลใจและการสนับสนุน

## 📞 ติดต่อ

**Project Link**: [https://github.com/yourusername/DiamondxTiktok](https://github.com/COOLKRIS-CYBER/DiamondxTiktok )

**Discord**: [Join our Discord](https://discord.gg/ZzvsnEDu)

---

⭐ **If you like this project, please give it a star!**


