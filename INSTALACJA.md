# Instrukcja instalacji — Ashes of the Singularity: Escalation

[Pobieranie i wymagania](https://marko22.pl/pobieranie#ashes-escalation) · [Wydanie GitHub](https://github.com/mariuszm22/Ashes-of-the-Singularity-Escalation-Spolszczenie-PL/releases/tag/v1.0.0)

## INSTALACJA PRZEZ KREATOR
1. Zamknij grę. Uruchom Ashes_Escalation_PL_Setup.exe.
2. Wybierz „Zainstaluj lub napraw spolszczenie”. W razie potrzeby wskaż
   katalog gry. W Steam znajdziesz go przez Zarządzaj → Przeglądaj pliki lokalne.
3. Jeśli chcesz zainstalować polskie filmy, pobierz opcjonalny plik
   Ashes_Escalation_PL_Filmy_1.0.0.pack. Połóż go obok instalatora lub wskaż
   go ręcznie. Filmy można doinstalować później tym samym instalatorem.
4. Sprawdź podsumowanie, kliknij „Zainstaluj” i poczekaj na zakończenie.

## INSTALACJA RĘCZNA Z ZIP
1. Zamknij grę i wypakuj Ashes_Escalation_PL_1.0.0.zip do osobnego katalogu.
   Jeśli grę instalujesz pierwszy raz, uruchom ją wcześniej raz przez Steam
   i zamknij, aby utworzyła swój profil w Dokumentach.
2. Otwórz katalog gry w Steam przez Zarządzaj → Przeglądaj pliki lokalne.
   Wykonaj kopię plików, które zamierzasz zastąpić. Skopiuj znajdujący się
   w paczce folder „gra\Assets” do katalogu gry. Scal zawartość
   folderów.
3. W systemowym folderze Dokumenty otwórz „My Games\Ashes of the Singularity - Escalation”.
   Jeśli masz już „Mods\marko22” lub „Mods.ini”, zrób ich kopie. Skopiuj folder
   „gra\profil\Mods\marko22” do „Mods” w tym profilu. Utwórz „Mods”,
   jeśli jeszcze go nie ma.
4. Uruchom grę, wejdź w „Modyfikacje”, włącz mod marko22 i uruchom grę ponownie,
   jeśli gra o to poprosi. Gdy używasz pliku Mods.ini do włączania modów,
   zachowaj jego pozostałe wpisy. W sekcji [AshesModConfiguration] dodaj
   parę z wolnym numerem w miejscu N, np. 0 w pustej konfiguracji

       ModN_Path=marko22/index.ashesmod
       ModN_Enabled=1

   Jeśli wpis marko22 już istnieje, zmień tylko jego _Enabled na 1. Jeżeli
   tworzysz sekcję od podstaw, umieść pod nagłówkiem również IniVersion=1.

## PO INSTALACJI
Uruchom grę przez Steam i upewnij się, że w ustawieniach języka wybrano English (angielski). Ze względu na ograniczenia silnika gry spolszczenie zastępuje język angielski i nie występuje jako osobna pozycja „Polski”.

## PRZYWRACANIE
Po instalacji kreatorem użyj „Odinstaluj całe spolszczenie” w instalatorze. Po instalacji
ręcznej wyłącz mod, zamknij grę i przywróć pliki z kopii wykonanej przed
instalacją. Usuń dodany folder Mods\marko22 wyłącznie wtedy, gdy przed
instalacją go nie było. Zachowaj inne mody, ustawienia i zapisy gry.

Projekt: https://marko22.pl/
