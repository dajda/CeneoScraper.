# CeneoScraper

# Struktura opinii w serwisie [Ceneo.pl](https://www.ceneo.pl/)

|Składowa opinii|Selektor|Nazwa zmiennej| Typ danych|
|---------------|--------|--------------|-----------|
|opinia|div.js_product-review|||
indentyfikator opinii|div.js_product-review\"data-entry-id"\]|||
|autor opinii|span.user-post__author-name|||
|remonedacja autora|span.user-post__author-recomendation > em|||
|liczba gwizdek|span.user-post__score-count|||
|treść opinii|div.user-post__text|||
|lista zalet||||
|lista wad||||
|dla ilu przydatna|button.vote-yes > span|||
|dla ilu nieprzydatna|button.vote-no > span|||
|data wystawienia opinii|span.user-post__published > time:nth-child(1)\["datetime"\]|||
|data zakupu produktu|span.user-post__published > time:nth-child(2)\["datetime"\]|||

