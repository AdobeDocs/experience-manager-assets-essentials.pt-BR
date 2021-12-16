---
title: Notas de versão
description: Notas de versão e problemas conhecidos de [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 0c849c92562f9102819aaea627f5945030b27a1e
workflow-type: tm+mt
source-wordcount: '380'
ht-degree: 1%

---

# Notas de versão de [!DNL Assets Essentials] {#release-notes}

A versão atual do [!DNL Assets Essentials] foi lançado em 16 de dezembro de 2021. Com esta versão:

* O Adobe implanta o Assets Essentials automaticamente após concluir o processo de provisionamento. Os administradores não precisam executar etapas adicionais para implantar o Assets Essentials usando [!DNL Cloud Manager] interface do usuário. Essa implantação automática estará disponível para ambientes provisionados após 6 de janeiro de 2022.
* Novas versões de plug-ins do Creative Cloud que funcionam com o Assets Essentials estão disponíveis no Adobe Exchange - [Adobe Asset Link para Adobe XD v 2.1.0](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) e [Adobe Asset Link para Photoshop / InDesign / Illustrator v 3.1.65](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html).
* Vários bugfixes e aprimoramentos de produtos, incluindo problemas conhecidos anteriores (as pastas agora são exibidas corretamente na árvore de navegação esquerda após o upload<!-- CQ-4337638 -->, arrastar e soltar upload permite que o usuário selecione a pasta atual ou qualquer subpasta ao soltar para upload<!-- CQ-4327753 -->).

Para saber mais sobre a solução, consulte o [introdução ao [!DNL Assets Essentials]](introduction.md). Para começar a usar os recursos, consulte [introdução](/help/get-started.md).

## Problemas conhecidos {#known-issues}

A lista de problemas conhecidos de [!DNL Assets Essentials] A oferta é revista e atualizada continuamente:

* Os ativos individuais não podem ser carregados na pasta superior (Ativos), somente em qualquer subpasta no sistema. <!-- CQ-4337638 -->

Se você encontrar problemas ou até solicitações de aprimoramento, [fornecer feedback](#provide-feedback) à equipe.

## Versões anteriores {#past-release}

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
