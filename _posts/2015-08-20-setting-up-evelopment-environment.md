---
layout: post
title:  "Setting up Your Development Environment."
date:   2015-08-20 14:32:09
categories: Development
---
工欲善其事，必先利其器。  

## Windows  

### Environment Variables  
**APPDATA**=D:\XXXX\AppData\Roaming  
**LOCALAPPDATA**=D:\XXXX\AppData\Local  
**USERNAME**=panhao  
**USERPROFILE**=D:\XXXX  
**HOME**=D:\XXXX  
**Path**=  
**PATHEXT**=.COM;.EXE;.BAT;.CMD;.VBS;.VBE;.JS;.JSE;.WSF;.WSH;.MSC;.PY  
**ComSpec**=C:\windows\system32\cmd.exe  
**JAVA_HOME**=D:\YYYY\jdk\jre  
**PYTHONPATH**=D:\YYYY\python  
**NODE_PATH**=D:\YYYY\node\node_modules  
**_JAVA_OPTIONS**=-Duser.home=D:\XXXX -Duser.language=en -Duser.country=CN -Dfile.encoding=UTF-8  

### Files Managements
[Total Commander](http://www.ghisler.com/)  
[MultiCommander](http://multicommander.com/)  
[Double Commander](http://doublecmd.sourceforge.net/)  

#### Set environment variables before launch files manager  

### Eclipse
Using x86_64, and x.x.2 version.

#### Backup important files before the first launching
configuration  
dropins  
p2  
artifacts.xml  
eclipse.ini  

#### Specify your eclipse.ini
{% highlight text %}
...
--launcher.defaultAction
openFile
--launcher.appendVmargs
-vm
jdk/bin/javaw.exe
-vmargs
-Dosgi.requiredJavaVersion=1.7
-Duser.language=en
-Duser.country=CN
-Dfile.encoding=UTF-8
-Xmn512m
-Xms1024m
-Xmx1024m
-XX:+UseParNewGC
-XX:+UseConcMarkSweepGC
-XX:+DisableExplicitGC
-Xverify:none
{% endhighlight %}

#### Using dropins folder to manage your plugins

#### Using keyboard
[Eclipse Shortcuts](http://www.shortcutworld.com/en/win/Eclipse.html)

#### Customize your perspectives

#### Using multi Window

#### Split your Editor


### IDEA

#### Specify your idea64.exe.vmoptions
{% highlight text %}
-ea
-Dsun.io.useCanonCaches=false
-Djava.net.preferIPv4Stack=true
-Dfile.encoding=UTF-8
-Xmn512m
-Xms1024m
-Xmx1024m
-XX:+UseParNewGC
-XX:+UseConcMarkSweepGC
-XX:ReservedCodeCacheSize=225m
-XX:SoftRefLRUPolicyMSPerMB=50
-XX:+DisableExplicitGC
-Xverify:none
{% endhighlight %}

#### Using keyboard
[IntelliJ IDEA Default Keymap](https://www.jetbrains.com/idea/docs/IntelliJIDEA_ReferenceCard.pdf)


### Text Editor
[Notepad++](https://notepad-plus-plus.org/)
[Sublime Text](http://www.sublimetext.com/)
[Atom](https://atom.io/)
[Brackets](http://brackets.io/)


### Console
Windows Command 
[TCC/LE](https://jpsoft.com/tccle-cmd-replacement.html)
[cmder](http://gooseberrycreative.com/cmder/)
[Clink](http://mridgers.github.io/clink/)
[ConEmu](http://conemu.github.io/)
[msys2](http://msys2.github.io/)


## Browser

### Chrome

#### Using standalone user data folder  
--user-data-dir=%XXXX%\Chrome_Blue

#### My development Chrome Extensions and Apps
[Context](https://chrome.google.com/webstore/detail/context/aalnjolghjkkogicompabhhbbkljnlka)  
[DHC - REST/HTTP API Client](https://chrome.google.com/webstore/detail/context/aejoelaoggembcahagimdiliamlcdmfm)  
[Caret-T](https://chrome.google.com/webstore/detail/context/agiednhnlghobdgpgfdnbdaflnngmoij)  
[Writebox](https://chrome.google.com/webstore/detail/context/bbehjmjchoiaglkeboicbgkpfafcmhij)  
[JSON Formatter](https://chrome.google.com/webstore/detail/context/bcjindcccaagfpapjjmafapmmgkkhgoa)  
[Web Developer](https://chrome.google.com/webstore/detail/context/bfbameneiokkgbdmiekhjnmfkcnldhhm)  
[DevTools Theme: Zero Dark Matrix](https://chrome.google.com/webstore/detail/context/bomhdjeadceaggdgfoefmpeafkjhegbo)  
[HTML Validator](https://chrome.google.com/webstore/detail/context/cgndfbhngibokieehnjhbjkkhbfmhojo)  
[JSONView](https://chrome.google.com/webstore/detail/context/chklaanhfefbnpoihckbnefhakgolnmc)  
[RegExp Tester App](https://chrome.google.com/webstore/detail/context/cmmblmkfaijaadfjapjddbeaoffeccib)  
[Clear Cache](https://chrome.google.com/webstore/detail/context/cppjkneekbjaeellbfkmgnhonkkjfpdn)  
[BuiltWith Technology Profiler](https://chrome.google.com/webstore/detail/context/dapjbgnjinbpoindlpdmhochffioedbn)  
[jQuery Debugger](https://chrome.google.com/webstore/detail/context/dbhhnnnpaeobfddmlalhnehgclcmjimi)  
[Tampermonkey](https://chrome.google.com/webstore/detail/context/dhdgffkkebhmkfjojejmpbldmpobfkfo)  
[Vim](https://chrome.google.com/webstore/detail/context/dhhoacdlegcbdglbfnhgnlchpkdlofkb)  
[Dark WebSocket Terminal](https://chrome.google.com/webstore/detail/context/dmogdjmcpfaibncngoolgljgocdabhke)  
[Markdown Editor](https://chrome.google.com/webstore/detail/context/dpibenlpmppnjcjfpcdgfomalnejildm)  
[Ra](https://chrome.google.com/webstore/detail/context/egipeapdjjhflkafmacobnmdbdkanoag)  
[ARC Welder](https://chrome.google.com/webstore/detail/context/emfinbmielocnlhgmfkkmkngdoccbadn)  
[Postman - REST Client](https://chrome.google.com/webstore/detail/context/fdmmgilgnpjigdojojpjoooidkmcomcm)  
[Full Page Screen Capture](https://chrome.google.com/webstore/detail/context/fdpohaocaechififmbbbbbknoalclacl)  
[RegExp Tester](https://chrome.google.com/webstore/detail/context/fekbbmalpajhfifodaakkfeodkpigjbk)  
[Postman](https://chrome.google.com/webstore/detail/context/fhbjgbiflinjbdggehcddcbncdddomop)  
[Serverauditor - SSH client](https://chrome.google.com/webstore/detail/context/fjcdjmmkgnkgihjnlbgcdamkadlkbmam)  
[Stylish](https://chrome.google.com/webstore/detail/context/fjnbnpbmkenffdnngjfgmeleoegfcffe)  
[Caret](https://chrome.google.com/webstore/detail/context/fljalecfjciodhpcledpamjachpmelml)  
[CSS Grady](https://chrome.google.com/webstore/detail/context/gdhlnmdfoeaagdlljpiklddgfnfidfli)  
[CSSViewer](https://chrome.google.com/webstore/detail/context/ggfgijbpiheegefliciemofobhmofgce)  
[Click&Clean](https://chrome.google.com/webstore/detail/context/ghgabhipcejejjmhhchfonmamedcbeod)  
[FastString - String Operations](https://chrome.google.com/webstore/detail/context/gpknmoniniacaobkeclmiiaekniaddnd)  
[Gradient Creator!](https://chrome.google.com/webstore/detail/context/hcplneddoadgichngfbobgpllfphdfla)  
[Font Playground](https://chrome.google.com/webstore/detail/context/hdpmpnhaoddjelneingmbnhaibbmjgno)  
[Advanced REST client](https://chrome.google.com/webstore/detail/context/hgmloofddffdnphfgcellkdfbfbjeloo)  
[Eye Dropper](https://chrome.google.com/webstore/detail/context/hmdcmlfkchdmnmnmheododdhjedfccka)  
[ExtensionJetBrains IDE Support](https://chrome.google.com/webstore/detail/context/hmhgeddbohgjknpmjagkdomcpobmllji)  
[Appspector](https://chrome.google.com/webstore/detail/context/homgcnaoacgigpkkljjjekpignblkeae)  
[Web Developer Checklist](https://chrome.google.com/webstore/detail/context/iahamcpedabephpcgkeikbclmaljebjp)  
[Live HTTP Headers](https://chrome.google.com/webstore/detail/context/iaiioopjkcekapmldfgbebdclcnpgnlo)  
[AngularJS Batarang](https://chrome.google.com/webstore/detail/context/ighdmehidhipcmcojjgiloacoafjmpfk)  
[jquery-injector](https://chrome.google.com/webstore/detail/context/indebdooekgjhkncmgbkeopjebofdoid)  
[WhatFont](https://chrome.google.com/webstore/detail/context/jabopobgcpjmedljpbcaablpmlmfcogm)  
[Chremacs](https://chrome.google.com/webstore/detail/context/kglkomofdfeolfjjnmhdpkadaildaogd)  
[Window Resizer](https://chrome.google.com/webstore/detail/context/kkelicaakdanhinjdeammmilcgefonfh)  
[Sketchpad](https://chrome.google.com/webstore/detail/context/kkghjbajgkcialbbimbifdcjilhcgoim)  
[Color Sphere!](https://chrome.google.com/webstore/detail/context/knomilfbnhpkmibhmleppnkmcempglag)  
[Hosts Manager](https://chrome.google.com/webstore/detail/context/kpfmckjjpabojdhlncnccfhkfhbmnjfi)  
[IcoMoon](https://chrome.google.com/webstore/detail/context/kppingdhhalimbaehfmhldppemnmlcjd)  
[IP Address and Domain Information](https://chrome.google.com/webstore/detail/context/lhgkegeccnckoiliokondpaaalbhafoa)  
[JSON Editor](https://chrome.google.com/webstore/detail/context/lhkmoheomjbkfloacpgllgjcamhihfaj)  
[Lightshot](https://chrome.google.com/webstore/detail/context/mbniclmhobmnbdlbpiphghaielnnpgdp)  
[App Runtime for Chrome](https://chrome.google.com/webstore/detail/context/mfaihdlpglflfgpfjcifdjdjcckigekc)  
[Tailor](https://chrome.google.com/webstore/detail/context/mfakmogheanjhlgjhpijkhdjegllgenf)  
[HostAdmin App](https://chrome.google.com/webstore/detail/context/mfoaclfeiefiehgaojbmncmefhdnikeg)  
[Parallax Background Builder](https://chrome.google.com/webstore/detail/context/mklkemobgbjfgpnhfbdbainmenjanpbe)  
[Text](https://chrome.google.com/webstore/detail/context/mmfbcljfglbokpmkimbfghdkjmjhdgbg)  
[HTTP/2 and SPDY indicator](https://chrome.google.com/webstore/detail/context/mpbpobfflnpcgagjijhmgnchggcjblin)  
[Poe: Markdown Editor](https://chrome.google.com/webstore/detail/context/mpghdlgejmakmgbigejnjnmgdjaddhje)  
[Chrome MySQL Admin](https://chrome.google.com/webstore/detail/context/ndgnpnpakfcdjmpgmcaknimfgcldechn)  
[PrettyPrint](https://chrome.google.com/webstore/detail/context/nipdlgebaanapcphbcidpmmmkcecpkhg)  
[Color Picker and Converter](https://chrome.google.com/webstore/detail/context/ofkcpbjmhcdipbhcdfechmckpaofdjlf)  
[Palette for Chrome](https://chrome.google.com/webstore/detail/context/oolpphfmdmjbojolagcbgdemojhcnlod)  
[Proxy SwitchyOmega](https://chrome.google.com/webstore/detail/context/padekgcemlokbadohgkifijomclgjgif)  
[Zed Code Editor](https://chrome.google.com/webstore/detail/context/pfmjnmeipppmcebplngmhfkleiinphhp)  
[Secure Shell](https://chrome.google.com/webstore/detail/context/pnhechapfaindjhompbnflcldabbghjo)  
[Chrome Dev Editor](https://chrome.google.com/webstore/detail/context/pnoffddplpippgcfjdhbmhkofpnaalpg)  