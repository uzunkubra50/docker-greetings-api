# 🌍 Dockerize Greetings API

Bu proje, farklı dillerde selamlamalar döndüren, Docker üzerinde çalışan bir **RESTful Mikro Hizmet** uygulamasıdır. IBM Developer Skills Network kapsamında geliştirilmiş ve konteyner teknolojilerinin temellerini uygulamalı olarak deneyimlemek amacıyla hazırlanmıştır.

---

## 🚀 Özellikler

| Özellik | Açıklama |
|---------|----------|
| **Python & Flask** | Hafif ve hızlı bir backend mimarisi |
| **Docker Entegrasyonu** | Tamamen izole konteyner — her ortamda aynı sonuç |
| **Multi-language Support** | 12 farklı dilde selamlama (Türkçe, İngilizce, İspanyolca vb.) |
| **RESTful Endpoint** | `/greetings` üzerinden JSON formatında veri döndürür |

---

## 🛠️ Kullanılan Teknolojiler

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square&logo=python)
![Flask](https://img.shields.io/badge/Flask-Framework-black?style=flat-square&logo=flask)
![Docker](https://img.shields.io/badge/Docker-Container-2496ED?style=flat-square&logo=docker)
![OpenAPI](https://img.shields.io/badge/API-OpenAPI%20%2F%20Swagger-85EA2D?style=flat-square&logo=swagger)

- **Dil:** Python
- **Framework:** Flask
- **Konteynerleştirme:** Docker
- **API Standardı:** OpenAPI (Swagger)

---

## 📦 Kurulum ve Çalıştırma

### 1. İmajı Build Edin
```bash
docker build . -t mynewserver
```

### 2. Konteyneri Başlatın
```bash
docker run -p 8080:8080 mynewserver
```

### 3. API'yi Test Edin

Tarayıcınızdan veya terminalden:
```
http://localhost:8080/greetings
```

cURL ile:
```bash
curl -X GET http://localhost:8080/greetings
```

---

## 🎓 Öğrenim Kazanımları

Bu proje süresince edinilen pratik deneyimler:

- Bir Python uygulamasının `Dockerfile` ile nasıl paketlendiği
- Port eşleştirme (port mapping) mantığı
- Docker konteyner yönetimi — `build`, `run`, `kill`
- OpenAPI standardına uygun RESTful endpoint tasarımı

---

## 👤 Geliştirici

**Kübra Uzun** — [github.com/uzunkubra50](https://github.com/uzunkubra50)  
Bu proje, IBM Developer Skills Network kapsamında konteyner teknolojileri ve mikro hizmet mimarisi pratikleri amacıyla hazırlanmıştır.
