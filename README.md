<div align="center">

# 🔥 Free Fire Like Sender API

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=700&size=24&duration=3000&pause=1000&color=F75C03&center=true&vCenter=true&width=700&lines=Free+Fire+Like+Sender+API;Powered+by+MAHENDRA;Fast+%7C+Reliable+%7C+Async;Protobuf+%2B+AES+Encryption" alt="Typing SVG" />

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,20,24&height=120&section=header&text=Free%20Fire%20Like%20API&fontSize=32&fontColor=ffffff&animation=fadeIn" />

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Flask-2.x-000000?style=for-the-badge&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/Protobuf-4.x-4285F4?style=for-the-badge&logo=google&logoColor=white" />
  <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/Maintained-Yes-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Made%20with-%E2%9D%A4%EF%B8%8F%20by%20MAHENDRA%20-red?style=flat-square" />
</p>

</div>

---

<div align="center">

### ⚡ **A Flask-based REST API that sends likes to a Free Fire player's profile using valid access tokens.**

It sends **AES-encrypted protobuf payloads**, parses the response using **Protobuf**, and returns detailed player info — **UID**, **nickname**, **level**, **likes before/after**, **region**, and **daily usage stats**.

</div>

---

## 🚀 Features

<table>
<tr>
<td>

- ✅ Sends **likes** to any Free Fire player by **UID**
- 🌍 **Multi-region support** (IND, BR, US, SAC, NA, BD)
- 📊 **Daily limit tracking** (200 likes/day)
- 🔐 **API key authentication** for secure access
- 🧠 **Token management** by region
- 📦 **Protobuf + AES encryption** for request/response
- ⚡ **Async request handling** with `aiohttp`
- 📈 Returns **likes before**, **likes after**, and **likes given by API**
- ☁️ **Vercel deployment** ready

</td>
</tr>
</table>

---

## 📦 Requirements

<div align="center">

| **Requirement** | **Version** |
|:---------------:|:-----------:|
| 🐍 Python       | **3.8+**    |
| 🌶️ Flask        | **2.x**     |
| 🔗 aiohttp      | **Latest**  |
| 📦 protobuf     | **Latest**  |
| 🔐 pycryptodome | **Latest**  |
| 🌐 requests     | **Latest**  |

</div>

```bash
pip install flask aiohttp requests protobuf pycryptodome
