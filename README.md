class Samochod:
    def __init__(self, marka_samochodu, model_samochodu, moc_silnika, pojemnosc_silnika, przyspieszenie_0_100, maksymalna_predkosc,
                 rodzaj_paliwa, liczba_cylindrow, skrzynia_biegow, naped, rodzaj_nadwozia,
                 dlugosc, szerokosc, wysokosc, rozstaw_osi, masa_wlasna, rodzaj_opon,
                 rozmiar_opon, hamulce_przod, hamulce_tyl, system_hamulcowy, kontrola_trakcji,
                 stabilizacja_toru_jazdy, liczba_miejsc, kolor_nadwozia, rodzaj_lakieru,
                 system_audio, glosniki, system_nawigacyjny, klimatyzacja, rodzaj_tapicerki,
                 kierownica_wielofunkcyjna, elektryczne_szyby_przod, elektryczne_szyby_tyl,
                 elektryczne_lusterka, elektryczne_fotele_przednie, podgrzewane_fotele_przednie,
                 podgrzewane_fotele_tylne, centralny_zamek, system_bezpieczenstwa,
                 monitorowanie_cisnienia_w_oponach, rozpoznawanie_znakow_drogowych,
                 automatyczne_parkowanie, asystent_pasa_ruchu, rozpoznawanie_zmeczenia_kierowcy,
                 rozruch_bez_klucza, start_stop, rodzaj_reflektorow, regulacja_wysokosci_reflektorow,
                 czujniki_parkowania_przod, czujniki_parkowania_tyl, dach_panoramiczny):
                
        self.marka_samochodu = marka_samochodu
        self.model_samochodu = model_samochodu
        self.moc_silnika = moc_silnika
        self.pojemnosc_silnika = pojemnosc_silnika
        self.przyspieszenie_0_100 = przyspieszenie_0_100
        self.maksymalna_predkosc = maksymalna_predkosc
        self.rodzaj_paliwa = rodzaj_paliwa
        self.liczba_cylindrow = liczba_cylindrow
        self.skrzynia_biegow = skrzynia_biegow
        self.naped = naped
        self.rodzaj_nadwozia = rodzaj_nadwozia
        self.dlugosc = dlugosc
        self.szerokosc = szerokosc
        self.wysokosc = wysokosc
        self.rozstaw_osi = rozstaw_osi
        self.masa_wlasna = masa_wlasna
        self.rodzaj_opon = rodzaj_opon
        self.rozmiar_opon = rozmiar_opon
        self.hamulce_przod = hamulce_przod
        self.hamulce_tyl = hamulce_tyl
        self.system_hamulcowy = system_hamulcowy
        self.kontrola_trakcji = kontrola_trakcji
        self.stabilizacja_toru_jazdy = stabilizacja_toru_jazdy
        self.liczba_miejsc = liczba_miejsc
        self.kolor_nadwozia = kolor_nadwozia
        self.rodzaj_lakieru = rodzaj_lakieru
        self.system_audio = system_audio
        self.glosniki = glosniki
        self.system_nawigacyjny = system_nawigacyjny
        self.klimatyzacja = klimatyzacja
        self.rodzaj_tapicerki = rodzaj_tapicerki
        self.kierownica_wielofunkcyjna = kierownica_wielofunkcyjna
        self.elektryczne_szyby_przod = elektryczne_szyby_przod
        self.elektryczne_szyby_tyl = elektryczne_szyby_tyl
        self.elektryczne_lusterka = elektryczne_lusterka
        self.elektryczne_fotele_przednie = elektryczne_fotele_przednie
        self.podgrzewane_fotele_przednie = podgrzewane_fotele_przednie
        self.podgrzewane_fotele_tylne = podgrzewane_fotele_tylne
        self.centralny_zamek = centralny_zamek
        self.system_bezpieczenstwa = system_bezpieczenstwa
        self.monitorowanie_cisnienia_w_oponach = monitorowanie_cisnienia_w_oponach
        self.rozpoznawanie_znakow_drogowych = rozpoznawanie_znakow_drogowych
        self.automatyczne_parkowanie = automatyczne_parkowanie
        self.asystent_pasa_ruchu = asystent_pasa_ruchu
        self.rozpoznawanie_zmeczenia_kierowcy = rozpoznawanie_zmeczenia_kierowcy
        self.rozruch_bez_klucza = rozruch_bez_klucza
        self.start_stop = start_stop
        self.rodzaj_reflektorow = rodzaj_reflektorow
        self.regulacja_wysokosci_reflektorow = regulacja_wysokosci_reflektorow
        self.czujniki_parkowania_przod = czujniki_parkowania_przod
        self.czujniki_parkowania_tyl = czujniki_parkowania_tyl
        self.dach_panoramiczny = dach_panoramiczny

# Użycie klasy
auto= Samochod(
    marka_samochodu="Ford",
    model_samochodu="custom",
    moc_silnika=200,
    pojemnosc_silnika=2.0,
    przyspieszenie_0_100=7,
    maksymalna_predkosc=220,
    rodzaj_paliwa='benzyna',
    liczba_cylindrow=4,
    skrzynia_biegow='automatyczna',
    naped='przedni',
    rodzaj_nadwozia='sedan',
    dlugosc=4.5,
    szerokosc=1.8,
    wysokosc=1.4,
    rozstaw_osi=2.6,
    masa_wlasna=1500,
    rodzaj_opon='letnie',
    rozmiar_opon='225/55R17',
    hamulce_przod='tarczowe',
    hamulce_tyl='tarczowe',
    system_hamulcowy='ABS',
    kontrola_trakcji='TCS',
    stabilizacja_toru_jazdy='ESC',
    liczba_miejsc=5,
    kolor_nadwozia='srebrny',
    rodzaj_lakieru='metalik',
    system_audio='CD/MP3',
    glosniki=6,
    system_nawigacyjny=True,
    klimatyzacja='automatyczna dwustrefowa',
    rodzaj_tapicerki='skóra',
    kierownica_wielofunkcyjna=True,
    elektryczne_szyby_przod=True,
    elektryczne_szyby_tyl=True,
    elektryczne_lusterka=True,
    elektryczne_fotele_przednie=True,
    podgrzewane_fotele_przednie=True,
    podgrzewane_fotele_tylne=False,
    centralny_zamek=True,
    system_bezpieczenstwa=['poduszki powietrzne', 'boczne', 'kurtynowe'],
    monitorowanie_cisnienia_w_oponach=True,
    rozpoznawanie_znakow_drogowych=True,
    automatyczne_parkowanie=True,
    asystent_pasa_ruchu=True,
    rozpoznawanie_zmeczenia_kierowcy=True,
    rozruch_bez_klucza=True,
    start_stop=True,
    rodzaj_reflektorow='LED',
    regulacja_wysokosci_reflektorow='automatyczna',
    czujniki_parkowania_przod=True,
    czujniki_parkowania_tyl=True,
    dach_panoramiczny=False
)

#  użycie utworzonego obiektu klasy Samochod
print("Marka samochodu:", auto.marka_samochodu )
print("Model  samochodu:", auto.model_samochodu)
print("Moc silnika:", auto.moc_silnika, "KM")
print("Pojemność silnika:", auto.pojemnosc_silnika, "litra")
print("Przyspieszenie 0-100 km/h:", auto.przyspieszenie_0_100, "sekundy")
print("Maksymalna prędkość:", auto.maksymalna_predkosc, "km/h")
print("Rodzaj paliwa:", auto.rodzaj_paliwa)
print("Liczba cylindrów:", auto.liczba_cylindrow)
print("Skrzynia biegów:", auto.skrzynia_biegow)
print("Napęd:", auto.naped)
print("Rodzaj nadwozia:", auto.rodzaj_nadwozia)
print("Długość:", auto.dlugosc, "metra")
print("Szerokość:", auto.szerokosc, "metra")
print("Wysokość:", auto.wysokosc, "metra")
print("Rozstaw osi:", auto.rozstaw_osi, "metra")
print("Masa własna:", auto.masa_wlasna, "kg")
print("Rodzaj opon:", auto.rodzaj_opon)
print("Rozmiar opon:", auto.rozmiar_opon)
