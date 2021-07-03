---
title: Formatos de arquivo não suportados
description: Formatos de arquivo suportados para os vários casos de uso de [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: e791ef4ffdfdad907b5e868b3f3eab0c597ae4cd
workflow-type: tm+mt
source-wordcount: '196'
ht-degree: 26%

---


# Suporte para formatos de arquivos em [!DNL Assets Essentials] {#file-format-support}

[!DNL Assets Essentials] O suporta uma grande variedade de formatos de arquivo e cada funcionalidade tem suporte variado para diferentes tipos de arquivo.

* ![tipo de arquivo de imagem ](assets/do-not-localize/image-icon.png) iconImagens: GIF, JPG, PNG e TIFF
* ![ícone do tipo de arquivo do documento ](assets/do-not-localize/document-icon.png) Documentos: DOCX, PDF, PPTX e XLSX
* ![ícone de tipo de arquivo de vídeo ](assets/do-not-localize/video-icon.png) Vídeos: MP4

Os vários tipos de arquivos têm diferentes graus de suporte para os casos de uso e recursos, conforme descrito abaixo. Use a legenda para entender o nível de suporte.

| Nível de suporte | Descrição |
|---------------|-------------------------|
| Instantâneo | Compatível |
| * | Suportado condicionalmente |
| - | Não aplicável |

* Outras tarefas de gestão de ativos:

## Adicionar, carregar e exibir ativos {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| Tipo de ativo | Procurar | Copiar | Imagem | Criar | Excluir | Detalhes | Zoom da imagem | Visualizado recentemente |
|---------------|----------|----------|----------|----------|----------|----------|------------|-----------------|
| Imagens rasteiras | Instantâneo | Instantâneo | Instantâneo | - | Instantâneo | Instantâneo | Instantâneo | Instantâneo |
| Pastas | Instantâneo | Instantâneo | Instantâneo | Instantâneo | Instantâneo | Instantâneo | - | - |
| Vídeos | Instantâneo | Instantâneo | Instantâneo | - | Instantâneo | * | - | Instantâneo |
| Bibliotecas CC | Instantâneo | - | Instantâneo | Instantâneo | Instantâneo | Instantâneo | - | - |
| PDF | Instantâneo | Instantâneo | Instantâneo | - | Instantâneo | Instantâneo | - | Instantâneo |
| PSD | Instantâneo | Instantâneo | Instantâneo | - | Instantâneo | * | - | Instantâneo |
| AI | Instantâneo | Instantâneo | Instantâneo | - | Instantâneo | * | - | Instantâneo |
| INDD | Instantâneo | Instantâneo | Instantâneo | - | Instantâneo | * | - | Instantâneo |

## Pesquisar, usar e editar ativos {#support-to-search-use-edit}

| Tipo de ativo | Download | Arrastar e soltar | Editor de imagens | Pesquisar   | Tags inteligentes | Renomeie | Versões |
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

| Tipo de ativo | Metadados | Representações | Lixeira | Copiar | Mover | [!DNL Adobe Asset Link] check-in |
|---------------|----------|------------|----------|----------|----------|----------------------------------|
| Imagens rasteiras | * | Instantâneo | Instantâneo | Instantâneo | Instantâneo | Instantâneo |
| Pastas | * | - | Instantâneo | Instantâneo | Instantâneo | - |
| Vídeos | * | - | Instantâneo | Instantâneo | Instantâneo | - |
| Bibliotecas CC | * | - | - | - | - | - |
| PDF | * | - | Instantâneo | Instantâneo | Instantâneo | - |
| PSD | * | - | Instantâneo | Instantâneo | Instantâneo | - |
| AI | * | - | Instantâneo | Instantâneo | Instantâneo | - |
| INDD | * | - | Instantâneo | Instantâneo | Instantâneo | - |

<!-- TBD: Saving template table separately.
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
