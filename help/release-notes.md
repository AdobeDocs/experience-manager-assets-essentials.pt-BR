---
title: Notas de versão
description: Notas de versão e problemas conhecidos de [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: a72c3399fabd37c561f3c51e51029810d038ae40
workflow-type: tm+mt
source-wordcount: '420'
ht-degree: 1%

---

# Notas de versão de [!DNL Assets Essentials] {#release-notes}

A versão atual do [!DNL Assets Essentials] foi lançado em 3 de fevereiro de 2022. Com esta versão:

* [!DNL Assets Essentials] O agora permite gerar um link e compartilhar ativos com outras pessoas que não têm acesso ao [!DNL Assets Essentials] aplicativo. Você pode definir: <!-- CQ-4329575 -->

   * Uma data de expiração para o link

   * Se os recipients tiverem permissão para baixar o ativo depois de acessar o link.

   Com base nessas configurações, o recipient do link pode optar por visualizar ou baixar os ativos.

* Melhorias de desempenho para a [!UICONTROL Create Folder] operação. <!-- CQ-4338818 -->

## Problemas conhecidos {#known-issues}

A lista de problemas conhecidos de [!DNL Assets Essentials] A oferta é revista e atualizada continuamente:

* Nenhum

Se você encontrar problemas ou até solicitações de aprimoramento, [fornecer feedback](#provide-feedback) à equipe.

## Versões anteriores {#past-release}

### Versão 2021.11.0 {#november-2021}

[!DNL Assets Essentials] O foi lançado em 16 de dezembro de 2021, com as seguintes atualizações:

* O Adobe implanta o Assets Essentials automaticamente após concluir o processo de provisionamento. Os administradores não precisam executar etapas adicionais para implantar o Assets Essentials usando [!DNL Cloud Manager] interface do usuário. Essa implantação automática estará disponível para ambientes provisionados após 6 de janeiro de 2022.
* Novas versões de plug-ins do Creative Cloud que funcionam com o Assets Essentials estão disponíveis no Adobe Exchange - [Adobe Asset Link para Adobe XD v 2.1.0](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) e [Adobe Asset Link para Photoshop / InDesign / Illustrator v 3.1.65](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html).
* Vários bugfixes e aprimoramentos de produtos, incluindo problemas conhecidos anteriores (as pastas agora são exibidas corretamente na árvore de navegação esquerda após o upload<!-- CQ-4337638 -->, arrastar e soltar upload permite que o usuário selecione a pasta atual ou qualquer subpasta ao soltar para upload<!-- CQ-4327753 -->).

### Versão 2021.8.0 {#august2021}

[!DNL Assets Essentials] O 2021.8.0 foi lançado em 30 de agosto de 2021, com as seguintes atualizações:

* Integrações com [!DNL Adobe Workfront] que permite [!DNL Workfront] Os usuários do gerenciam seus ativos digitais no contexto do gerenciamento de seu trabalho. Para obter mais informações, consulte [integrações com outras soluções do Adobe](/help/integration.md).

### Versão 2021.7.0 {#july2021}

[!DNL Assets Essentials] O 2021.7.0 foi lançado em 29 de julho de 2021, com as seguintes atualizações:

* Você pode criar e gerenciar formulários de metadados personalizados a serem usados para exibir propriedades de metadados aos usuários na tela de detalhes do ativo em [!UICONTROL Metadata Forms] opção em [!DNL Settings]. Consulte [formulários de metadados](metadata.md#metadata-forms).
* Várias correções de erros e aprimoramentos de produtos, incluindo melhor desempenho ao fazer upload de uma pasta aninhada com muitas subpastas.

### Versão 2021.6.0 {#june2021}

A primeira versão do [!DNL Assets Essentials], disponibilizado em 21 de junho de 2021, oferece recursos leves de gerenciamento de ativos. Ele oferece suporte aos seguintes principais recursos e operações de CRUD (criar, ler, atualizar e excluir):

* Faça upload e adicione ativos, incluindo pastas aninhadas. Visualize os ativos e as versões.
* Pesquisa de texto completo, filtros de pesquisa aprimorados e pesquisas salvas para detecção rápida de ativos.
* Operações básicas de gerenciamento de ativos como atualizar, excluir, baixar e gerenciar metadados.
* [!DNL Assets Essentials] está disponível para [!DNL Adobe Journey Optimizer] usuários para gerenciar os ativos ao criar mensagens. Para obter mais informações, consulte [integrações com outras soluções do Adobe](/help/integration.md).
