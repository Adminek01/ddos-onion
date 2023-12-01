# ddos-onion
Attack ddos HTTP nowszy sposub trochę "używajcie w calch edukacji 

## ddos-onion - Narzędzie Testowe do Oceny Odporności Serwera na Ataki DDoS

### Opis:

`ddos-onion` jest narzędziem stworzonym w celach edukacyjnych i testowania bezpieczeństwa. Jest to implementacja prostego ataku DDoS (rozproszonego ataku odmowy usługi) w języku Python, której celem jest zasymulowanie dużej liczby połączeń do serwera w krótkim czasie. Program ten ma na celu pomóc administratorom serwerów w zrozumieniu potencjalnych słabości i skuteczności środków obronnych przed atakami DDoS.

### Instrukcja Użycia:

1. **Konfiguracja:**
   - Upewnij się, że masz zainstalowanego Pythona na swoim systemie.
   - Pobierz kod źródłowy `ddos-onion`.
   - Uruchom terminal i przejdź do katalogu, gdzie znajduje się kod źródłowy.

2. **Uruchomienie:**
   - Uruchom program, wpisując w terminalu: `python ddos-onion.py` (lub odpowiednia komenda w zależności od środowiska Pythona).

3. **Parametry Wiersza Poleceń:**
   - Program obsługuje różne parametry wiersza poleceń, np. `-h` dla pomocy, `-t` dla określenia docelowego hosta, `-p` dla określenia portu, itp.

4. **Opcje Dodatkowe:**
   - Dostosuj program do swoich potrzeb, modyfikując kod źródłowy. Możesz zmieniać ilość połączeń, używane nagłówki, itp.

5. **Uwaga:**
   - Program jest przeznaczony do użytku wyłącznie w środowisku testowym, w ramach edukacji i testowania bezpieczeństwa. Niedozwolone jest używanie go w celach szkodliwych ani nielegalnych.

### Przykłady:

- Atak na lokalny serwer HTTP na porcie 80:
  ```
  python ddos-onion.py -t localhost -p 80
  ```

- Atak na serwer HTTPS z losowym User-Agent:
  ```
  python ddos-onion.py -t example.com -p 443 --https --randuseragent
  ```

### Uwagi końcowe:

Pamiętaj, aby używać tego narzędzia zgodnie z zasadami etyki oraz przestrzegać prawa. Atakowanie serwerów bez ich zgody jest nielegalne. Program `ddos-onion` został stworzony wyłącznie w celach edukacyjnych, a jego użycie powinno być ograniczone do własnych zasobów lub w pełni upoważnionych testów bezpieczeństwa.