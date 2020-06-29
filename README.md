# www.serverless.ovh

[Serverless - czym jest i jak działa?](https://bulldogjob.pl/articles/1047-serverless-czym-jest-i-jak-dziala)

> ## A miało być tak pięknie...
> 
> Skoro jest tak szybko i tanio - gdzie jest haczyk? Oto kubeł zimnej wody prosto z Twittera:  
>   
> 
> ![](https://cdn.bulldogjob.com/system/photos/files/000/003/538/original/serverless_2.png)
> 
>   
> W dużym skrócie: usługa była złożona w całości z rozwiązań serverless. Wydajność i skalowalność nie stanowiły problemu  – były nim rosnące koszty. Część, która generowała ich najwięcej, została przepisana z NodeJS do Elixira i wdrożona na klaster kubernetesowy, gdzie **z powodzeniem obsługuje obciążenie sięgające 12 milionów żądań na godzinę** - za ułamek wcześniejszych kosztów. O szczegółach historii, która kryje się za powyższym tweetem, przeczytasz [tutaj](https://medium.com/coryodaniel/from-erverless-to-elixir-48752db4d7bc).
> 
> Usługi serverless nie są więc magicznym rozwiązaniem wszystkich problemów, a korzystając z nich trzeba mieć świadomość ich ograniczeń. Istnieje ryzyko, że koszty mogą nam się szybko wymknąć spod kontroli (na skutek nietrafnych oszacowań, programistycznych błędów). Częstą krytyką jest też to, że wybierając daną usługę bardzo mocno wiążemy się z konkretnym dostawcą. Jeśli tzw. _vendor lock-in_ jest problemem, warto zapoznać się z open source’owym frameworkiem Serverless ([https://serverless.com/](https://serverless.com/)), będącym warstwą abstrakcji ponad usługami konkretnych dostawców. Nie mówię tu już o ogólnych wątpliwościach natury chmurosceptycznej - dotyczących miejsca przechowywania danych czywspółdzielenia środowiska z innymi użytkownikami chmury.

fragment artykułu ze strony:
https://bulldogjob.pl/articles/1047-serverless-czym-jest-i-jak-dziala
