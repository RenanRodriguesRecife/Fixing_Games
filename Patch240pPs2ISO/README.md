Por algum motivo quase todos os jogos que eram nativamente 240p foram covertido para 480i (provavelmente para ser compatível com as tvs LCDs da época - ou que a resolução 240p não iria ser mais obrigatória a compatibilidade)

Você pode fazer um patch em alguns jogos com um editor HEX para coverter para 240p 

Change:
```
01 00 24 32 ff 00 45 32
```
to
```
00 00 04 20 ff 00 45 32
```

and
```
01 00 24 32 04 00 06 a6
```
to
```
00 00 04 20 04 00 06 a6
```

Lista de compatibilidade

Funcionam
```
King of fighter collection Orochi Saga
King of fighter 2002
Street Fighter Alpha Anthology

```
Não funciona
```
Apenas Intro:
King of fighter NEST collection

```

https://shmups.system11.org/viewtopic.php?t=61532
