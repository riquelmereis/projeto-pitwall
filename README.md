# 🏁 PIT WALL — GP de São Paulo

Projeto de estudo desenvolvido para a disciplina de **Linguagem de Marcação (LIMA)**, focado na reprodução de uma landing page temática de Fórmula 1 (GP de São Paulo em Interlagos) utilizando exclusivamente **HTML5** e **CSS3**.

---

## 📋 Sobre o Projeto

O **Desafio Pit Wall** tem como objetivo consolidar conceitos fundamentais de estruturação semântica e estilização moderna responsiva, simulando a interface de transmissão e venda de ingressos do Grande Prêmio de São Paulo.

### ✨ Seções da Página
1. **Topbar (`header.topbar`):** Barra de navegação com logotipo estilizado, links de âncora e botão de ação principal.
2. **Hero & Zebra (`section.hero` + `div.kerb`):** Banner principal com corte diagonal em degradê, imagem de fundo, estatísticas da pista (voltas, extensão e curvas) e faixa simulando a zebra do circuito.
3. **Grid de Pilotos (`section#pilotos`):** Cards responsivos exibindo pilotos, números estilizados com opacidade e identificação visual por cores das equipes.
4. **Classificação (`section#classificacao`):** Barra de filtros (busca e seleção de equipe) e tabela completa de pontuação com destaque para o líder do campeonato.
5. **Ingressos (`section#ingressos`):** Layout em duas colunas contendo informações dos setores/valores e formulário completo de reserva.
6. **Rodapé (`footer`):** Créditos do projeto de estudo e identificação do autor.

---

## 🚀 Tecnologias e Conceitos Aplicados

* **HTML5 Semântico:** Uso adequado de tags estruturais (`header`, `main`, `section`, `nav`, `table`, `form`, `footer`).
* **Variáveis CSS (`:root` e `var()`):** Gerenciamento centralizado da paleta de cores escura e das cores individuais de cada escuderia.
* **Flexbox (`display: flex`):** Alinhamento do cabeçalho, distribuição do conteúdo no Hero, dados da pista e barra de filtros.
* **CSS Grid (`display: grid`):**
  * `repeat(auto-fit, minmax(220px, 1fr))` para ajuste automático dos cards de pilotos.
  * Grade de duas colunas para a seção de ingressos e estrutura interna do formulário (`form-grid` com campos em largura total via `grid-column: 1 / -1`).
* **Estilização Avançada:**
  * Gradientes lineares com corte seco (`linear-gradient`) e repetição (`repeating-linear-gradient` para a zebra da pista).
  * Sobreposição de camadas de fundo (gradiente + `url()`).
  * Estados interativos com `:hover` e transições suaves (`transition`).
* **Tipografia:** Integração com **Google Fonts** utilizando a fonte *Titillium Web*.
* **Responsividade (`@media`):** Adaptação completa para dispositivos móveis (`max-width: 768px`), reorganizando grids, empilhando formulários e habilitando rolagem horizontal na tabela de classificação.

---

## 📁 Estrutura de Pastas

```text
pit-wall/
├── index.html        # Estrutura principal da página
├── styles.css        # Folha de estilos e regras de responsividade
└── img/
    └── piloto.jpg    # Imagem de fundo utilizada na seção Hero
```

---

## 👨‍💻 Autor

Desenvolvido por **Riquelme Reis Santos** como atividade prática da disciplina de **Linguagem de Marcação (LIMA)** — *Prof. André Denani e Prof. Raul Lopes*.
