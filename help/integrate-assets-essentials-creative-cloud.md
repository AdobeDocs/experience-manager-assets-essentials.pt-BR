---
title: Integre o Assets Essentials aos aplicativos do Creative Cloud
description: Integre o Assets Essentials aos aplicativos do Creative Cloud para que você possa usar o painel do link Adobe Asset no aplicativo para se conectar [!DNL Assets Essentials] repositório de dentro do [!DNL Adobe Creative Cloud] aplicativos de desktop.
source-git-commit: f4e56fc6bb76eeb2770b18be88b7da1a1829069c
workflow-type: tm+mt
source-wordcount: '854'
ht-degree: 4%

---


# Integre o Assets Essentials aos aplicativos do Creative Cloud {#integrate-assets-essentials-creative-cloud-applications}

![Preferência para alternar entre temas escuro e claro](assets/cce-creative-cloud.png)

## A história até agora

Depois [configuração do Experience Manager Assets Essentials](adminster-aem-assets-essentials.md) neste tutorial, você pode aproveitar a experiência para integrar os aplicativos do Creative Cloud com o Assets Essentials.

## Objetivo

* **Público**: Creative Cloud administradores

* **Objetivo**: Integre o Assets Essentials aos aplicativos do Creative Cloud para que seus usuários criativos possam usar o link Adobe Asset no painel do aplicativo para se conectar [!DNL Assets Essentials] repositório de dentro do [!DNL Adobe Creative Cloud] aplicativos de desktop.

## Visão geral

[Painel no aplicativo do Adobe Asset Link](https://www.adobe.com/creativecloud/business/enterprise/adobe-asset-link.html) permite que os profissionais de criação se conectem ao [!DNL Assets Essentials] repositório de dentro do [!DNL Adobe Creative Cloud] aplicativos de desktop. O painel está disponível para [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign] e [!DNL Adobe XD]. Ele simplifica o acesso aos ativos, o que, por sua vez, ajuda a aumentar a velocidade do conteúdo.

Os usuários do aplicativo do Creative Cloud podem usar o painel no aplicativo Adobe Asset Link somente quando você integra os aplicativos Creative Cloud com o repositório do Experience Manager Assets Essentials.

Execute as seguintes tarefas para integrar o Assets Essentials com aplicativos Creative Cloud:

* [Criar diretório confiável entre o Creative Cloud e o Experience Cloud Admin Console](#directory-trusting-cc-assets-essentials-consoles)

* [Adicionar usuários do Creative Cloud aos perfis de produto do Assets Essentials](#add-cc-users-assets-essentials-product-profiles)

* [Instalar o Adobe Asset Link](#install-asset-link)

* [Usar Adobe Asset Link](#use-asset-link)

## Criar diretório confiável entre o Creative Cloud e o Experience Cloud Admin Console {#directory-trusting-cc-assets-essentials-consoles}

Se o Creative Cloud for implantado em um Adobe Admin Console separado daquele com o Assets Essentials (solução Experience Cloud), será necessário adicionar um relacionamento de confiança entre os dois consoles.

Para integrar aplicativos Creative Cloud e Assets Essentials, os usuários disponíveis no Admin Console for Creative Cloud devem ser disponibilizados no Admin Console for Experience Cloud. Se o Creative Cloud e o Assets Essentials forem implantados em Admin Console separadas, a relação de confiança entre eles será necessária para habilitar isso.

No Experience Cloud Admin Console, clique em **[!UICONTROL Configurações]** e use o **[!UICONTROL Diretórios]** para criar um diretório para estabelecer [confiabilidade no diretório](https://helpx.adobe.com/enterprise/using/set-up-identity.html#directory-trusting) entre as duas Admin Console.

## Adicionar usuários do Creative Cloud aos perfis de produto do Assets Essentials {#add-cc-users-assets-essentials-product-profiles}

Depois de estabelecer a confiabilidade de diretório entre o Admin Console para o Creative Cloud e o Admin Console para o Experience Cloud, atribua os usuários do Creative Cloud para ao **[!DNL Assets Essentials]Usuários** perfil de produto sob [!DNL Assets Essentials] placa de produto no Experience Cloud. Isso permitirá que os usuários do Creative Cloud acessem o Assets Essentials a partir do painel de plug-in do Adobe Asset Link; além disso, ele dará acesso à interface completa do usuário da Web do Assets Essentials para fazer upload, organizar, marcar e encontrar ativos digitais usando um navegador da Web.

Outros perfis de produto do Assets Essentials - **[!DNL Assets Essentials]Administradores** e **[!DNL Assets Essentials]Usuários do consumidor** - são usados para diferentes direitos do usuário (administradores de aplicativos e usuários acessando o Assets Essentials por meio de integrações do Experience Cloud).

Para obter mais informações sobre como atribuir usuários a perfis de produtos do Assets Essentials, consulte [Atribuir usuários a perfis de produto do Assets Essentials](adminster-aem-assets-essentials.md#add-users-to-product-profiles).

## Instalar o Adobe Asset Link {#install-asset-link}

[!DNL Adobe Asset Link] O plug-in pode ser instalado e disponibilizado para usuários criativos de duas formas:

* Usuários criativos podem instalar o plug-in a partir de seus [!DNL Creative Cloud Desktop] aplicativo
* O administrador do Creative Cloud pode adicionar o plug-in Asset Link a um pacote Creative Cloud no Admin Console

A escolha depende das políticas de TI da organização.

**Instalação usando [!DNL Creative Cloud Desktop] aplicativo** é descrito [here](https://helpx.adobe.com/creative-cloud/kb/installingextensionsandaddons.html). Há dois plug-ins disponíveis e hospedados em [Adobe Exchange](https://exchange.adobe.com/) marketplace, dependendo do aplicativo Creative Cloud:

* Para [!DNL Adobe Photoshop], [!DNL Adobe Illustrator]e [!DNL Adobe InDesign]: [CEP do Adobe Asset Link](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)
* Para [!DNL Adobe XD]: [Adobe Asset Link](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)

**Instalação com um pacote de Creative Cloud** é feito pelo administrador do Creative Cloud no Admin Console, ao incluir o plug-in do Asset Link ao criar um pacote de implantação, que pode ser implantado posteriormente em máquinas do usuário. Na tela Escolher plug-ins gerenciados, procure por **Adobe Asset Link** no **Plug-ins comerciais em destaque** seção. Para obter mais informações, consulte [aplicativos de empacotamento via Admin Console](https://helpx.adobe.com/enterprise/using/package-apps-admin-console.html).

## Usar Adobe Asset Link {#use-asset-link}

Agora os usuários criativos podem usar o Adobe Asset Link com o Photoshop, Illustrator, InDesign ou XD. Para abrir o painel no InDesign ou Illustrator, acesse Windows > Extensões > Adobe Asset Link. No Photoshop, vá para Janela > Extensões (herdadas) > Adobe Asset Link.

Para obter informações sobre como configurar o Adobe Asset Link para o Adobe XD, clique em [here](https://helpx.adobe.com/enterprise/using/adobe-asset-link-for-xd.html).

>[!NOTE]
>
>Ao trabalhar no hardware Apple Silicon / M1, a Adobe Photoshop precisa ser iniciada usando o modo de compatibilidade Rosetta para garantir que os usuários criativos tenham acesso ao painel Adobe Asset Link, já que ele é criado usando a tecnologia de extensão CEP. Para obter mais informações, consulte [Photoshop para Silício do Apple](https://helpx.adobe.com/photoshop/kb/photoshop-for-apple-silicon.html).


Use o Adobe Asset Link para trabalhar com e modificar ativos armazenados no repositório do Assets Essentials. Você pode executar várias tarefas, como:

* Pesquisar e procurar ativos

* Fazer upload de ativos

* Classificar e filtrar ativos

* Inserir, baixar e arrastar um ativo

* Fazer check-out e check-in de um ativo

* Exibir o histórico da versão e os detalhes do arquivo

Para obter instruções sobre como executar essas tarefas, consulte [Gerenciar ativos usando o Adobe Asset Link](https://helpx.adobe.com/in/enterprise/using/manage-assets-using-adobe-asset-link.html).

## O que vem a seguir

Agora que você integrou os aplicativos Creative Cloud ao Assets Essentials, [integrar o Adobe Workfront com o Experience Manager Assets Essentials](integrate-assets-essentials-workfront.md).
