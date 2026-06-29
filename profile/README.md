<div align="center">

# VELAR

### Trazabilidad pública y verificable de bonos políticos sobre Stellar

*Infraestructura abierta para tokenizar, validar y auditar la propiedad de bonos
políticos — un registro inmutable, público y verificable por cualquier ciudadano.*

[![Stellar](https://img.shields.io/badge/Built_on-Stellar-black?logo=stellar)](https://stellar.org)
[![Soroban](https://img.shields.io/badge/Smart_Contracts-Soroban-blue)](https://soroban.stellar.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

</div>

---

## ¿Qué es VELAR?

En Costa Rica, los **bonos políticos** (deuda que el Estado reconoce a los partidos
por sus gastos de campaña) se negocian hoy con poca trazabilidad. VELAR los lleva a
la blockchain de **Stellar**: cada emisión, asignación, transferencia y validación
queda registrada on-chain de forma **inmutable y auditable**, y cualquier persona
puede verificar el historial completo de un bono **sin cuenta y sin saber de blockchain**.

## Cómo funciona

| Pieza | Descripción |
|---|---|
| 🪙 **Token real en Stellar** | Cada bono es un activo on-chain (Classic Asset + contrato Soroban `VelarBond`). |
| 🔒 **Escrow on-chain** | Compra/venta coordinada vía Trustless Work (Stellar testnet). |
| 🏛️ **Tres roles** | TSE (emisor/auditor), Partido (tenedor), Ciudadano (verificador). |
| 🔎 **Verificación pública** | `/verificar` y explorer público con enlaces directos al ledger de Stellar. |
| 🌎 **Multi-país** | Arquitectura lista para LATAM (Costa Rica 100%; CO/BR/AR en roadmap). |

## Repositorios

| Repo | Qué contiene |
|---|---|
| [**Velar**](https://github.com/Velar-Bonds/Velar) | Monorepo principal: API (NestJS) + Web (Next.js) + contrato Soroban + esquema Supabase. |
| [**velar-docs**](https://github.com/Velar-Bonds/velar-docs) | Documentación: arquitectura, API, modelo de roles y niveles Web3. |

## Stack

`Stellar` · `Soroban (Rust)` · `Trustless Work` · `NestJS` · `Next.js` · `TypeScript` · `Supabase/Postgres`

---

<div align="center">
<sub>Construido para transparencia institucional · Hackathon PULSO · Stellar</sub>
</div>
