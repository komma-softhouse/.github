<div align="center">

<img src="https://avatars.githubusercontent.com/u/292441092?s=200&v=4" alt="Komma SoftHouse" width="120" height="120" />

# Komma SoftHouse

**We build multi-tenant SaaS — clean architecture, production-ready, made in Galicia.**

[![Laravel](https://img.shields.io/badge/Laravel-13-FF2D20?style=flat-square&logo=laravel&logoColor=white)](https://laravel.com/docs/13.x)
[![PHP](https://img.shields.io/badge/PHP-8.4-777BB4?style=flat-square&logo=php&logoColor=white)](https://www.php.net)
[![Filament](https://img.shields.io/badge/Filament-v5-F59E0B?style=flat-square&logo=laravel&logoColor=white)](https://filamentphp.com/docs)
[![Livewire](https://img.shields.io/badge/Livewire-v4-FB70A9?style=flat-square&logo=livewire&logoColor=white)](https://livewire.laravel.com)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![Docker](https://img.shields.io/badge/Docker_Swarm-Spin_Pro-2496ED?style=flat-square&logo=docker&logoColor=white)](https://serversideup.net/open-source/spin/)

</div>

---

## About

Komma SoftHouse is a software studio focused on **building and shipping multi-tenant SaaS products**. We design systems that scale per tenant from day one — isolated databases, wallets, entitlements, payments and billing — without reinventing the foundations for every new product.

Everything we ship runs on a modern, opinionated Laravel + Filament stack and is deployed as containerized services on Docker Swarm.

## What we do

- **Multi-tenant SaaS** — database-per-tenant isolation, per-tenant configuration and feature flags.
- **Payments & billing** — integrations with Redsys (incl. Bizum), Revolut, Paycomet and manual flows, with idempotent processing and encrypted credentials.
- **Wallets & loyalty** — dual-layer wallet systems for credits, coins and cashback.
- **Admin panels** — fast, polished back-offices built on FilamentPHP v5.
- **Deployment** — reproducible, containerized infrastructure with Spin Pro and Docker Swarm.

## Tech stack

| Layer        | Technology                   |
| ------------ | ---------------------------- |
| Framework    | Laravel 13                   |
| Language     | PHP 8.4                      |
| Admin / UI   | FilamentPHP v5 · Livewire v4 |
| Styling      | Tailwind CSS v4              |
| Multitenancy | DB-per-tenant architecture   |
| Deployment   | Spin Pro · Docker Swarm      |

## Komma — Core

Our products are built on **Komma**, an internal multi-tenant SaaS starter-kit that bundles the parts every SaaS needs out of the box:

- 🏢 **Multi-tenancy** — isolated database per tenant.
- 💳 **Payment providers** — Redsys (with Bizum), Revolut, Paycomet and manual adapters behind a unified gateway with automatic failover.
- 🪙 **Wallets** — dual-layer wallet (central credit + per-tenant coin).
- 🔐 **Entitlements** — modules, grants, permissions and feature flags.
- 🎁 **Discounts & referrals** — built-in promotions and user referral system.

## Fiscal compliance & e-invoicing

Built-in compliance with Spanish and Basque tax regulations — invoicing, registry submission and time-tracking, ready for production.

<div align="center">

[![Veri*factu](https://img.shields.io/badge/Veri*factu-AEAT-E30613?style=for-the-badge&logoColor=white)](https://sede.agenciatributaria.gob.es)
[![TicketBAI](https://img.shields.io/badge/TicketBAI-Euskadi-009639?style=for-the-badge&logoColor=white)](https://www.euskadi.eus/ticketbai/)
[![FACe](https://img.shields.io/badge/FACe-Facturae_3.2.2-005BBB?style=for-the-badge&logoColor=white)](https://face.gob.es)
[![Registro de Jornada](https://img.shields.io/badge/Control_Horario-Registro_de_Jornada-6E40C9?style=for-the-badge&logoColor=white)](#)

</div>

| Module                | Standard                              | What it covers                                                                                                    |
| --------------------- | ------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| 🧾 **Veri\*factu**     | AEAT — RD 1007/2023                   | Anti-fraud invoicing records, QR on invoice, real AEAT SOAP client with mTLS (P12), async submission with retries |
| 🟢 **TicketBAI**       | Hacienda Foral (País Vasco / Navarra) | Signed invoice chaining and fiscal XML for Basque tax authorities                                                 |
| 🏛️ **FACe**            | Facturae 3.2.2 (`.xsig`)              | Electronic invoices to public administrations, XAdES signature, FACe submission & status                          |
| ⏱️ **Control Horario** | Registro de Jornada (RDL 8/2019)      | Employee time-tracking with RFID, exportable records for labor compliance                                         |

## Connect

[![Instagram](https://img.shields.io/badge/Instagram-@kommasofthouse-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/kommasofthouse)
[![Email](https://img.shields.io/badge/Email-info@kommasofthouse.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:info@kommasofthouse.com)
[![Location](https://img.shields.io/badge/Made_in-Galicia,_Spain-007A33?style=flat-square)](https://github.com/Komma-SoftHouse)

<div align="center">
<sub>© Komma SoftHouse · Crafted with Laravel & Filament in Spain 🇪🇸</sub>
</div>
