# Como usar `/adaptar-profissional`

Com o projeto aberto no Claude Code (VS Code ou terminal), digite:

```
/adaptar-profissional
```

O Claude vai guiar você por todas as etapas automaticamente:

1. **Pergunta os dados** do novo profissional (nome, CREFITO, WhatsApp, Instagram, endereço, especialidade)
2. **Pergunta o caminho** da pasta com os assets do novo profissional
3. **Analisa o projeto** atual e os assets novos
4. **Copia os arquivos** (logo, fotos, stamps, bg) para a raiz
5. **Adapta a paleta de cores** com base na `paleta-de-cores.jpg`
6. **Substitui todos os textos** — nome, contatos, especialidade, bio, FAQ, mapa, meta tags
7. **Verifica resíduos** das cores e textos anteriores
8. **Faz commit e push** com mensagem descritiva

---

## O que você precisa preparar antes de rodar

Uma pasta com os seguintes arquivos (igual ao `exportaveis-eder/`):

| Arquivo | Descrição |
|---|---|
| `logo-[nome].svg` | Logo do profissional |
| `dr-[nome].png` | Foto principal (hero) |
| `bg-hero-[nome].jpg` | Imagem de fundo do hero |
| `quem-sou-eu.jpg` | Foto da seção de perfil |
| `stamp-full.svg` | Selo completo |
| `stamp-iso.svg` | Ícone isolado (vira favicon) |
| `stamp-txt.svg` | Texto do selo animado |
| `paleta-de-cores.jpg` | Referência visual da paleta |

---

## Dados necessários do profissional

- Nome completo
- Registro profissional (CREFITO, CRM, CRO etc.)
- Número do WhatsApp com DDD
- @ do Instagram
- URL do site (opcional)
- Endereço completo da clínica
- Especialidade principal e condições/tratamentos oferecidos
