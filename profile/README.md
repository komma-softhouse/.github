<div align="center">

<img src="https://avatars.githubusercontent.com/u/292441092?s=200&v=4" alt="Komma SoftHouse" width="120" height="120" />

# Komma SoftHouse

**Fiscal compliance, time tracking and document certification for Spanish businesses — built on Laravel and Filament, made in Galicia.**

[![Laravel](https://img.shields.io/badge/Laravel-13-FF2D20?style=flat-square&logo=laravel&logoColor=white)](https://laravel.com/docs/13.x)
[![PHP](https://img.shields.io/badge/PHP-8.4-777BB4?style=flat-square&logo=php&logoColor=white)](https://www.php.net)
[![Filament](https://img.shields.io/badge/Filament-v5-F59E0B?style=flat-square&logo=laravel&logoColor=white)](https://filamentphp.com/docs)
[![Livewire](https://img.shields.io/badge/Livewire-v4-FB70A9?style=flat-square&logo=livewire&logoColor=white)](https://livewire.laravel.com)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)

[English](#products) · [Español](#español)

</div>

---

## Products

### 🧾 filament-verifactu — Spanish fiscal compliance for Filament 5

The fiscal engine for any Laravel + Filament application that invoices in
Spain. **All four regimes in one plugin**, behind a single gate:

| Regime | What ships |
| --- | --- |
| **AEAT** (common territory) | VERI\*FACTU and non-Verifactu chained records, hash chain, XAdES signing, tributary QR, queued submission with flow control, homologation battery |
| **TicketBAI** (Araba, Bizkaia, Gipuzkoa) | Signature-chained registration, cancellation, corrective invoices, Zuzendu, per-territory endpoints — and **both chapters of Bizkaia's LROE** (issued and received) |
| **Navarra** | Full document lifecycle and the foral report drafts (F-69, F-50, 349, 715, 759); NaTicket plugs in the day the Orden Foral is published |
| **Public and B2B e-invoicing** | Facturae 3.2.2, FACe and FACeB2B with the complete receiver-side lifecycle |

On top of the fiscal core: the whole document flow (quotes → invoices,
credit notes, SAT repair orders), **the received side of the ledger**
(supplier invoices and expenses, OCR capture, attachment preview), A4 and
thermal printing with a live template designer, a Print Agent for cloud
tills, an on-prem API sidecar for POS/ERP terminals, and tax drafts that
read both sides — 303/347/349, withholding, and a corporate-tax estimate.

230 tests. Six languages. `->expenses()`, `->face()`, `->ocr()` and every
other surface is an explicit opt-in.

**→ [Documentation](https://github.com/komma-softhouse/filament-verifactu-docs)** · [Issues](https://github.com/komma-softhouse/filament-verifactu-docs/issues) · [Discussions](https://github.com/komma-softhouse/filament-verifactu-docs/discussions)

The plugin's source is private. Documentation, issues and discussions live
in the public docs repository; lifetime licence holders get access to the
[source repository](https://github.com/komma-softhouse/filament-verifactu)
and report there.

### ⏱️ Kontime — working-time records (Registro de Jornada)

Employee time tracking built for Spain's RDL 8/2019: RFID clock-in, shift
records that cannot be edited after the fact, and exportable reports for a
labour inspection.

**→ [kontime.kommasofthouse.com](https://kontime.kommasofthouse.com)**

### 🔏 Komma Stamps — document certification on blockchain

Proof of existence and integrity for any document: a hash anchored on
**Arbitrum One** (contract v2), a verifiable certificate, and an eIDAS
roadmap — qualified RFC 3161 timestamps and PAdES-LTV signatures.

**→ [stamps.kommasofthouse.com](https://stamps.kommasofthouse.com)**

## Open-source engines

The fiscal plugin stands on four public engines — the plugin depends on
them through Composer, so they are open by design:

[![verifactu-engine](https://img.shields.io/packagist/v/komma-softhouse/verifactu-engine?style=flat-square&label=verifactu-engine)](https://github.com/komma-softhouse/verifactu-engine)
[![tbai-engine](https://img.shields.io/packagist/v/komma-softhouse/tbai-engine?style=flat-square&label=tbai-engine)](https://github.com/komma-softhouse/tbai-engine)
[![facturae-engine](https://img.shields.io/packagist/v/komma-softhouse/facturae-engine?style=flat-square&label=facturae-engine)](https://github.com/komma-softhouse/facturae-engine)

- **[verifactu-engine](https://github.com/komma-softhouse/verifactu-engine)** — AEAT VERI\*FACTU records, hash chain and SOAP client.
- **[tbai-engine](https://github.com/komma-softhouse/tbai-engine)** — TicketBAI for the three Basque territories, Zuzendu, and Bizkaia's LROE (Batuz), issued and received chapters.
- **[facturae-engine](https://github.com/komma-softhouse/facturae-engine)** — Facturae 3.2.2, XAdES, FACe and FACeB2B.

## Standards we implement

<div align="center">

[![Veri*factu](https://img.shields.io/badge/Veri*factu-AEAT_·_RD_1007/2023-E30613?style=for-the-badge)](https://sede.agenciatributaria.gob.es)
[![TicketBAI](https://img.shields.io/badge/TicketBAI-Araba_·_Bizkaia_·_Gipuzkoa-009639?style=for-the-badge)](https://www.euskadi.eus/ticketbai/)
[![Batuz](https://img.shields.io/badge/Batuz_LROE-Bizkaia_140/240-0B6E4F?style=for-the-badge)](https://www.batuz.eus)
[![Navarra](https://img.shields.io/badge/Hacienda_Foral-Navarra-C8102E?style=for-the-badge)](https://hacienda.navarra.es)
[![FACe](https://img.shields.io/badge/FACe_·_FACeB2B-Facturae_3.2.2-005BBB?style=for-the-badge)](https://face.gob.es)
[![Registro de Jornada](https://img.shields.io/badge/Registro_de_Jornada-RDL_8/2019-6E40C9?style=for-the-badge)](#)

</div>

## Stack

Laravel 13 · PHP 8.4 · FilamentPHP v5 · Livewire v4 · Tailwind CSS v4 ·
containerised on Docker Swarm.

## Connect
 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Komma_SoftHouse-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/komma-softhouse)
[![Instagram](https://img.shields.io/badge/Instagram-@kommasofthouse-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/kommasofthouse)
[![Email](https://img.shields.io/badge/Email-info@kommasofthouse.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:info@kommasofthouse.com)
[![Location](https://img.shields.io/badge/Made_in-Galicia,_Spain-007A33?style=flat-square)](https://github.com/komma-softhouse)
---

## Español

**Cumplimiento fiscal, registro de jornada y certificación documental para empresas españolas — sobre Laravel y Filament, hecho en Galicia.**

### 🧾 filament-verifactu — cumplimiento fiscal español para Filament 5

El motor fiscal para cualquier aplicación Laravel + Filament que facture en
España. **Los cuatro regímenes en un solo plugin**, detrás de una única
puerta:

| Régimen | Qué incluye |
| --- | --- |
| **AEAT** (territorio común) | Registros encadenados VERI\*FACTU y no Verifactu, cadena de huellas, firma XAdES, QR tributario, remisión en cola con control de flujo, batería de homologación |
| **TicketBAI** (Araba, Bizkaia, Gipuzkoa) | Alta encadenada por firma, anulación, rectificativas, Zuzendu, endpoints por territorio — y **los dos capítulos del LROE de Bizkaia** (emitidas y recibidas) |
| **Navarra** | Ciclo documental completo y los borradores forales (F-69, F-50, 349, 715, 759); NaTicket se conecta el día que se publique la Orden Foral |
| **Factura electrónica pública y B2B** | Facturae 3.2.2, FACe y FACeB2B con el ciclo completo del lado receptor |

Sobre el núcleo fiscal: todo el flujo documental (presupuestos →
facturas, abonos, órdenes de reparación SAT), **el lado de las compras**
(facturas de proveedor y gastos, captura por OCR, vista del justificante),
impresión A4 y térmica con diseñador de plantillas en vivo, un agente de
impresión para TPV en la nube, una API on-prem para terminales POS/ERP, y
borradores fiscales que leen ambos lados — 303/347/349, retenciones y una
estimación del Impuesto de Sociedades.

230 tests. Seis idiomas. `->expenses()`, `->face()`, `->ocr()` y cada
superficie es un opt-in explícito.

**→ [Documentación](https://github.com/komma-softhouse/filament-verifactu-docs)** · [Issues](https://github.com/komma-softhouse/filament-verifactu-docs/issues) · [Discusiones](https://github.com/komma-softhouse/filament-verifactu-docs/discussions)

El código del plugin es privado. Documentación, issues y discusiones
viven en el repositorio público de docs; las licencias lifetime tienen
acceso al [repositorio del código](https://github.com/komma-softhouse/filament-verifactu)
y reportan allí.

### ⏱️ Kontime — registro de jornada

Control horario para el RDL 8/2019: fichaje RFID, registros de jornada
que no se pueden editar a posteriori y exportaciones listas para una
inspección de trabajo.

**→ [kontime.kommasofthouse.com](https://kontime.kommasofthouse.com)**

### 🔏 Komma Stamps — certificación documental en blockchain

Prueba de existencia e integridad para cualquier documento: la huella
anclada en **Arbitrum One** (contrato v2), un certificado verificable y una
hoja de ruta eIDAS — sellos de tiempo cualificados RFC 3161 y firmas
PAdES-LTV.

**→ [stamps.kommasofthouse.com](https://stamps.kommasofthouse.com)**

### Motores de código abierto

El plugin fiscal se apoya en cuatro motores públicos — depende de ellos
por Composer, así que son abiertos por diseño y puedes usarlos por separado:
**[verifactu-engine](https://github.com/komma-softhouse/verifactu-engine)**
(registros VERI\*FACTU de la AEAT, cadena de huellas y cliente SOAP),
**[tbai-engine](https://github.com/komma-softhouse/tbai-engine)** (TicketBAI
para los tres territorios, Zuzendu y el LROE de Bizkaia con ambos capítulos),
**[facturae-engine](https://github.com/komma-softhouse/facturae-engine)**
(Facturae 3.2.2, XAdES, FACe y FACeB2B)

<div align="center">
<sub>© Komma SoftHouse · Hecho con Laravel y Filament en Galicia 🇪🇸</sub>
</div>
