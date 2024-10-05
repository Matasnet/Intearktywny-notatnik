# Interaktywny-notatnik
Interaktywny notatnik w Google CoLab, który ma pomagać w tworzeniu uproszczonej wyceny np. jakiegoś projektu czy innego przedsięwzięcia
  
Projekt powstał z ciekawości jak zrobić wycenę do pewnego projektu, wycena była wcześniej robiona przy pomocy Excela i chciałem przenieść to na Pythona. Zastanawiałem się nad kilkoma elementami, które miał ten projekt posiadać:  
1. Dodawanie elementów nie powinno następować w kodzie - jakieś małe i proste GUI,
2. Stworzona tabelka powinna być możliwa do zapisania w pliku CSV lub Excela - ponieważ taki plik należy komuś np. udostępnić,
3. Elementy automatyzacji - dodająć cenę i ilość program powinien sam wyliczyć + inne elemnty jak np. rabat,
4. Prostota obsłujgi - mimo wszystko program powinien być jak najprostszy w obsłudze i efekty pracy nie powinny wyglądać źle.

Udało mi się zrealizować te 4 elementy:  
1. Program posiada interfejs który uzupełniamy ręcznie,
2. Istnieje możliwość pobrania i zapisania na dysku efektów pracy w formacie CSV lub Excela,
3. Program przemnaża ilość przez cenę i dodaje możliwość obliczenia rabatu,
4. Pomijając kod na górze, w którym nie musimy "grzebać" obsługa polega na wpisaniu danych i kliknięcia w przycisk w celu dodania, efekty pracy widzimy w czasie rzeczywistym.  
