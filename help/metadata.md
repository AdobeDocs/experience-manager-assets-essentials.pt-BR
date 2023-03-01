---
title: Gerenciar metadados
description: Gerenciar metadados de ativos no  [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: cfc105d1-41fc-4418-9905-b2a28a348682
source-git-commit: fecbd1b05cc91148f41c576f4569f1799df6095e
workflow-type: ht
source-wordcount: '1252'
ht-degree: 100%

---

# Metadados no [!DNL Assets Essentials] {#metadata}

Os metadados são dados ou descrições sobre os dados. Por exemplo, suas imagens como um ativo podem conter informações sobre a câmera com a qual ela foi fotografada ou quaisquer informações de direitos autorais. Essas informações são os metadados da imagem. Os metadados são essenciais para um gerenciamento eficiente de ativos. Os metadados são a coleção de todos os dados disponíveis para um ativo, mas que podem não estar necessariamente contidos nesse ativo.

Os metadados ajudam a categorizar os ativos e são úteis à medida que a quantidade de informações digitais cresce. É possível gerenciar algumas centenas de arquivos com base apenas nos nomes de arquivo, miniaturas e memória. No entanto, essa abordagem não é escalável. Ela é limitada quando o número de pessoas envolvidas e o número de ativos gerenciados aumentam.

Com a adição de metadados, o valor de um ativo digital cresce, porque o ativo se torna,

* Mais acessível — os sistemas e usuários podem encontrá-lo facilmente.
* Mais fácil de gerenciar — é possível encontrar ativos com o mesmo conjunto de propriedades mais facilmente e realizar alterações neles.
* Completo — o ativo carrega mais informações e contexto com mais metadados.

Por esses motivos, o Assets fornece o meio certo de criar, gerenciar e trocar metadados para os seus ativos digitais.

## Visualizar os metadados {#view-metadata}

Para visualizar os metadados de um ativo, navegue até o ativo ou pesquise por ele, selecione-o e clique em **[!UICONTROL Detalhes]** na barra de ferramentas.

![Visualizar metadados de um ativo](assets/metadata-view1.png)

*Figura: para visualizar um ativo e seus metadados, clique em **[!UICONTROL Detalhes]** na barra de ferramentas ou clique duas vezes no ativo.*

Os metadados básicos, como título, descrição e data de upload estão disponíveis na guia [!UICONTROL Básico]. A guia [!UICONTROL Avançado] contém metadados mais avançados, como modelo de câmera, detalhes da lente e identificação geográfica. A guia [!UICONTROL Tags] contém tags aplicadas automaticamente com base no conteúdo da imagem.

## Atualizar metadados {#update-metadata}

É possível atualizar alguns campos de metadados manualmente. Os campos incluem [!UICONTROL Título], [!UICONTROL Descrição], [!UICONTROL Autor] e [!UICONTROL Palavras-chave].

## Tags {#tags}

O [!DNL Assets Essentials] usa a inteligência artificial fornecida pelo [Adobe Sensei](https://www.adobe.com/br/sensei.html) para aplicar automaticamente tags relevantes a todos os ativos carregados. Essas tags, devidamente chamadas de Tags inteligentes, aumentam a velocidade do conteúdo de seus projetos, ajudando você a encontrar ativos relevantes rapidamente. As tags inteligentes são um exemplo de metadados que não estão contidos na imagem.

As tags inteligentes são aplicadas em tempo quase real e geradas com base no conteúdo da imagem. Ao fazer upload de um ativo, a interface exibe [!UICONTROL Processando] na miniatura do ativo por algum tempo. Após concluir o processamento, é possível [visualizar os metadados](#view-metadata) e as tags inteligentes.

![Visualizar as Tags inteligentes de um ativo](assets/metadata-view-tags.png)

*Figura: para visualizar as Tags inteligentes de um ativo, clique em **[!UICONTROL Detalhes]** na barra de ferramentas ou clique duas vezes no ativo.*

As Tags inteligentes também contêm uma pontuação de confiança como uma porcentagem. Ela indica a confiança associada à tag aplicada. Você pode moderar as tags inteligentes aplicadas automaticamente.

## Adicionar ou atualizar tags {#manually-tag}

É possível adicionar mais tags aos seus ativos, além das Tags inteligentes que são adicionadas automaticamente usando o serviço inteligente do [!DNL Adobe Sensei]. Abra um ativo para pré-visualização, clique em [!UICONTROL Tags] e digite as palavras-chave desejadas no campo [!UICONTROL Palavras-chave]. Para adicionar a tag, pressione Return. O [!DNL Assets Essentials] indexa a palavra-chave em tempo quase real, e sua equipe poderá pesquisar os ativos atualizados em breve usando as novas palavras-chave.

Também é possível remover tags da seção [!UICONTROL Tags inteligentes] que são adicionadas automaticamente pelo [!DNL Assets Essentials] em todos os ativos carregados.

## Configurar formulários de metadados {#metadata-forms}

>[!CONTEXTUALHELP]
>id="assets_metadata_forms"
>title="Formulários de metadados"
>abstract="O [!DNL Experience Manager Assets] fornece vários campos padrão de metadados, por padrão. As organizações têm necessidades adicionais de metadados e precisam de mais campos para adicionar metadados específicos de negócios. Os formulários de metadados permitem que as empresas adicionem campos de metadados personalizados à página Detalhes de um ativo. Os metadados específicos de negócios melhoram a governança e a descoberta de ativos."

Por padrão, o Assets Essentials fornece vários campos de metadados padrão. As organizações têm necessidades adicionais de metadados e precisam de mais campos para adicionar metadados específicos de negócios. Os formulários de metadados permitem que as empresas adicionem campos de metadados personalizados à página [!UICONTROL Detalhes] de um ativo. Os metadados específicos de negócios melhoram a governança e a descoberta de ativos. É possível criar formulários do zero ou redefinir a finalidade de um formulário existente.

É possível configurar formulários de metadados para diferentes tipos de ativos (diferentes tipos de MIME). Use o mesmo nome de formulário como o tipo de MIME do arquivo. O Assets Essentials corresponde automaticamente os ativos carregados do tipo MIME ao nome do formulário e atualiza os metadados dos ativos carregados com base nos campos de formulário.

Por exemplo, se um formulário de metadados chamado `PDF` ou `pdf` existir, os documentos PDF carregados conterão campos de metadados conforme definidos no formulário.

O Assets Essentials usa a seguinte sequência ao pesquisar nomes de formulário de metadados existentes para aplicar os campos de metadados aos ativos carregados de um tipo específico:

Subtipo MIME > Tipo MIME > Formulário `default` > Formulário pronto para uso

Por exemplo, se um formulário de metadados chamado `PDF` ou `pdf` existir, os documentos PDF carregados contêm campos de metadados conforme definidos no formulário. Se não existir um formulário de metadados chamado `PDF` ou `pdf`, o Assets Essentials corresponderá se houver um formulário de metadados chamado `application`. Se houver um formulário de metadados chamado `application`, os documentos PDF carregados contêm campos de metadados conforme definidos no formulário. Se o Assets Essentials ainda não encontrar um formulário de metadados correspondente, ele pesquisará pelo formulário de metadados `default` para aplicar campos de metadados definidos no formulário aos documentos PDF carregados. Se nenhuma dessas etapas funcionar, o Assets Essentials aplicará os campos de metadados definidos no formulário pronto para uso a todos os documentos PDF carregados.

>[!IMPORTANT]
>
>O novo formulário de metadados para um tipo de arquivo específico substitui completamente o formulário de metadados padrão que o [!DNL Assets Essentials] fornece. Se você excluir ou renomear um formulário de metadados, os campos de metadados padrão estarão disponíveis novamente para novos ativos.

Para criar um formulário de metadados, siga estas etapas:

1. No painel à esquerda, clique em **[!UICONTROL Configurações]** > **[!UICONTROL Formulários de metadados]**.

   ![opção de formulários de metadados na barra lateral esquerda](assets/metadata-forms-sidebar.png)

1. Clique em **[!UICONTROL Criar]** na área superior direita da interface.
1. Forneça um nome para o formulário e clique em **[!UICONTROL Criar]**.
1. Forneça um nome para a guia em **[!UICONTROL Configurações]** no painel direito.
1. A partir do menu **[!UICONTROL Componentes]**, disponível no painel à esquerda, arraste os componentes necessários para uma guia do formulário. Arraste os componentes na sequência desejada.

   ![opção de formulários de metadados na barra lateral esquerda](assets/metadata-form-new.png)

   *Figura: a interface de criação do formulário de metadados com a opção de adicionar componentes e de pré-visualizar o formulário.*

1. Para cada componente, no campo Forneça um nome do menu **[!UICONTROL Configurações]** do painel direito, forneça um mapeamento com as propriedades compatíveis.
1. Opcionalmente, para um componente, selecione **[!UICONTROL Obrigatório]** para tornar o campo de metadados obrigatório e selecione **[!UICONTROL Somente leitura]** para transformá-lo em um campo não editável na página [!UICONTROL Detalhes] do ativo.
1. Opcionalmente, clique em **[!UICONTROL Pré-visualização]** para pré-visualizar o formulário que está sendo criado.
1. Como opção, adicione mais guias e os componentes necessários em cada guia.
1. Clique em **[!UICONTROL Salvar]** quando o formulário estiver finalizado.

Assista a este vídeo para ver a sequência de etapas:

>[!VIDEO](https://video.tv.adobe.com/v/341275)

Depois que um formulário é criado, ele é aplicado automaticamente quando os usuários carregam um ativo do tipo MIME correspondente.

Para reutilizar um formulário existente para criar um novo formulário, selecione um formulário de metadados, clique em **[!UICONTROL Copiar]** na barra de ferramentas, forneça um nome e clique em **[!UICONTROL Confirmar]**. É possível editar um formulário de metadados para alterá-lo. Quando você altera um formulário, ele é usado para ativos carregados após a alteração. Isso não altera os ativos existentes.

## Próximas etapas {#next-steps}

* [Assista a um vídeo sobre gerenciamento de formulários de metadados no Assets Essentials](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/configuring/metadata-forms.html?lang=pt-BR)

* Forneça feedback sobre o produto usando a opção de [!UICONTROL Feedback] disponível na interface do Assets Essentials

* Forneça feedback sobre a documentação usando as opções [!UICONTROL Editar esta página] ![editar a página](assets/do-not-localize/edit-page.png) ou [!UICONTROL Registrar um problema] ![criar um problema do GitHub](assets/do-not-localize/github-issue.png) disponíveis na barra lateral direita

* Entre em contato com o [Atendimento ao cliente](https://experienceleague.adobe.com/?support-solution=General&amp;lang=pt-BR#support)

<!-- TBD: Cannot create a form using the second option. Documenting only the first option for now.
To reuse an existing form to create a new form, do one of these:

* Select a metadata form and click **[!UICONTROL Copy]** from the toolbar, provide a name, and click **[!UICONTROL Confirm]**.

* Click **[!UICONTROL Create]**, select **[!UICONTROL Use existing form structure as template]** option, and select an existing form. 
-->

<!-- TBD: Queries for PM and engg.

Can we edit the existing metadata in any form?

How to moderate smart tags?

Allow or deny list for smart tags?

What about Tags displayed just above Smart Tags in the UI?

Is there a detailed metadata tab. Where do the other details of an asset go?

How can one search based strictly on the metadata. Similar to AEM Assets GQL queries.
-->

<!-- TBD: Link to related articles if any.

>[!MORELIKETHIS]
>
>* [Search assets](search.md).
-->
