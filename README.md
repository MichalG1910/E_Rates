# E_Rates - skrypt korzysta z danych api.nbp.pl
# Po uruchomieniu skrypt pobiera aktualną tabelę kursów walut z API NBP w formacie JSON, parsuje je i wyświetla w odpowiednich zakładkach interfejsu graficznego (biblioteka Tkinter). 
# Dodatkowo generuje plik w formacie txt, w którym zapisuje aktualną tabelę kursów. Plik jest zapisaywany lokalizacji skryptu, w katalogu "Reports"(tworzony automatycznie, jeśli nie istnieje)
# Dzięki wykorzystaniu biblioteki Matplotlib, możemy w oknie głównym aplikacji w zakładce "Wykres", narysować wykres dowolnej waluty (dostępnej w API NBP) w porównaniu do Złotego
# Dodatkowo możemy na ten wykres nałożyć linię trendu oraz min/max wartości na wykresie. Wykres rusujemy w wybranym przedziale czasowym
# Wykres ten później możemy zapisać w katalogu "Reports"
# W zakładce "Wiele wykresów" możemy generować do 15 wykresów jednocześnie (będą wyświetlone w jednym oknie pełnoekranowym). 
# Mamy możliwość narysowania w jednym oknie wielu wykresów jednej waluty w różnych przedziałach czasowych (dostępne są 2 widoki do generowania wielu wykresów)
# Wiele wykresów też możemy generować z dodatkowymi opcjami i zapisywać w katalogu "Reports"
# W zakładce "Raport" możemy wygenerować raport w formacie txt i csv, zawierające tabele kursów z ustalonego wcześniej przedziału czasowego.
# Raporty można generować od dnia 2004-05-04 (dane o tej daty są dostępne w API NBP)
# Wszystkie pliki tworzone w aplikacji są automatycznie nazywane i umieszczane w katalogu "Reports".
