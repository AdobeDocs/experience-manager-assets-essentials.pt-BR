---
title: Como gerenciar com eficácia as permissões de pastas?
description: Práticas recomendadas para o gerenciamento eficaz de permissões
source-git-commit: fe716385939d18aa23d01dac5fe5f041541d2b31
workflow-type: tm+mt
source-wordcount: '398'
ht-degree: 0%

---

# Práticas recomendadas para o gerenciamento eficaz de permissões {#best-practices-permissions-management}

Como administrador, antes de começar a gerenciar as permissões de pasta para o repositório do Assets Essentials, há várias práticas recomendadas que você pode implementar para tornar a infraestrutura intuitiva para administradores e usuários finais durante o gerenciamento de operações.

Você pode incorporar essas práticas recomendadas ao:

* [Criação de grupos de usuários no Admin Console](#admin-console-best-practices)

* [Criação da estrutura de pastas no repositório Assets Essentials](#folder-structure-assets-essentials)

* [Gerenciamento de permissões no repositório Assets Essentials](#folder-permissions)

## Admin Console {#admin-console-best-practices}

Identifique as necessidades de acesso com base nos grupos de usuários em sua organização. Planeje e crie grupos de usuários para sua organização e adicione usuários a esses grupos de usuários. É mais fácil gerenciar permissões de pastas com base em grupos de usuários e não em usuários individuais.

## Estrutura de pastas para o repositório Assets Essentials {#folder-structure-assets-essentials}

Considere os seguintes pontos quando você começa a planejar criar uma estrutura de pastas no repositório do Assets Essentials:

* Governação futura: As pastas que são controladas pelos administradores e pelas pastas que são [delegado para permissões para outros usuários como proprietários](manage-permissions.md##manage-permissions-folders).

* Escalável: A estrutura de pastas deve atender às necessidades futuras de sua organização e deve ser facilmente escalável.

* Tamanho: Uma pasta não deve conter muitos ativos. Isso pode levar a problemas de usabilidade e pode se tornar difícil de gerenciar.

* Intuitivo: A estrutura de pastas deve ser fácil de navegar e intuitiva para os usuários finais. Os usuários devem ser capazes de identificar facilmente onde fazer upload de um novo ativo na estrutura de pastas.

Há vários tipos possíveis de estrutura de pastas que você pode usar para sua organização. Veja a seguir alguns exemplos de estruturas de pastas típicas:

* Baseada em funções e categorizações

   ![Função e Categorização](assets/function-categorization.png)

* Baseado em campanha

   ![Baseado em Campanha](assets/campaign-based.png)

* Localização da oferta (ou canal) baseada

   ![Localização da oferta baseada](assets/offer-location.png)


## Permissões de pasta {#folder-permissions}

Depois de criar grupos de usuários para sua organização, adicionar usuários a esses grupos de usuários e selecionar e criar uma estrutura de pastas no repositório do Assets Essentials que atenda às necessidades de sua organização, você pode começar a gerenciar permissões de pastas para sua organização. Considere os seguintes pontos ao iniciar o gerenciamento de permissões de pasta:

* Aplique permissões para grupos de usuários, não para usuários individuais. Isso resulta em uma estrutura de permissões mais simples e eficiente.

* Mantenha a estrutura de permissões o mais simples possível para oferecer eficiência operacional.

* Use as permissões de acesso Negar com cuidado e prefira aplicar permissões positivas (Pode editar, Pode visualizar, proprietário) à estrutura de pastas.

Para obter exemplos sobre como obter uma estrutura de pastas simples e eficiente, consulte [Gerenciar permissões em pastas](manage-permissions.md##manage-permissions-folders).

