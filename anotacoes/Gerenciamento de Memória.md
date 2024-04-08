Tópico::
Links::

---

## Anotações

### Notas Principais

- [[SO-Aula6_GerenciamentoDeMemoria.pdf]]

### Questões-Chave

- 
- Defina reentrância

### Resumo

- > [!PDF|yellow] [[SISTEMAS-OPERACIONAIS-MODERNOS.pdf#page=721&selection=45,0,92,26&color=yellow|SISTEMAS-OPERACIONAIS-MODERNOS, p.702]]
> > A reentrância se caracteriza pela possibilidade de o código ser executado duas ou mais vezes simultaneamente. Em um multiprocessador, existe sempre o perigo de que, enquanto uma CPU executa alguma rotina, outra CPU inicialize a execução da mesma rotina também, antes que a primeira tenha acabado. Nesse caso, dois (ou mais) threads em diferentes CPUs podem estar executando o mesmo código ao mesmo tempo. Essa situação deve ser evitada usando mutexes ou outros mecanismos que protejam regiões críticas. No entanto, o problema também existe em um monoprocessador. Em particular, a maior parte de qualquer sistema operacional trabalha com as interrupções habilitadas. Para trabalhar de outro modo, muitas interrupções seriam perdidas e o sistema não se mostraria confiável. Enquanto o sistema operacional está ocupado executando alguma rotina, P, é totalmente possível que uma interrupção ocorra e que o tratador de interrupção também chame P. Se as estruturas de dados de P estiverem em um estado inconsistente no momento da interrupção, o tratador verá esse estado inconsistente e falhará. Um outro caso claro dessa ocorrência é se P for o escalonador. Suponha que algum processo tenha usado seu quantum e o sistema operacional o tenha movido para o final de sua fila. Enquanto o sistema realiza a manipulação da lista, a interrupção ocorre, tornando algum processo pronto, e, com isso, o escalonador é executado novamente. Com as filas em um estado de inconsistência, o sistema provavelmente travará. Como consequência, mesmo em um monoprocessador, é melhor que a maior parte do sistema operacional seja reentrante, com estruturas de dados críticas protegidas por mutexes e as interrupções sendo desabilitadas nos momentos em que não puderem ser toleradas.
> 
> 




