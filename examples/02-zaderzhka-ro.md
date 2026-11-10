---
title: "Пример 2 (RO): задержка поставки"
tags: [skill, example]
---

# Пример 2 (RO): сообщение клиенту о задержке поставки

Ситуация: клиент пишет по-румынски; поставка по заказу № 104 задерживается, новой даты в данных нет. Склад подтвердил, что заказ остаётся в резерве за клиентом.

## Плохо

```text
Subiect: Comanda

Salut,

Va informam ca comanda nu a ajuns din cauza furnizorului nostru care a intarziat. Garantam livrarea pana luni si va oferim transport gratuit. Daca nu ajunge, platim penalitati.

Multumim
```

Что не так: тема без сути и номера; «Salut» и обращение не на «dumneavoastră»; нет диакритики (Vă, informăm, întârziat, mulțumim); вина поставщика; обещан срок «până luni» без данных; бесплатная доставка и штрафы без согласования; нет подписи.

## Хорошо

```text
Subiect: Comanda nr. 104: întârziere la livrare

Bună ziua, doamnă Popescu,

Vă informăm că livrarea comenzii nr. 104 se amână. Ne cerem scuze pentru neplăcere.

Verificăm acum data exactă de sosire și vă vom comunica noul termen imediat ce îl primim. Comanda rămâne rezervată pentru dumneavoastră.

Dacă doriți să schimbați adresa sau modul de livrare, vă rugăm să ne răspundeți la acest mesaj.

Cu stimă,
<Prenume Nume>, manager vânzări
[Compania dumneavoastră]
<nume>@example.com
```

Чек-лист §8: все пункты выполнены, диакритика ș, ț с запятой снизу, 65 слов (с подписью).
