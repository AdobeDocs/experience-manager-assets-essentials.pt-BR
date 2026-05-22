---
title: Como gerenciar modelos do Dynamic Media?
description: Saiba como criar modelos do Dynamic Media usando um editor de modelo WYSIWYG e incluir várias camadas de imagens e texto para criar banners e folhetos rapidamente e usá-los em aplicativos downstream.
hide: true
hidefromtoc: true
role: User
exl-id: 07de648e-4ae2-4524-8e05-3cf10bb6006d
source-git-commit: 4c176db86c9f3219f2cb63edda71435a2aa76850
workflow-type: tm+mt
source-wordcount: '3000'
ht-degree: 99%

---

# Modelos do Dynamic Media{#dynamic-media-templates}

| [Práticas recomendadas de pesquisa](https://experienceleague.adobe.com/pt-br/docs/experience-manager-cloud-service/content/assets/best-practices/search-best-practices) | [Práticas recomendadas para metadados](https://experienceleague.adobe.com/pt-br/docs/experience-manager-cloud-service/content/assets/best-practices/metadata-best-practices) | [Centro de conteúdo](https://experienceleague.adobe.com/pt-br/docs/experience-manager-cloud-service/content/assets/content-hub/product-overview) | [Documentação do AEM Assets para desenvolvedores](https://developer.adobe.com/experience-cloud/experience-manager-apis/) |
| ------------- | --------------------------- |---------|-----|

>[!CONTEXTUALHELP]
>id="assets_dm_templates"
>title="Gerenciar modelos do Dynamic Media"
>abstract="Crie e personalize banners de imagem e texto a qualquer momento, com uma interface WYSIWYG fácil de usar e incorpore o URL do Dynamic Media em qualquer aplicativo próprio ou de terceiros para impulsionar experiências com alto nível de engajamento. Experimente!"
>additional-url="https://images-tv.adobe.com/mpcv3/4477/b74738ca-888c-4a37-9a9e-14fabd68ee45_1738206841.854x480at800_h264.mp4" text="Assistir ao vídeo"

Crie modelos do Dynamic Media usando um editor de modelo WYSIWYG e inclua várias camadas de imagens e texto para criar banners e folhetos rapidamente e usá-los em aplicativos downstream. Você também pode adicionar parâmetros às camadas de imagens e texto incluídas no modelo e usar as [URLs do Dynamic Media](https://experienceleague.adobe.com/pt-br/docs/commerce-admin/content-design/wysiwyg/storage/catalog-urls-dynamic-media) para atualizar os valores dessas camadas em tempo real.

Alguns dos principais recursos são:

* **Editor de modelo WYSIWYG do Dynamic Media:** crie banners personalizáveis com camadas de imagem e texto.
* **Parametrização de camada:** defina pares de chave-valor dinâmicos em camadas para habilitar atualizações em tempo real.
* **Suporte a URLs do Dynamic Media:** use URLs do Dynamic Media em modelos, integrando valores personalizados de aplicativos próprios ou de terceiros.
* **Controle de visibilidade de camada:** oculte ou mostre camadas dinamicamente, conforme necessário.
* **Redimensionamento de texto inteligente:** ajuste automaticamente o tamanho do texto para se encaixar nas áreas designadas.

Alguns dos principais benefícios dos modelos do Dynamic Media são:

* **Otimizar 1:1 personalização:** personalize o conteúdo para sinais de clientes em tempo real.
* **Reduzir o esforço manual:** automatize e acelere a criação e o gerenciamento de conteúdo.
* **Garantir experiências omnicanal consistentes:** mantenha a consistência da marca em todos os canais.
* **Reutilizar conteúdo de forma eficaz:** evite conteúdo de uso único e dimensione com modelos dinâmicos e parametrizados.
* **Atenuar riscos:** atualize preços, descontos e links em tempo real.
* **Aprimorar o engajamento com o cliente:** promova experiências interativas e relevantes contextualmente.

>[!NOTE]
>
>Os clientes que assinam o SKU de Segurança aprimorada não podem usar nenhum recurso do Dynamic Media, incluindo Modelos do Dynamic Media, nesse programa do Cloud Services.

## Antes de começar{#prerequisites-for-dynamic-media-wysiwyg-template}

Para criar um modelo do Dynamic Media, você deve ter:

1. Acesso ao Dynamic Media.
1. [Sincronizado as imagens disponíveis na sua instância do AEM Assets com o Dynamic Media para usá-las na criação do modelo](https://experienceleague.adobe.com/pt-br/docs/experience-manager-cloud-service/content/assets/dynamicmedia/config-dm).
1. Verificado o seguinte na interface para toque:
   * Na **[!UICONTROL página Editar configuração do Dynamic Media]**, o **[!UICONTROL modo de sincronização do Dynamic Media]**, que está definido como **[!UICONTROL Desabilitado por padrão]**, não é aplicado a todas as pastas do AEM (**[!UICONTROL Sincronizar todo o conteúdo]** está desmarcada). Consulte [Configuração do serviço de nuvem do Dynamic Media](https://experienceleague.adobe.com/pt-br/docs/experience-manager-cloud-service/content/assets/dynamicmedia/config-dm) para obter mais informações.
   * O **[!UICONTROL modo de sincronização do Dynamic Media]** está definido como **[!UICONTROL Habilitar para subpastas]** na pasta ou subpasta de destino em que você salvará o modelo após a criação. Consulte [Configuração do serviço de nuvem do Dynamic Media](https://experienceleague.adobe.com/pt-br/docs/experience-manager-cloud-service/content/assets/dynamicmedia/config-dm) para obter mais informações.

## Criar modelo WYSIWYG do Dynamic Media{#how-to-create-dynamic-media-wysiwyg-template}

Para criar um modelo do DM, siga estas etapas:

1. [Criar uma tela em branco](#create-a-canvas)
1. [Adicionar imagens à tela](#add-images-to-the-canvas)
1. [Adicionar camadas de texto à tela](#add-text-to-the-canvas)
1. [Editar ou excluir uma camada](#edit-or-delete-a-layer)
1. [Parametrizar camadas](#parameterise-a-layer)

### Criar uma tela em branco{#create-a-canvas}

Execute estas etapas para criar uma tela em branco:

1. Navegue até o Assets Essentials e clique em **[!UICONTROL Ativos do Dynamic Media]**, disponível no painel esquerdo.

   ![Modelos do Dynamic Media](/help/using/assets/DM-Assets1.png)

1. Clique em **[!UICONTROL Criar modelo]** para salvar o modelo em Ativos do Dynamic Media ou navegue até uma pasta e clique em **[!UICONTROL Criar modelo]** para salvar o modelo nessa pasta. A caixa de diálogo **[!UICONTROL Novo modelo]** é exibida.
   ![como criar modelos dinâmicos que podem ser personalizados em tempo real](/help/using/assets/new-template.png)
Para [criar uma pasta](/help/using/add-delete.md) em **[!UICONTROL Ativos do Dynamic Media]**, crie uma pasta em **[!UICONTROL Ativos]**. A árvore de pastas em **[!UICONTROL Ativos]** é replicada em **[!UICONTROL Ativos do Dynamic Media]**.
1. Especifique um nome de modelo, defina a largura e a altura da tela e clique em **[!UICONTROL Criar]**. Uma tela em branco é exibida com opções de menu em ambos os lados para serem usadas na criação do modelo. Passe o mouse sobre as opções de menu para ver a dica de ferramenta.
   ![modelo personalizável em tempo real](/help/using/assets/blank-canvas-page.png)

>[!NOTE]
>
> A faixa de largura e altura permitida é de 50 a 5000.

**Opções de menu no painel direito:** use essas opções para adicionar as camadas de imagens e texto necessárias à tela.

* ![Modelos do DM](/help/using/assets/add-image.svg): clique para adicionar imagens à tela.
* ![modelos personalizáveis](/help/using/assets/add-text.svg): clique para adicionar textos à tela.
* ![modelos personalizáveis](/help/using/assets/show-layers-list.svg): clique para ver a lista de todas as camadas (imagem e texto) na tela. Todas as imagens e textos adicionadas à tela são representadas como uma camada separada.

**Opções de menu no painel esquerdo:** use essas opções para ações comuns do editor, conforme mencionado abaixo.

* ![Modelos do DM](/help/using/assets/layer-selector.svg): selecione uma camada.
* ![criar um modelo que possa ser personalizado instantaneamente](/help/using/assets/undo.svg): clique para desfazer a última ação ou pressione **Ctrl** + **Z** (Windows) ou **Cmd** + **Z** (Mac).
* ![modelo para criar banners rapidamente](/help/using/assets/redo.svg): clique para refazer a última ação ou pressione **Ctrl** + **Y** (Windows) ou **Cmd** + **Y** (Mac).
* ![modelo para criar folhetos rapidamente](/help/using/assets/zoomin.svg): clique para ampliar a tela ou pressione **Ctrl** + **+** (Windows) ou Cmd + **+** (Mac).
* ![modelo para criar banners rapidamente](/help/using/assets/ZoomOut-1.svg): clique para reduzir a tela ou pressione **Ctrl** + **-** (Windows) ou **Cmd** + **-** (Mac).
* Pressione **Backspace** ou **delete** para excluir a camada selecionada se nenhum texto ou propriedade estiver sendo editado.

Clique em ![modelo para criar folhetos rapidamente](/help/using/assets/show-layers-list.svg) **>** mais opções (![](/help/using/assets/three-dots.svg)) na camada Tela para editar as dimensões da tela a qualquer momento durante a criação do modelo.
![](/help/using/assets/edit-canvas1.png)

>[!NOTE]
>
> Os modelos permitem no máximo 20 camadas, incluindo a Tela.

### Adicionar imagens à tela{#add-images-to-the-canvas}

Execute estas etapas para adicionar imagens à tela:

1. Clique em ![criar um banner rapidamente](/help/using/assets/add-image.svg) para exibir o painel [Seletor de ativos](https://experienceleague.adobe.com/pt-br/docs/experience-manager-cloud-service/content/assets/manage/asset-selector/overview-asset-selector). O painel exibe as imagens na sua instância do AEM Assets que são sincronizadas com o Dynamic Media.
1. Explore o painel ou use palavras-chave na barra de pesquisa para localizar uma imagem específica.
1. Arraste e solte uma imagem na tela para usá-la. Consulte o [**[!UICONTROL Painel Propriedades]**](#reposition-resize-delete-a-layer) para redimensionar ou reposicionar uma camada na tela.
   ![criar um banner em segundos](/help/using/assets/add-image-to-canvas.png)

### Adicionar camadas de texto à tela{#add-text-to-the-canvas}

Execute estas etapas para adicionar camadas de texto à tela:

1. Clique em ![criando novos banners rapidamente](/help/using/assets/add-text.svg) para adicionar uma camada de texto à tela e abrir o painel Propriedades.
1. Selecione a camada e clique no texto para atualizá-la.
1. Habilite **[!UICONTROL Redimensionamento de texto inteligente]** no painel Propriedades para ajustar automaticamente o comprimento do texto e o tamanho da fonte para que se ajustem perfeitamente à área designada.
   ![melhores banners personalizáveis](/help/using/assets/add-text-layer.png)

Consulte [**[!UICONTROL Painel de propriedades]**](#reposition-resize-delete-a-layer) para reposicionar, redimensionar, girar ou excluir a camada. Formate o texto para a fonte, o tamanho, a cor, o estilo e o alinhamento desejados (na camada) alterando os valores nos respectivos campos na seção **[!UICONTROL Texto]** do painel.

>[!NOTE]
>
> Para usar uma fonte diferente da família de fontes Adobe Sans F2 padrão, é necessário carregar e publicar o arquivo de fonte no AEM Assets e no Dynamic Media. Se você tiver algumas fontes antigas na sua instância, certifique-se de [reprocessar](/help/using/reprocessing.md) para exibi-las no Editor de modelo.

### Editar ou excluir uma camada {#edit-or-delete-a-layer}

Execute estas etapas para editar ou excluir uma camada da tela:

1. Clique em ![modelos com suporte a atualizações dinâmicas](/help/using/assets/show-layers-list.svg) e selecione a camada na tela ou na lista Camadas.
1. Clique em **mais opções** (![modelos com suporte a atualizações em tempo real](/help/using/assets/three-dots.svg)) para editar ou excluir a camada.
1. Clique em **[!UICONTROL Excluir]** para excluir a camada.
1. Clique em **[!UICONTROL Editar]** para editar a camada usando o [**[!UICONTROL Painel Propriedades]**](#reposition-resize-delete-a-layer).
   ![criação rápida de banner](/help/using/assets/edit-delete-layer.png)

### Painel de propriedades{#properties-panel}

Para navegar até o painel de propriedades de uma camada:

1. Clique em ![criação rápida de conteúdo](/help/using/assets/show-layers-list.svg).
1. Selecione a camada na lista.

Esse painel exibe a posição do ponto central da camada no plano da tela (valores X e Y) e as dimensões da camada (largura e altura) juntamente com as opções de formatação de texto.

![criação rápida de conteúdo](/help/using/assets/properties-panel.png)

No painel de propriedades de uma camada, selecione outra camada na tela para navegar até o painel de propriedades correspondente.


#### Reposicionar, redimensionar, girar ou excluir uma camada{#reposition-resize-delete-a-layer}

Veja estas ações comuns de edição de camadas para editar uma camada de texto ou imagem:

* **Reposicionar a camada:** arraste a camada para movê-la para qualquer lugar na tela. Essa ação atualiza os valores X e Y no painel de propriedades.
* **Redimensionar a camada:** selecione a camada e arraste suas alças de borda para redimensioná-la. Essa ação atualiza os valores W (largura) e H (altura) no painel de propriedades.
* **Girar a camada:** arraste a alça quadrada colocada verticalmente acima da camada para girá-la em torno de seu centro. Essa ação atualiza os valores de ângulo no painel de propriedades.
* **Excluir a camada:** pressione **Backspace** ou **delete** e clique em **[!UICONTROL Confirmar]** para excluir uma camada selecionada.

#### Opções de formatação de texto{#text-formatting-options-on-properties-panel}

Formate o texto para a fonte, o tamanho, a cor, o estilo e o alinhamento desejados (na camada) alterando os valores nos respectivos campos na seção **[!UICONTROL Texto]** do painel.

**[!UICONTROL Redimensionamento de texto inteligente]** Certifique-se de incluir **[!UICONTROL Redimensionamento de texto inteligente]** ([Ajuste de texto](https://experienceleague.adobe.com/pt-br/docs/dynamic-media-developer-resources/image-serving-api/image-serving-api/http-protocol-reference/text-formatting/r-copy-fitting)) para ajustar qualquer texto na área designada de forma ideal, ajustando seu tamanho de fonte e comprimento de forma inteligente. Esse recurso evita o excesso de texto ou minimiza espaços extras na parte inferior do texto.
![criação de conteúdo em segundos](/help/using/assets/smart-text-resize.png)

### Parametrizar camadas {#parameterise-a-layer}

Depois de criar um modelo com várias camadas de imagens e textos, parametrize as camadas selecionadas. Quando uma camada ou sua propriedade é parametrizada, ela obtém um par de chave-valor (também chamado de parâmetro). Esse parâmetro pode ser incluído no URL do modelo para atualizar a posição, o tamanho ou o conteúdo da camada em tempo real, resultando na personalização rápida do modelo.

Para parametrizar uma camada:

1. clique em ![criação instantânea de conteúdo](/help/using/assets/show-layers-list.svg), selecione uma camada e clique em **[!UICONTROL Parâmetros]**. O painel **[!UICONTROL Parâmetros]** é exibido.
1. Alterne **[!UICONTROL Incluir parâmetro]** para parametrizar uma propriedade. Consulte [this](#parameterisation-options-or-allowed-parameters) para saber o comportamento da propriedade após a parametrização.
1. **Opcional:** renomeie o nome do parâmetro. Um nome de parâmetro tem o nome da camada seguido por um sufixo. Em uma camada selecionada, todas as propriedades parametrizadas compartilham o mesmo nome da camada com um sufixo variável. Renomeie o nome da camada seguindo a convenção de nomeação semântica para que, ao incluir o parâmetro no URL, o próprio nome do parâmetro tenha informações sobre o conteúdo da camada ou sua finalidade.
1. Clique em **[!UICONTROL Salvar]**.
   ![Criação de conteúdo instantânea](/help/using/assets/parameterise-a-layer.png)
Para alternar entre o painel Parâmetro de uma camada de imagem e de uma camada de texto, selecione a camada na tela e clique em **[!UICONTROL Parâmetros]**.

#### Opção do painel Parâmetros {#parameterisation-options-or-allowed-parameters}

As propriedades parametrizadas podem ser incluídas como parâmetros de URL no URL do modelo para editar o modelo em tempo real através do URL.

**Parâmetros de imagem:**

**X:** inclua para mover a camada horizontalmente ao longo de sua linha central, paralelamente ao eixo X do plano do modelo, alterando o valor do parâmetro no URL.
**Y:** inclua para mover a camada verticalmente ao longo de sua linha central, paralelamente ao eixo Y do plano do modelo, alterando o valor do parâmetro no URL.
**Largura:** inclua para ajustar a largura da camada alterando o valor do parâmetro no URL.
**Altura:** inclua para ajustar a altura da camada alterando o valor do parâmetro no URL.
**Ocultar:** inclua para ocultar ou exibir a camada no modelo usando 0 (exibir) e 1 (ocultar).
**Origem:** inclua para substituir a imagem da camada por uma nova imagem alterando o caminho da imagem no valor do parâmetro do URL.

**Parâmetros de formatação de texto:**

Inclua os parâmetros abaixo para editar o texto, sua fonte, cor e tamanho a partir do URL atualizando os valores de parâmetro no URL.

**Texto:** inclua para atualizar o texto a partir do URL.
**Família da fonte:** inclua para atualizar a fonte do texto a partir do URL.
**Tamanho da fonte:** inclua para atualizar o tamanho da fonte do texto a partir do URL.
**Cor do texto:** inclua para atualizar a cor da fonte do texto a partir do URL.

### Agrupe camadas para controlar a visibilidade delas simultaneamente{#group-layers}

Outra maneira de manter os modelos flexíveis é utilizar um único nome de parâmetro para controlar várias camadas. Essa estratégia é útil para o parâmetro de visibilidade (ocultar ou exibir camadas) na atualização do design ou dos gráficos de um único modelo.

Siga estas etapas para atribuir o mesmo nome aos parâmetros de ocultação (![criação de conteúdo rápida](/help/using/assets/Visibility-icon.svg)) de várias camadas, permitindo ocultá-las ou exibi-las simultaneamente.

1. Navegue até o [**[!UICONTROL Painel propriedades]**](#parameterise-a-layer) de uma camada.
1. Alterne o parâmetro **[!UICONTROL ocultar]** se não for parametrizado anteriormente.
1. **Opcional:** renomeie o parâmetro ocultar.
1. Copie o nome do parâmetro ocultar.
1. Vá para o painel Parâmetro de outras camadas selecionando-as na tela e alterne o parâmetro **[!UICONTROL ocultar]** delas se não estiver parametrizado.
1. Substitua o nome do **[!UICONTROL parâmetro ocultar]** delas pelo nome copiado.
1. Clique em **[!UICONTROL Salvar]** para agrupar as camadas.
1. Execute a etapa 3 e depois a etapa 4 na seção [**[!UICONTROL Visualizar e publicar]**](#preview-and-publish-template-and-copy-template-deliver-url) para ver as alterações.

## Visualizar e publicar o modelo para copiar o URL de entrega{#preview-and-publish-template-and-copy-template-deliver-url}

Execute estas etapas para visualizar e publicar o modelo e copiar o URL de entrega:

1. Na página da tela, clique em **[!UICONTROL Visualizar]**. Também é possível navegar para o **[!UICONTROL Assets Essentials]** **>** **[!UICONTROL Dynamic Media Assets]** **>** localizar e selecionar o modelo **>** clicar em **[!UICONTROL Editar modelo]** **>** e clicar em **[!UICONTROL Visualizar]**. A página de visualização exibe o modelo, seus parâmetros (camadas e propriedades parametrizadas), status de publicação e a opção **[!UICONTROL Publicar]**.
1. Selecione parâmetros a partir do painel **[!UICONTROL Parâmetros do modelo]** para editar seus valores e atualizar instantaneamente o conteúdo, o tamanho, a posição ou a formatação de texto da camada de modelo correspondente na visualização. Por exemplo:
   1. Selecione uma camada de texto e edite seu texto ou
   1. Selecione uma camada de imagem, clique em ![Criar conteúdo rapidamente](/help/using/assets/add-image.svg), selecione uma imagem no seletor de ativos e clique em **[!UICONTROL Atualizar]**.

   O modelo é atualizado imediatamente, exibindo o texto editado e substituindo a imagem anterior pela nova. Além disso, o valor do parâmetro de imagem reflete o novo caminho de imagem. Da mesma forma, é possível redimensionar uma camada ajustando seus valores, e as alterações são aplicadas ao modelo em tempo real.
1. Selecione o parâmetro ocultar para [camadas agrupadas](#group-layers) da lista para exibi-las ou ocultá-las no modelo.
1. **Opcional:** altere o valor do parâmetro **[!UICONTROL Ocultar]** entre 0 e 1 e clique em **[!UICONTROL Atualizar]** para ver as alterações. Camadas com o mesmo parâmetro de ocultação são ocultadas ou exibidas em conjunto. Da mesma forma, é possível controlar a visibilidade das camadas a partir do URL.

   ![Criar conteúdo rapidamente](/help/using/assets/dm-templates-publish-status.png)
Você também pode ativar a opção **[!UICONTROL Incluir todos os parâmetros]** para editar todos os valores de parâmetros exibidos e ver as atualizações na visualização do modelo.
   <br>
1. Para publicar o modelo na página de visualização, clique em **[!UICONTROL Publicar]** e confirme para publicar. A mensagem Publicação concluída é exibida e o status de publicação é atualizado para Publicado.

>[!NOTE]
>
>Para publicar o modelo, é necessário que as imagens do modelo sejam publicadas primeiro.

### Copiar o URL de entrega

Os parâmetros selecionados na página **[!UICONTROL Visualização]** tornam-se os parâmetros de URL no URL de modelo.

Para copiar o URL do modelo publicado exibido na pré-visualização:

1. Clique em **[!UICONTROL Copiar URL]**. A caixa de diálogo **[!UICONTROL Copiar URL]** é exibida. Selecione e copie o URL exibido. Observe que o primeiro parâmetro no URL começa após um ponto de interrogação **(?)** e um par chave-valor começa com **$** e termina com **&amp;**. A chave e o valor são separados por um sinal de igual **(=)**, com a chave à esquerda e o valor à direita.
1. Cole esse URL na guia do navegador e veja seu modelo em tempo real. Personalize o modelo em tempo real atualizando o valor do parâmetro necessário (valor da chave) diretamente no URL, conforme demonstrado na [etapa 2](#preview-and-publish-template-and-copy-template-deliver-url) da seção **Visualizar e Publicar**.
1. Use este URL para um merchandising rápido de seus produtos ou serviços. Você pode compartilhar esse URL com seus clientes ou integrá-lo ao seu site ou a qualquer aplicativo downstream de terceiros para exibir o banner e fazer atualizações em tempo real nele para refletir as ofertas em andamento.

Saiba como criar um modelo do Dynamic Media passo a passo neste vídeo.
>[!VIDEO](https://video.tv.adobe.com/v/3443281)

## Faça atualizações em tempo real no modelo a partir do URL{#update-the-template-from-the-url}

Editar parâmetros diretamente no URL pode ser entediante. Para simplificar:

1. Copie o URL e cole-o em um bloco de notas.
1. Use Cmd+F (Mac) ou Ctrl+F (Windows) para localizar e editar os valores de parâmetro. Tais como:
   * Substituir caminhos de imagem para camadas de imagem.
   * Ajustar dimensões e posições da camada (se [parametrizada](#parameterise-a-layer)).
   * Editar texto, fonte, cor, tamanho ou alinhamento para camadas de texto.
   * Alterar valores de visibilidade entre 0 e 1.

Cole esse URL atualizado no navegador para visualizar as alterações.

## Editar o modelo{#edit-the-template}

Edite o modelo seguindo estas etapas:

1. No Assets Essentials, clique em **[!UICONTROL Ativos do Dynamic Media]**.
2. Acesse o local do modelo.
3. Selecione o modelo.
4. Clique em **[!UICONTROL Editar modelo]**. A tela de modelo exibe o modelo e a lista de todas as suas camadas no painel Camadas. Comece a editar o modelo de acordo com seus requisitos.

## Pontos importantes a observar {#important-points-to-note}

* Depois de criar um modelo com camadas de imagem parametrizadas para atualizações dinâmicas, verifique se as imagens destinadas a atualizações futuras compartilham as mesmas dimensões que as imagens parametrizadas. Isso garante que as imagens se encaixem perfeitamente nas camadas sem transbordar ou deixar espaços vazios. Atualmente, o modelo não oferece suporte a ajustes de dimensão automáticos para ajustar imagens às camadas.
* Não há suporte para substring em uma camada de texto. O usuário não pode aplicar propriedades de fonte diferentes em uma substring de uma camada de texto.
* No momento, o suporte a várias empresas do Dynamic Media não está disponível nos Modelos do Dynamic Media.
* Ao copiar ou mover, o Seletor de destino exibe todas as pastas (incluindo as pastas não sincronizadas com o Dynamic Media). Além disso, no momento, ele não exibe os ativos do Modelo do Dynamic Media (ambos são limitações do seletor de destino).
* Qualquer operação de atualização em uma pasta (por exemplo, Publicar ou Excluir) da seção Ativos afeta os Modelos do Dynamic Media disponíveis nessa pasta.
* A lixeira não funciona para Modelos do Dynamic Media. Se um ativo for movido para a lixeira e depois restaurado, ele será restaurado no AEM, mas não no Dynamic Media. O mesmo é válido para Modelos do Dynamic Media.

## Consulte também:

1. Explore o [Dynamic Media e seus recursos](https://experienceleague.adobe.com/pt-br/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media)
1. Explore o [Dynamic Media com recursos da OpenAPI](https://experienceleague.adobe.com/pt-br/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media-open-apis/dynamic-media-open-apis-overview)
