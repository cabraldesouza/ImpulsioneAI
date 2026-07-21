# 📁 ImpulsioneAI — Documentação Completa do Projeto
**Gerado em:** Junho 2026  
**Status:** Em construção ativa  

---

## 🧠 VISÃO GERAL DO PROJETO

**Nome da Agência:** ImpulsioneAI  
**Tipo:** Agência de Tech para PMEs  
**Serviços:** Websites de Conversão · Automação de Processos · Marketing Digital & Tráfego  
**Público-Alvo:** Pequenas e Médias Empresas (PMEs) brasileiras  
**Posicionamento:** Tech séria + inovação com IA, executada com velocidade  
**Diferencial:** Founder técnico (full-stack dev) com expertise em IA aplicada  

---

## 🎨 IDENTIDADE VISUAL

### Logo
- **Conceito:** Letra "A" corporativa + Seta ascendente central + Ponto embaixo (referência ao "i" de AI)
- **Significado:**
  - A maiúscula → Corporativo, profissional, confiança para PMEs
  - Seta ascendente → Crescimento, momentum, ação, impulso
  - Ponto (·) → O "i" de AI — referência óbvia a inteligência artificial
  - Funciona como monograma (inicial de marca)

### Variações da Logo
| Variação | Uso |
|----------|-----|
| Colorida (Roxo + Preto) | Web, redes sociais, marketing |
| Monocromática (Preto) | Impressão, B&W, documentos |
| Invertida (Branco em Roxo) | Backgrounds coloridos |
| Branca em Preto | Backgrounds escuros |
| Logo + Wordmark Horizontal | Website, header, apresentações |
| Logo + Wordmark Vertical | Apps, Instagram, espaços limitados |
| Ícone isolado | Favicon, avatar |

### Paleta de Cores
| Nome | Hex | Uso |
|------|-----|-----|
| Roxo Principal | `#7C3AED` | Cor primária, CTAs, destaques |
| Roxo Light | `#A78BFA` | Gradientes, highlights |
| Roxo Dark | `#5B21B6` | Hovers, variações |
| Preto Corporativo | `#1F2937` | Textos, backgrounds escuros |
| Preto Deep | `#0A0A0F` | Background principal (dark mode) |
| Preto Card | `#16161E` | Cards, containers |
| Borda | `#2A2A35` | Divisores, bordas sutis |
| Cinza Texto | `#9CA3AF` | Textos secundários |
| Branco | `#FFFFFF` | Textos em fundo escuro |

### Tipografia
| Fonte | Uso |
|-------|-----|
| Space Grotesk | Display, títulos, logo wordmark |
| Inter | Corpo de texto, UI, parágrafos |

### Regras de Uso da Logo
✅ Usar sempre nas proporções originais (1:1)  
✅ Manter espaço mínimo ao redor (10% do tamanho)  
❌ Não rotacionar  
❌ Não distorcer (sempre manter proporção)  
❌ Não mudar as cores  
❌ Não adicionar sombra ou efeitos 3D  

---

## 🌐 LANDING PAGE

### Arquivo
`ImpulsioneAI_Premium.html`

### Stack / Tecnologias
- HTML5 + CSS3 puro (sem framework)
- GSAP 3.12.2 + ScrollTrigger (animações)
- Google Fonts: Inter + Space Grotesk
- SVG inline para logo

### Seções
1. **Nav** — Sticky com blur ao rolar, logo + links + CTA
2. **Hero** — Headline impactante, badge animado, glow roxo, grid de fundo, scroll hint
3. **Stats** — Contador animado (24h · 100% · 3 soluções · R$0 na conversa)
4. **Serviços** — 3 cards com glow dinâmico ao hover, tags de tecnologias
5. **Case Study** — Screenshot real da Danilla Dantas + métricas
6. **Processo** — 4 etapas (Discovery → Proposta → Execução → Lançamento)
7. **CTA Final** — WhatsApp + Email com glow parallax
8. **Footer** — Logo + links + copyright

### Animações GSAP Implementadas
| Animação | Onde |
|----------|------|
| Entrada em cascata | Hero (badge → título → subtítulo → botões) |
| Parallax vertical | Glow do hero ao scrollar |
| Contador numérico | Stats (sobe do zero ao entrar na tela) |
| Fade-up | Todos os títulos e textos de seção |
| Fade-in + scale | Case visual (screenshot) |
| Stagger | Cards de serviços, métricas, etapas do processo |
| Parallax scale | Glow do CTA final |
| Cursor personalizado | Segue mouse com delay suave, transforma em hover |
| Glow dinâmico | Cards de serviço seguem posição do cursor |

### Customizações Necessárias (TODO)
```
[ ] Substituir: +55 34 99999-9999  →  seu WhatsApp real
[ ] Substituir: https://wa.me/5534999999999  →  link WhatsApp real
[ ] Substituir: contato@impulsioneai.com  →  email real da Hostinger
[ ] Confirmar autorização para usar case Danilla Dantas publicamente
[ ] Comprar domínio: impulsioneai.com
```

---

## 📧 EMAIL CORPORATIVO

### Estratégia Definida
**Email Hostinger + Receber no Gmail**

### Por que essa solução
- Email profissional: `contato@impulsioneai.com`
- Interface Gmail que você já conhece
- Custo: R$ 0 (incluso na Hostinger)
- Escalável para Google Workspace futuramente

### Setup
1. Criar email no cPanel da Hostinger
2. Configurar IMAP no Gmail:
   - Servidor: `mail.impulsioneai.com`
   - Porta: `993`
   - Usuário: `contato@impulsioneai.com`
3. Ativar envio como `contato@impulsioneai.com` via Gmail

### Quando Migrar para Google Workspace
- Após fechar 3+ clientes
- Faturamento mínimo R$ 3k/mês
- Necessidade de compartilhamento de docs em equipe
- Custo: R$ 6–12/mês

---

## 🏗️ HOSPEDAGEM

### Plataforma: Hostinger
**Plano recomendado:** Premium (~R$ 6–10/mês)  
**Inclui:** Domínio grátis 1º ano · Hospedagem · Email ilimitado · SSL grátis · Backup automático · Suporte PT-BR

### Passo a Passo de Upload
1. Acessar cPanel Hostinger
2. Gerenciador de Arquivos → `public_html`
3. Deletar `index.html` padrão
4. Upload do `ImpulsioneAI_Premium.html` → renomear para `index.html`
5. Testar acesso: `impulsioneai.com`

### Por que não Vercel/Netlify
| Aspecto | Hostinger | Vercel/Netlify |
|---------|-----------|----------------|
| Domínio | Incluso | Separado |
| Email corporativo | Incluso | Não inclui |
| Suporte | PT-BR | English only |
| Múltiplos sites | Sim | Limitado grátis |
| Praticidade | Alta | Técnica |

---

## 💰 ESTRATÉGIA DE RECEITA

### Fonte 1: Serviços de Agência (Médio Prazo)

**Pacote Infoproduto Express (Estratégia Yan Pedro)**
- Criar Web App com Claude + Lovable
- Setup no Kirvano
- Estratégia de conteúdo Instagram
- **Preço:** R$ 2.500 – R$ 4.500 por cliente
- **Margem:** R$ 125–225/hora
- **Meta:** 2–3 clientes/mês = R$ 5–13.5k/mês

**Serviço Geral de Agência**
- Website + Automação + Tráfego
- **Preço:** R$ 3.000–8.000 por projeto
- **Meta:** 1–2 projetos/mês

### Fonte 2: Infoproduto Próprio (Curto Prazo — Teste Yan Pedro)

**Como Funciona**
1. Criar app de desenvolvimento pessoal com Claude
2. Publicar no Lovable (gratuito)
3. Cadastrar no Kirvano (R$ 29,90)
4. Criar perfil "dark" no Instagram
5. Postar 3x/dia por 5 dias (estratégia dos 5 dias)
6. Mineralizar conteúdo viral gringo + traduzir + recriar

**Stack Necessário**
- Claude ✅ (já tem)
- Lovable (gratuito)
- Kirvano (gratuito + comissão)
- ChatGPT (R$ 20/mês)
- Canva Pro (R$ 120/ano)
- Instagram (gratuito)

**Investimento:** ~R$ 200  
**Receita esperada Mês 1:** R$ 300–1.500  
**Receita esperada Mês 2–3:** R$ 900–1.500/mês (semi-passivo)

**Nichos sugeridos para teste**
- Disciplina & Rotinas (Modo Caverna/Lobo)
- Automação para Freelancers
- Produtividade para PMEs

### Fonte 3: SaaS (Longo Prazo)

**Conceito:** ImpulseBuilder  
Plataforma all-in-one que automatiza toda a operação do infoproduto:

| Feature | Descrição |
|---------|-----------|
| Template Editor | Criar app sem código |
| Integração Kirvano | Cadastro automático de produto |
| Content Miner | Scraping de posts virais + tradução |
| Social Scheduler | Agendar 3x/dia automático |
| Analytics | Vendas + CTR + ROI |

**Preços sugeridos**
- Free: 1 app/mês
- Pro: R$ 99–149/mês
- Agency: R$ 299/mês

**Receita potencial:** 100 usuários Pro = R$ 14.900/mês (recorrente)

---

## 📊 CASE STUDY — DANILLA DANTAS SEMI JOIAS

### Sobre o Projeto
- **Cliente:** Danilla Dantas (familiar)
- **Tipo:** E-commerce de semi joias artesanais
- **Nicho:** Semi joias elegantes e sofisticadas
- **Slogan da marca:** "Conectando Amor Através de Peças"

### O que Foi Feito
- E-commerce completo com catálogo de produtos
- Design premium: fundo preto + dourado
- Integração WhatsApp para atendimento
- Botão "Fale Conosco" + "Explorar Catálogo"
- Seção "Nossas Categorias"
- Carrinho de compras
- Badge "Fabricação Própria"

### Design Visual do Site
- Background: Preto escuro com gradiente
- Cores: Preto + Dourado (#C9A84C region)
- Tipografia serif elegante nos títulos
- Vibe: Luxo acessível, premium

### Resultados
- ✅ Site funcional e no ar
- ✅ Presença digital criada do zero
- ✅ Integração WhatsApp ativa
- ✅ Catálogo digital de produtos

### Status na Landing
- Screenshot real integrado na seção Case Study
- URL exibida: `danilladantas.com.br`
- **Pendente:** Confirmar autorização para uso público do nome

---

## 📋 CHECKLIST DE LANÇAMENTO

### Fase 1: Hostinger (30 min)
- [ ] Acessar hostinger.com.br
- [ ] Comprar domínio `impulsioneai.com` + hospedagem Premium
- [ ] Anotar credenciais de acesso

### Fase 2: Upload do Site (15 min)
- [ ] Acessar cPanel → Gerenciador de Arquivos
- [ ] Abrir `public_html`
- [ ] Deletar `index.html` padrão
- [ ] Upload do `ImpulsioneAI_Premium.html` como `index.html`
- [ ] Testar: `impulsioneai.com`

### Fase 3: Email Corporativo (20 min)
- [ ] cPanel → Email → Criar `contato@impulsioneai.com`
- [ ] Configurar IMAP no Gmail
- [ ] Testar envio e recebimento

### Fase 4: Customizar (30 min)
- [ ] Substituir WhatsApp fake pelo real
- [ ] Substituir email fake pelo real
- [ ] Decidir sobre uso público do case Danilla Dantas

### Fase 5: Testes (15 min)
- [ ] Testar em desktop + mobile
- [ ] Verificar todos os CTAs
- [ ] Verificar velocidade de carregamento
- [ ] Verificar SSL (https)

### Fase 6: Pós-Lançamento
- [ ] Criar Instagram da agência
- [ ] Listar 20 PMEs para prospecção
- [ ] Iniciar teste de infoproduto em paralelo

---

## 🗓️ ROADMAP

### Semana 1–2 (Agora)
- [x] Definir nome: ImpulsioneAI
- [x] Criar logo definitiva
- [x] Criar landing page premium
- [ ] Hostinger + domínio
- [ ] Email corporativo
- [ ] Site no ar

### Semana 3–4
- [ ] Iniciar teste infoproduto (nicho a escolher)
- [ ] Criar Instagram da agência
- [ ] Primeiro pitch para PMEs
- [ ] 1º cliente ou 1ª venda de infoproduto

### Mês 2
- [ ] Documentar case Danilla Dantas formalmente
- [ ] 2–3 clientes de agência
- [ ] Escalar infoproduto se validado
- [ ] Começar prototipagem do SaaS

### Mês 3–6
- [ ] Equipe (1 assistente)
- [ ] 4–5 clientes/mês
- [ ] MVP do ImpulseBuilder
- [ ] Primeiros usuários pagantes do SaaS

---

## 📁 ARQUIVOS DO PROJETO

| Arquivo | Descrição |
|---------|-----------|
| `ImpulsioneAI_Premium.html` | Landing page final com GSAP + screenshot real |
| `ImpulsioneAI_Logo_Definiva.html` | Sistema de logo completo com todas as variações |
| `ImpulsioneAI_3_Conceitos.html` | 3 conceitos de logo (histórico) |
| `ImpulsioneAI_Logo_System.html` | Sistema de logo v1 (histórico) |
| `Estrategia_Infoproduto_AI_Analise.md` | Análise completa da estratégia Yan Pedro |
| `Prompt_Logo_ImpulsioneAI.md` | Prompt detalhado para geração de logo |
| `CHECKLIST_Implementacao_ImpulsioneAI.md` | Checklist de lançamento passo a passo |
| `ImpulsioneAI_Documentacao_Completa.md` | Este arquivo — documentação master |

---

## 💡 DECISÕES TOMADAS

| Decisão | Escolha | Motivo |
|---------|---------|--------|
| Nome da agência | ImpulsioneAI | Melhor resposta emocional |
| Estilo da logo | A com Seta + Ponto | Corporativo, memorável, monograma |
| Cores | Roxo #7C3AED + Preto #1F2937 | Premium, diferenciado, durável |
| Hospedagem | Hostinger | Tudo em um, suporte PT-BR |
| Email | Hostinger + Gmail | Grátis, praticidade do Gmail |
| Outlook vs Gmail | Gmail | Interface + integração melhor |
| Landing page | Dark mode premium | Mais impacto e diferenciação |

---

## 🔑 CREDENCIAIS (PREENCHER)

> ⚠️ **IMPORTANTE:** Preencher e guardar em local seguro (ex: Bitwarden, 1Password)

```
Hostinger
  Login: _______________
  Senha: _______________
  Domínio: impulsioneai.com

Email Corporativo
  Endereço: contato@impulsioneai.com
  Senha: _______________
  IMAP: mail.impulsioneai.com:993

WhatsApp da Agência
  Número: _______________
  Link: https://wa.me/55_______________
```

---

*Documentação gerada automaticamente a partir das conversas do projeto ImpulsioneAI.*  
*Atualizar conforme o projeto evolui.*
