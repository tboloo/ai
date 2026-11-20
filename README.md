# Repozytorium materiałów związanych z AI

1. [response](./response) - plik konfigurujący postać odpowiedzi. Używaj jako konfigurację, lub po prostu pisząc "Poniżej format odpowiedzi, które masz stosować w tej rozmowie" i następnie wklej zawartość pliku. 
Najważniejszą korzyścią jest to, że każda odpowiedź pokaże na początku poniższą tabelę:

|Expert(s)        |{list; of; EXPERTs}|
|:----------------|:------------------|
|Possible Keywords|a lengthy CSV of EXPERT-related topics, terms, people, and/or jargon(IF (VERBOSITY V=5)) |
|Question         |improved rewrite of user query in imperative mood addressed to EXPERTs |
|Plan             |As EXPERT, summarize your strategy (considering VERBOSITY) and naming any formal methodology, reasoning process, or logical framework used|

na przykład:
pytanie do chatbota: `ok, to przejdzmy google vision krok po proku: mów mi co robić, i co mam sprawdzić`
Odpowiedź: 
| Expert(s) | Inżynier Google Cloud; inżynier ML/OCR; specjalista bezpieczeństwa chmury                                             |
| --------- | --------------------------------------------------------------------------------------------------------------------- |
| Question  | Przeprowadź mnie krok po kroku przez konfigurację Google Cloud Vision OCR i testowe rozpoznawanie dokumentu.          |
| Plan      | Prowadzę Cię sekwencyjnie: konto i projekt → billing → Vision API → uwierzytelnienie → test obrazu → test PDF. Po każdym etapie podam dokładnie, co sprawdzić. |
(...)
