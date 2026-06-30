<div align="center">

# VELAR

### Trazabilidad pública y verificable de bonos políticos sobre Stellar

*Infraestructura abierta para tokenizar, validar y auditar la propiedad de bonos
políticos — registro inmutable, público y verificable.*

[![Stellar](https://img.shields.io/badge/Built_on-Stellar-7D00FF?logo=stellar&logoColor=white)](https://stellar.org)
[![Soroban](https://img.shields.io/badge/Contracts-Soroban-0284FF)](https://soroban.stellar.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

[**Demo en vivo**](https://velar-web.vercel.app) · [**Documentación**](https://github.com/Velar-Bonds/velar-docs) · [**Contribuir**](./CONTRIBUTING.md)

</div>

---

## Mapa de repositorios

| Repo | Rol |
|------|-----|
| [**Velar**](https://github.com/Velar-Bonds/Velar) | 🚀 **Producto** — API (NestJS) + Web (Next.js) + Supabase |
| [**velar-contracts**](https://github.com/Velar-Bonds/velar-contracts) | ⛓️ Contratos Soroban (`VelarBond`) |
| [**velar-spec**](https://github.com/Velar-Bonds/velar-spec) | 📐 Schemas, estados, contratos entre repos |
| [**velar-docs**](https://github.com/Velar-Bonds/velar-docs) | 📚 Documentación pública |
| [**velar-examples**](https://github.com/Velar-Bonds/velar-examples) | 🧪 Ejemplos curl / integración |
| [**velar-brand**](https://github.com/Velar-Bonds/velar-brand) | 🎨 Marca, pitch, assets |

---

## ¿Qué es VELAR?

En Costa Rica, los **bonos políticos** se negocian con poca trazabilidad pública. VELAR los representa como **tokens en Stellar**: emisión, transferencia, escrow y auditoría quedan registrados on-chain. Cualquier ciudadano puede verificar un bono **sin crear cuenta**.

| Capacidad | Detalle |
|-----------|---------|
| 🪙 Token on-chain | Classic Asset + contrato Soroban por bono |
| 🔒 Escrow | Trustless Work + canasta custodial |
| 💳 Pagos | SINPE, transferencia, **wallet USDC (DvP)** |
| 🏛️ Roles | TSE · Partido · Comprador |
| 🌎 Multi-país | CR producción; CO/BR/AR en roadmap |

---

## Stack

```
Stellar · Soroban (Rust) · Trustless Work · NestJS · Next.js · TypeScript · Supabase
```

---

## Empezar en 60 segundos

```bash
git clone https://github.com/Velar-Bonds/Velar.git && cd Velar
npm install
cp apps/api/.env.example apps/api/.env
cp apps/web/.env.example apps/web/.env.local
npm run dev
```

→ Web `http://localhost:3000` · API `http://localhost:3001/api`

Variables completas: [velar-docs · Environment](https://github.com/Velar-Bonds/velar-docs/blob/main/docs/09-environment.md)

---

## Enlaces

| | |
|---|---|
| 🌐 Demo | [velar-web.vercel.app](https://velar-web.vercel.app) |
| 🔌 API | [velar-api.vercel.app/api/health](https://velar-api.vercel.app/api/health) |
| 🔎 Explorer testnet | [stellar.expert](https://stellar.expert/explorer/testnet) |

---

<div align="center">

**Transparencia institucional · Hackathon PULSO · Stellar**

<br />

[![Org repos](https://img.shields.io/badge/GitHub-Velar--Bonds-181717?logo=github)](https://github.com/Velar-Bonds)

</div>
