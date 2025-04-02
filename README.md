# 🍳 Java Meal Planner – Planer Śniadań

Prosty projekt w języku **Java**, który pozwala planować śniadania na każdy dzień tygodnia, wybierać je z gotowej listy (100 pozycji w Excelu), oraz losować posiłki.

## ✅ Funkcje:
- Dodawanie śniadania na konkretny dzień
- Przeglądanie planu tygodnia
- Wczytywanie śniadań z pliku Excel (`.xlsx`)
- Losowanie śniadania
- (opcjonalnie) Zapisywanie planu do pliku

## 📁 Struktura klas:
| Klasa         | Opis                                 |
|---------------|--------------------------------------|
| `Meal`        | Przechowuje nazwę, kalorie, opis     |
| `MealPlan`    | Mapa z dniami tygodnia i posiłkami   |
| `MealLoader`  | Wczytuje listę śniadań z Excela      |
| `Main`        | Menu tekstowe i logika programu      |

## 🧰 Wymagania:
- Java 17 lub nowsza
- Biblioteka [Apache POI](https://poi.apache.org/) – do wczytywania plików Excel
