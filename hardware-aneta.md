# MUST HAVE

 **NVMe SSD drive** 

- Mega boost for
  - OS Responsivness
  - I/O performance, which is needed for loading big projects 



# Archicad

## Hardware Req

### Hardware for ARCHICAD 23

##### Recommended hardware

- **Processor**: 64-bit processor with **four or more cores**
- **RAM**: 16 GB or more is recommended; for complex, **detailed models 32 GB or more** may be required
- **Hard disk**: installing ARCHICAD on a SSD drive is recommended; 5 GB free disk space is required for the installation, 10 GB or more is required per active project
- Display: A resolution of 1920 x 1080 or higher is recommended
- **Graphics** card: Dedicated **OpenGL 4.0 compatible** graphics card is recommended to fully exploit hardware acceleration capabilities. **2 GB+ VRAM** is recommended, opt for 4 GB+ with 4K displays. You can find a list of recommended graphics cards at: [http://www.graphisoft.com/videocards](https://www.graphisoft.com/videocards)

You can find more details about recommended hardware on [Help Center](https://helpcenter.graphisoft.com/knowledgebase/25883/).

https://www.graphisoft.com/support/system_requirements/AC23/

## Forum

### 1: https://archicad-talk.graphisoft.com/viewtopic.php?f=7&t=67286

> If you run out of RAM, it doesn't matter how fast your other components are, your systems slows down dramatically.
> For me, the order of priority of components are:
>
> 1. RAM
> 2. CPU
> 3. SSD (NMVe)
> 4. GPU

> Artlantis uses the CPU, while Twinmotion uses the GPU.

>  In my experience, the most important system components in order of priority for me are:
>
> \- RAM (amount of RAM, not clockrate)
> \- CPU
> \- Storage (NMVe SSD)
> \- GPU

### 2: https://archicad-talk.graphisoft.com/viewtopic.php?f=7&t=62655&start=10

> Q: How important is the GPU on these systems when the rendering is CPU based?
>
> A: **GPU affects your day to day interaction with the software, how fast the screen redraws pans etc and whether you get artifacts such as pixelation tearing etc**.
>
> Buy a good GPU, I would recommend a proper workstation card (Quadro) over a gaming card (GeForce) as the drivers and hardware are more reliable. You can buy a mid level quadro P2000 5Gb 

### 3: https://archicad-talk.graphisoft.com/viewtopic.php?f=7&t=66844

> I wouldn’t buy a MacBook at this time, best buying a good PC laptop. At present I’m working from a **HP Zbook studio** and am very happy with the performance. Projects I’m working on include a 24000m2 hospital building and have no performance issues

### APPLE 

# pCon.planner 8.1

## Product Documentation (08-03-2019)

### System requirements: pCon.planner 8.1

| Processor | Quad Core – processor (class 3 GHz)    |
| --------- | -------------------------------------- |
| memory    | 8 GB                                   |
| system    | Windows 10 (64-bit)                    |
| Graphics  | AMD, nVidia, 1 GB, Hardware OpenGL 4.5 |
| Screen    | 1920 x 1080                            |

## Technical tips

> As the pCon.planner is 3D software, it will need adequate resources on the hardware side. This means that it can only be used to its full performance level if installed with a dedicated graphics card.

## Blog official answers

### 1: Src: https://www.easterngraphics.com/pcon/en/2016/09/02/high-quality-computer-low-quality-display/

> Q: Is it possible that rendering is only supported by CPU? I looked at the 3D-Options in the NVIDIA Control Panel and i don’t see a switch where i could choose the graphics card. At CUDA-GPUs i can olny see my GTX 960.
>
> A: Thanks for using pcon.planner! Rendering (both Yafaray and OSPRay) functions **only through the CPU**, so you shouldn’t need to switch the graphic card for rendering purposes.

> Q: I would like to know if you plan to update the Pcon planner to render (OSPRay) **through a graphics cards**. I want to use your program more often to work and
>
> A: **This option isn’t currently a part of future plans**, but we would be sure to inform readers if this becomes a topic for us! The one option that is available right now would be to export your pCon.planner plan as an fbx file. This would allow you to **use pCon.planner for all planning purposes and to open the plan is other rendering programs that are suitable to your needs.**



### 2: https://www.easterngraphics.com/pcon/en/2017/12/12/how-to-solve-display-and-performance-problems-in-pcon-planner/

>  However, to simulate complex calculations such as displaying 3D conent, materials and lighting, you need more power. Your computer usually already brings this power with a hybrid graphics system in the form of a so-called “[dedicated graphics card](http://www.toptenreviews.com/computers/articles/graphics-cards-integrated-vs.-dedicated/)”. This is a second, more powerful graphics card that pops in whenever the chip runs out of steam.





# Cinerender

> Cinerender doesn't use GPU for rendering, this is true. However you want a somewhat decent GPU for working in the 3D window and for showing the 2D views at reasonable speed / frame rate.
>
> For cinerender: a good multicore CPU and at least 16 GB of RAM (for say max A4 size 300 dpi renders) or more if you need to render larger / more complex scenes.



# Ogolnie o softach tego typu

https://max3d.pl/forums/topic/100884-upgrade-zestawu-do-2000-czy-wymiana-na-nowy/

> dokładnie nie wiem, jak działa Corona do Maxa. Renderuje CPU/GPU, czy tylko CPU ?
>
> Ram możesz dokupić, ale szybkości CPU to nie poprawi. Jedynie przełknie **więcej siatki 3D.**
>
>  Ogólnie inwestuj w nowy, mocny procesor. - pracujesz na 3DMaxie.

> Ram ci jest jedynie potrzbny jak renderujesz. Nie ktore aplikacje i sceny tez obciążają RAM. Jeśli twoje sceny nie przekraczają zasobów RAM podczas renderowania to nie ma co kupować. Problem pojawia się jak zaczynają przekraczać to wtedy rendering zwolni bo zaczyna korzystać z zasobów dysku twardego a ten jest znacznie wolniejszy. **Jedynie kasy której nie utopisz to zmieniając kartę. Będziesz miał wydalniejszy <u>viewport</u>**. 
>
> Nie musisz koniecznie iść w 2060 możesz rownie dobrze kupić 1060 lub 1070 - choćby używane. Napewno wpłynie to na **jakość pracy w texturowaniu czy pracy w photoshopie i wydajność viewportu.**
>
> Upgrade RAMu nie wygląda na jakiś wielki koszt. Na pewno taniej to niż kupić nowy komputer. Ja w domu mam 6700k a w pracy robie na 4870k. Mam dużo ramu 64GB ze wzgledu na Zbrusha. 32GB mam w domu.
>
> Texturatorzy podostawali <u>nowe karty</u> pod substance. 
>
> Renderowcy/ lighterzey <u>RAM I nowe thredripery</u>

https://max3d.pl/forums/topic/100903-karta-graficzna-do-3ds-max-2014-i-mental-ray/

> Q: GTX 1660 przyspieszy czas renderingu czy nie ma to w ogóle znaczenia i ta wersja maxa i mental ray korzystają tylko z cpu i ram??
>
> A: Mental Ray **nie korzysta z GPU.**

# GTX VS QUADRO

> **Reliability** is where a quadro card wins out over a GTX card, you will find **multiple posts on these forums where people experience totally random issues which are caused by the GTX** drivers especially the GeForce experience software.
>
> GTX is like a sports car, can get you there very quickly but will require troubleshooting and unplanned maintenance whereas a Quadro card is more like a prime mover designed to run at full load each and every day with minimal downtime