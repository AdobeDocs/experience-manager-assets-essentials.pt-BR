---
title: Formatos de arquivo não suportados
description: Formatos de arquivo compatíveis com os vários casos de uso de [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: bc44e98d-446e-41ff-b5b4-9dc324834630
source-git-commit: b9d333a862cca6227ef386ae8dadf431c2fb6d71
workflow-type: tm+mt
source-wordcount: '308'
ht-degree: 16%

---

# Suporte para formatos de arquivos em [!DNL Assets Essentials] {#file-format-support}

[!DNL Assets Essentials] O suporta uma grande variedade de formatos de arquivo e cada funcionalidade tem suporte variado para diferentes tipos de arquivo.

* ![ícone de tipo de arquivo de imagem](assets/image-icon.svg) Imagens: JPG, PNG, GIF, TIFF e outros
* ![ícone creative cloudtype](assets/creative-cloud-files.svg) Arquivos Creative Cloud: PSD, AI e INDD
* ![ícone de tipo de câmera](assets/camera-icon.svg) Arquivos Camera Raw: CR2/CR3, NEF, SRW/SRF e outros
* ![ícone de tipo de arquivo do documento](assets/document-icon.svg) Documentos: DOCX, PDF, PPTX e XLSX
* ![ícone de tipo de arquivo de vídeo](assets/video-icon.svg) Vídeos: MP4

[!DNL Assets Essentials] O suporta qualquer formato de arquivo binário com serviços básicos, como armazenamento, upload, cópia, movimentação, exclusão e adição de metadados.

[!DNL Assets Essentials] também suporta arquivos RAW de câmera de uma grande variedade de principais fabricantes de câmeras, incluindo Canon (CR2/CR3), Nikon (NEF), Sony (SRW/SRF), FujiFilm (RAF), Olympus (ORF) e outros, fornecidos pela Adobe Camera Raw.

Os vários tipos de arquivos têm diferentes graus de suporte para os casos de uso e recursos, conforme descrito abaixo. Use a legenda para entender o nível de suporte.

| Nível de suporte | Descrição |
|-------------------|-------------------------|
| ✓ | Compatível |
| ✓ ‡ | Suportado condicionalmente |
| - | Não aplicável |

## Adicionar, carregar e exibir ativos {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| Tipo de ativo | [Navegar](/help/navigate-view.md) | Copiar | [Imagem](/help/add-delete.md) | Criar | [Excluir](/help/add-delete.md#delete-assets) | Detalhes | Zoom da imagem | [Visualizado recentemente](/help/navigate-view.md) |
|-------------------|----------|----------|----------|----------|----------|-------------------|------------|-----------------|
| Imagens rasteiras | ✓ | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| Arquivos RAW | ✓ | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| Pastas | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | - | - |
| Vídeos MP4 | ✓ | ✓ | ✓ | - | ✓ | ✓ ‡ | - | ✓ |
| PDF | ✓ | ✓ | ✓ | - | ✓ | ✓ | - | ✓ |
| PSD, AI e INDD | ✓ | ✓ | ✓ | - | ✓ | ✓ ‡ | - | ✓ |
| Outros arquivos binários | ✓ | ✓ | ✓ | - | ✓ | ✓ | - | ✓ |

<!-- Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## Pesquisar, usar e editar ativos {#support-to-search-use-edit}

| Tipo de ativo | [Download](/help/manage-organize.md#download) | Arrastar e soltar | [Editor de imagens](/help/edit-images.md) | [Pesquisar](/help/search.md) | [Tags inteligentes](/help/metadata.md#tags) | [Renomeie](/help/manage-organize.md) | [Versões](/help/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| Imagens rasteiras | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| Arquivos RAW | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ | ✓ |
| Pastas | ✓ | ✓ | - | ✓ | - | ✓ | ✓ |
| Vídeos | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| Bibliotecas CC | - | - | - | - | - | ✓ | ✓ |
| PDF | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| PSD, AI e INDD | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| Outros arquivos binários | ✓ | ✓ | - | ✓ | - | ✓ | ✓ |


## Revisar ativos e colaborar {#support-to-review-collaborate}

| Tipo de ativo | Anotar | Comentário | Criar tarefas e revisar |
|---------------|----------|----------|-------------------------|
| Imagens rasteiras | ✓ | ✓ | ✓ |
| Arquivos RAW | ✓ | ✓ | ✓ |
| Pastas | - | - | - |
| Vídeos | - | ✓ | ✓ |
| Bibliotecas CC | - | - | - |
| PDF | - | ✓ | ✓ |
| PSD, AI e INDD | - | ✓ | ✓ |
| Outros arquivos binários | - | ✓ | ✓ |

## Outras tarefas de gestão de ativos {#support-to-manage-assets}

| Tipo de ativo | [Metadados](/help/metadata.md) | [Representações](/help/add-delete.md#renditions) | [Lixeira](/help/add-delete.md#delete-assets) | Copiar | Mover |
|---------------|-------------------|------------|----------|----------|----------|
| Imagens rasteiras | ✓ | ✓ | ✓ | ✓ | ✓ |
| Arquivos RAW | ✓ | ✓ | ✓ | ✓ | ✓ |
| Pastas | ✓ | - | ✓ | ✓ | ✓ |
| Vídeos | ✓ | - | ✓ | ✓ | ✓ |
| Bibliotecas CC | ✓ | - | - | - | - |
| PDF | ✓ | - | ✓ | ✓ | ✓ |
| PSD, AI e INDD | ✓ | - | ✓ | ✓ | ✓ |
| Outros arquivos binários | ✓ | - | ✓ | ✓ | ✓ |

Usuários de [!DNL Adobe Asset Link] pode fazer upload e check-in (fazer upload de uma nova versão) de arquivos no [!DNL Assets Essentials] repositório do [!DNL Adobe Creative Cloud] aplicativos de desktop.

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
