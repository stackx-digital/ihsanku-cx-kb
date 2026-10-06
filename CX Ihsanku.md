---
title: CX Ihsanku — Customer Experience Chatbot
type: hub
tags: [ihsanku, cx, chatbot, customer-experience]
created: 2026-09-30
---

# CX Ihsanku — Customer Experience Chatbot

> Knowledge Base & konfigurasi untuk Ihsanku CX chatbot
> Hermes Profile: `ihsanku-cx`
> Model: `qwen3.5:9b` (Ollama)

## Pautan Utama

- [[SOUL — Identiti Ihsan|Identiti & Persona (SOUL)]]
- [[SKILL — Ihsanku CX Skill|Skill Definition]]
- [[Chatbot — Profile Template|Profile Template (10 seksyen)]]
- [[Knowledge Base Index|KB Index]]

## Knowledge Base

- [[ORG-001 — Organisasi Ihsanku|Maklumat Organisasi]]
- [[KMPN-GAZA-AQSA-001 — Bantuan Kecemasan Misi Al-Aqsa]]
- [[KMPN-GAZA-KLINIK-002 — Klinik & Rawatan Anak Gaza]]
- [[KMPN-GAZA-SEKOLAH-003 — Bina Sekolah Gaza]]
- [[KMPN-GAZA-AIR-004 — Air Bersih Gaza]]
- [[KMPN-PALESTIN-IHSAN-007 — Ihsan Palestin]]
- [[KMPN-SABAH-SURAU-005 — Surau Kampung Silungai]]
- [[KMPN-SABAH-MTDI-008 — Maahad Tahfiz Darul Isnad]]
- [[KMPN-SABAH-BACALAH-009 — Projek Bacalah]]
- [[KMPN-SABAH-AIR-KG-HUJUNG-010 — Air Bersih Kg Hujung]]
- [[KMPN-PATANI-RUMAH-PADI-006 — Rumah Padi Anak Yatim]]

## Kempen Aktif (10)

| Kempen | Lokasi | Kategori | Target | Link |
|--------|--------|----------|--------|------|
| [[KMPN-GAZA-AQSA-001 — Bantuan Kecemasan Misi Al-Aqsa|Al-Aqsa]] | Gaza | Kecemasan | [isi] | [link](https://www.ihsanku.org/campaign/bantuan-kecemasan-aqsa/) |
| [[KMPN-GAZA-KLINIK-002 — Klinik & Rawatan Anak Gaza|Klinik Gaza]] | Gaza | Perubatan | [isi] | [link](https://www.ihsanku.org/campaign/klinik-anak-gaza/) |
| [[KMPN-GAZA-SEKOLAH-003 — Bina Sekolah Gaza|Sekolah Gaza]] | Gaza | Pendidikan | [isi] | [link](https://www.ihsanku.org/campaign/bina-sekolah-gaza/) |
| [[KMPN-GAZA-AIR-004 — Air Bersih Gaza|Air Gaza]] | Gaza | Air | RM250K | [link](https://www.ihsanku.org/campaign/air-bersih-gaza/) |
| [[KMPN-PALESTIN-IHSAN-007 — Ihsan Palestin|Ihsan Palestin]] | Gaza | Kecemasan | [isi] | [link](https://sumbang.ihsanku.org/order/form/crm-ihsanpalestin) |
| [[KMPN-SABAH-SURAU-005 — Surau Kampung Silungai|Surau Silungai]] | Sabah | Wakaf | [isi] | [link](https://www.ihsanku.org/campaign/surau-kg-silungai/) |
| [[KMPN-SABAH-MTDI-008 — Maahad Tahfiz Darul Isnad|MTDI]] | Sabah | Pendidikan | RM50K | [link](https://sumbang.ihsanku.org/order/form/crm-ihsanjariahmtdi) |
| [[KMPN-SABAH-BACALAH-009 — Projek Bacalah|Bacalah]] | Sabah | Pendidikan | RM20K | [link](https://sumbang.ihsanku.org/order/form/crm-projekbacalah) |
| [[KMPN-SABAH-AIR-KG-HUJUNG-010 — Air Bersih Kg Hujung|Air Kg Hujung]] | Sabah | Wakaf | RM200K | [link](https://sumbang.ihsanku.org/order/form/crm-infaqairkghujung) |
| [[KMPN-PATANI-RUMAH-PADI-006 — Rumah Padi Anak Yatim|Rumah Padi]] | Patani | Yatim | RM150K | [link](https://www.ihsanku.org/campaign/rumah-padi/) |

## Cara Update KB

1. Kempen baru → copy file [[KMPN-PATANI-RUMAH-PADI-006 — Rumah Padi Anak Yatim]] sebagai template → isi maklumat → save → update [[Knowledge Base Index|INDEX]]
2. Kempen tamat → tukar Status: TAMAT → jangan delete
3. Maklumat berubah → edit file kempen → update INDEX jika perlu

## Sync ke Hermes Profile

Selepas edit di Obsidian, copy ke Hermes:

```bash
# Sync KB
cp /Users/im/Obsidian/cx-ihsanku/kb/*.md \
   /Users/im/.hermes/profiles/ihsanku-cx/workspace/ihsanku-cx-kb/

# Sync Skill
cp /Users/im/Obsidian/cx-ihsanku/skill/SKILL.md \
   /Users/im/.hermes/profiles/ihsanku-cx/skills/ihsanku-cx/

# Sync SOUL
cp /Users/im/Obsidian/cx-ihsanku/profile/SOUL.md \
   /Users/im/.hermes/profiles/ihsanku-cx/
```

## Yang Perlu Confirm Dengan Ihsanku

- [ ] 3 kempen tak ada reference bank code (Sekolah Gaza, Air Gaza, Surau Sabah)
- [ ] 4 kempen tak ada target sumbangan
- [ ] Tarikh mula/tutup untuk kebanyakan kempen
- [ ] Status pelaksanaan terkini

Lihat checklist penuh di [[Knowledge Base Index|INDEX]].