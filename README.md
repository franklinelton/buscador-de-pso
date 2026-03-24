# Sistema de Download de Imagens e Informações de Produtos (PSO)

## Qual problema isso resolve?

Eu precisava acessar imagens e informações de produtos (como título e descrição) para diferentes demandas de e-commerce, mas isso era feito de forma manual, buscando em múltiplas fontes, copiando dados e baixando imagens uma a uma.

Esse processo consumia tempo, gerava inconsistência e dificultava a padronização dos materiais.

## O que essa aplicação faz?

A aplicação centraliza tudo em um único lugar.

Você digita o EAN ou nome do produto e o sistema:

Encontra o produto automaticamente
Exibe informações relevantes (título, descrição, etc.)
Lista todas as imagens disponíveis
Permite baixar imagens individuais ou todas em ZIP
Possibilita ajustar tamanho e formato das imagens antes do download

Tudo isso de forma simples e visual, sem precisar navegar em múltiplas plataformas.

## Como fica a sua rotina após implementar?
Reduza drasticamente o tempo gasto buscando assets de produto
Pare de depender de múltiplas fontes e retrabalho manual
Ganhe mais consistência na padronização de imagens
Consiga responder demandas de e-commerce com muito mais agilidade

O que antes levava vários minutos (ou até horas), agora resolve em poucos cliques.

## Como usar
Digite o EAN ou nome do produto na busca
Selecione o produto sugerido ou pressione buscar
Visualize as informações e imagens disponíveis
Escolha:
Baixar uma imagem específica
Selecionar várias imagens
Baixar todas em ZIP
(Opcional) Defina dimensões e formato antes de baixar

## Como configurar para uso próprio

**1. Prepare suas imagens**

Reuna suas imagens em pastas preferencialmente nomeadas pelo EAN de cada produto, onde cada imagem esteja indicando a posição em que deve ser executada na Página de Descrição do Produto (PDP). Depois disso, suba em um diretório público no github nomeado "imagens-ean", assim o código do buscador não precisa ser alterado.
> Dependendo do número de pastas, pdoe ser necessário uma automação para upload no github. Utilize a IA para te dar esse passo a passo.

**2. Crie um arquivo json com seu catalogo**

Você pode colocar as informações que tiver/achar relevantes. No exemplo aqui proposto o arquivo tem EAN, nome do produto, título completo, título reduzido para apps de entrega, descrição longa e descrição curta. Caso já tenha um arquivo com essas e outras informações, baixe o arquivo [catalogo.json](https://github.com/franklinelton/buscador-de-pso/blob/1074910de0db5d2c9ce59dd2424aa7e2938f3336/catalogo.json) e peça para a IA criar um arquivo json com os mesmos campos do exemplo.
Depois disso, suba o arquivo no seu github com o nome "catalogo.json".

**3. Copie o arquivo index.html para o seu GitHub**
Peça o passo a passo para a IA para adicionar um novo arquivo no seu GitHub (caso não saiba como) e edite os principais campos onde esta indicado "Your Name".

**4. Salve o logo da sua empresa no GitHub**

Salve o logo como "YourLogoHere.png" para que o código incorpore a imagem no html da aplicação. Crie um favicon com o seu logo para que ele seja incluído na Barra superior do navegador e salve-o no GitHub como "YourLogoHere.ico".

**5. Aguarde alguns minutos e teste**

## Feito com vibecoding 🤖

Não sou desenvolvedor. Construí isso usando IA como ferramenta de desenvolvimento.

Usei IA para estruturar lógica, interface e resolver problemas práticos do dia a dia.

Se eu consegui transformar uma dor real em uma ferramenta funcional, você também consegue.
