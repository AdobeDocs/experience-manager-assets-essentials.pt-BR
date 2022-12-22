---
title: Integrar o Assets Essentials aos aplicativos da Creative Cloud
description: Integre o Assets Essentials aos aplicativos da Creative Cloud para que você possa usar o painel no aplicativo do Adobe Asset Link para se conectar ao repositório do  [!DNL Assets Essentials]  de dentro dos aplicativos de desktop compatíveis da  [!DNL Adobe Creative Cloud] .
exl-id: 817bc955-0074-435e-83a8-3fd5f7f2505a
source-git-commit: 6194a778133842d40c4ef2bc257eec8a34b0a481
workflow-type: ht
source-wordcount: '761'
ht-degree: 100%

---

# Integrar o Assets Essentials aos aplicativos da Creative Cloud {#integrate-assets-essentials-creative-cloud-applications}

[O painel no aplicativo do Adobe Asset Link](https://www.adobe.com/br/creativecloud/business/enterprise/adobe-asset-link.html) permite que os profissionais de criação se conectem ao repositório do [!DNL Assets Essentials] de dentro dos aplicativos de desktop compatíveis da [!DNL Adobe Creative Cloud]. O painel está disponível para [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign] e [!DNL Adobe XD]. Ele simplifica o acesso aos ativos, o que, por sua vez, ajuda a aumentar a velocidade do conteúdo.

Os usuários do aplicativo da Creative Cloud podem usar o painel no aplicativo do Adobe Asset Link somente quando você integra os aplicativos da Creative Cloud ao repositório do Experience Manager Assets Essentials.

Execute as seguintes tarefas para integrar o Assets Essentials aos aplicativos da Creative Cloud:

* [Crie confiabilidade de diretório entre o Admin Console da Creative Cloud e o Admin Console da Experience Cloud](#directory-trusting-cc-assets-essentials-consoles)

* [Adicionar usuários da Creative Cloud aos perfis de produto do Assets Essentials](#add-cc-users-assets-essentials-product-profiles)

* [Instalar o Adobe Asset Link](#install-asset-link)

* [Usar o Adobe Asset Link](#use-asset-link)

## Criar confiabilidade de diretório entre o Admin Console da Creative Cloud e o Admin Console da Experience Cloud {#directory-trusting-cc-assets-essentials-consoles}

Se a Creative Cloud for implantada em uma instância do Adobe Admin Console diferente da utilizada com o Assets Essentials (solução da Experience Cloud), será necessário adicionar um relacionamento de confiança entre os dois consoles.

Para integrar aplicativos da Creative Cloud e do Assets Essentials, os usuários disponíveis no Admin Console da Creative Cloud devem ser disponibilizados no Admin Console da Experience Cloud. Se a Creative Cloud e o Assets Essentials forem implantados em diferentes instâncias do Admin Console, será necessário criar uma relação de confiança entre elas.

No Admin Console da Experience Cloud, clique em **[!UICONTROL Configurações]** e use a guia **[!UICONTROL Diretórios]** para criar um diretório e estabelecer [confiabilidade de diretório](https://helpx.adobe.com/br/enterprise/using/set-up-identity.html#directory-trusting) entre as duas instâncias do Admin Console.

## Adicionar usuários da Creative Cloud aos perfis de produto do Assets Essentials {#add-cc-users-assets-essentials-product-profiles}

Depois de estabelecer a confiabilidade de diretório entre o Admin Console da Creative Cloud e o Admin Console da Experience Cloud, atribua o perfil de produto dos usuários do **[!DNL Assets Essentials]** aos usuários da Creative Cloud, por meio do cartão de produto do [!DNL Assets Essentials] no Admin Console da Experience Cloud. Isso permitirá que os usuários da Creative Cloud acessem o Assets Essentials a partir do painel de plug-in do Adobe Asset Link; além disso, isso lhes concederá acesso à interface web completa do Assets Essentials para fazer upload, organizar, marcar e encontrar ativos digitais usando um navegador da web.

Outros perfis de produto do Assets Essentials, como administradores do **[!DNL Assets Essentials]** e usuários consumidores do **[!DNL Assets Essentials]**, são usados para diferentes direitos de usuário (administradores de aplicativos e usuários que acessam o Assets Essentials por meio de integrações da Experience Cloud).

Para obter mais informações sobre como atribuir usuários a perfis de produtos do Assets Essentials, consulte [Atribuir usuários a perfis de produto do Assets Essentials](deploy-administer.md#add-users-to-product-profiles).

## Instalar o Adobe Asset Link {#install-asset-link}

O plug-in do [!DNL Adobe Asset Link] pode ser instalado e disponibilizado aos usuários de criação de duas maneiras:

* Os usuários de criação podem instalar o plug-in a partir de seus aplicativos da [!DNL Creative Cloud Desktop]
* O administrador da Creative Cloud pode adicionar o plug-in do Asset Link a um pacote da Creative Cloud no Admin Console

A escolha depende das políticas de TI da organização.

**A instalação usando o aplicativo da [!DNL Creative Cloud Desktop]** é descrita [aqui](https://helpx.adobe.com/br/creative-cloud/kb/installingextensionsandaddons.html). Há dois plug-ins disponíveis e hospedados no Marketplace do [Adobe Exchange](https://exchange.adobe.com/), dependendo do aplicativo da Creative Cloud:

* Para o [!DNL Adobe Photoshop], [!DNL Adobe Illustrator] e [!DNL Adobe InDesign]: [Adobe Asset Link CEP](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)
* Para o [!DNL Adobe XD]: [Adobe Asset Link](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)

**A instalação com um pacote da Creative Cloud** é feita pelo administrador da Creative Cloud no Admin Console, o qual inclui o plug-in do Asset Link ao criar um pacote de implantação, que pode ser implantado posteriormente nas máquinas dos usuários. Na tela Escolher plug-ins gerenciada, pesquise por **Adobe Asset Link** na seção **Plug-ins comerciais em destaque**. Para obter mais informações, consulte [Criação de pacotes de aplicativos no Admin Console](https://helpx.adobe.com/br/enterprise/using/package-apps-admin-console.html).

## Usar o Adobe Asset Link {#use-asset-link}

Agora, os usuários de criação podem usar o Adobe Asset Link com o Photoshop, Illustrator, InDesign ou XD. Para abrir o painel no InDesign ou Illustrator, acesse Windows > Extensões > Adobe Asset Link. No Photoshop, acesse Janela > Extensões (herdadas) > Adobe Asset Link.

Para obter mais informações sobre como configurar o Adobe Asset Link para o Adobe XD, clique [aqui](https://helpx.adobe.com/br/enterprise/using/adobe-asset-link-for-xd.html).

>[!NOTE]
>
>Ao trabalhar em um hardware Apple Silicon/M1, o Adobe Photoshop precisa ser iniciado usando o modo de compatibilidade Rosetta, para garantir que os usuários de criação tenham acesso ao painel Adobe Asset Link, já que ele é construído usando a tecnologia de extensão CEP. Para obter mais informações, consulte [Photoshop para Apple Silicon](https://helpx.adobe.com/br/photoshop/kb/photoshop-for-apple-silicon.html).


Use o Adobe Asset Link para modificar e trabalhar com ativos armazenados no repositório do Assets Essentials. É possível executar várias tarefas, como:

* Pesquisar e navegar pelos ativos

* Fazer upload de ativos

* Classificar e filtrar ativos

* Colocar, baixar e arrastar um ativo

* Fazer check-out e check-in de um ativo

* Exibir o histórico da versão e os detalhes do arquivo

Para obter instruções sobre como executar essas tarefas, consulte [Gerenciar ativos usando o Adobe Asset Link](https://helpx.adobe.com/br/enterprise/using/manage-assets-using-adobe-asset-link.html).
