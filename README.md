DNS Checker

Intrukcja obsługi:

1. Pobierz repozytorium

2. Otwórz pobrany folder

3. Nadaj uprawnienia dla pliku dns_check (chmod +x dns_checker)

4. Uruchom skrypt (./dns_check)

5. Po zakończeniu działania skrypt wygeneruje plik output.csv, w którym będą 3 kolumny:

	a. hostname - nazwa hosta
	
	b. rr - czy wykryto balansowanie ruchu na poziomie DNS (Round Robin). Dozwolone wartości to 0 (nie wykryto) i 1 (wykryto)
	
	c. cdn - czy wykryto rozproszenie zasobów (CDN). Dozwolone wartości to 0 (nie wykryto) i 1 (wykryto)

Pliki wejściowe:

	dnsservers.txt - lista adresów ip serwerów DNS. Można skopiować jeden z przygotowanych plików (tiny - 10 DNS, small - 100 DNS, big - 44000 DNS)
	
	hostserwers.txt - lista stron internetowych. Nazwy takie jak wpisujemy w przeglądarce (np. onet.pl)

