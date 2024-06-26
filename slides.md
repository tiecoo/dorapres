
<h2 class="r-fit-text">DORA Metrics</h2>
<h2 class="r-fit-text">O que é, o que comem, onde vivem</h2>

------

### Early reminder
Essa aprensentação estamos usando markdown e reveal.js :)

---

## O que é DORA Metrics

<span style="font-size:22px;">
Conceito relativamente recente <small>2014</small>, seguindo as evoluções da transformação digital.
Nada mais é que métricas que nos ajudam a avaliar o desenvolvimento, implantação e ajustes de software.
Significa: <i> DevOps Research and Assessment </i> ou em nosso bom ptBr: Pesquisa e avaliação de DevOps
</span>
---

## Como surgiu
<span style="font-size:22px;">
A DORA identificou 4 indicadores a partir de um estudo ao longo de 6 anos com milhares de   no mundo todo.
Considerado o MAIOR e mais antigo (embora relativamente novo) estudo voltado a esse tipo.
Tem como finalidade entender quais recursos impulsionam um software e avaliar o desempenho.
</span>
---

## Mas o que é DORA Metrics
São 4 DORA Metrics:
<p class="fragment fade-up">- Deployment Frequency </p>
<p class="fragment fade-up">- Lead Time for Changes </p>
<p class="fragment fade-up">- Change Failure Rate </p>
<p class="fragment fade-up">- Time to Restore Service</p>
<p class="fragment fade-up">Cada uma podendo ser avaliada com as notas Elite, High, Medium e Low</p>

------

### Bom lembrar que
Essas notas são reavaliadas ANUALMENTE para criar novas referencias

---

## Vantagens do DORA
<span style="font-size:22px;">
Quando começamos a analisar esses dados, conseguimos entender onde estão os gargalos e como podemos atacar.
Acaba agregando mais valor ao nosso produto, conseguimos tomar decisões com base em dados concretos e a criar uma cultura de melhoria contínua
</span>

---


## Pilares

Vamos abordar pilar por pilar agora

------

## Deployment frequency<small> Frequência de implantação </small>
<span style="font-size:22px;">
Avalia com qual frequencia atualizamos um software.
Com uma taxa alta se entende que esta sendo entregue valor com mais agilidade, além de entender tambem como melhoria contínua.
</span>

------

## Lead Time for Changes<small> Tempo para implantações </small>
<span style="font-size:22px;">
Tempo médio para sair de desenvolvimento para a implantação do software.
O que se leva em conta é a data inicio de testes e a data de implantação real(produtivo)
Ajuda a entender a capacidade de produção da equipe, sempre pensando em reduzir o tempo e deixa-lo mais agil
</span>
------

## Change failure rate<small> Taxa de falhas nas implantações </small>
<span style="font-size:22px;">
Mede as alterações que resultaram em alguma falha e que demandam alguma correção.
Foco em manter essa métrica baixa, rsrs, para mantermos a eficiencia nas imlpantações.
Cáculo simples: dividir a quantidade de defeitos identificados pelo número de implantações do período avaliado.
</span>
------

## Time to restore service<small> Tempo para restaurar o serviço  </small>
<span style="font-size:22px;">
Mede o tempo médio para que a funcionalidade de um sistema ou aplicativo seja reparada ou restaurada.
Impacta diretamente a eficiência do negócio
</span>

---

![Dora metrics table](https://storage.googleapis.com/gweb-cloudblog-publish/images/Calculating_the_metrics_frOhcbp.max-1000x1000.jpg)

---

## Principais desafios na implantação
<p class="fragment fade-up">- Coleta de dados </p>
<p class="fragment fade-up">- Criar ideias </p>
<p class="fragment fade-up">- Descobrir a meta </p>

---

## Por onde começar
<p class="fragment fade-up">- Loggar dados desde o inicio da esteira </p>
<p class="fragment fade-up">- Centralize suas informações, exemplo : mudanças, implantações e incidentes </p>
<p class="fragment fade-up">- Extraia e processe melhor os dados </p>

---
## Como podemos trazer isso para o nosso dia-a-dia
<p class="fragment fade-up">- Utilizar tags como `bug`, `feat` para fazermos calculos </p>
<p class="fragment fade-up">- Analisar o tempo do commit para o horário do deploy </p>
<p class="fragment fade-up">- Analisar a quantidade de deploys </p>
<p class="fragment fade-up">- Grafana ja da algumas opções para a gente, temos que entender como funciona </p>

