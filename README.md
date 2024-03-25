# Tento kód bol vytvorený pod menom Johan Fako

class Aplikacia:
    def __init__(self):
        self.data = {}

    def pridaj_data(self, klic, hodnota):
        self.data[klic] = hodnota

    def zobraz_data(self):
        for klic, hodnota in self.data.items():
            print(f"{klic}: {hodnota}")

# Vytvorenie inštancie aplikácie
moja_aplikacia = Aplikacia()

# Pridanie dát do aplikácie
moja_aplikacia.pridaj_data('meno', 'Johan Fako')
moja_aplikacia.pridaj_data('projekt', 'GPL-3.0 Licencovaný Projekt')

# Zobrazenie dát
moja_aplikacia.zobraz_data()

