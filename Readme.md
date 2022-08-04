# ATM RUSH CLONE 
Level-Up Akademi süreci boyunca 3 ekip arkadaşımla birlikte yapmış olduğumuz ATM Rush oyununun kopyasının kaynak kodlarını sizlerle paylaşıyoruz.

## Proje Süreci ve Yönetimi
Projeye başlamadan önce ekip arkadaşlarımla birlikte UML Diagram oluşturarak ilerleyeceğimiz yolda bir harita çizdik. 
Genel bir çok durumu oyunun orijinalini inceleyerek düşünmeye çalıştık ve aşağıda görmüş olduğunuz UML diagramını oluşturduk.

![image](https://user-images.githubusercontent.com/68375602/182611639-d04ae482-c368-4480-9f24-42f47ae495c0.png)

Diagramı oluştururken bazı eksik durumları oyunun yapım esnasında tekrar düzenleyerek oyuna entegre işlemini sorunsuz bir şekilde gerçekleştirdik. 
Genel kod mimarisi üzerine öğrendiğimiz gelişmeleri bu oyunda kullanarak diğer kodlara olan bağımlılığı en aza indirgeyecek senaryoları oluşturarak 
oyunumuzda temel olarak Observer Pattern'i kullandık. Bununla birlikte Command Pattern, Scriptable Object, Facade Pattern, Singleton gibi yapılardan da yararlanarak
daha anlaşılır ve düzgün bir kod yapısı oluşturduk.
## Oynanış
![ATmRushGamePlay](https://user-images.githubusercontent.com/76806086/182844698-6b5e4e0b-68bd-46da-b014-22393a04e234.gif)


## Kullanılan Ek Paketler

* Toony Colors 
* DOTween
* Easy Save
* GUI Packages
* Epic Toon

## Yapılan Mekanikler
* Object Lerp
* Player Movement
* Object Scale size up and down
* Minigame
* Atm deposit Mechanic
* Change Mesh
* Obstacle Animation and Collision


