# Pontos em Aberto de GeneXus

## Contexto

Este arquivo registra pontos em aberto que não bloqueiam o trabalho atual, mas podem ser úteis para retomar em futuras sessões de trabalho com GeneXus.

## Pontos em Aberto

- Os nomes exatos na IDE para `Index`, `Pattern Settings`, `Theme Class`, `Work With for Web`, `Data Store` e `Generator` já foram confirmados e não devem mais ser tratados como nomes inferidos.
- Ainda é necessário manter a distinção entre nome oficial do tipo de objeto e nome de diretório usado na extração XML.
- Os diretórios extraídos em `ObjetosDaKbEmXml` seguem uma convenção compacta sem espaços, como `DataProvider`, `DataSelector`, `ThemeClass`, `ThemeColor`, `WebPanel`, `DataStore` e `WorkWithForWeb`.
- O caso que merece cuidado adicional é `Module` para o GUID `c88fffcd-b6f8-0000-8fec-00b5497e2117`, porque no acervo extraído ele aparece como diretório `PackagedModule` por refletir metadados de empacotamento do XML exportado.
- A geração sintética de `XPZ` já foi validada com sucesso em pelo menos um cenário real de importação, build e execução, mas o processo ainda não foi documentado como método totalmente generalizado para conjuntos arbitrários de objetos.
- A criação de uma skill local dedicada para análise, geração de `XPZ` e convenções compartilhadas de GeneXus continua pendente. Por enquanto, o conhecimento está registrado apenas em arquivos `.md`.

## Situação Atual

Nenhum dos pontos acima bloqueia o trabalho em andamento. Eles devem ser tratados como lembretes para refinamento futuro, e não como pendências críticas.


