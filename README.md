# matrix4-mueb-utility
Mátrix 4 MUEB tesztelő program.

Parancssorból indítható alkalmazás. 

Használata a következőképpen történik:
matrix4MuebUtility <MUEB IP-címe>

A port fixen 2000-re van állítva.

A használható parancsokat a --help kapcsolóval tudjuk kilistáztatni a programmal.

# Build info
Built with 
Microsoft Visual Studio Community 2017 
Version 15.6.4
VisualStudio.15.Release/15.6.4+27428.2015
Microsoft .NET Framework
Version 4.7.03062

# Fordítás Linux rendszeren

A fordításhoz szükséges az ```mcs``` program, amit Debian rendszerben a ```mono-mcs``` csomagban találunk meg. A fordítása a ```make``` parancs kiadásával történik. A kimeneti fájl a Makefile mellé jön létre.

Természetesen a futtatáshoz szükséges a ```mono``` futtatókörnyezet.
