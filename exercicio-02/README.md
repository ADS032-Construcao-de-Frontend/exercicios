# Objetivo
Nesta prática, você assumirá o papel de Desenvolvedor Frontend e transformará o protótipo do projeto "TechStore" em código real. O foco desta aula é estruturar a página com HTML5 semântico e utilizar os conceitos de Flexbox (Flex Container e Flex Items) para construir o layout da vitrine digital.

---

## Tecnologias / Ferramentas / Frameworks

<img  alt="VS Code"  title="VS Code"  src="https://user-images.githubusercontent.com/1680157/87443751-492e6900-c5cc-11ea-9854-f82d4d921133.png"  height="24">&nbsp;&nbsp;<img  alt="HTML"  title="HTML"  src="https://user-images.githubusercontent.com/1680157/87443762-4af82c80-c5cc-11ea-85cf-57be0e83c169.png"  height="24">&nbsp;&nbsp;<img  alt="CSS"  title="CSS"  src="https://user-images.githubusercontent.com/1680157/87443759-4a5f9600-c5cc-11ea-8ae0-715433c1f781.png"  height="24">&nbsp;&nbsp;<img  alt="JavaScript"  title="JavaScript"  src="https://user-images.githubusercontent.com/1680157/87443764-4af82c80-c5cc-11ea-82c2-c368ee12cf6d.png"  height="24">

---

## Estudo de Caso: Projeto "TechStore"Requisitos de Telas e Estrutura (HTML5)
- [ ] Crie um arquivo "index.html" e estruture as seguintes seções utilizando tags semânticas:
- [ ] Header (Cabeçalho): Deve conter o logotipo da "TechStore" alinhado à esquerda e um ícone de carrinho de compras (com um contador numérico) alinhado à direita.
- [ ] Hero Section (Banner): Um banner principal contendo uma imagem de fundo (ou cor de destaque) e uma frase de impacto centralizada (Exemplo: "As melhores ofertas de tecnologia").
- [ ] Grid de Produtos (Vitrine): Uma seção principal que abrigará pelo menos 6 cards de produtos eletrônicos.
- [ ] Footer (Rodapé): O rodapé da página contendo informações de contato, direitos autorais e links de redes sociais.

### Anatomia do "Card de Produto" (Flex Item)
Cada um dos 6 produtos no seu HTML deve ser encapsulado em uma tag de artigo ou bloco contendo:
- [ ] Espaço para a imagem do produto.
- [ ] Nome do produto.
- [ ] Preço original (riscado) e o preço com desconto em destaque.
- [ ] Botão de ação: "Adicionar ao Carrinho".
- [ ] Aplicando o Flexbox e o Guia de Estilos (CSS3)
- [ ] Crie um arquivo ```style.css``` (não se esqueça de importá-lo no HTML). Você deve aplicar os seguintes conceitos:

#### Guia de Estilos:
- [ ] Defina uma paleta de 3 cores (Primária, Secundária e Neutra).
- [ ] Importe do Google Fonts e aplique 2 fontes diferentes (uma para os títulos e outra para os textos/preços).

#### Flex Containers e Flex Items:
- [ ] **Header:** Transforme em um Flex Container e utilize a propriedade "justify-content" para separar a logo do carrinho. Utilize "align-items" para centralizá-los verticalmente.
- [ ] **Hero Section:** Use Flexbox para garantir que a frase de impacto fique perfeitamente centralizada na tela, tanto horizontal quanto verticalmente.
- [ ] **Grid de Produtos:** Transforme a vitrine em um Flex Container e aplique a quebra de linha automática (flex-wrap) para que os cards se ajustem quando não houver espaço na tela. Utilize a propriedade "gap" para dar espaçamento entre os cards.
- [ ] **Card Interno:** Transforme o próprio card em um Flex Container organizado em coluna (flex-direction: column) para que a imagem, título, preços e botão fiquem perfeitamente empilhados.

#### Instruções de Execução e EntregaPreparação do Ambiente
- [ ] Abra o terminal, certifique-se de estar na branch "develop" e crie uma nova branch chamada "feature/pratica02".Desenvolvimento
- [ ] Acesse a pasta "praticas" e crie a subpasta "pratica02". Dentro dela, crie os arquivos index.html e style.css e implemente os requisitos acima.
**Dica:** Para ver o resultado em tempo real, utilize a extensão "Live Server" no Visual Studio Code.Envio para o GitHub

- [ ] Após finalizar o código, adicione os arquivos ao controle de versão, crie um commit com uma mensagem descritiva (Exemplo: "Feat: Cria o layout da vitrine TechStore usando Flexbox") e envie as alterações para o repositório remoto (push).Finalização
- [ ] No GitHub, abra um ```Pull Request``` da sua ```branch``` da prática para a branch ```develop```.

- [ ] Na descrição, explique brevemente o que foi desenvolvido e referencie o número da Issue correspondente. Por fim, envie o link do seu ```Pull Request``` na plataforma de ensino para avaliação do professor.
