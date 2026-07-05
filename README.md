**Zadanie 1: Algorytmy sortowania**
Celem zadania jest implementacja wybranych algorytmów sortowania, przeprowadzenie systematycznych eksperymentów porównawczych oraz analiza ich złożoności obliczeniowej w praktyce

5 algorytmow sortowania:
1. Shell Sort z algorytmem bazowym Insertion Sort oraz przyrostami Knutha, (`shellsort.cpp`)
2. Merge Sort, (`mergesort.cpp`)
3. Heap Sort, (`heapsort.cpp`)
4. Quick Sort rekurencyjny z pivotem, którym jest pierwszy element ciągu, (`quicksort.cpp`)
5. Quick Sort iteracyjny z pivotem, którym jest pierwszy element ciągu. (`quicksortiter.cpp`)

**Dane wejściowe:**
1. program powinien umożliwiać wczytanie z klawiatury n-elementowego ciągu liczb naturalnych
(dla n12 – tryb demonstracyjny) (`zadanie1demoWSZYSTKIERAZEM.CPP`)
2. generowanie danych testowych przy użyciu wbudowanego generatora. (`zadanie1eksperyment.cpp`)

**Dane wyjściowe: dla każdego uruchomienia algorytmu program powinien podawać**
1. czas sortowania,
2. liczbę operacji porównań i zamian elementów (dla Merge Sort zliczamy tylko porównania),
3. dodatkowo w trybie demonstracyjnym (dla niewielkich ciągów), program powinien wyświetlać:
• ciąg wejściowy i wyjściowy,
• dla Quick sort – wartość pivota w każdej iteracji,
• dla Merge sort – liczbę scaleń podzbiorów,
• dla Shell sort – wartość przyrostu w kolejnych iteracjach.

+ sprawozdanie które porównuje działania każdego algorytmu i wyciąga odpowiednie wnioski.
