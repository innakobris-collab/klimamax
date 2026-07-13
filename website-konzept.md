# Website-Konzept — Klima-Fachbetrieb NRW (для сборки сайта в другом чате)

Дата: 2026-07-13.
> **Читающему это чату:** это контент/структура/копирайт/функционал для лендинг-сайта климафирмы (NRW, Германия). **ДИЗАЙН НЕ ВКЛЮЧЁН намеренно** — визуал делает отдельно человек-дизайнер, стиль = **luxury / премиум**. Твоя задача — реализовать структуру, тексты (немецкие готовы ниже), функционал и SEO, НЕ навязывать свой дизайн-язык. Опции для тебя помечены «[ОПЦИЯ]».

---

## 0. Цель и вводные
- **Цель сайта:** лидген (заявки/звонки), НЕ визитка. Главная метрика — заявка (Anfrage) / звонок / WhatsApp.
- **Регион:** NRW (Köln, Düsseldorf, Essen, Dortmund…). Язык: **немецкий**.
- **Два трека аудитории:** B2C (частники, горячий поиск) + **B2B** (серверные/Praxis/Hausverwaltung — приоритет).
- **Позиционирование:** премиум/сервис, не дёшево. Тон: экспертный, спокойный, точный (немецкий B2B стиль). Слоган: **„Kühlen. Heizen. Sicher betreut."**
- **Стек:** [ОПЦИЯ] на усмотрение — рекомендация Next.js/Astro (быстро, SEO). Требование: быстрый, mobile-first, чистый HTML для SEO.

---

## 1. Sitemap (структура)
1. **Startseite** (главная)
2. **Leistungen** (услуги) — с под-разделами:
   - Klimaanlagen für Unternehmen (B2B)
   - Serverraum- & Technikkühlung
   - Klimaanlagen für Praxen & Büros
   - Klimaanlagen für Zuhause (B2C)
   - Wartung & Service / Notdienst
3. **Ablauf** (как проходит проект)
4. **Über uns** (о компании / Meisterbetrieb / сертификаты)
5. **Referenzen** (кейсы/отзывы)
6. **Ratgeber/FAQ** (SEO-контент: ASR, TA Lärm, Förderung, Kosten)
7. **Kontakt / Anfrage** (форма + Konfigurator)
8. Юр-страницы (обязательны в DE): **Impressum, Datenschutzerklärung, AGB, Cookie-Banner**

---

## 2. Startseite — секции + готовый копирайт

**Hero:**
- H1: **Klimatechnik für Unternehmen und Zuhause in NRW**
- Sub: **Kühlen. Heizen. Sicher betreut.** Vom Serverraum bis zur Praxis — Beratung, Montage und Wartung aus einer Hand.
- CTA-Buttons: **[Kostenlose Vor-Ort-Analyse]** · **[Anrufen]** · **[WhatsApp]**
- [ОПЦИЯ] под hero: строка доверия — Meisterbetrieb · F-Gas-zertifiziert · 5 Jahre Gewährleistung · ⭐ Google-Bewertung

**Problem/Nutzen блок:**
> Überhitzte Räume kosten Geld: Ausfall von Technik, unzufriedene Kunden, ab 30 °C gesetzliche Pflichten (ASR A3.5). Wir schaffen stabile Temperaturen — wirtschaftlich und rechtssicher.

**Leistungen (карточки):** Unternehmen · Serverraum · Praxis & Büro · Zuhause · Wartung & Notdienst (каждая → своя страница).

**Warum wir (УТП, 5 иконок):**
- Reaktion in 24 h + Sommer-Notdienst
- Rechtssicher: § 62 BauO, TA-Lärm-Nachweis, WEG-Vorlagen
- Alles aus einer Hand — ein Ansprechpartner
- Transparenter Festpreis, drei Varianten
- Meisterbetrieb, 5 Jahre Gewährleistung

**Ablauf (6 шагов):** Erstgespräch → Vor-Ort-Termin → Angebot → Montage → Abnahme → Wartung.

**Referenzen/Trust:** отзывы, лого клиентов, счётчик установок [Platzhalter].

**CTA-Sektion:** **Jetzt kostenlose Vor-Ort-Analyse vereinbalten** + форма/телефон.

---

## 3. Ключевой функционал (лидген)
- **[ОПЦИЯ] Konfigurator / Schnellrechner** — 3-5 полей (Raumtyp, Fläche m², Anzahl Räume, Nutzung Büro/Server/Praxis, Ort) → ориентировочный диапазон + «Angebot anfordern». Быстро (пара минут), необязывающе. Это главный конверсионный элемент (у топ-конкурентов есть).
- **Anfrage-Formular** — минимум полей (Name, Kontakt, Objekttyp, Nachricht) + **чекбокс согласия на обработку данных (DSGVO)** обязателен.
- **Click-to-Call** + **WhatsApp-Button** (mobile) — быстрый контакт.
- **Быстрая реакция** — форма шлёт уведомление владельцу (email/Telegram) для ответа <24ч.
- [ОПЦИЯ] Termin-Buchung (Calendly-подобное) для Vor-Ort-Termin.
- **Google Business Profile** — связать, выводить отзывы.

---

## 4. B2B vs B2C — разделение
- **B2B-раздел** (приоритет): страницы Serverraum-Kühlung, Praxis/Büro, Hausverwaltungen. Упор: риск/непрерывность, ASR, референсы, «ein Ansprechpartner», Wartungsvertrag, Angebot für Gewerbe. Отдельный B2B-CTA.
- **B2C-раздел**: Klimaanlage Zuhause. Упор: комфорт, Festpreis, чистый монтаж, тихо (TA Lärm), гарантия. Konfigurator.

---

## 5. SEO (обязательно — так нас найдут)
- **Локальные ключи (страницы под город):** `Klimaanlage Köln`, `Klimaanlage Düsseldorf`, `Serverraumkühlung NRW`, `Klimaanlage Praxis Köln`, `Klimaanlage Firma/Gewerbe`, `Klimaanlage Wartung NRW`.
- Landing-страницы под город × услугу.
- **Ratgeber/FAQ** статьи (SEO + доверие): «Klimaanlage im Büro — was sagt ASR A3.5?», «Was kostet eine Klimaanlage mit Montage?», «Klimaanlage & Nachbarn: TA Lärm», «Förderung 2026 — wann KfW greift», «Serverraum kühlen — Redundanz & Notdienst».
- Технически: быстрый, mobile-first, schema.org LocalBusiness, alt-тексты, чистые URL.

---

## 6. Контент/тон
- Немецкий, «Sie», экспертный, спокойный. Слова: prüfen, ermitteln, nachvollziehbar, verbindlich, wirtschaftlich sinnvoll, fachgerecht. НЕ: revolutionär, garantiert, хайп.
- НЕ обещать субсидии («Wir prüfen die Förderfähigkeit»).
- Доверие везде: Meisterbetrieb, F-Gas, референсы, 5 лет гарантии.

---

## 7. Обязательные юр-элементы (Германия — не пропускать)
- **Impressum** (§5 DDG/TMG): фирма, адрес, GF, контакт, Handelsregister/USt-IdNr., Handwerkskammer/Innung.
- **Datenschutzerklärung** (DSGVO) — вкл. формы, cookies, аналитику.
- **Cookie-Consent-Banner** (opt-in для не-необходимых cookies).
- **AGB** (опц., но желательно).
- Формы: чекбокс согласия + ссылка на Datenschutz.

---

## 8. Что НЕ делаем здесь (важно для сборщика)
- **Дизайн/визуал НЕ навязывать** — стиль luxury/премиум задаёт человек-дизайнер отдельно. Дай чистую семантическую структуру + компоненты, которые дизайнер/владелец оформит.
- Не выдумывать референсы/цифры/отзывы — оставить `[Platzhalter]`, заполнит владелец реальными.
- Не вставлять фейковые сертификаты/лого брендов без подтверждения.

---

## 9. Данные компании (заполнить перед публикацией)
`[Firmenname]` (рабочее: GradKlar — проверить юридически) · `[Adresse NRW]` · `[Tel]` · `[E-Mail]` · `[GF]` · `[Handelsregister/USt-IdNr.]` · `[Handwerkskammer-Nr.]` · `[бренды оборудования]` · `[реальные референсы/отзывы]`.

> Контекст проекта — в `../CLAUDE.md` и `../research/`. Позиционирование, УТП, боли клиентов, каналы — там. Продающие тексты/фразы — в `../verkaufs-playbook.md` и `../vertrieb/onepager-b2b.md`.
