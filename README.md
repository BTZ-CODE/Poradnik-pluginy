# Poradnik pluginy
Poradnik jak nauczyć się programować pluginy do gry Minecraft w języku Java.

# Wprowadznie
Cześć, dziś przedstawię ci kompletną drogę jaką musisz przebyć i czego musisz się nauczyć aby stworzyć swój pierwszy plugin
lub zostać majnkraft developa

## Spis treśći:
 - **1. Nauka Javy**
 - **2. Nauka czytania docs'ów**
 - **3. Nauka wykorzystywania API**
 - **4. Przeczytanie dokumentacji PAPERA/SPIGOTA (preferowany paper)**


# 1. Nauka Javy
Po pierwsze, musisz nauczyć się javy. Nie masz jechać na templatkach czy innym shicie, który niczego cię nie nauczy, a tylko zrujnuje frajde.
Aby nauczyć się javy możesz skorzystać z różnych dróg (czytanie docs'ów/Poradniki na yt). Osobiście preferuję to 2. Poniżej wylistuje Ci parę fajnych kursów z których sam korzystałem (obejrzyj najpierw pierwszy, potem w drugim uzupełnij wiedzę):

 - https://youtube.com/playlist?list=PLp9WLfHXxbccTjbdEqf79zE5eJ9n6aaPW&si=HxiLApIo8m3rT9Lu
 - https://youtube.com/playlist?list=PL6aekdNhY7DCM1wGLQCE9eP3kPzu-P7E7&si=cbv9NSRv7SCtuzJi

### Pamiętaj, że nauka samej Javy też trochę ci zajmię!
**Po każdym odcinku stosuj nowo poznaną wiedzę w boju**

# Polecam teraz przestać to czytać jeżeli nie wykonałeś pierwszego etapu

# 2. Czytanie dokumentacji
Aby zacząć programować bardzo ważną kwestią jest **nauka czytania dokumentacji**. Dokumentacja to nic innego jak wikipedia stworzona przez autora innego programu, do którego chcesz coś dopisywać, np. paper. W dokumentacji znajdują się przykłady, dostępne metody, metody które są zdeprekatowane/przestarzałe itp.
Czytanie dokumentacji **NIE JEST** jak czytanie książki, czytasz, wracasz się o parę linijek, próbujesz zastosować to czego potrzebujesz. Aby zacząć pisać wystarczy znaleźć tylko to co cię interesuje, nic więcej, ale na sam początek warto przeczytać podstawy dokumentacji.


# 3. Korzystanie z API
Aby zacząć wykorzystywać zewnętrzne API pluginów trzeba je dodać jako dependency w pluginie i je zaimportować, wtedy po przeczytaniu **dokumentacji** (patrz punkt 2) możesz korzystać z metod dostępnych w innym programie (np. paper). Aby tworzyć pluginy do Minecraft'a wystarczy wgrać sobie do InteliJ idea plugin Minecraft, wybierasz opcję Minecraft podczas tworzenia projektu, wersje, silnik itp. i gotowe, masz swój pom.xml.

# 4. Przeczytaj dokumentację Papera
Aby stworzyć pierwszy plugin musisz znać dostępne metody itp. Jest to niezbędne do stworzenia funkcjonującego pluginu. Jako, że nie ma na YouTub'ie żadnego sensownego poradnika to przez ten proces musi przeprowadzić cię dokumentacja papera dostępna tutaj: https://docs.papermc.io/paper

# Pierwszy plugin
Nie rzucaj się od razu na głęboką wodę, napisz coś prostego, ja na starcie napisałem własny core, który ee, nie jest idealny? Co z tego skoro pisałem go po to żeby się nauczyć jak robić to lepiej.

## Nie korzystajcie z CommandExecutor, w tym repo wrzucę wam customowe API do rejestracji komend którego używam.

A tu macie prosty CodeBlock wykorzystujący je:

 ```java     private final Main main;
    public SpawnKill(Main main) {
        super("SpawnKill", "&6/SpawnKill", "Opis komendy", "permisja.komendy", null);
        this.main = main;
        this.register;
    }
```

P.S z pytaniami możesz pisać tu: https://discord.gg/ZVgMDakFZK lub dodając mnie na discordzie btzcior ;D
