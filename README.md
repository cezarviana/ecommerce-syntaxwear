# 👟 E-commerce SyntaxWear

## 📝 Descrição do Projeto
**SyntaxWear** é o front-end de um e-commerce fictício especializado em tênis e sneakers, desenvolvido como um projeto para demonstrar habilidades em HTML e CSS. O site apresenta um design moderno e responsivo, focado na experiência do usuário e na apresentação visual dos produtos.

O layout foi concebido a partir de um design no Figma, que pode ser acessado aqui: [Design no Figma](https://www.figma.com/design/zOjgtKyjjgJnNTiPvATzpK/E-commerce-SyntaxWear?node-id=0-1&p=f&t=Eu9jtW4KEBaA73O2-0)

Repositório do projeto: [SyntaxWear Repositório](https://github.com/cezarviana/ecommerce-syntaxwear)
Acesse o site aqui: [SyntaxWear](https://cezarviana.github.io/ecommerce-syntaxwear/)

## 🔎 Funcionalidades
- **Responsividade:** Layout adaptável para uma experiência de navegação consistente em desktops, tablets e dispositivos móveis.
- **Menu Mobile:** Menu "hambúrguer" para facilitar a navegação em telas menores.
- **Estrutura Semântica:** HTML5 semântico para melhor acessibilidade e SEO.
- **Arquitetura CSS Modular:** O CSS é organizado em componentes (header, footer, hero, etc.), facilitando a manutenção e escalabilidade do estilo.
- **Seções da Página:**
    - **Hero Section:** Destaque principal com título, subtítulo e botões de chamada para ação (CTA).
    - **Categorias de Produtos:** Seção visual para navegar entre as principais categorias (Casual, Esporte, etc.).
    - **Grid de Produtos:** Layout em grade para exibir os tênis em destaque.
    - **Rodapé Completo:** Inclui formulário de inscrição para newsletter, links para redes sociais e navegação adicional.

## 🛠️ Ferramentas utilizadas
- **HTML5:** Estruturação do conteúdo do site.
- **CSS3:** Estilização, layout (Flexbox/Grid), responsividade e animações.
- **Git & GitHub:** Controle de versão e hospedagem do código.
- **Figma:** Ferramenta de design utilizada para criar o protótipo da interface.

## 🎨 Imagens do projeto
<div align="center">
  <p><em>(./images/gifs/syntaxwear.gif)</em></p>
  <br><br>
  <p><em>(./images/gifs/syntaxwear-mobile.gif)</em></p>
  <br>
</div>

## 💡 Decisões do projeto
1. **CSS Reset:** Foi utilizado um reset de CSS moderno (baseado no de Andy Bell) para garantir a consistência visual entre diferentes navegadores, removendo estilos padrão e estabelecendo uma base sólida com `box-sizing: border-box`.

2. **Variáveis CSS:** O projeto faz uso extensivo de variáveis CSS (`:root`) para gerenciar cores e fontes. Essa abordagem centraliza os valores de design, tornando mais fácil a aplicação de um tema consistente e futuras alterações.
   ```css
   :root {
       /* Cores da Marca */
       --color-brand: #6329A2; 
       /* Fontes */
       --font-primary: 'Ubuntu', sans-serif; 
   }
   ```

3. **Arquitetura de CSS por Componentes:** A folha de estilos foi dividida em múltiplos arquivos, cada um responsável por um componente específico da interface (`header.css`, `hero.css`, `footer.css`). Isso melhora a organização, facilita a localização de estilos e promove a reutilização de código.

4. **Fonte Customizada:** A fonte 'Ubuntu' foi importada do Google Fonts para alinhar o projeto com uma identidade visual moderna e de boa legibilidade, conforme definido no arquivo `variables.css`.

Link da fonte: [Ubuntu](https://fonts.google.com/specimen/Ubuntu)

## 💦 Desafios e Aprendizados
- **Estruturação do Grid de Produtos:** Criar um layout de grade assimétrico e responsivo para os produtos foi um desafio interessante, que exigiu um bom planejamento com CSS Grid.
- **Menu Responsivo com CSS Puro:** A implementação do menu hambúrguer utilizando apenas HTML e CSS (com a técnica da `checkbox` e `label`) foi uma ótima prática para aprofundar o conhecimento em seletores CSS avançados e interatividade sem JavaScript.
- **Organização de Arquivos:** Manter a estrutura de arquivos CSS organizada por componentes foi um aprendizado valioso sobre como construir projetos de front-end mais escaláveis e fáceis de manter.

## 💭 Possíveis atualizações futuras
- [ ] Adicionar interatividade com JavaScript (ex: carrossel de produtos, validação de formulário).
- [ ] Criar as páginas de detalhes do produto.
- [ ] Implementar a funcionalidade do carrinho de compras.
- [ ] Desenvolver as páginas de categoria (Masculino, Feminino, etc.).
- [ ] Adicionar um modo escuro (Dark Mode) utilizando as variáveis CSS já existentes.
- [ ] Otimizar as imagens para um carregamento mais rápido.

## 🚀 Como rodar o projeto
Este é um projeto estático de front-end, então você não precisa de um servidor complexo para executá-lo.

### Pré-requisitos
- **Navegador Web:** Qualquer navegador moderno como Chrome, Firefox ou Edge.
- **Git (Opcional):** Para clonar o repositório.


### Passos

1. **Clone o repositório (se estiver usando Git):**
   ```bash
   git clone https://github.com/cezarviana/ecommerce-syntaxwear.git
   ```
   Se não estiver usando Git, você pode baixar o projeto como um arquivo ZIP diretamente do GitHub.

2. **Navegue até a pasta do projeto:**
   ```bash
   cd ecommerce-syntaxwear
   ```

3. **Abra o arquivo `index.html`:**
   Abra o arquivo `index.html` diretamente no seu navegador de preferência para visualizar o site.

---

*Este README foi gerado com base em um template e adaptado para o projeto.*