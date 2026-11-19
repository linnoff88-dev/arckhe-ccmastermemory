# ðŸ§  CC Master Memory

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


> Curso completo e profundo sobre **injeÃ§Ã£o de memÃ³ria em Claude Code via hooks**.
> Formato **INEMA.CLUB** â€” HTML puro, dark/light, sem build.

---

## O que vocÃª vai aprender

Dominar a memÃ³ria do Claude Code Ã© dominar a sua produtividade. Este curso vai do **problema** (por que Claude esquece) atÃ© o **sistema completo** (hooks + camadas + backends), passando por todas as decisÃµes de design que vocÃª precisa tomar.

### A grande ideia

- **CLAUDE.md Ã© sugestivo** â†’ acerta 7 em 10 vezes.
- **Hooks sÃ£o determinÃ­sticos** â†’ acerta 10 em 10.

O curso prova isso com experimentos reproduzÃ­veis e ensina vocÃª a construir seu prÃ³prio sistema de memÃ³ria sob medida.

---

## Trilhas

| # | Trilha | Cor | Foco |
|---|--------|-----|------|
| **T1** | Por que memÃ³ria importa | ðŸŸ¢ Emerald | Fundamento + problema |
| **T2** | Os 7 nÃ­veis de memÃ³ria | ðŸ”µ Blue | Modelo mental em camadas |
| **T3** | Anatomia dos 18 hooks | ðŸŸ£ Purple | Ferramental completo |
| **T4** | Os 3 hooks crÃ­ticos | ðŸŸ¡ Amber | SessionStart, PreCompact, UserPromptSubmit |
| **T5** | Arquitetura e backends | ðŸŸ¢ Teal | Camadas, formatos, paradigmas |
| **T6** | Projeto prÃ¡tico + integraÃ§Ãµes | ðŸ”´ Rose | Construir seu sistema + Gemini/multi-agent |

**Total:** 6 trilhas Â· 36 mÃ³dulos Â· ~24h de conteÃºdo

---

## Como usar

### OpÃ§Ã£o 1 â€” Online (GitHub Pages)

Acesse direto o `index.html` hospedado.

### OpÃ§Ã£o 2 â€” Local

```bash
git clone https://github.com/inematds/ccmastermemory.git
cd ccmastermemory
# Abrir index.html no navegador (Chrome, Firefox, Edge)
xdg-open index.html   # Linux
open index.html       # macOS
start index.html      # Windows
```

NÃ£o precisa de servidor, build ou dependÃªncias. Ã‰ HTML + Tailwind CDN.

---

## Estrutura

```
ccmastermemory/
â”œâ”€â”€ index.html                     # Landing do curso
â”œâ”€â”€ curso/
â”‚   â”œâ”€â”€ trilha1/ ... trilha6/     # Trilhas com index + mÃ³dulos
â”œâ”€â”€ labs/                          # CÃ³digo dos experimentos
â”‚   â”œâ”€â”€ palavra-codigo/            # Lab CLAUDE.md vs hook
â”‚   â”œâ”€â”€ prime-md/                  # Template de identidade
â”‚   â”œâ”€â”€ context-md/                # Template de contexto crÃ­tico
â”‚   â”œâ”€â”€ promote-py/                # Script de promoÃ§Ã£o 3-strikes
â”‚   â”œâ”€â”€ decay-py/                  # Script de decay
â”‚   â””â”€â”€ gemini-summary/            # SessionEnd â†’ Gemini Flash
â”œâ”€â”€ exemplos-hooks/                # settings.json de referÃªncia
â””â”€â”€ docs/                          # DocumentaÃ§Ã£o complementar
```

---

## PrÃ©-requisitos

- **Claude Code** instalado (`npm install -g @anthropic-ai/claude-code`)
- Editor de texto (VS Code recomendado)
- Terminal com `bash` ou `zsh`
- Para Trilha 6: Python 3.10+ e (opcional) chave Gemini API

---

## Material-fonte

- VÃ­deo: [Master ALL 7 Levels of Claude Code Memory](https://www.youtube.com/watch?v=OMkdlwZxSt8)
- Skill: `memory-architect` (derivada)
- Docs oficiais: https://docs.claude.com/en/docs/claude-code

---

## LicenÃ§a

ConteÃºdo didÃ¡tico de uso livre para estudo pessoal e institucional.
ContribuiÃ§Ãµes e correÃ§Ãµes: abra uma issue ou PR.

**INEMA.CLUB** Â· 2026

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>