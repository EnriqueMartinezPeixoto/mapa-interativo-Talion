# Talion — Atlas Interativo

Bem-vindo ao **Talion — Atlas Interativo**, uma aplicação web desenvolvida para explorar o universo de *Sombras de Talion*. Este projeto combina uma interface de mapa 2D clássica com um modo de exploração imersivo em 3D, permitindo uma gestão rica e detalhada dos pontos de interesse do teu mundo.

## 🗺️ Sobre o Projeto

O Atlas de Talion foi desenhado para ser uma ferramenta de apoio a campanhas de RPG, escrita de histórias ou simples construção de mundo (worldbuilding). Através de uma interface intuitiva, os utilizadores podem navegar pelo mapa, pesquisar locais específicos e adicionar os seus próprios marcadores personalizados com descrições e detalhes.

## ✨ Funcionalidades Principais

*   **Navegação 2D:** Panorâmica e zoom num mapa bidimensional detalhado.
*   **Modo de Exploração 3D:** Transição fluida para um ambiente tridimensional utilizando a biblioteca Three.js, proporcionando uma perspetiva imersiva do mundo de Talion.
*   **Sistema de Marcadores (POIs):** 
    *   Adicionar, editar e remover pontos de interesse no mapa.
    *   Painel de edição para inserir títulos, descrições detalhadas e categorias para cada local.
*   **Pesquisa Integrada:** Uma barra de pesquisa rápida para localizar marcadores específicos no vasto atlas.
*   **Interface Responsiva:** Design limpo e adaptável gerido através de CSS e HTML.

## 🛠️ Tecnologias Utilizadas

O projeto foi construído utilizando tecnologias web padrão, mantendo-se leve e acessível:

*   **HTML5** - Estrutura da aplicação.
*   **CSS3** - Estilização da interface e layout do mapa.
*   **JavaScript (Vanilla)** - Lógica principal, interatividade, sistema de pesquisa e gestão do estado dos marcadores.
*   **Three.js** - Motor 3D responsável pela renderização do modo de exploração tridimensional.

## 🚀 Como Executar

Como o projeto é construído integralmente com tecnologias frontend (HTML, CSS e JS contidos num único ficheiro, ou com dependências servidas via CDN), a execução é extremamente simples:

1.  Faz o download do ficheiro HTML principal (ex: `Talion — Atlas interativo (1)_2.html`).
2.  Clica duas vezes no ficheiro ou arrasta-o para o teu navegador web preferido (Chrome, Firefox, Edge, Safari).
3.  A aplicação será carregada imediatamente e estará pronta a ser utilizada (requer ligação à internet para carregar bibliotecas externas como o Three.js, caso sejam chamadas via CDN).

*Nota: Para garantir que todas as texturas 3D ou recursos locais carreguem corretamente devido a políticas de CORS dos navegadores modernos, pode ser recomendado correr o ficheiro através de um servidor local simples (como o plugin "Live Server" do VS Code).*

## 📝 Trabalho Futuro / Melhorias Previstas

*   Implementação de um sistema de gravação (Local Storage ou base de dados) para que os marcadores criados não se percam ao atualizar a página.
*   Adição de camadas de mapa (ex: visão política, relevo, clima).
*   Personalização de ícones para diferentes tipos de marcadores.

---
*Construído para o universo de Sombras de Talion.*