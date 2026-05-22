---
title: Integração de Content Credentials
description: As Content Credentials, integradas ao AEM Assets e presentes na interface do AEM Assets Essentials, podem fornecer contexto sobre o histórico de um ativo, incluindo como ele foi criado e quem estava envolvido na sua criação. Como um rótulo nutricional para conteúdo digital, as Content Credentials podem ajudar a aumentar a transparência e gerar confiança junto a públicos-alvo.
role: User
exl-id: 703f74a6-24d4-4181-8174-9ff4a90ee7aa
TQID: https://experienceleague.adobe.com/witCqgAh8EKfD-hdn8efjZ-M4sypX44KB2ELs3ECInI
product_v2: id: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
feature_v2: id: ec4263d9-bf7c-44c7-b3f1-3e664861c8f2
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
topic_v2: id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dc
source-git-commit: f026b389ce582ece5d2ca8745d291b1ae50d657e
workflow-type: tm+mt
source-wordcount: 474
ht-degree: 100%

---

# Content Credentials {#content-credentials}

As marcas estão mais preocupadas do que nunca com a transparência de conteúdo, a divulgação do uso de IA e a prevenção da adulteração de ativos. A Content Authenticity Initiative (CAI) na Adobe cria ferramentas em conformidade com o padrão técnico [Coalizão para Proveniência e Autenticidade de Conteúdo](https://c2pa.org/specifications/specifications/1.1/specs/C2PA_Specification.html#_trust_model) (C2PA). As Content Credentials, um novo tipo de metadados criptografados e invioláveis, podem ajudar visualizadores a entender a linhagem do conteúdo e garantir a integridade dos ativos da marca. Elas podem incluir uma grande variedade de dados de origem que oferecem insights sobre o histórico de um ativo digital.

Essa informação inclui:

* **Emissor ou signatário:** informações sobre a entidade ou empresa que emitiu a assinatura digital para certificar ou assinar o ativo.
* **Data de emissão:** a data em que a Content Credential foi aplicada ao ativo.
* **Crédito e uso:** informações sobre o produtor do ativo, incluindo nome, identificadores de redes sociais ou outras informações relacionadas à identidade.
* **Processo:** registros de qualquer edição ou modificação feita no ativo.
* **Detalhes do dispositivo:** informações sobre o aplicativo ou dispositivo usado para criar ou editar o ativo.
* **Ferramenta de IA usada:** se a IA generativa foi usada para editar ou criar o ativo, o nome do modelo usado pode ser incluído.
* **Outras informações pertinentes:** dados adicionais também podem ser incluídos para ajudar a oferecer mais contexto sobre o histórico de um ativo.

Para obter uma exibição completa, [Verificar](https://contentcredentials.org/verify) pode oferecer um insight mais abrangente sobre o histórico de ativos.

O Adobe Experience Manager Assets agora é compatível com Content Credentials, permitindo que os usuários vejam as Content Credentials diretamente na interface do Assets Essentials do AEM. Ao observar os detalhes do ativo, qualquer imagem com Content Credentials (como aquelas criadas com serviços de IA generativa) mostra os detalhes do manifesto em um painel dedicado. Se o ativo for baixado, publicado ou compartilhado, as credenciais permanecerão intactas no ativo.

![ativos](/help/using/assets/content-credentials.png)

## Acessar Content Credentials {#access-content-credentials}

1. Vá para a interface do Assets Essentials e clique em **Ativos** no painel esquerdo.
1. Navegue para uma pasta e selecione o ativo desejado.
1. Clique em **Detalhes** e selecione `Cr pin` no painel mais à direita. A guia Content Credentials exibe as seguintes informações sobre o ativo.
   1. **Imagem gerada:** data e hora em que as Content Credentials foram aplicadas.
   1. **Resumo do conteúdo:** indica se o ativo foi gerado parcial ou completamente por IA ou como foi editado.
      ![resumo do conteúdo](/help/using/assets/content-credentials1.png)
   1. **Processo:** detalha o aplicativo, o dispositivo e a ferramenta de IA (como o Adobe Firefly) usada para gerar o ativo, bem como as alterações feitas posteriormente.
      ![processo](/help/using/assets/CR-Process.png)
   1. **Sobre estas Content Credentials:** nome do emissor, juntamente com a data e a hora de emissão.
      ![emissor](/help/using/assets/CR-issuer.png)
