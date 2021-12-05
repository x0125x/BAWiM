# Zadania z projektu 
#### Bezpieczeństwo aplikacji webowych i mobilnych
*prowadzący:* Heorhi Kupryianau, Patrycja Nędza

## Sposoby przechowywania i przetwarzania danych w aplikacjach mobilnych oraz zagrożenia z tym związane 
##### Wszystkie potrzebne programy i pliki znajdziesz w folderze Resources
##### Odpowiedzi na podpunkty z :japanese_ogre: trzeba umieścić na Upelu
##
#### Zadanie 1
1.  Wykorzystaj **`Android Studio`**, by stworzyć wirtualne urządzenie android
2.  Rozpakuj **`DestroyIt.apk`** do AVD
3.  Otwórz plik **`DestroyIt>assets>bin>Data>Managed>Assembly-CSharp.dll`** w **`dnSpy`**

![image](https://user-images.githubusercontent.com/52840109/144683170-0db93078-4d17-4f8d-92fb-8887e8ac2ba4.png)

3.  W jaki sposób są zabiezpieczone pliki zapisów?:japanese_ogre:
4.  Znajdź informacje niezbędne do poprawnego odczytu i edycji pliku.:japanese_ogre:

#### Zadanie 2
1.  Utwórz urządzenie wirtualne android w **`Android Studio`**.
2.  Zainstaluj **`DestroyIt.apk`** na urządzeniu wirtualnym.
3.  Otwórz i ~~zagraj~~ zamknij zainstalowaną przed chwilą grę, by dane się zapisały __*(zapamiętaj wartość monet)*__.
4.  Przenieś plik **`Android>data>com.GameCompany.DestroyIt>files>save`** do **`Downloads`** (bez root'a nie ma dostępu do **`Android>data`**).
5.  Otwórz **`save`** za pomocą **`AES256`**.

    ![image](https://user-images.githubusercontent.com/52840109/144723227-cfff48df-8b59-44d9-9db3-5ef476971fa1.png)
    -   Deszyfruj dane za pomocą informacji uzyskanych w **`Zadaniu 1`** (powinien się pojawić plik **`decrypted`**).
6.  Otwórz **`decrypted`** w dowolnym hex edytorze. 
    -   Znajdź __*zapomiętaną wartość monet*__ i zamień ją na 65 535 (FF FF).
7.  Zaszyfruj **`decrypted`** za pomocą **`AES256`** (powinien się pojawić plik **`encrypted`**).
8.  Zmień nazwę **`encrypted`** na **`save`** i przenieś go do **`Android>data>com.GameCompany.DestroyIt>files`**.
    -   By przenieść plik do folderu **`Android>data`** trzeba mieć root, albo można użyć **`Mix`** *(**`Resources>Mix.apk`**)*.
9.  Sprawdź czy wartość monet się zmieniła.:japanese_ogre:

#### Zadanie 3
1.  Otwórz program **`Hackme.exe`**
2.  Spróbuj zgadnąć liczbę, jeżeli się nie uda, znajdź ją za pomocą inżynierii wstecznej i narzędzia **`Snowman`**:japanese_ogre:

#### Zadanie 4
1. Co się wypiszę do konsoli w następującym kodzie po obfuskacji?:japanese_ogre:
![image](https://user-images.githubusercontent.com/52840109/144746394-a2c269a0-669a-4775-9d0f-02433a652e4f.png)
