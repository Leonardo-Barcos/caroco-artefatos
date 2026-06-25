# Projeto CAROÇO — Artefatos de Modelagem e Documentação Técnica

**CAROÇO — Coleta, Gestão de Dados e Resíduos do Açaí com Incentivo à Coleta Seletiva**

Aplicativo móvel e Sistema de Informação Geográfica (SIG) para a gestão dos resíduos da cadeia do açaí em **Ananindeua-PA**.

Este repositório reúne os artefatos de concepção, modelagem e documentação técnica produzidos na fase preliminar do projeto. Ele acompanha o resumo expandido submetido ao **XVIII SICTI / XI SIMIT (IFPA)** e serve como material de consulta e referência dos resultados apresentados no trabalho.

**Autores:** Leonardo Jacomini Barcos · Adalberto Cavalcante de Melo · Aldrin Mario da Silva Benjamin
**Instituição:** Instituto Federal do Pará (IFPA) — Campus Ananindeua
**Ano:** 2026

---

## Artefatos

| # | Artefato | Descrição |
|---|----------|-----------|
| 01 | Diagrama de Contexto | Visão geral do sistema, atores e fronteiras do CAROÇO. |
| 02 | Arquitetura do Ecossistema | Visão em camadas: coleta em campo, núcleo tecnológico (API, banco de dados, camada geoespacial, governança) e análise/decisão. |
| 04 | Fluxo de Navegação | Telas e percurso do usuário no aplicativo. |
| 05 | Protótipos / Wireframes | Esboços de interface das principais telas. |
| 06 | Modelo de Dados / DER | Entidades conceituais e relações com o SIG e os módulos analíticos. |
| 07 | Dicionário de Dados | Consolida 37 campos (21 obrigatórios), 8 entidades e 7 domínios controlados. |
| 08 | Fluxo de Integração App–SIG–Relatórios | Percurso do dado, da coleta até mapas e relatórios. |
| 09 | Quadro de Decisão Tecnológica (ADR) | Alternativas avaliadas e arquitetura evolutiva recomendada. |
| 10 | Roadmap de Evolução | Fases de desenvolvimento previstas. |

## Arquitetura tecnológica de referência

Estratégia **evolutiva**, definida no Artefato 09:

1. **Validação** — Google Forms/Sheets ou KoboToolbox/ODK para coleta inicial e validação dos campos.
2. **Consolidação** — aplicativo personalizado em **Flutter** ou **React Native** com API própria.
3. **Integração** — **PostgreSQL/PostGIS** + **QGIS** + módulo analítico com **IA** para mapas, rotas, relatórios e indicadores de mercado.

## Como citar

> BARCOS, L. J.; MELO, A. C. de; BENJAMIN, A. M. da S. **CAROÇO: artefatos de modelagem e documentação técnica.** Ananindeua: IFPA, 2026. Repositório de artefatos. Disponível em: <URL-DO-REPOSITÓRIO>. Acesso em: 24 jun. 2026.

## Licença

Material acadêmico disponibilizado para fins de consulta e referência. Uso recomendado com atribuição aos autores.
