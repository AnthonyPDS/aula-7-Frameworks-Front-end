# AURA MODA — Loja de Roupas com Tailwind CSS (Atividade 02)

Projeto desenvolvido para a disciplina de **Frameworks Front-end (SENAI)** — **Prof. Me. Deivison S. Takatu**.  
A aplicação consiste na Home Page responsiva da loja fictícia **AURA MODA**, construída com a abordagem **Utility-First** do **Tailwind CSS v4 (Play CDN)**, utilizando **45 classes utilitárias diferentes** distribuídas em 9 categorias (cores, tipografia, espaçamentos, dimensões, bordas, posicionamento, flexbox, grid e responsividade).

---

## 🔗 Link do Projeto / Repositório

- **Repositório GitHub:** https://github.com/AnthonyPDS/aula-7-Frameworks-Front-end
- **Arquivo Principal:** [`atividade-02/index.html`](./index.html)

---

## 📸 Prints do Projeto

> Substitua os caminhos abaixo pelos arquivos de captura de tela salvos na pasta do seu repositório ao publicar no GitHub.

### 1. Print do Código (`index.html`)
![Print do Código](./print-codigo.png)

### 2. Print da Aplicação em Funcionamento (Navegador)
![Print da Aplicação](./print-aplicacao.png)

---

## 📋 Lista das Classes Utilizadas e Suas Respectivas Funções (45 Classes)

Abaixo estão listadas e documentadas **45 classes diferentes do Tailwind CSS** utilizadas no arquivo [`index.html`](./index.html), superando o requisito mínimo de 30 classes e cobrindo todas as categorias solicitadas:

### 1. Cores (Background e Texto)
| # | Classe Tailwind | Função |
| :---: | :--- | :--- |
| 01 | `bg-slate-50` | Define a cor de fundo geral da página em cinza muito claro (`slate-50`). |
| 02 | `bg-slate-900` | Define fundo escuro (`slate-900`) para a barra de navegação, banner principal e rodapé. |
| 03 | `bg-white` | Define fundo branco puro para os cards de categorias e produtos. |
| 04 | `bg-indigo-600` | Define fundo azul-índigo vibrante para botões de destaque e selos principais. |
| 05 | `bg-emerald-500` | Define fundo verde-esmeralda para o selo de produto `"NOVO"`. |
| 06 | `bg-amber-400` | Define fundo amarelo-âmbar de destaque para tags promocionais. |
| 07 | `text-white` | Define a cor do texto como branco para contraste em fundos escuros. |
| 08 | `text-slate-600` | Define cor cinza intermediária para textos descritivos secundários. |

### 2. Tipografia
| # | Classe Tailwind | Função |
| :---: | :--- | :--- |
| 09 | `font-sans` | Aplica a família de fontes sem serifa padrão do sistema. |
| 10 | `font-bold` | Define o peso da fonte como negrito (`700`) para títulos, preços e botões. |
| 11 | `font-semibold` | Define o peso da fonte como seminegrito (`600`) para links de navegação. |
| 12 | `text-xs` | Define tamanho de fonte extra pequeno (`0.75rem`) para badges e legendas. |
| 13 | `text-sm` | Define tamanho de fonte pequeno (`0.875rem`) para descrições e menus. |
| 14 | `text-lg` | Define tamanho de fonte grande (`1.125rem`) para títulos de produtos e preços. |
| 15 | `text-2xl` | Define tamanho de fonte `1.5rem` para os títulos das seções da loja. |
| 16 | `text-3xl` | Define tamanho de fonte `1.875rem` para a chamada principal do Hero Banner. |
| 17 | `uppercase` | Transforma todas as letras do texto em maiúsculas. |
| 18 | `tracking-wider` | Aumenta o espaçamento entre letras (`letter-spacing`) para melhorar a leitura de siglas e selos. |
| 19 | `text-center` | Centraliza horizontalmente o texto dentro do elemento. |

### 3. Espaçamentos (Padding e Margin)
| # | Classe Tailwind | Função |
| :---: | :--- | :--- |
| 20 | `p-6` | Aplica preenchimento interno (`padding: 1.5rem`) em todos os lados do elemento. |
| 21 | `px-4` | Aplica preenchimento interno horizontal (`padding-left` e `padding-right` de `1rem`). |
| 22 | `py-3` | Aplica preenchimento interno vertical (`padding-top` e `padding-bottom` de `0.75rem`). |
| 23 | `mx-auto` | Centraliza horizontalmente containers de largura fixa usando margens laterais automáticas. |
| 24 | `mt-8` | Adiciona margem externa superior (`margin-top: 2rem`). |
| 25 | `mb-6` | Adiciona margem externa inferior (`margin-bottom: 1.5rem`). |

### 4. Dimensões (Largura e Altura)
| # | Classe Tailwind | Função |
| :---: | :--- | :--- |
| 26 | `w-full` | Faz o elemento ocupar `100%` da largura disponível do elemento pai. |
| 27 | `max-w-6xl` | Limita a largura máxima do container a `72rem` (`1152px`) para telas grandes. |
| 28 | `h-16` | Define altura fixa de `4rem` (`64px`) para a barra de navegação. |
| 29 | `h-40` | Define altura fixa de `10rem` (`160px`) para o quadro visual de cada produto. |
| 30 | `min-h-screen` | Garante que o `<body>` ocupe no mínimo `100vh` (100% da altura da tela). |

### 5. Bordas e Sombras
| # | Classe Tailwind | Função |
| :---: | :--- | :--- |
| 31 | `border` | Adiciona uma borda sólida de `1px` ao redor do elemento. |
| 32 | `border-slate-200` | Define a cor da borda em cinza suave (`slate-200`) nos cards de produtos. |
| 33 | `rounded-lg` | Arredonda os cantos do elemento com raio médio (`0.5rem`). |
| 34 | `rounded-xl` | Arredonda os cantos dos cards e banners com raio amplo (`0.75rem`). |
| 35 | `rounded-full` | Deixa as bordas totalmente circulares/pílula nos selos de desconto e novidades. |
| 36 | `shadow-sm` | Aplica uma sombra suave de elevação aos cards da vitrine. |

### 6. Posicionamento
| # | Classe Tailwind | Função |
| :---: | :--- | :--- |
| 37 | `sticky` | Mantém a barra de navegação fixa no topo da tela durante a rolagem (`position: sticky`). |
| 38 | `top-0` | Posiciona o cabeçalho colado na extremidade superior (`top: 0px`). |
| 39 | `relative` | Define `position: relative` no quadro do produto para servir de referência aos selos internos. |
| 40 | `absolute` | Define `position: absolute` nos selos (`NOVO`, `TOP 1`, `-15%`) no canto superior direito do produto. |
| 41 | `z-10` | Controla a camada de empilhamento (`z-index: 10`) para que o menu fique acima do conteúdo ao rolar. |

### 7. Flexbox
| # | Classe Tailwind | Função |
| :---: | :--- | :--- |
| 42 | `flex` | Ativa o modo de layout Flexbox (`display: flex`) no container. |
| 43 | `flex-col` | Organiza os itens filhos em coluna vertical (`flex-direction: column`). |
| 44 | `items-center` | Alinha os itens filhos verticalmente ao centro no eixo transversal (`align-items: center`). |
| 45 | `justify-between` | Distribui os itens com espaço máximo entre eles (`justify-content: space-between`). |

### 8. Grid e Espaçamento entre Itens (`gap`)
| # | Classe Tailwind | Função |
| :---: | :--- | :--- |
| 46 | `grid` | Ativa o CSS Grid Layout (`display: grid`) nas vitrines de categorias e produtos. |
| 47 | `grid-cols-1` | Define 1 coluna por padrão em dispositivos móveis (abordagem *Mobile First*). |
| 48 | `gap-6` | Define espaçamento uniforme de `1.5rem` (`24px`) entre as linhas e colunas do Grid/Flexbox. |

### 9. Responsividade (Breakpoints `sm:`, `md:`, `lg:`)
| # | Classe Tailwind | Função |
| :---: | :--- | :--- |
| 49 | `sm:px-8` | Aumenta o espaçamento lateral para `2rem` em telas a partir de `640px`. |
| 50 | `md:flex-row` | Altera a direção do banner principal de coluna para linha horizontal em telas médias (`≥ 768px`). |
| 51 | `md:grid-cols-2` | Exibe os cards de produtos em 2 colunas em tablets (`≥ 768px`). |
| 52 | `lg:grid-cols-4` | Exibe os cards de categorias e produtos em 4 colunas em telas desktop (`≥ 1024px`). |

---

## 🚀 Como Executar o Projeto

1. Clone este repositório ou baixe os arquivos.
2. Abra o arquivo [`atividade-02/index.html`](./index.html) em qualquer navegador web moderno (é necessário estar conectado à internet para carregar o script Play CDN do Tailwind CSS).

