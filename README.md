# 🧩 OLT Templates — Templates Iniciais para Zabbix v7

> Este repositório reúne **Templates Zabbix v6 v7 (XML)** para **OLTs GPON/EPON**, com **OIDs SNMP, MIBs e LLD** por fabricante/modelo.  
> Palavras-chave: **zabbix template**, **olt gpon**, **olt epon**, **snmp**, **mib**, **oid**, **lld**, **intelbras**, **zte**, **fiberhome**, **huawei**, **v-solution**, **nokia**.
> zabbix 6, zabbix 7, zabbix template olt, template zabbix gpon, template zabbix epon,  
> snmp oid mib olt, low-level discovery, lld zabbix,  
> nokia isam fx r5.7 r6.2, zte c320 c600 c610, think tk-80 v2 tk7000, c-data fd1104s fd1108s,  
> datacom dm4615 16gpon, v-solution v1600d v1600a v1600b v1600g0 v1600g1 v1600gs, vsol,  
> intelbras 4840e 8820g 8820i cassette g16, huawei ma5608t ma5680t, fiberhome an5516 an6000,  
> bdcom fnl4000 p3310d, parks fiberlink 30024 30028, ubnt edgeos olt, hsgq g008, tenda tes7008, phyhome fhl2100

Gere **templates iniciais para Zabbix** e **agilize o desenvolvimento** do seu monitoramento.  
Compatível com **Intelbras, Nokia, Huawei, ZTE, V-Solution** e outras — ideal para **desenvolvedores criarem soluções personalizadas**.

🌐 **Acesse agora:** https://www.olt-templates.com

---

## 🎯 O que é o OLT Templates?

O **OLT Templates** oferece **modelos base** (XML) para Zabbix que servem como **ponto de partida**.  
Você economiza tempo para iniciar o SNMP de **OLTs GPON/EPON** sem precisar criar cada item ou trigger manualmente.

> **Importante:** Estes templates são gerados com auxílio de **IA** e entregues como **base inicial de desenvolvimento**.  
> Não são prontos para uso imediato em produção — é necessário **ajustar e personalizar** conforme o seu ambiente Zabbix.

---

## 🔌 OIDs Marcas e modelos disponíveis

A tabela a seguir mostra os **prefixos SNMP (OIDs base)** usados em cada template e seus respectivos modelos:

| Fabricante / Tipo | Padrão OID base | Modelos Relacionados |
|-------------------|-----------------|----------------------|
| **BDCOM (OLT-EPON)** | `.1.3.6.1.4.1.3320.x.x.x.x.x` | FNL4000-BD / P3310D |
| **C-DATA (OLT-EPON)** | `1.3.6.1.4.1.34592.x.x.x.x.x.x` | FD1104S / FD1108S |
| **CHIMA (OLT-GPON)** | `.1.3.6.1.4.1.13464.x.x.x.x.x.x.x.x` | CASSETTE V100R001B01D002P002SP1-WEB2.0 |
| **CIANET (OLT-GPON)** | `1.3.6.1.4.1.17409.x.x.x.x.x.x` | OLT-01MF / G8PS |
| **DIGISTAR (OLT-GPON)** | `.1.3.6.1.4.1.29450.x.x.x.x.x.x.x` | ESW 2.6.35.14-svn57811 |
| **DM4615 (OLT-GPON)** | `.1.3.6.1.4.1.3709.x.x.x.x.x.x` | DM4615 16GPON+4GT+4XS<br>Compatível com versões:<br>8.2.4-003-2-ge1a0e29dad<br>7.2.0-013-1-g1b8f1c9398<br>9.0.0-345-1-g479ba56c8a |
| **V-SOLUTION (OLT-EPON)** | `1.3.6.1.4.1.37950.x.x.x.x.x.x` | V1600D / MINI |
| **V-SOLUTION (OLT-EPON)** | `1.3.6.1.4.1.37950.x.x.x.x.x.x` | V1600A / V1600B OLT-0.3 e Software Version = OLT-1.5.28s |
| **V-SOLUTION (OLT-GPON)** | `1.3.6.1.4.1.37950.x.x.x.x.x.x` | V1600G0 / V1600G1 / V1600GS / G0B / G1B |
| **SROROLINE (OLT-GPON)** | `1.3.6.1.4.1.37950.x.x.x.x.x.x` | SH-RG8608-G8 |
| **OVERTEK (OLT-EPON)** | `.1.3.6.1.4.1.34592.x.x.x.x.x.x` | OLT-8110 |
| **OVERTEK (OLT-GPON)** | `1.3.6.1.4.1.3320.x.x.x.x.x.x` | OT-8835-GP / OT-8836-GP |
| **HIOSO (OLT-EPON)** | `1.3.6.1.4.1.25355.x.x.x.x.x.x` | HA7004T V2.2.57 |
| **THINK (OLT-EPON)** | `.1.3.6.1.4.1.25355.x.x.x.x.x.x.x` | v7.58 / HA7000 / TK7000 |
| **THINK (OLT-GPON)** | `1.3.6.1.4.1.17409.x.x.x.x.x.x` | TK-80 V2 |
| **UBIQUITI (OLT-GPON)** | `1.3.6.1.4.1.41112.x.x.x.x.x.x` | EdgeOS 4.8.0 |
| **PARKS (OLT-GPON)** | `1.3.6.1.4.1.6771.x.x.x.x.x.x` | Fiberlink 30024 / 30028 |
| **PHYHOME (OLT-EPON)** | `.1.3.6.1.4.1.17409.x.x.x.x.x.x` | LE4-NEXT / FHL104C / FH22B1800008 |
| **PHYHOME (OLT-GPON)** | `.1.3.6.1.4.1.13464.x.x.x.x.x.x` | CASSETTE OLT V100R001B01D002P009 |
| **HSGQ (OLT-EPON)** | `1.3.6.1.4.1.50224.x.x.x.x.x.x` | HSGQ-E04L G008 |
| **HSGQ (OLT-GPON)** | `.1.3.6.1.4.1.50224.x.x.x.x.x` | G008 NEUTRAL |
| **FiberHome (OLT-GPON)** | `1.3.6.1.4.1.5875.x.x.x.x.x.x` | AN5516 / AN6000 |
| **Huawei (OLT-GPON)** | `1.3.6.1.4.1.2011.x.x.x.x.x.x` | MA5608T / MA5680T |
| **Nokia (OLT-GPON)** | `1.3.6.1.4.1.637.x.x.x.x.x.x` | ISAM FX Series (R5.7 / R6.2) |
| **Intelbras (OLT-EPON)** | `.1.3.6.1.4.1.13464.x.x.x.x.x.x` | OLT 4840E V4.0 / EPON OLT 4840E V5.0 |
| **Intelbras (OLT-GPON)** | `.1.3.6.1.4.1.26138.x.x.x.x.x.x` | RR-Tech 8820i / 8820g / olt8820plus |
| **Intelbras (OLT-GPON)** | `.1.3.6.1.4.1.13464.x.x.x.x.x.x.x.x` | CASSETTE G16 |
| **TENDA (OLT-GPON)** | `1.3.6.1.4.1.17409.x.x.x.x.x.x` | TES7008 |
| **ZTE (OLT-GPON)** | `.1.3.6.1.4.1.3902.x.x.x.x.x.x` | C320 Version V2.1.0 |
| **ZTE (OLT-GPON)** | `.1.3.6.1.4.1.3902.x.x.x.x.x.x.x.x` | C600 / C610 ZXA10 V1.2.2 |

---

## 🔎 Como encontrar por OID/Modelo (GitHub/Google)

Pesquise usando **combinações** de fabricante + OID + Zabbix:

- `C-DATA 1.3.6.1.4.1.34592 zabbix template`
- `V-SOLUTION 1.3.6.1.4.1.37950 GPON Zabbix`
- `Intelbras 1.3.6.1.4.1.26138 olt gpon mib`
- `ZTE C320 1.3.6.1.4.1.3902 zabbix xml`
- `FiberHome AN5516 1.3.6.1.4.1.5875 lld`
- `THINK TK-80 V2 1.3.6.1.4.1.17409 zabbix`

✅ **Observações Importantes**
- Alguns OIDs se repetem entre marcas diferentes (como V-SOLUTION e SROROLINE), mas os **templates são distintos** devido a diferenças internas de MIB.  
- A coluna “Modelos Relacionados” indica os firmwares ou variações validadas em laboratório.  
- Cada OID base é usado como referência de descoberta SNMP para **gerar automaticamente os itens Zabbix**.

---

<details>
<summary>📚 Glossário de termos (para buscadores)</summary>

Zabbix v6 v7 · Template XML · SNMP · MIB · OID · LLD (Low-Level Discovery) · GPON · EPON ·  
Triggers · Value maps · ONUs · PON · RX/TX power · ifOperStatus · discovery[...]
</details>

<details>
<summary>🔎 Buscas populares (ajuda na indexação)</summary>

zabbix 6 template olt gpon  
zabbix 7 template olt epon  
zabbix olt nokia isam fx r6.2  
zabbix template zte c320 oid 1.3.6.1.4.1.3902  
zabbix template vsol v-solution 1.3.6.1.4.1.37950  
zabbix intelbras 8820g oid 1.3.6.1.4.1.26138  
zabbix datacom dm4615 gpon  
zabbix fiberhome an5516 oid 1.3.6.1.4.1.5875  
zabbix huawei ma5608t 1.3.6.1.4.1.2011  
zabbix think tk-80 v2 1.3.6.1.4.1.17409  
zabbix c-data fd series 1.3.6.1.4.1.34592
</details>

📧 **Contato:** comercial@olt-templates.com  
🌐 **Acesse:** https://www.olt-templates.com

<p align="center">
  <a href="https://www.olt-templates.com" target="_blank">
    <img src="https://img.shields.io/badge/Gerar%20Template%20Zabbix-%E2%86%92-6C5CE7?style=for-the-badge" alt="Gerar Template Zabbix">
  </a>
</p>

