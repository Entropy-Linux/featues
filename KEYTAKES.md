**The Core** Projekt Entropy to wysoce konfigurowalny, oparty na skryptach ekosystem bazujący na Arch Linux, ściśle zintegrowany z w pełni darmową, anonimową siecią społecznościową (szmelc) oraz asystentami AI.

**Crucial Data Points**

* **Repozytoria:** Kod udostępniany jest na GitHubie (Entropy-Linux), SourceForge oraz we własnym repozytorium AUR.
* **Wersja prototypowa:** "entropy beta v1 prototype" obejmuje bazę Arch Linux, środowisko Hyprland oraz autorskie skrypty naprawcze.
* **Infrastruktura sprzętowa:** Do obsługi darmowych zapytań AI autor wykorzystuje własny serwer wyposażony w nową kartę graficzną, dysk 8 TB i dedykowany zasilacz.
* **Zabezpieczenia kont:** Konta w sieci społecznościowej są opcjonalne, nie wymagają adresu e-mail i są powiązane systemowo z unikalnym, niezmiennym numerem UUID wygenerowanym dla jądra systemu użytkownika.

**Key Mechanics / Arguments**

* **Modułowość i Instalacja:** Skrypty "konwolucyjne" pozwalają na instalację całego, dostosowanego systemu (lub powrót do czystego Archa) za pomocą jednej komendy (`entropy install setup` lub `addons manager`). Planowana jest opcjonalna obsługa "Pacman Ostry" (architektura typu immutable) oraz odtwarzanie pełnej konfiguracji z jednego pliku na wzór NixOS.
* **Zaawansowany Bootloader ("Sernik"):** Zmodyfikowane systemd-boot oraz GRUB2 posiadają "Advanced menu" umożliwiające awaryjne odpalenie powłoki bash jako root, skanowanie i dodawanie systemów do bootowania, klonowanie dysków, odzyskiwanie danych, bootowanie PXE oraz diagnostykę sprzętu.
* **Integracja Sztucznej Inteligencji:** System wbudowuje AI w terminal (obsługa np. poprzez Shell GPT, Grok, integrację z XAI), które może analizować błędy, pisać komendy, a nawet autonomicznie programować i wdrażać gotowe narzędzia internetowe czy skrypty na żądanie użytkowników. Zapytania są darmowe, realizowane przez sprzęt autora lub pule API udostępniane przez społeczność.
* **Prywatność i P2P Sieć "Szmelc":** Użytkownicy mogą uczestniczyć w zintegrowanej, szyfrowanej sieci proxy P2P, w której anonimizują swój ruch nawzajem. Wszelka telemetria służąca do debugowania jest minimalna i wysyłana w formie zaszyfrowanych haszy, bez gromadzenia adresów IP czy danych osobowych. Odzyskiwanie konta opiera się na jednym, zdefiniowanym przez użytkownika słowie-kluczu.
* **Ekonomia Społecznościowa i Transparentność:** Użytkownicy, którzy pomagają innym (np. poprzez zintegrowany kanał IRC) lub udostępniają zasoby, otrzymują systemowe "gwiazdki" zwiększające ich limity na zapytania AI i dostępną u autora przestrzeń dyskową na backup konfiguracji. Projekt finansowany jest z dobrowolnych datków, a na stronie znajduje się jawny, publiczny licznik kosztów utrzymania i posiadanych środków.

**Actionable Takeaways**

* Zainstalować nową kartę graficzną, dysk 8 TB oraz zasilacz w jednostce centralnej, aby uruchomić lokalny hosting modeli AI.
* Skonfigurować routing sieciowy na routerze, aby przekierować ruch ze środowiska testowego na domenę szmelc.
* Uruchomić prototyp v1 w zamkniętym gronie, aby rozpocząć testowanie podstawowych funkcji i skryptów przed wdrożeniem interfejsów API i zaawansowanych funkcji społecznościowych.

---
