---
title: Configurar o Assets Essentials para Creative Cloud Pro com soluções de gerenciamento de trabalho
description: 'Este tutorial apresenta uma jornada de administrador para permitir que o aplicativo Assets Essentials se integre aos aplicativos de desktop do Creative Cloud e ao aplicativo Adobe Workfront. Os aplicativos de desktop do Creative Cloud incluem Adobe Photoshop, Adobe Illustrator, Adobe InDesign e Adobe XD. '
source-git-commit: f4e56fc6bb76eeb2770b18be88b7da1a1829069c
workflow-type: tm+mt
source-wordcount: '900'
ht-degree: 10%

---


# Assets Essentials para Creative Cloud Pro com Soluções de Gerenciamento de Trabalho {#creative-cloud-enterprise-user-journeys}

![Preferência para alternar entre temas escuro e claro](assets/cce-next-banner-landing-page.png)

## Introdução {#introduction}

O Creative Cloud Pro para empresas com soluções de gerenciamento de trabalho integra ferramentas criativas, de conteúdo e de gerenciamento de trabalho para aumentar sua capacidade de produzir conteúdo criativo e atingir rapidamente as metas dos negócios. A solução inclui os seguintes componentes:

* Creative Cloud Pro

* Adobe Workfront

* Experience Manager Assets Essentials

Este tutorial apresenta uma jornada de administrador para permitir que o aplicativo Assets Essentials se integre aos aplicativos de desktop do Creative Cloud e ao aplicativo Adobe Workfront. Os aplicativos de desktop do Creative Cloud incluem Adobe Photoshop, Adobe Illustrator, Adobe InDesign e Adobe XD.

## Tipos de implantação {#deployment-types}

Como a solução consiste em aplicativos e serviços do Creative Cloud e da Adobe Experience Cloud, eles podem ser implantados em um ou dois Adobe Admin Console para sua empresa.

No caso de implantação em dois Admin Console, é necessária uma etapa de configuração adicional:

* Os serviços e aplicativos Creative Cloud (Creative Cloud para enterprise Pro e módulos opcionais) são gerenciados em [Adobe Admin Console para sua implantação do Creative Cloud](https://chl-author-preview.corp.adobe.com/content/help/en/enterprise/admin-guide.html).

* O Adobe Workfront e a Adobe Experience Manager Assets Essentials são gerenciados em [Adobe Admin Console para soluções Experience Cloud](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html).

Para integrar aplicativos Creative Cloud e Assets Essentials, os usuários disponíveis no Admin Console for Creative Cloud devem ser disponibilizados no Admin Console for Experience Cloud. Para disponibilizar os usuários no Experience Cloud Admin Console, crie um diretório para estabelecer [confiabilidade no diretório](https://helpx.adobe.com/enterprise/using/set-up-identity.html#directory-trusting) entre os dois consoles de administrador.

![Usuários da Creative Cloud](assets/creative-cloud-users.svg)

Conforme descrito no diagrama, os usuários do Creative Cloud são automaticamente disponibilizados no Admin Console de Experience Cloud com base em uma relação de confiança entre os dois consoles. Em seguida, é possível adicionar os usuários aos perfis de produto do Assets Essentials. Como resultado, os usuários do Creative Cloud podem acessar o aplicativo Adobe Asset Link que pode interagir com o repositório do Assets Essentials. Para obter mais informações, consulte [Integre o Assets Essentials aos aplicativos do Creative Cloud](integrate-assets-essentials-creative-cloud.md).

## jornadas de documentação do Experience Manager {#documentation-journeys}

Uma Jornada de Documentação reúne vários tópicos e recursos diferentes e talvez complexos, fornecendo uma narrativa que ajuda o leitor, que pode ser novo no Assets Essentials, a entender e resolver um problema de negócios do início ao fim, além de assumir um tópico anterior mínimo ou um conhecimento do Assets Essentials.

As Jornadas de documentação são projetadas com base nos princípios de práticas recomendadas, informadas pela pesquisa mais recente do Adobe, experiência comprovada de implementação de consultores de Adobe e feedback de projetos de clientes.

## Pré-requisitos

* [Acesso ao Adobe Admin Console para soluções Experience Cloud](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html)

* [Acesso ao Adobe Admin Console para Creative Cloud para implantação corporativa](https://helpx.adobe.com/enterprise/admin-guide.html)

## Administrar o Experience Manager Assets Essentials {#administer-assets-essentials}

![Preferência para alternar entre temas escuro e claro](assets/cce-assets.png)

O Adobe Experience Manager Assets Essentials é uma edição nova e leve dos ativos Adobe Experience Manager. O Assets Essentials fornece gerenciamento e colaboração unificados de ativos com uma interface do usuário simplificada e consistente. A facilidade de uso permite que mais equipes de criação e marketing armazenem, descubram e distribuam ativos digitais.

A Adobe Experience Manager Assets Essentials é provisionada pela Adobe para seus clientes. Como parte do provisionamento, a Assets Essentials é adicionada à organização de um cliente na Adobe Admin Console.

Os administradores usam o Admin Console para gerenciar os direitos do usuário para o produto Assets Essentials:

* Adicionar grupos de usuários

* Adicionar usuários a grupos de usuários

* Adicionar usuários aos perfis de produto do Assets Essentials

Após gerenciar os direitos do usuário no Admin Console, os administradores podem usar o aplicativo Assets Essentials para:

* Crie uma estrutura de pastas para atender melhor às necessidades da organização

* Gerenciar permissões para a estrutura de pastas

* Configurar formulários de metadados

[![Consulte o Guia](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](adminster-aem-assets-essentials.md)

## Integre aplicativos Creative Cloud com o Experience Manager Assets Essentials {#administer-creative-cloud-applications}

![Preferência para alternar entre temas escuro e claro](assets/cce-creative-cloud.png)

[Painel no aplicativo do Adobe Asset Link](https://www.adobe.com/creativecloud/business/enterprise/adobe-asset-link.html) permite que os profissionais de criação se conectem ao [!DNL Assets Essentials] repositório de dentro do [!DNL Adobe Creative Cloud] aplicativos de desktop. O painel está disponível para [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign] e [!DNL Adobe XD]. Ele simplifica o acesso a ativos, o que, por sua vez, aumenta a velocidade do conteúdo.

Este tutorial o orienta a integrar [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign]e [!DNL Adobe XD] aplicativos com o Experience Manager Assets Essentials.

Metas:

* Criar diretório confiável entre o Creative Cloud e o Experience Cloud Admin Console

* Adicionar usuários do Creative Cloud aos perfis de produto do Assets Essentials

* Instalar o Adobe Asset Link

* Usar Adobe Asset Link

[![Consulte o Guia](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-assets-essentials-creative-cloud.md)

## Integrar o Adobe Workfront com o Experience Manager Assets Essentials {#administer-adobe-workfront}

![Preferência para alternar entre temas escuro e claro](assets/cce-workfront.png)

[[!DNL Adobe Workfront]](https://www.workfront.com/) é um aplicativo de gerenciamento de trabalho que ajuda você a gerenciar todo o ciclo de vida do trabalho em um único local. A integração nativa entre [!DNL Adobe Workfront] e [!DNL Assets Essentials] permite que as organizações melhorem a velocidade do conteúdo e o tempo de comercialização ao conectar intrinsecamente o trabalho e o gerenciamento de ativos. No contexto do gerenciamento de trabalho, os usuários têm acesso aos documentos e imagens necessários na mesma solução.

Este tutorial o orienta a administrar o Adobe Workfront e a integrá-lo ao Experience Manager Assets Essentials.

Metas:

* Adicionar usuários aos perfis de produto do Workfront

* Adicionar usuários aos perfis de produto do Assets Essentials

* Configurar a integração do Experience Manager Assets Essentials

[![Consulte o Guia](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-assets-essentials-workfront.md)


