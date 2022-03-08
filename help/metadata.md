---
title: Gerenciar metadados
description: Gerenciar metadados de ativos no [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: cfc105d1-41fc-4418-9905-b2a28a348682
source-git-commit: cd7af0c946a042430e62528fa6aa19bdab139f67
workflow-type: tm+mt
source-wordcount: '962'
ht-degree: 0%

---

# Metadados em [!DNL Assets Essentials] {#metadata}

Metadados significa dados ou descrição sobre os dados. Por exemplo, suas imagens como um ativo podem conter informações sobre a câmera com a qual ele foi clicado ou quaisquer informações de direitos autorais. Essas informações são metadados da imagem. Os metadados são essenciais para um gerenciamento eficiente de ativos. Metadados é a coleta de todos os dados disponíveis para um ativo, mas pode não estar necessariamente contida nesse ativo.

Os metadados ajudam a categorizar os ativos e são úteis à medida que a quantidade de informações digitais cresce. É possível gerenciar algumas centenas de arquivos com base apenas nos nomes de arquivo, miniaturas e memória. No entanto, essa abordagem não é escalável. Fica aquém de quando o número de pessoas envolvidas e o número de ativos gerenciados aumentam.

Com a adição de metadados, o valor de um ativo digital cresce, porque o ativo se torna,

* Mais acessível - os sistemas e usuários podem encontrá-lo facilmente.
* Mais fácil de gerenciar: é possível encontrar ativos com o mesmo conjunto de propriedades mais facilmente e aplicar alterações a eles.
* Concluído - o ativo carrega mais informações e contexto com mais metadados.

Por esses motivos, o Assets fornece o meio certo de criar, gerenciar e trocar metadados para seus ativos digitais.

## Visualizar os metadados {#view-metadata}

Para exibir os metadados de um ativo, navegue até o ativo ou pesquise o ativo, selecione o ativo e clique em **[!UICONTROL Detalhes]** na barra de ferramentas.

![Exibir metadados de um ativo](assets/metadata-view1.png)

*Figura: Para exibir um ativo e seus metadados, clique em **[!UICONTROL Detalhes]**na barra de ferramentas ou clique duas vezes no ativo.*

Os metadados básicos, como título, descrição e data de upload, estão disponíveis na variável [!UICONTROL Básico] guia . O [!UICONTROL Avançado] A guia contém metadados mais avançados, como modelo de câmera, detalhes da lente e geotags. O [!UICONTROL Tags] contém tags aplicadas automaticamente com base no conteúdo da imagem.

## Atualizar metadados {#update-metadata}

Você pode atualizar alguns campos de metadados manualmente. Os campos incluem [!UICONTROL Título], [!UICONTROL Descrição], [!UICONTROL Autor]e [!UICONTROL Palavras-chave].

## Tags {#tags}

[!DNL Assets Essentials] usa inteligência artificial fornecida pelo [Adobe Sensei](https://www.adobe.com/br/sensei.html) para aplicar automaticamente tags relevantes a todos os ativos carregados. Essas tags, devidamente chamadas de Tags inteligentes, aumentam a velocidade do conteúdo de seus projetos, ajudando você a encontrar ativos relevantes rapidamente. As tags inteligentes são um exemplo de metadados que não estão contidos na imagem.

As tags inteligentes são aplicadas em tempo quase real e geradas com base no conteúdo da imagem. Ao fazer upload de um ativo, a interface do usuário é exibida [!UICONTROL Processamento] na miniatura do ativo por algum tempo. Após concluir o processamento, é possível [exibir os metadados](#view-metadata) e as tags inteligentes.

![Exibir tags inteligentes de um ativo](assets/metadata-view-tags.png)

*Figura: Para exibir as Tags inteligentes de um ativo, clique em **[!UICONTROL Detalhes]**na barra de ferramentas ou clique duas vezes no ativo.*

Tags inteligentes também contêm uma pontuação de confiança como uma porcentagem. Indica a confiança associada à tag aplicada. Você pode moderar as tags inteligentes aplicadas automaticamente.

## Adicionar ou atualizar tags {#manually-tag}

Você pode adicionar mais tags aos seus ativos, além das Tags inteligentes que são adicionadas automaticamente usando o [!DNL Adobe Sensei] serviço inteligente. Abra um ativo para visualização, clique em [!UICONTROL Tags]e digite as palavras-chave desejadas na [!UICONTROL Palavras-chave] campo. Para adicionar a tag , pressione Return. [!DNL Assets Essentials] indexa a palavra-chave em tempo quase real e sua equipe poderá pesquisar os ativos atualizados em breve usando as novas palavras-chave.

Você também pode remover tags do [!UICONTROL Tags inteligentes] seção que é adicionada automaticamente por [!DNL Assets Essentials] para todos os ativos carregados.

## Formulários de metadados {#metadata-forms}

O Assets Essentials fornece vários campos de metadados padrão por padrão. As organizações têm necessidades adicionais de metadados e precisam de mais campos de metadados para adicionar metadados específicos de negócios. Os formulários de metadados permitem que as empresas adicionem campos de metadados personalizados a um ativo [!UICONTROL Detalhes] página. Os metadados específicos de negócios melhoram a governança e a descoberta de seus ativos.

Você pode configurar formulários de metadados para diferentes tipos de ativos (diferentes tipos MIME). Use o mesmo nome de formulário do tipo MIME do arquivo. O Essentials corresponde automaticamente os ativos carregados ao nome do formulário. Por exemplo, se um formulário de metadados for usado pelo nome `PDF` ou `pdf` existir, os documentos PDF carregados contêm campos de metadados, conforme definido no formulário. É possível criar formulários do zero ou redefinir a finalidade de um formulário existente.

>[!IMPORTANT]
>
>O novo formulário de metadados para um tipo de arquivo específico substitui completamente o formulário de metadados padrão que [!DNL Assets Essentials] fornece. Se você excluir ou renomear um formulário de metadados, os campos de metadados padrão estarão disponíveis novamente para novos ativos.

Para criar um formulário de metadados, siga estas etapas:

1. No painel à esquerda, clique em **[!UICONTROL Configurações]** > **[!UICONTROL Forms de metadados]**.

   ![opção de formulários de metadados na barra lateral esquerda](assets/metadata-forms-sidebar.png)

1. Clique em **[!UICONTROL Criar]**, na área superior direita da interface do usuário do .
1. Forneça um nome para o formulário e clique em **[!UICONTROL Criar]**.
1. Forneça um nome para a guia em **[!UICONTROL Configurações]** no painel direito.
1. No **[!UICONTROL Componentes]** disponível no painel à esquerda, arraste os componentes necessários em uma guia do formulário. Arraste os componentes na sequência desejada.

   ![opção de formulários de metadados na barra lateral esquerda](assets/metadata-form-new.png)

   *Figura: A interface de criação do formulário de metadados com opções para adicionar componentes e opções para visualizar o formulário.*

1. Para cada componente, no , forneça um nome na função **[!UICONTROL Configurações]** no painel direito, forneça um mapeamento com as propriedades compatíveis.
1. Opcionalmente, para um componente, selecione **[!UICONTROL Obrigatório]** para tornar o campo de metadados obrigatório e selecione **[!UICONTROL Somente leitura]** para tornar o campo ineditável no ativo [!UICONTROL Detalhes] página.
1. Opcionalmente, clique em **[!UICONTROL Visualizar]** para visualizar o formulário que está sendo criado.
1. Como opção, adicione mais guias e os componentes necessários em cada guia.
1. Clique em **[!UICONTROL Salvar]** quando o formulário for preenchido.

Depois que um formulário é criado, ele é aplicado automaticamente quando os usuários carregam um ativo do tipo MIME correspondente.

Para reutilizar um formulário existente para criar um novo formulário, selecione um formulário de metadados, clique em **[!UICONTROL Copiar]** na barra de ferramentas, forneça um nome e clique em **[!UICONTROL Confirmar]**. É possível editar um formulário de metadados para alterá-lo. Quando você altera um formulário, ele é usado para ativos carregados após a alteração. Não altera os ativos existentes.

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
