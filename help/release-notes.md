---
title: Notas de versão
description: Notas de versão e problemas conhecidos de [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: fd95cf87ae8e5449471cd580405b228c32ede264
workflow-type: tm+mt
source-wordcount: '275'
ht-degree: 1%

---


# Notas de versão de [!DNL Assets Essentials] {#release-notes}

A versão atual é a primeira versão pública do [!DNL Assets Essentials] que foi disponibilizada em 21 de junho de 2021. [!DNL Assets Essentials] O oferece recursos leves de gerenciamento de ativos e sua primeira versão oferece suporte aos seguintes principais recursos e operações CRUD (criar, ler, atualizar e excluir):

* Faça upload e adicione ativos, incluindo pastas aninhadas. Visualize os ativos e as versões.
* Pesquisa de texto completo, filtros de pesquisa aprimorados e pesquisas salvas para detecção rápida de ativos.
* Operações básicas de gerenciamento de ativos como atualizar, excluir, baixar e gerenciar metadados.
* Integração com [[!DNL Adobe Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html).

Atualmente, [!DNL Assets Essentials] está disponível para [[!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer.html) clientes.

Para saber mais sobre a solução, consulte a [introdução a [!DNL Assets Essentials]](introduction.md). Para começar a usar os recursos, consulte [começar](/help/get-started.md).

## Versão atual {#release-notes-current}

A versão atual do Assets Essentials é 2021.7.0, lançada em 29 de julho de 2021, com as seguintes atualizações:

* Você pode criar e gerenciar formulários de metadados personalizados a serem usados para exibir propriedades de metadados aos usuários na tela de detalhes do ativo na opção [!UICONTROL Metadata Forms] em [!DNL Settings].
* Várias correções de erros e aprimoramentos de produtos, incluindo melhor desempenho ao fazer upload de uma pasta aninhada com muitas subpastas.

## Problemas conhecidos {#known-issues}

A lista de problemas conhecidos da oferta [!DNL Assets Essentials] é revisada e atualizada continuamente:

* Para fazer upload de uma pasta ou ativos, ao arrastar os itens para uma pasta com subpastas no repositório, o upload vai para uma das subpastas automaticamente. A solução é clicar na opção [!DNL Upload assets] e arrastar para a caixa de diálogo. <!-- CQ-4327753 -->
* Após o upload da pasta, novas pastas podem, às vezes, ser exibidas incorretamente no painel à esquerda, em vez de na visualização em árvore. A solução alternativa é atualizar o navegador. <!-- CQ-4323534 -->

<!--
* Use assets that do not have whitespace in the file names. The replies to comments do not work for such assets.
-->

Se você encontrar problemas ou até mesmo solicitações de aprimoramento, [forneça feedback](#provide-feedback) para a equipe.
