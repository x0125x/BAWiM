# Zadania z projektu 
#### Bezpieczeństwo aplikacji webowych i mobilnych
*prowadzący:* Heorhi Kupryianau, Patrycja Nędza

## Sposoby przechowywania i przetwarzania danych w aplikacjach mobilnych oraz zagrożenia z tym związane 
##### Wszystkie potrzebne programy i pliki znajdziesz w folderze Resources
##### Odpowiedzi na podpunkty z :japanese_ogre: trzeba umieścić na Upelu
##
#### Zadanie 1
1.  Wykorzystaj Android Studio, by stworzyć wirtualne urządzenie android
2.  Rozpakuj DestroyIt.apk do AVD
3.  Otwórz plik **`DestroyIt>assets>bin>Data>Managed>Assembly-CSharp.dll`** w **`dnSpy`**

![image](https://user-images.githubusercontent.com/52840109/144683170-0db93078-4d17-4f8d-92fb-8887e8ac2ba4.png)

3.  W jaki sposób są zabiezpieczone pliki zapisów?:japanese_ogre:
4.  Znajdź informacje niezbędne do poprawnego odczytu i edycji pliku.:japanese_ogre:

#### Zadanie 2
1.  Utwórz urządzenie wirtualne android w **`Android Studio`**
2.  Zainstaluj **`DestroyIt.apk`** na urządzeniu wirtualnym
3.  Otwórz i ~~zagraj~~ zamknij zainstalowaną przed chwilą grę, by dane się zapisały __*(zapamiętaj wartość monet)*__
4.  Przenieś plik **`Android>data>com.GameCompany.DestroyIt>files>save`** do **`Downloads`** (by mieć możliwość przenieść go na komputer bez root'a)
5.  Otwórz **`save`** za pomocą **`AES256`**
    -   Deszyfruj dane za pomocą informacji uzyskanych w **`Zadaniu 1`** (powinien się pojawić plik **`encrypted`**)
6.  Otwórz **`encrypted`** w dowolnym hex edytorze. 
    -   Znajdź __*zapomiętaną wartość monet*__ i zamień ją na 65 535 (FF FF)
7. Zaszyfruj **`encrypted`** za pomocą **`AES256`** (powinien się pojawić plik **`decrypted`**)
Wykorzystując znalezione w poprzednim zadaniu informacje zmień wartość zmiennej coins. 
Podmień plik zapisu i sprawdź poprawność dokonanych zmian.

#### Zadanie 3
Jaki był kod przed obfuskacją? Napisz działający odpowiednik programu.
![alt text](https://github.com/x0125x/BAWiM/blob/main/zadanie%203.png)

#### Zadanie 4
Znajdź liczbę, o którą prosi program Hackme.exe
