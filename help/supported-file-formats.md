---
title: Formatos de arquivo não suportados
description: Formatos de arquivo suportados para os vários casos de uso de [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: c63e9ab1054398dc055643f0dca6631bae881047
workflow-type: tm+mt
source-wordcount: '206'
ht-degree: 24%

---


# Suporte para formatos de arquivos em [!DNL Assets Essentials] {#file-format-support}

[!DNL Assets Essentials] O suporta uma grande variedade de formatos de arquivo e cada funcionalidade tem suporte variado para diferentes tipos de arquivo.

* ![tipo de arquivo de imagem ](assets/do-not-localize/image-icon.png) iconImagens: GIF, JPG, PNG e TIFF
* ![ícone do tipo de arquivo do documento ](assets/do-not-localize/document-icon.png) Documentos: DOCX, PDF, PPTX e XLSX
* ![ícone de tipo de arquivo de vídeo ](assets/do-not-localize/video-icon.png) Vídeos: MP4

Os vários tipos de arquivos têm diferentes graus de suporte para os casos de uso e recursos, conforme descrito abaixo. Use a legenda para entender o nível de suporte.

| Nível de suporte | Descrição |
|-------------------|-------------------------|
| Instantâneo | Compatível |
| ‡ | Suportado condicionalmente |
| - | Não aplicável |

## Adicionar, carregar e exibir ativos {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| Tipo de ativo | [Navegar](/help/navigate-view.md) | Copiar | [Imagem](/help/add-delete.md) | Criar | [Excluir](/help/add-delete.md#delete-assets) | Detalhes | Zoom da imagem | [Visualizado recentemente](/help/navigate-view.md) |
|-------------------|----------|----------|----------|----------|----------|-------------------|------------|-----------------|
| Imagens rasteiras | Instantâneo | Instantâneo | Instantâneo | - | Instantâneo | Instantâneo | Instantâneo | Instantâneo |
| Pastas | Instantâneo | Instantâneo | Instantâneo | Instantâneo | Instantâneo | Instantâneo | - | - |
| Vídeos MP4 | Instantâneo | Instantâneo | Instantâneo | - | Instantâneo | ‡ | - | Instantâneo |
| PDF | Instantâneo | Instantâneo | Instantâneo | - | Instantâneo | Instantâneo | - | Instantâneo |
| PSD, AI e INDD | Instantâneo | Instantâneo | Instantâneo | - | Instantâneo | ‡ | - | Instantâneo |

<!-- Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## Pesquisar, usar e editar ativos {#support-to-search-use-edit}

| Tipo de ativo | [Download](/help/manage-organize.md#download) | Arrastar e soltar | [Editor de imagens](/help/edit-images.md) | [Pesquisar](/help/search.md) | [Tags inteligentes](/help/metadata.md#tags) | [Renomeie](/help/manage-organize.md) | [Versões](/help/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| Imagens rasteiras | Instantâneo | Instantâneo | Instantâneo | Instantâneo | Instantâneo | Instantâneo | Instantâneo |
| Pastas | Instantâneo | Instantâneo | - | Instantâneo | - | Instantâneo | - |
| Vídeos | Instantâneo | Instantâneo | - | Instantâneo | Instantâneo | Instantâneo | - |
| Bibliotecas CC | - | - | - | - | - | Instantâneo | - |
| PDF | Instantâneo | Instantâneo | - | Instantâneo | Instantâneo | Instantâneo | - |
| PSD | Instantâneo | Instantâneo | - | Instantâneo | Instantâneo | Instantâneo | - |
| AI | Instantâneo | Instantâneo | - | Instantâneo | Instantâneo | Instantâneo | - |
| INDD | Instantâneo | Instantâneo | - | Instantâneo | Instantâneo | Instantâneo | - |

## Revisar ativos e colaborar {#support-to-review-collaborate}

| Tipo de ativo | Anotar | Comentário | Criar tarefas e revisar |
|---------------|----------|----------|-------------------------|
| Imagens rasteiras | Instantâneo | Instantâneo | Instantâneo |
| Pastas | - | - | - |
| Vídeos | - | Instantâneo | Instantâneo |
| Bibliotecas CC | - | - | - |
| PDF | - | Instantâneo | Instantâneo |
| PSD | - | Instantâneo | Instantâneo |
| AI | - | Instantâneo | Instantâneo |
| INDD | - | Instantâneo | Instantâneo |

## Outras tarefas de gestão de ativos {#support-to-manage-assets}

| Tipo de ativo | [Metadados](/help/metadata.md) | [Representações](/help/add-delete.md#renditions) | [Lixeira](/help/add-delete.md#delete-assets) | Copiar | Mover |
|---------------|-------------------|------------|----------|----------|----------|
| Imagens rasteiras | Instantâneo | Instantâneo | Instantâneo | Instantâneo | Instantâneo |
| Pastas | Instantâneo | - | Instantâneo | Instantâneo | Instantâneo |
| Vídeos | Instantâneo | - | Instantâneo | Instantâneo | Instantâneo |
| Bibliotecas CC | Instantâneo | - | - | - | - |
| PDF | Instantâneo | - | Instantâneo | Instantâneo | Instantâneo |
| PSD | Instantâneo | - | Instantâneo | Instantâneo | Instantâneo |
| AI | Instantâneo | - | Instantâneo | Instantâneo | Instantâneo |
| INDD | Instantâneo | - | Instantâneo | Instantâneo | Instantâneo |

Os usuários de [!DNL Adobe Asset Link] podem fazer check-in das imagens raster no repositório [!DNL Assets Essentials] a partir dos aplicativos de desktop compatíveis [!DNL Adobe Creative Cloud].

<!-- TBD: Saving the template table separately for later use.
| Asset type    | Features |
|---------------|----------|
| Raster images |          |
| Folders       |          |
| Videos        |          |
| CC Libraries  |          |
| PDF files     |          |
| PSD           |          |
| AI            |          |
| INDD          |          |

>[!MORELIKETHIS]
>
>* []()
-->
