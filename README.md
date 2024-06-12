# kursy_cs_.net
Grzegorz Mirecki 18737

Projekt powinno otwierać się w środowisku programistycznym obsługującym język C#.

Przed odtworzeniem należy upewnić się czy wersję .NET Core lub .NET Framework jest zainstalowana.

Kopiuj podany kod i wklej go do odpowiedniego programu umożliwiającego jego kompilację.

Postępuj zgodnie z instrukcjami wyświetlanymi w konsoli, aby dodawać kursy, uczestników, oraz wyświetlać listy kursów i uczestników.

Uwagi:
Kod używa konsoli do interakcji z użytkownikiem, więc upewnij się, że jest ona dostępna podczas uruchamiania programu.
Aby zamknąć program, wybierz opcję "Wyjscie" podczas wyświetlania menu głównego.

Kod zgodnie z założeniem instrukcji wykonania ćwiczenia posiada : 

- Co najmniej dwie pojedyncze funkcjonalności wielokrotnego użytku:
Zarządzanie kursami: Poprzez jedną z klas możemy dodawać kursy i wyświetlać ich listę wielokrotnie, 
co zapewnia wielokrotną użyteczność kodu. Podobnie jak kursy, możemy dodawać uczestników 
i wyświetlać ich listę wielokrotnie.

- Posiada interfejs dla użytkownika. Interfejs ten jest zaimplementowany w metodzie KonsolaUI().
Wyświetlane jest menu z różnymi opcjami, takimi jak dodawanie kursu, dodawanie uczestnika itp.
Użytkownik może wybrać jedną z opcji, wpisując odpowiedni numer.
W zależności od wyboru użytkownika, program wykonuje odpowiednie działania.
Program wykonuje pętlę, aby umożliwić użytkownikowi wybór kolejnych opcji, aż zdecyduje się wyjść z programu.

- Umożliwia interakcję z użytkownikiem poprzez konsolowy interfejs użytkownika (UI). 
Jednakże, jest on w tym stanie ograniczony do konsolowego środowiska i nie zapewnia graficznego interfejsu użytkownika (GUI).
 Aby zmienić ten interfejs na inny np. GUI, wymagana byłaby implementacja odpowiedniej logiki obsługi interfejsu użytkownika oraz interakcji z nim.
