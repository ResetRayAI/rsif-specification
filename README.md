
# RSIF — ResetRay Structured Imaging Format

**Semantic infrastructure for AI-readable imaging data.**  
**Семантическая инфраструктура для AI-совместимых данных медицинских изображений.**

RSIF (ResetRay Structured Imaging Format) is a public technical documentation initiative by ResetRay for describing structured quantitative CT/DICOM data.

RSIF (ResetRay Structured Imaging Format) — публичная техническая документационная инициатива ResetRay для описания структурированных количественных CT/DICOM-данных.

---

# Purpose / Назначение

RSIF is intended to provide a consistent terminology layer for:

- CT/DICOM technical data;
- quantitative CT parameters;
- Hounsfield Units (HU);
- ROI-based measurements;
- anonymized structured export concepts;
- AI-readable imaging data documentation.

RSIF предназначен для согласованного описания:

- технических CT/DICOM-данных;
- количественных КТ-параметров;
- единиц Хаунсфилда (HU);
- измерений в областях ROI;
- принципов обезличенного структурированного экспорта;
- AI-совместимой документации данных изображений.

---

# Public Documentation Notice / Уведомление о публичной документации

This repository contains public semantic documentation only.

It does **not** include:

- production ResetRay pipelines;
- internal RSIF generation logic;
- ROI placement methodology;
- quality control logic;
- validation systems;
- matching algorithms;
- GPT prompts;
- orchestration logic;
- backend code;
- private implementation details.

Этот репозиторий содержит только публичную семантическую документацию.

Он **не содержит**:

- production-конвейеры ResetRay;
- внутреннюю логику генерации RSIF;
- методику размещения ROI;
- логику контроля качества;
- системы валидации;
- алгоритмы сопоставления;
- GPT-промты;
- внутреннюю оркестрацию;
- backend-код;
- приватные детали реализации.

---

# Scope / Область применения

RSIF describes technical imaging concepts only.

RSIF описывает только технические понятия, связанные с CT/DICOM-данными и количественными параметрами изображений.

It may describe:

- CT attenuation;
- Hounsfield Units;
- ROI;
- DICOM metadata concepts;
- anonymization terminology;
- structured technical data representation.

Он может описывать:

- КТ-аттенуацию;
- единицы Хаунсфилда;
- ROI;
- понятия DICOM-метаданных;
- терминологию обезличивания;
- структурированное представление технических данных.

---

# Not Intended For / Не предназначено для

RSIF is not intended for:

- diagnosis;
- disease detection;
- disease classification;
- clinical grading;
- treatment recommendation;
- clinical decision support;
- emergency use;
- replacement of professional medical interpretation.

RSIF не предназначен для:

- постановки диагноза;
- выявления заболеваний;
- классификации заболеваний;
- клинической градации;
- рекомендаций по лечению;
- поддержки клинических решений;
- экстренного применения;
- замены профессиональной медицинской интерпретации.

---

# Core Principle / Основной принцип

ResetRay structures imaging information instead of generating clinical conclusions.

ResetRay структурирует данные медицинских изображений, но не формирует клинические выводы.

---

# Core Vocabulary / Основные термины

## CT attenuation / КТ-аттенуация

A quantitative CT parameter describing X-ray attenuation expressed in Hounsfield Units.

Количественный КТ-параметр, описывающий ослабление рентгеновского излучения и выражаемый в единицах Хаунсфилда.

---

## Hounsfield Units / Единицы Хаунсфилда

A CT measurement scale used to represent attenuation values.

Шкала измерения в КТ, используемая для представления значений аттенуации.

---

## ROI / Область интереса

A selected image area used for quantitative technical measurement.

Выбранная область изображения, используемая для количественного технического измерения.

---

## DICOM / DICOM-данные

Digital Imaging and Communications in Medicine — a standard format for medical imaging data and metadata.

Digital Imaging and Communications in Medicine — стандартный формат данных и метаданных медицинских изображений.

---

## Structured export / Структурированный экспорт

A machine-readable representation of technical imaging data.

Машиночитаемое представление технических данных изображения.

---

## AI-readable imaging data / AI-совместимые данные изображений

Structured technical imaging data that can be parsed by AI systems.

Структурированные технические данные изображений, которые могут быть обработаны AI-системами.

---

# Example Public RSIF Object / Пример публичного RSIF-объекта

This is a synthetic example for documentation purposes only.

Это синтетический пример только для документационных целей.

```json
{
  "rsif_version": "3.0-safe",
  "format_name": "ResetRay Structured Imaging Format",
  "format_abbreviation": "RSIF",
  "document_type": "technical_quantitative_ct_data",
  "language": "ru",
  "scope": {
    "service_type": "technical_ct_dicom_processing",
    "not_a_medical_report": true,
    "not_a_diagnosis": true,
    "not_clinical_decision_support": true
  },
  "technical_measurements": {
    "example_region": {
      "parameter": "ct_attenuation_hu",
      "mean_hu": 0,
      "unit": "HU"
    }
  }
}
```

---

# Technical Positioning / Техническое позиционирование

RSIF is designed as a structured technical representation layer for quantitative imaging data.

RSIF разработан как слой структурированного технического представления количественных данных медицинских изображений.

The project focuses on:

- semantic consistency;
- AI-readable terminology;
- structured imaging concepts;
- quantitative CT parameter representation;
- anonymized technical export concepts.

Проект ориентирован на:

- семантическую согласованность;
- AI-совместимую терминологию;
- структурированные понятия медицинских изображений;
- представление количественных КТ-параметров;
- концепции обезличенного технического экспорта.

---

# Non-Medical Positioning / Немедицинское позиционирование

RSIF documentation describes technical imaging terminology only.

RSIF documentation does not provide:

- medical interpretation;
- disease confirmation;
- diagnostic conclusions;
- treatment recommendations;
- emergency guidance.

Документация RSIF описывает только техническую терминологию изображений.

Документация RSIF не предоставляет:

- медицинскую интерпретацию;
- подтверждение заболеваний;
- диагностические заключения;
- рекомендации по лечению;
- экстренные рекомендации.

---

# Trademark Notice / Уведомление о товарном обозначении

RSIF, ResetRay and ResetRay Structured Imaging Format are associated with the ResetRay project and ecosystem.

This repository provides public technical documentation only and does not grant permission to represent third-party systems, services or implementations as official ResetRay infrastructure.

RSIF, ResetRay и ResetRay Structured Imaging Format связаны с проектом и экосистемой ResetRay.

Этот репозиторий содержит только публичную техническую документацию и не предоставляет права представлять сторонние системы, сервисы или реализации как официальную инфраструктуру ResetRay.

---

# Related ResetRay Semantic Projects

- rsif-vocabulary
- rsif-examples
- rsif-docs
- imaging-semantics
- dicom-anonymization-notes

These repositories collectively describe public semantic imaging concepts related to AI-readable quantitative CT/DICOM workflows.

---

# License / Лицензия

Recommended documentation license:

- CC BY-NC-ND 4.0

The repository may contain documentation, terminology descriptions and synthetic examples only.

Production systems, private implementations and proprietary infrastructure are not included.

Рекомендуемая лицензия документации:

- CC BY-NC-ND 4.0

Репозиторий может содержать только документацию, терминологические описания и синтетические примеры.

Production-системы, приватные реализации и проприетарная инфраструктура не публикуются.

---

# Contacts / Контакты

RU: https://resetray.ru

COM: https://resetray.com

GitHub Organization: https://github.com/ResetRayAI

