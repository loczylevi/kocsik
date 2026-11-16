# Python – Kocsik gyakorlófeladatok

**Adatfájl:** `kocsik.txt`

A fájl tartalma:

```text
TRU-234,Opel Astra,21
HGT-873,Mazda Mazda3,3
LOT-295,Toyota Yaris,1
OPO-223,Seat Cordoba,9
PPT-111,Alfa Romeo,4
RET-776,Ford C-Max,5
ETW-231,BMW i3,2
SSA-772,Hyundai i30,5
KCT-254,Opel Corsa,12
GGT-434,Toyota Prius,4
JTZ-774,Ford Fiesta,25
```

## 1. Alapfeladatok

1. Olvasd be a fájlt egy `lista` nevű listába!
2. Írd ki a lista első sorát!
3. Írd ki a lista utolsó sorát!
4. Írd ki a fájl 6. sorát!
5. Írd ki az első autó nevét!
6. Írd ki az első autó évszámát!
7. Írd ki a harmadik autó rendszámát!
8. Írd ki az ötödik autó nevét!
9. Írd ki az utolsó előtti autó összes adatát!

## 2. Bejárás `for` ciklussal

10. Írd ki az összes autó nevét!
11. Írd ki az összes autó rendszámát!
12. Írd ki az autók rendszámát és nevét egymás mellett!
13. Írd ki minden autó nevét és évszámát!

## 3. Feltételes kiválasztás

14. Írd ki azokat az autókat, amelyek évszáma kisebb mint 5!
15. Írd ki azokat az autókat, amelyek évszáma nagyobb mint 10!
16. Írd ki azokat az autókat, amelyek évszáma pontosan 5!
17. Írd ki azokat az autókat, amelyek neve `Opel` szóval kezdődik!
18. Írd ki azt az autót, amelynek rendszáma `TRU-234`!

## 4. Darabszám és összegzés

19. Számold meg, hány autó található a fájlban!
20. Számold meg, hány autónak nagyobb az évszáma 5-nél!
21. Számold meg, hány Opel található a listában!
22. Számold ki az autók évszámainak összegét!
23. Számold ki az autók évszámainak átlagát!

## 5. Minimum és maximum keresése

24. Keresd meg a legkisebb évszámot!
25. Keresd meg a legnagyobb évszámot!
26. Írd ki annak az autónak a nevét, amelyikhez a legkisebb évszám tartozik!
27. Írd ki annak az autónak a nevét, amelyikhez a legnagyobb évszám tartozik!

## 6. Keresés

28. Kérj be a felhasználótól egy rendszámot, és keresd meg, szerepel-e a listában!
29. Kérj be egy autómárkát, és írd ki az összes hozzá tartozó autót!
30. Kérj be egy évszámot, és keresd meg, van-e ilyen évszámú autó!
31. Keresd meg a Toyota márkájú autók darabszámát!
32. Keresd meg a legnagyobb évszámú autót, és írd ki minden adatát!

## 7. Összetett gyakorlófeladatok

33. Írd ki az összes olyan autót, amelynek évszáma 3 és 10 közé esik!
34. Keresd meg a legkisebb évszámú Opel autót!
35. Számold meg, hány autó évszáma páros!
36. Írd ki azokat az autókat, amelyek évszáma nagyobb az összes autó átlagos évszámánál!

---

## Segítség – a fájl beolvasásának mintája

```python
with open("kocsik.txt", "r", encoding="UTF-8") as f:
    lista = []
    for sor in f:
        lista.append(sor.strip().split(","))
```

