---
title: Gerenciar relatórios no Assets Essentials
description: Use as informações nos relatórios do Assets Essentials para derivar as principais métricas de sucesso para medir a adoção dos Ativos na sua empresa e por clientes.
source-git-commit: 511b7904eca972e76f55e574c7c364dd88fb1721
workflow-type: tm+mt
source-wordcount: '515'
ht-degree: 4%

---

# Gerenciar relatórios {#manage-reports}

Os relatórios de ativos permitem que os administradores avaliem a utilidade da implantação do Adobe Experience Manager Assets Essentials. Os relatórios fornecem informações úteis sobre como os usuários interagem com ativos disponíveis na implantação.

Use as informações nos relatórios para derivar as principais métricas de sucesso para medir a adoção dos Ativos dentro da sua empresa e por clientes.

## Relatórios de acesso {#access-reports}

Todos os usuários atribuídos à variável [Perfil de produto Administradores do Assets Essentials](deploy-administer.md) O pode acessar estatísticas e relatórios em tempo real no Assets Essentials.

## Exibir estatísticas ao vivo {#view-live-statistics}

O Assets Essentials permite que você visualize dados de download gerados automaticamente para sua implantação do Assets Essentials. É possível optar por exibir o número de downloads de ativos realizados nos últimos 30 dias ou nos últimos 12 meses.

![Opções da barra de ferramentas ao selecionar um ativo](assets/asset-reports-live-statistics.png)

Navegar para **[!UICONTROL Configurações]** > **[!UICONTROL Estatísticas ao vivo]** para exibir os dados de download gerados automaticamente.

## Criar um relatório {#create-report}

Para criar um relatório:

1. Navegar para **[!UICONTROL Configurações]** > **[!UICONTROL Relatórios]** e clique em **[!UICONTROL Criar relatório]**.

1. No [!UICONTROL Configuração] , especifique um título e uma descrição opcional para o relatório.

1. Selecione o caminho da pasta, que compreende os ativos nos quais o relatório será executado, usando o **[!UICONTROL Selecionar caminho da pasta]** campo.

1. Selecione o intervalo de datas do relatório.

1. No [!UICONTROL Colunas] selecione os nomes das colunas que devem ser exibidas no relatório.

1. Clique em **[!UICONTROL Criar]**.

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
      <td>Caminho</td>
      <td>O caminho da pasta onde o ativo está disponível no Assets Essentials.</td>
     </tr>
     <tr>
      <td>Tipo</td>
      <td>O tipo MIME do ativo.</td>
     </tr>
     <tr>
      <td>Tamanho</td>
      <td>O tamanho do ativo.</td>
     </tr>
     <tr>
      <td>Baixado por</td>
      <td>A ID do email do usuário que baixou o ativo.</td>
     </tr>
     <tr>
      <td>Data de download</td>
      <td>A data em que a ação de download de ativo é executada.</td>
     </tr>
     <tr>
      <td>Autor</td>
      <td>O autor do ativo.</td>
     </tr>
     <tr>
      <td>Data de criação</td>
      <td>A data em que o ativo é carregado no Assets Essentials.</td>
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
      <td>Baixado por nome de usuário</td>
      <td>O nome do usuário que baixou o ativo.</td>
     </tr>           
    </tbody>
   </table>

## Exibir a lista de relatórios {#view-report-list}

Depois [criação do relatório](#create-report), é possível exibir a lista de relatórios e selecionar para baixá-los em um formato CSV ou excluí-los.

Para exibir a lista de relatórios, navegue até **[!UICONTROL Configurações]** > **[!UICONTROL Relatórios]**.

Para cada relatório, é possível visualizar o título do relatório, o tipo do relatório, a descrição especificada durante a criação do relatório, o status do relatório, a ID de email do autor que criou o relatório e a data de criação do relatório.

`Completed ` o status do relatório representa que o relatório está pronto para download.

![Lista de relatórios](assets/list-of-reports.png)


## Baixar um relatório CSV {#download-csv-report}

Para baixar um relatório no formato CSV:

1. Navegar para **[!UICONTROL Configurações]** > **[!UICONTROL Relatórios]**.

1. Selecione um relatório e clique em **[!UICONTROL Baixar CSV]**.

O relatório selecionado é baixado no formato CSV. As colunas exibidas no relatório CSV dependem das colunas selecionadas ao [criação do relatório](#create-report).

## Excluir um relatório {#delete-report}

Para excluir um relatório:

1. Navegar para **[!UICONTROL Configurações]** > **[!UICONTROL Relatórios]**.

1. Selecione um relatório e clique em **[!UICONTROL Excluir]**.
