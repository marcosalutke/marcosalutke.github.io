# 🌐 Portfólio Profissional | Marcos Lutke

Bem-vindo ao repositório do meu portfólio pessoal. Este projeto foi construído do zero para atuar como minha vitrine digital, consolidando minha trajetória de **Infraestrutura e Operações de TI** para **Desenvolvimento Backend**.

🚀 **Acesse o site ao vivo:** [marcosalutke.github.io](https://marcosalutke.github.io)

---

## 🎯 Objetivo Arquitetural

Como um desenvolvedor focado em Backend e DevOps, o objetivo deste frontend foi construir uma página de alta performance, leve e sem dependência de frameworks ou bibliotecas pesadas (como React ou Bootstrap). A arquitetura prioriza o carregamento rápido, SEO e a manutenibilidade do código puro.

## 🛠️ Tecnologias e Decisões Técnicas

* **HTML5 Semântico:** Uso rigoroso de tags semânticas (`<main>`, `<article>`, `<aside>`, `<figure>`) para garantir total acessibilidade e melhor indexação por motores de busca.
* **CSS3 Moderno (Vanilla):**
  * **Layout:** Construído inteiramente com `Flexbox` e `CSS Grid` para alinhamento preciso.
  * **Animações e UI:** Implementação de transições suaves (`@keyframes fadeInUp`), scrollbar customizada e efeitos de *glassmorphism/neon* nos cards para uma interface moderna (Dark Mode nativo).
  * **Modularização:** Separação lógica de estilos (`reset.css`, `header.css`, `style.css`) para facilitar a manutenção.
* **📱 Design Responsivo (Mobile-First):** O layout se adapta dinamicamente a qualquer tamanho de tela (smartphones, tablets e desktops) utilizando Media Queries estratégicas, garantindo fluidez sem quebra de elementos.
* **🌐 Asset Management Inteligente:** Para manter o repositório extremamente leve, **nenhuma imagem ou ícone é hospedado localmente**. Todos os assets (Devicon, FontAwesome e fotos de perfil) são consumidos via links externos e CDNs, otimizando o tempo de requisição e o cache do navegador.

## 📁 Estrutura de Diretórios

```text
📦 marcosalutke.github.io
 ┣ 📂 css
 ┃ ┣ 📜 header.css      # Estilos exclusivos da barra de navegação
 ┃ ┣ 📜 reset.css       # Normalização de estilos entre navegadores
 ┃ ┗ 📜 style.css       # Estilos globais, tipografia, seções e animações
 ┣ 📜 index.html        # Estrutura principal e roteamento de âncoras
 ┗ 📜 README.md         # Documentação técnica
