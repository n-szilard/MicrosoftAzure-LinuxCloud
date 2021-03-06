# MicrosoftAzure-LinuxCloud
A Microsoft Azure a Microsoft által üzemeltetett számítási felhő szolgáltatás a Microsoft által felügyelt adatközpontokon keresztül történő alkalmazáskezeléshez. Szoftvert szolgáltatásként (SaaS), platformot szolgáltatásként (PaaS) és infrastruktúrát szolgáltatásként (IaaS) biztosít, és számos különböző programozási nyelvet, eszközt és keretrendszert támogat, beleértve a Microsoft-specifikus és harmadik féltől származó szoftvereket és rendszereket. A Microsoft Azure szolgáltatásaiért fizetni kell.
Szolgáltatásai tartalmazza: tárolás, mesterséges intelligencia, tárolás, gépi tanulás, üzenetküldés, számítások, adatmenedzsment, fejlesztői ezközök.  

A platform forráskódja zárt, viszont a szoftverfejlesztői csomag (SDK) nyílt forráskódú.

## Platform as a service (PaaS)
Felhőalapú platformszolgáltatás, amely keretrendszert biztosít a fejlesztőknek egyéni alkalmazások létrehozásához. A programozók online érik el ezt a szervert, így nem kell semmi komoly dologgal foglalkozniuk, és megtehetnek, amit tudnak. előny: 
- Felhőalapú komponensek beágyazása a szoftverükbe. 
- néhány funkció készen áll (webszolgáltatás, adatbázis integráció) 
- Sok fejlesztő tud párhuzamosan dolgozni (fejlesztő, tesztelés, telepítés) 
- kevesebb kódolást igényel Vagyis a cég méretétől függően leegyszerűsítheti és költséghatékonyabbá teheti az egészet.

## Software as a Service (SaaS)
A szoftver, mint szolgáltatás egy szoftverlicenc és szállítási modell, amelyben a szoftver licencelése előfizetéses alapon történik, és központilag hostolt. A SaaS más néven on-demand (azaz igény szerinti) szoftver és webalapú/web-hosztolt szoftver.

## Function as a Service (FaaS)
A Function as a service (FaaS) a felhőalapú számítástechnikai szolgáltatások olyan kategóriája, amely olyan platformot biztosít, amely lehetővé teszi az ügyfelek számára az alkalmazások funkcionalitásának fejlesztését, futtatását és kezelését anélkül, hogy bonyolult lenne az infrastruktúra kiépítése és karbantartása, amely általában az alkalmazások fejlesztéséhez és elindításához kapcsolódik. A „szerver nélküli” architektúra elérésének egyik módja egy alkalmazás elkészítése ezen modell szerint, és általában mikroszolgáltatási alkalmazások építésekor használják. Legelterjetteb szolgáltatója az AWS, de a Microsoft Azure is nyújt Function as a Service szolgáltatásokat.

## Infrastructure as a Service (IaaS)
A szolgáltatott infrastruktúra (IaaS) olyan felhőalapú számítási szolgáltatás, amely igény szerint, használatalapú fizetéses alapon kínálja a szükséges számítási, tárolási és hálózati erőforrásokat. Az IaaS a négy felhőszolgáltatás egyike a szolgáltatott szoftver (SaaS), a szolgáltatott platform (PaaS) és a kiszolgáló nélküli megoldások mellett.

# Linux felhőszolgáltatások  
## ownCloud
A ownCloud egy kliens-szerver szoftvercsomag fájltárhely-szolgáltatások létrehozására és használatára. Az ownCloud funkcionálisan hasonlít a széles körben használt Dropboxhoz. Az elsődleges különbség az ownCloud és a Dropbox között az, hogy az ownCloud elsősorban szerverszoftver. Az ownCloud Server Edition ingyenes és nyílt forráskódú, így bárki ingyenesen telepítheti és működtetheti saját privát linux alapú szerverén.  
Az owncloud csak szoftvertermék és nem kínál felhő tárhelyet. A felhasználó saját eszközén kell biztosítani a tárhely kapacitást.

## Nextcloud
A Nextcloud egy kliens-szerver szoftvercsomag fájltárhely-szolgáltatások létrehozására és használatára. Vállalati használatra kész, átfogó támogatási lehetőségekkel. Ingyenes és nyílt forráskódú szoftverről lévén szó, bárki telepítheti és működtetheti saját privát szervereszközén.

A Nextcloud funkcionálisan hasonló a Dropboxhoz, az Office 365-höz vagy a Google Drive-hoz, ha a Collabora Online vagy az OnlyOffice irodai programcsomagokkal együtt használják. A felhőben vagy a helyszínen is tárolható. .
