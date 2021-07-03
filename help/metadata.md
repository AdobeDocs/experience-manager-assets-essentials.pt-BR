---
title: Gerenciar metadados
description: Gerenciar metadados de ativos em [!DNL Assets Essentials]
role: User,Leader,Administrator,Architect,Developer
contentOwner: AG
source-git-commit: 5bae37e18ac587aaacaa004e5ec02775888d7f9a
workflow-type: tm+mt
source-wordcount: '544'
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

Para exibir os metadados de um ativo, navegue até o ativo ou pesquise o ativo, selecione o ativo e clique em **[!UICONTROL Details]** na barra de ferramentas.

![Exibir metadados de um ativo](assets/metadata-view1.png)

*Figura: Para exibir um ativo e seus metadados, clique em **[!UICONTROL Details]**na barra de ferramentas ou clique duas vezes no ativo.*

Os metadados básicos, como título, descrição e data de upload, estão disponíveis na guia [!UICONTROL Basic]. A guia [!UICONTROL Advanced] contém metadados mais avançados, como modelo de câmera, detalhes da lente e geotags. A guia [!UICONTROL Tags] contém tags aplicadas automaticamente com base no conteúdo da imagem.

## Atualizar metadados {#update-metadata}

Você pode atualizar alguns campos de metadados manualmente. Os campos incluem [!UICONTROL Title], [!UICONTROL Description], [!UICONTROL Author] e [!UICONTROL Keywords].

## Tags {#tags}

[!DNL Assets Essentials] O usa inteligência artificial fornecida pelo  [Adobe ](https://www.adobe.com/br/sensei.html) Senseito para aplicar automaticamente tags relevantes a todos os ativos carregados. Essas tags, devidamente chamadas de Tags inteligentes, aumentam a velocidade do conteúdo de seus projetos, ajudando você a encontrar ativos relevantes rapidamente. As tags inteligentes são um exemplo de metadados que não estão contidos na imagem.

As tags inteligentes são aplicadas em tempo quase real e geradas com base no conteúdo da imagem. Ao fazer upload de um ativo, a interface do usuário exibe [!UICONTROL Processing] na miniatura do ativo por algum tempo. Quando o processamento estiver concluído, você poderá [visualizar os metadados](#view-metadata) e as tags inteligentes.

![Exibir tags inteligentes de um ativo](assets/metadata-view-tags.png)

*Figura: Para exibir as Tags inteligentes de um ativo, clique em **[!UICONTROL Details]**na barra de ferramentas ou clique duas vezes no ativo.*

Tags inteligentes também contêm uma pontuação de confiança como uma porcentagem. Indica a confiança associada à tag aplicada. Você pode moderar as tags inteligentes aplicadas automaticamente.

## Adicionar ou atualizar tags {#manually-tag}

Você pode adicionar mais tags aos seus ativos, além das Tags inteligentes que são adicionadas automaticamente usando o serviço inteligente [!DNL Adobe Sensei]. Abra um ativo para visualização, clique em [!UICONTROL Tags] e digite as palavras-chave desejadas no campo [!UICONTROL Keywords]. Para adicionar a tag , pressione Return. [!DNL Assets Essentials] indexa a palavra-chave em tempo quase real e sua equipe poderá pesquisar os ativos atualizados em breve usando as novas palavras-chave.

Você também pode remover tags da seção [!UICONTROL Smart Tags] que são adicionadas automaticamente por [!DNL Assets Essentials] a todos os ativos carregados.

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
