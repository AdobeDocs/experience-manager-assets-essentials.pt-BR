---
title: Gerenciar relatórios no Assets Essentials
description: Acesse os dados na seção de relatórios do Assets Essentials para avaliar o uso de produtos e recursos e obter insights sobre as principais métricas de sucesso.
exl-id: c7155459-05d9-4a95-a91f-a1fa6ae9d9a4
source-git-commit: 71a0381f5f7c32d3da1923778b3cd7b678391cae
workflow-type: tm+mt
source-wordcount: '862'
ht-degree: 100%

---

# Gerenciar relatórios {#manage-reports}

Os relatórios de ativos fornecem aos administradores visibilidade sobre as atividades do ambiente do Adobe Experience Manager Assets Essentials. Esses dados fornecem informações úteis sobre como os usuários interagem com o conteúdo e o produto. Todos os(as) usuários(as) podem acessar o painel Insights e aqueles que estiverem atribuídos(as) ao perfil de produto Administrador podem criar relatórios definidos pelo(a) usuário(a).

## Acessar relatórios {#access-reports}

Todos os usuários atribuídos ao [Perfil de produto de administradores do Assets Essentials](deploy-administer.md) podem acessar o painel Insights e criar relatórios definidos pelo usuário no Assets Essentials.

Para acessar os relatórios, navegue até **[!UICONTROL Relatórios]** em **[!UICONTROL Configurações]**.

![Relatórios](assets/reports.png)
<!--
In the **[!UICONTROL Reports]** screen, various components are shown in the tabular format which includes the following:

* **Title**: Title of the report
* **Type**: Determines whether the report is uploaded or downloaded to the repository
* **Description**: Provide details of the report that was given during uploading/downloading the report
* **Status**: Determines whether the report is completed, under progress, or deleted.
* **Author**: Provides email of the author who has uploaded/downloaded the report.
* **Created**: Gives information of the date when the report was generated.
-->

## Exibir o Insights {#view-live-statistics}

>[!CONTEXTUALHELP]
>id="assets_reports"
>title="Relatórios"
>abstract="O painel Insights permite visualizar as métricas de eventos em tempo real do seu ambiente do Experience Manager Assets nos últimos 30 dias ou nos últimos 12 meses. A lista de eventos inclui o número de downloads, uploads, principais pesquisas e assim por diante."

O Assets Essentials permite que você visualize dados do seu ambiente Assets Essentials em tempo real, por meio do painel Insights. Você pode visualizar métricas de evento em tempo real dos últimos 30 dias ou dos últimos 12 meses.

<!--![Toolbar options when you select an asset](assets/assets-essentials-live-statistics.png)-->

Clique na opção **[!UICONTROL Insights]**, disponível no painel de navegação esquerdo, para exibir os seguintes gráficos gerados automaticamente:

* **Downloads**: o número de ativos baixados do ambiente do Assets Essentials nos últimos 30 dias ou 12 meses representados por meio de um gráfico de linhas.
  ![downloads](/help/using/assets/insights-downloads2341.svg)

* **Uploads**: o número de ativos enviados para o ambiente do Assets Essentials nos últimos 30 dias ou 12 meses representados por meio de um gráfico de linhas.
  ![uploads](/help/using/assets/insights-uplods2.svg)

<!--* **Asset Count by Size**: The division of count of assets based on their range of various sizes from 0 MB to 100 GB.-->

* **Uso do armazenamento**: o uso de armazenamento (em bytes) no ambiente do Assets Essentials, representado por um gráfico de barras.
  ![utilização do armazenamento](/help/using/assets/insights-storage-usage1.svg)
  <!--* **Delivery**: The graph depicts the count of assets as the delivery dates.-->

<!--* **Asset Count by Asset Type**: Represents count of various MIME types of the available assets. For example, application/zip, image/png, video/mp4, application/postscripte.-->

* **Principais pesquisas**: visualize os principais termos pesquisados junto com o número de vezes que eles foram pesquisados em seu ambiente do Assets Essentials nos últimos 30 dias ou 12 meses representados em formato tabular.
  ![utilização do armazenamento](/help/using/assets/insights-top-search.svg)

  <!--
   ![Insights](assets/insights1.png)
   ![Insights](assets/insights2.png)
   -->

## Criar um relatório de downloads {#create-download-report}

Para criar um relatório de downloads:

1. Navegue até **[!UICONTROL Configurações]** > **[!UICONTROL Relatórios]** e clique em **[!UICONTROL Criar relatório]**.

1. Na guia [!UICONTROL Configuração], especifique o tipo de relatório como **[!UICONTROL Baixar]**.

1. Especifique um título e uma descrição opcional para o relatório.

1. Selecione o caminho da pasta que compreende os ativos para os quais o relatório será criado, usando o campo **[!UICONTROL Selecionar caminho da pasta]**.

1. Selecione o intervalo de datas do relatório.

   >[!NOTE]
   >
   > O Assets Essentials converte todos os fusos horários locais para o Tempo universal coordenado (UTC).

1. Na guia [!UICONTROL Colunas], selecione os nomes das colunas que devem ser exibidas no relatório.

1. Clique em **[!UICONTROL Criar]**

   ![Baixar relatório](assets/download-reports-config.png)

A tabela a seguir explica o uso de todas as colunas que você pode adicionar ao relatório:

<table>
    <tbody>
     <tr>
      <th><strong>Nome da coluna</strong></th>
      <th><strong>Descrição</strong></th>
     </tr>
     <tr>
      <td>Título</td>
      <td>O título do ativo.</td>
     </tr>
     <tr>
      <td>Caminho </td>
      <td>O caminho da pasta onde o ativo está disponível no Assets Essentials.</td>
     </tr>
     <tr>
      <td>Tipo MIME</td>
      <td>O tipo MIME do ativo.</td>
     </tr>
     <tr>
      <td>Tamanho</td>
      <td>O tamanho do ativo em bytes.</td>
     </tr>
     <tr>
      <td>Baixado por</td>
      <td>A ID do email do usuário que baixou o ativo.</td>
     </tr>
     <tr>
      <td>Data de download</td>
      <td>A data em que a ação de download do ativo foi executada.</td>
     </tr>
     <tr>
      <td>Autor</td>
      <td>O autor do ativo.</td>
     </tr>
     <tr>
      <td>Data de criação</td>
      <td>A data em que o ativo foi carregado para o Assets Essentials.</td>
     </tr>
     <tr>
      <td>Data da modificação</td>
      <td>A data em que o ativo foi modificado pela última vez.</td>
     </tr>
     <tr>
      <td>Expirado</td>
      <td>O status de expiração do ativo.</td>
     </tr>
     <tr>
      <td>Baixado por Nome de usuário</td>
      <td>O nome do usuário que baixou o ativo.</td>
     </tr>           
    </tbody>
   </table>

## Criar um relatório de uploads {#create-upload-report}

Para criar um relatório de uploads:

1. Navegue até **[!UICONTROL Configurações]** > **[!UICONTROL Relatórios]** e clique em **[!UICONTROL Criar relatório]**.

1. Na guia [!UICONTROL Configuração], especifique o tipo de relatório como **[!UICONTROL Fazer upload]**.

1. Especifique um título e uma descrição opcional para o relatório.

1. Selecione o caminho da pasta que compreende os ativos para os quais o relatório será criado, usando o campo **[!UICONTROL Selecionar caminho da pasta]**.

1. Selecione o intervalo de datas do relatório.

1. Na guia [!UICONTROL Colunas], selecione os nomes das colunas que devem ser exibidas no relatório.

1. Clique em **[!UICONTROL Criar]**.

   ![Relatório de uploads](assets/upload-reports-config.png)

A tabela a seguir explica o uso de todas as colunas que você pode adicionar ao relatório:

<table>
    <tbody>
     <tr>
      <th><strong>Nome da coluna</strong></th>
      <th><strong>Descrição</strong></th>
     </tr>
     <tr>
      <td>Título</td>
      <td>O título do ativo.</td>
     </tr>
     <tr>
      <td>Caminho </td>
      <td>O caminho da pasta onde o ativo está disponível no Assets Essentials.</td>
     </tr>
     <tr>
      <td>Tipo MIME</td>
      <td>O tipo MIME do ativo.</td>
     </tr>
     <tr>
      <td>Tamanho</td>
      <td>O tamanho do ativo.</td>
     </tr>
     <tr>
      <td>Autor</td>
      <td>O autor do ativo.</td>
     </tr>
     <tr>
      <td>Data de criação</td>
      <td>A data em que o ativo foi carregado para o Assets Essentials.</td>
     </tr>
     <tr>
      <td>Data da modificação</td>
      <td>A data em que o ativo foi modificado pela última vez.</td>
     </tr>
     <tr>
      <td>Expirado</td>
      <td>O status de expiração do ativo.</td>
     </tr>              
    </tbody>
   </table>

## Visualizar relatórios existentes {#view-report-list}

Depois de [criar o relatório](#create-download-report), é possível visualizar a lista de relatórios existentes e baixá-los em formato CSV ou excluí-los.

Para visualizar a lista de relatórios, navegue até **[!UICONTROL Configurações]** > **[!UICONTROL Relatórios]**.

É possível visualizar o título, o tipo, a descrição especificada durante a criação, o status, a ID de email do autor e a data de criação de cada relatório.

O status `Completed ` do relatório significa que ele está pronto para download.

![Lista de relatórios](assets/list-of-reports.png)


## Baixar um relatório em formato CSV {#download-csv-report}

Para baixar um relatório no formato CSV:

1. Navegue até **[!UICONTROL Configurações]** > **[!UICONTROL Relatórios]**.

1. Selecione um relatório e clique em **[!UICONTROL Baixar CSV]**.

O relatório selecionado é baixado no formato CSV. As colunas exibidas no relatório CSV dependem das colunas selecionadas ao [criar o relatório](#create-download-report).

## Excluir um relatório {#delete-report}

Para excluir um relatório:

1. Navegue até **[!UICONTROL Configurações]** > **[!UICONTROL Relatórios]**.

1. Selecione um relatório e clique em **[!UICONTROL Excluir]**.

1. Clique em **[!UICONTROL Excluir]** novamente para confirmar.
