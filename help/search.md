---
title: Pesquise e descubra ativos em [!DNL Assets Essentials]
description: Pesquise e descubra ativos em [!DNL Assets Essentials].
role: User
exl-id: be9597a3-056c-436c-a09e-15a03567c85a
source-git-commit: cd7af0c946a042430e62528fa6aa19bdab139f67
workflow-type: tm+mt
source-wordcount: '389'
ht-degree: 1%

---

# Pesquisar ativos em [!DNL Assets Essentials] {#search-assets}

[!DNL Assets Essentials] fornece pesquisa eficaz, que funciona apenas por padrão. A pesquisa é abrangente, pois é uma pesquisa de texto completo. A poderosa funcionalidade de pesquisa permite descobrir rapidamente o ativo apropriado e ajudá-lo a melhorar a velocidade do conteúdo. [!DNL Assets Essentials] O fornece pesquisa de texto completo e até mesmo pesquisas por meio de metadados, como tags inteligentes, título, data de criação e copyright.

Para pesquisar ativos,

* Clique na caixa de pesquisa na parte superior da página. Por padrão, ele pesquisa na pasta que você está navegando no momento. Faça uma das seguintes opções:

   ![caixa de pesquisa](assets/search-box.png)

   * Pesquisar usando uma palavra-chave e, opcionalmente, alterar a pasta. Pressione Return (Retornar).

   * Comece a trabalhar com um ativo exibido recentemente, procurando diretamente por ele. Clique na caixa de pesquisa e selecione um ativo exibido recentemente a partir das sugestões.

## Filtrar os resultados da pesquisa {#refine-search-results}

Você pode filtrar os resultados da pesquisa com base nos seguintes parâmetros.

![Filtros de pesquisa](assets/filters1.png)

*Figura: Filtre ativos pesquisados com base em vários parâmetros.*

* Tipo de arquivo: Filtre os resultados da pesquisa pelos tipos de arquivos suportados, ou seja, `Images`, `Documents`e `Videos`.
* Tipo MIME: Filtrar um ou mais formatos de arquivo compatíveis. <!-- TBD:  [supported file formats](/help/supported-file-formats.md). -->
* Tamanho da imagem: Forneça uma ou mais das dimensões mínima e máxima para filtrar imagens. O tamanho é fornecido em dimensões em pixel e não é o tamanho do arquivo das imagens.
* Criar data: A data de criação do ativo, conforme fornecido nos metadados. O formato de data padrão usado é `yyyy-mm-dd`.
* Data de modificação: A data da última modificação dos ativos. O formato de data padrão usado é `yyyy-mm-dd`.

Você pode classificar os ativos pesquisados em ordem crescente ou decrescente de `Name`, `Relevancy`, `Size`, `Modified`e `Created`.

## Pesquisas salvas {#saved-search}

A funcionalidade de pesquisa é bastante fácil de usar no [!DNL Assets Essentials]. Na caixa de pesquisa, você não pode apenas digitar uma palavra-chave e pressionar return para ver os resultados, você também pode pesquisar rapidamente novamente por palavras-chave pesquisadas recentemente em um único clique.

Também é possível filtrar os resultados da pesquisa com base em critérios específicos sobre metadados e tipo de ativos. Para filtros usados com frequência, para melhorar a experiência de pesquisa, [!DNL Assets Essentials] permite salvar os parâmetros de pesquisa. Em seguida, você pode selecionar a pesquisa salva para pesquisar e aplicar o filtro com apenas um clique também.

Para criar uma pesquisa salva, pesquise por algum ativo, aplique um ou mais filtros e clique em [!UICONTROL Salvar pesquisa] no [!UICONTROL Filtros] painel.

![Pesquisa salva do painel Filtros](assets/saved-search.png)

<!-- TBD: Search behavior. Full-text search. Ranking and rank boosts. Hidden assets.
Report poor UX that users can only save a filtered search and not a simple search.
.
Are other supported files fully indexed and support full-text search? Eg. audio/videos files can at best have metadata indexed.
Anything about ranking of assets displayed in search results?

What about temporarily hiding an asset (suspending search on it) from the search results? If an asset is undergoing review collaboration, should it be used by others? Should it be hidden in search?

When userA is searching and userB add an asset that matches search results, will the asset display in search as soon as userA refreshes the page? Assuming indexing is near real-time. May not be so for bulk uploads.
-->
