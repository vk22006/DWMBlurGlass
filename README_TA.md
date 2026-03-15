# DWMBlurGlass
உலகளாவிய கணினித் தலைப்புப் பட்டையில் தனிப்பயன் எஃபெக்ட்ஸ்களைச் சேர்க்கவும்; இது Windows 10 மற்றும் Windows 11-ஐ ஆதரிக்கிறது.

给全局系统标题栏添加自定义效果，支持win10和win11
#
| [中文](/README_ZH.md) | [English](/README.md) | [italiano](/README_IT.md) | [français](/README_FR.md) | [Türkçe](/README_TR.md) | [español](/README_ES.md) | [German](/README_DE.md) | [Português Brasil](/README_PTBR.md) | [עברית](/README_HE.md) | [தமிழ்](/README_TA.md)

இந்த project [LGNU V3 license](/COPYING.LESSER) -ஸை பயன்படுத்துகிறது.

## !!! DWMBlurGlass-ஐ வேறு எங்கிருந்தும் பதிவிறக்கம் செய்யாதீர்கள்.!!!!
> [!WARNING]
> எங்களைப்போல் நடித்துக்கொண்டு, தீங்கு விளைவிக்கும்  நோக்கத்துடன் DWMBlurGlass-ஐ ஒருவர் பதிவிட்டு வருவதை நாங்கள் கண்டறிந்துள்ளோம்.
> 
> இதுபோன்ற நிகழ்வுகள் மீண்டும் நடைபெறுவதைத் தவிர்க்க, தயவுசெய்து அதிகாரப்பூர்வமற்ற முகவரிகளிலிருந்து மென்பொருளைப் பதிவிறக்கம் செய்யாதீர்கள்!
> 
> **எங்களுக்கு எந்தவொரு அதிகாரப்பூர்வ Discord server-உம் இல்லை.**
> 
> நாங்கள் மென்பொருளை [Github](https://github.com/Maplespe/DWMBlurGlass/releases), [Bilibili](https://space.bilibili.com/87195798) மற்றும் [winmoes](https://winmoes.com)-இல் மட்டுமே விநியோகிக்கிறோம்.
> 
> மேலும், சோதனைக்கான புதிய பதிப்புகள் எவையும், பைனரிகளை (binaries) முன்கூட்டியே வெளியிடுவதற்குப் பதிலாக, முதலில் சோதனைப் பிரிவிற்கே (test branch) அனுப்பப்படுகின்றன.

[![license](https://img.shields.io/github/license/Maplespe/DWMBlurGlass.svg)](https://www.gnu.org/licenses/lgpl-3.0.en.html)
[![Github All Releases](https://img.shields.io/github/downloads/Maplespe/DWMBlurGlass/total.svg)](https://github.com/Maplespe/DWMBlurGlass/releases)
[![GitHub release](https://img.shields.io/github/release/Maplespe/DWMBlurGlass.svg)](https://github.com/Maplespe/DWMBlurGlass/releases/latest)
<img src="https://img.shields.io/badge/language-c++-F34B7D.svg"/>
<img src="https://img.shields.io/github/last-commit/Maplespe/DWMBlurGlass.svg"/>  

## Catalog
- [எஃபெக்ட்ஸ் ](#effects)
- [இணக்கத்தன்மை](#compatibility)
- [கேலரி](#gallery)
- [மெட்டீரியல் எபெக்ட்ஸ்](#material-effects)
  - [Blur](#blur)
  - [Aero](#aero)
  - [Acrylic](#acrylic)
  - [Mica](#mica)
  - [MicaAlt](#micaalt)
- [எப்படி பயன்படுத்துவது](#how-to-use)
  - [நிறுவுதல்](#install)
  - [நிறுவல் நீக்கம்](#uninstall)
- [மொழி கோப்புகள்](#language-files)
- [சார்பு கூறுகள்](#dependencies)

## எஃபெக்ட்ஸ் 
* உலகளாவிய அமைப்பு தலைப்புப் பட்டியில் தனிப்பயன் எஃபெக்ட்ஸ்களைச் சேர்க்கிறது.
* தனிப்பயனாக்கக்கூடிய உலகளாவிய blur radius அல்லது title bar blur radius மட்டும்.
* தனிப்பயனாக்கக்கூடிய தலைப்புப் பட்டை கலப்பு வண்ணங்கள்.
* தனிப்பயனாக்கக்கூடிய தலைப்புப் பட்டை உரை நிறம்.
* ரோ பிரதிபலிப்புகள் மற்றும் பேரலக்ஸ் எஃபெக்ட்ஸ்கள் கிடைக்கின்றன.
* Windows 7 பாணி தலைப்புப் பட்டை பொத்தான் உயரத்தை மீட்டமை.
* Windows 7 பாணி தலைப்புப் பட்டை பொத்தான் பளபளப்பை மீட்டமை.
* பழைய Windows 7 API DwmEnableBlurBehindWindow ஐப் பயன்படுத்தும் நிரல்களுக்கு blur எஃபெக்ட்ஸ்களை இயக்குவதற்கான ஆதரவு.
* `Blur`, `Aero`, `Acrylic` மற்றும் `Mica (Win11 மட்டும்)` எஃபெக்ட்ஸ்களை ஆதரிக்கிறது.
* தனித்தனியாக தனிப்பயனாக்கக்கூடிய Light/Dark வண்ண பயன்முறை தானியங்கி மாறுதல்.
* `CustomBlur`, `AccentBlur` மற்றும் `SystemBackdrop` blur முறைகள் கிடைக்கின்றன.
* மூன்றாம் தரப்பு தீம் ஆதரவு.

![image](./Screenshot/001701.png)
![image](./Screenshot/10307.png)

## இணக்கத்தன்ம
**Windows 10 2004** முதல் **Windows 11-இன் சமீபத்திய பதிப்பு** வரை ஆதரிக்கப்படுகிறது. (Windows Insider பதிப்புகளில் சில blurring முறைகள் ஆதரிக்கப்படுவதில்லை.).

DWM ஐ மேலும் தனிப்பயனாக்க மூன்றாம் தரப்பு கருப்பொருள்களுடன் பயன்படுத்தலாம்.

பயன்பாட்டின் ரெண்டரிங் லாஜிக்கை நாங்கள் மாற்றுவதில்லை, இது MicaForEveryone இன் லாஜிக்கிலிருந்து முற்றிலும் வேறுபட்டது, எனவே மூன்றாம் தரப்பு நிரல்களுடன் இணக்கத்தன்மையை அதிகரிக்கிறது.

நாங்கள் DWM ஐ தலைகீழாக பகுப்பாய்வு செய்து, அதிர்ச்சியூட்டும் காட்சி விளைவுகளைக் கொண்டுவர தனிப்பயன் blur முறையை உருவாக்கினோம், ஆனால் நீங்கள் "SystemBackdrop`" blur முறையைத் தேர்வுசெய்தால், அது கணினியின் பொதுவில் கிடைக்கும் இடைமுகங்களைப் பயன்படுத்துகிறது மற்றும் MicaForEveryone ஐப் போலவே அதே விளைவைக் கொண்டுள்ளது.

MicaForEveryone உடன் பயன்படுத்த பரிந்துரைக்கப்படவில்லை, அதனுடன் இணக்கத்தன்மையை நாங்கள் உத்தரவாதம் செய்ய மாட்டோம்.

[ExplorerBlurMica](https://github.com/Maplespe/ExplorerBlurMica)உடன் இணக்கமானது, இவை இணைந்து செயல்படும்போது செயல்திறன் சிறப்பாக இருக்கும்.

[TranslucentFlyouts](https://github.com/ALTaleX531/TranslucentFlyouts) உடன் இணக்கமானது. (**குறிப்பு: இப்பணித்திட்டம் TF உடன் இணக்கமாக இருப்பினும், EBMv2 ஆனது TFv2 உடன் முழுமையாக இணக்கமாக இல்லை.**)

## கேலரி
<details><summary><b>Windows 11</b></summary>
  
![image](./Screenshot/10307.png)

![image](./Screenshot/102134.png)

- [x] DWMAPI Mica விளைவை மேலெழுது (Win11)

![image](./Screenshot/013521.png)
</details>

<details><summary><b>Windows 10</b></summary>

![image](./Screenshot/001701.png)

![image](./Screenshot/100750.png)

மூன்றாம் தரப்புத் தோற்றங்களைப் பயன்படுத்துதல்

- [x] பாடெர்களுக்கும் எஃபெக்ட்ஸ்களைை நீட்டித்தல் (Win10)
- [x] Aero பிரதிபலிப்பு எஃபெக்ட்ஸ்
- [x] Win7 பாணியிலான தலைப்புப் பட்டி பொத்தான் அளவை மீட்டமைத்தல்

![image](./Screenshot/025410.png)

</details>

## மெட்டீரியல் எபெக்ட்ஸ்
### Blur
> அடிப்படையான, pure blur. இதில் விசேஷம் ஏதுமில்லை.

![image](./Screenshot/blur.png)

### Aero
> Windows 7-இன் கண்ணாடி விளைவு, with saturation and exposure effects on the background when a window is inactive.

![image](./Screenshot/aero.png)

![image](./Screenshot/aero_inactive.png)

### Acrylic
> அக்ரிலிக் செய்முறை: பின்னணி, மங்கலாக்கம், விலக்கல் கலப்பு, செறிவூட்டல், நிறம்/சாயல் மேலடுக்கு மற்றும் இரைச்சல்.

![image](./Screenshot/acrylic.png)

### Mica
> Mica செய்முறை: மங்கலாக்கப்பட்ட வால்பேப்பர், செறிவூட்டல் மற்றும் வண்ண/சாயல் மேலடுக்கு.

![image](./Screenshot/mica.png)

### MicaAlt
மேற்கூறிய விளைவுகள் அனைத்தையும், வண்ணங்களை ஒன்றிணைக்கும் வகையில் தனிப்பயனாக்கிக்கொள்ள முடியும்.

MicaAlt என்பது சாம்பல் நிறச் சாயலைக் கொண்ட 'Mica' ஆகும்; MicaAlt விளைவைப் பெறுவதற்கு, நீங்கள் விரும்பும் வகையில் வண்ணக் கலவையை நீங்களே மாற்றியமைத்துக்கொள்ளலாம்.

## எப்படி பயன்படுத்துவது

### நிறுவுதல்
1. [Release](https://github.com/Maplespe/DWMBlurGlass/releases) பக்கத்திலிருந்து தொகுக்கப்பட்ட நிரல் காப்பகத்தைப் பதிவிறக்கவும்.
2. அதை "`C:\Program Files`" போன்ற ஒரு இடத்தில் பிரித்தெடுக்கவும்.
<details><summary><b>3. DWMBlurGlass.exe GUI நிரலை இயக்கி, 'Install' என்பதைக் கிளிக் செய்யவும்.</b></summary>

![image](./Screenshot/012746.png)

> நீங்கள் 'Install' என்பதைக் கிளிக் செய்யும்போது எதுவும் நிகழவில்லை என்றால், நீங்கள் 'Symbols' பக்கத்திற்குச் சென்று 'Download' என்பதைக் கிளிக் செய்ய வேண்டும்.

> **எதிர்காலத்தில், குறிப்பாக கணினிப் புதுப்பிப்புகளுக்குப் பிறகு, 'symbols' விடுபட்டிருப்பது குறித்த அறிவிப்பை நீங்கள் பெறக்கூடும்.**

![image](./Screenshot/012924.png)

</details>

### நிறுவல் நீக்கம்
1. DWMBlurGlass.exe GUI நிரலை இயக்கி, 'Uninstall' என்பதைக் கிளிக் செய்யவும்.
2. தொடர்புடைய கோப்புகளை நீக்கவும்.

## மொழி கோப்புகள்
நாங்கள் ஆங்கிலம், எளிமைப்படுத்தப்பட்ட சீனம், ஸ்பானிஷ், போர்த்துகீசியம் மற்றும் பல மொழிகளை வழங்குகிறோம்.
வேறு மொழிகளில் மொழிபெயர்க்க எங்களுக்கு உதவ நீங்கள் விரும்பினால், மொழி கோப்பு வடிவங்கள் குறித்த விவரங்களுக்குக் கீழே பார்க்கவும்.

1. முதலில், நீங்கள் இந்த களஞ்சியத்தை (repository) 'fork' செய்து, அதை உங்கள் கணினியில் (locally) 'clone' செய்ய வேண்டும்.
2. "`Languagefiles`" கோப்புறையைத் திறந்து, "`en-US.xml`" போன்ற ஏற்கனவே உள்ள ஒரு மொழிக் கோப்பைத் தேர்ந்தெடுத்து, அதன் நகல் ஒன்றை உருவாக்கவும்.
3. அந்தக் கோப்புப் பெயரில் உள்ள குறியீட்டை, நீங்கள் மொழிபெயர்க்க விரும்பும் [இலக்கு மொழியின் பெயருக்கு](https://learn.microsoft.com/en-us/windows/win32/intl/locale-names) ஏற்றவாறு மாற்றியமைக்கவும்; பின்னர் அந்த XML கோப்பை உங்களுக்குப் பிடித்த ஏதேனும் ஒரு உரைத் தொகுப்பானில் (text editor) திறக்கவும்.
4. கோப்பின் இரண்டாவது வரியில் உள்ள "`local`" புலத்தில், உங்கள் இலக்கு மொழியின் குறியீட்டை உள்ளிடவும்; இந்தக் குறியீடு, கோப்புப் பெயரில் உள்ள குறியீட்டிற்குச் சமமாக இருக்க வேண்டும் (.xml நீட்டிப்பு இல்லாமல்).
5. "`author`" புலத்தில் உங்கள் பெயரை உள்ளிடலாம்.
6. அடுத்து, XML வடிவத்தில் உள்ள புலங்களின் மதிப்புகளை மொழிபெயர்க்கவும் (புலங்களின் பெயர்களை மொழிபெயர்த்துவிடாமல் கவனமாக இருக்கவும்). இதற்கான சரியான வடிவம்: `<config>Config</config>` என்பதை `<config>xxxx</config>` என மாற்றுவதாகும்.
7. மொழிபெயர்ப்பு முடிந்ததும் கோப்பைச் சேமித்து, DWMBlurGlass.exe நிரல் அமைந்துள்ள கோப்புறையில் உள்ள "data\lang" அடைவிற்குள் அதை நகலெடுக்கவும்.
8. அடுத்து, DWMBlurGlass.exe நிரலைத் திறந்து, அந்த மொழிக் கோப்பு சரியாகச் செயல்படுகிறதா என்பதைச் சோதித்துப் பார்க்கவும். அது சரியாகச் செயல்படவில்லை என்றால், மொழிக் குறியீடு அமைப்புகளைச் சரிபார்க்கவும்; மேலும் அந்தக் கோப்பு XML வடிவமைப்பு விதிமுறைகளுக்கு இணங்க உள்ளதா என்பதையும் உறுதிப்படுத்திக்கொள்ளவும்.
9. இறுதியாக, அந்தக் கோப்பை நீங்கள் 'fork' செய்துள்ள உங்கள் சொந்த களஞ்சியத்தில் 'commit' செய்யவும்; பின்னர் திட்டத்தின் முதன்மைக் கிளைக்கு (main branch) ஒரு 'pull request' அனுப்பவும்.
10. உங்கள் கோரிக்கை அங்கீகரிக்கப்பட்ட பிறகு, எதிர்காலத்தில் வெளியாகும் மென்பொருள் புதுப்பிப்புடன் உங்கள் மொழிக் கோப்பும் வெளியிடப்படும்.
   

## சார்பு கூறுகள்
* [MiaoUI Lite interface library v2](https://github.com/Maplespe/MiaoUILite)
* [AcrylicEverywhere](https://github.com/ALTaleX531/AcrylicEverywhere) - CustomBlur முறையின் தனித்த, மேல்நிலைச் செயலாக்கம், இதற்கான ஆய்வு மற்றும் ஆதரவை வழங்கிய ALTaleX-க்கு நன்றி.
* [minhook](https://github.com/m417z/minhook)
* [pugixml](https://github.com/zeux/pugixml)
* [VC_LTL](https://github.com/Chuyu-Team/VC-LTL5)
* [Windows Implementation Libraries](https://github.com/Microsoft/wil)
