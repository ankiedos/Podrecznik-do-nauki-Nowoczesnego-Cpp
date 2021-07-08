# Preprocesowanie (przetwarzanie wstępne)
Polega na ekspandowaniu makr (wstawianiu odpowiednich wartości w miejsce wywołania makra)
# Kompilacja
W jej trakcie zachodzi optymalizacja wykonywana przez kompilator. G++ kompiluje preprocesowany kod źrółowy języka C++ do kodu języka GIMPLE (ang.: *Generic Simple*, Ogólny Prosty), a następnie do kodu RTL (ang.: *Register Transfer Language*, Język Transferu Rejestrów).
Po optymalizacji RTL jest kompilowany do języka GNU As będącego wysokopoziomowym językiem asemblera.
# Asemblacja
Instrukcje zawarte w skompilowanym pliku są następnie asemblowane do pliku objektowego.
# Linkowanie (konsolidacja)
Uzyskany plik objektowy jest linkowany razem z innymi plikami objektowymi do kodu maszynowego. Powstaje biblioteka statyczna, współdzielona (dynamiczna), albo plik wykonywalny.

W folderze znajdują się również pliki hello.exe i hello.s zawierające odpowiednio kod maszynowy w formacie PE i kod GNU As programu omawianego w lekcji Wstęp/2. Pierwszy program.