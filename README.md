MultiCraft-JAR Conf
=====
This project has the goal to make some time gains to many of us.     
Quickly find a multicraft configuration in the list of JAR profiles!     

You will find here, panel translations , serveur profiles (Vanilla, Spigot, PaperMC, Custom), script setup helpers, etc

Methods to start :

- [[HOW-TO] Installation Multicraft on Linux](https://www.multicraft.org/site/docs/install#1.1)     
- [[HOW-TO] How To Install Java JDK on Debian 11](https://tecadmin.net/how-to-install-java-on-debian-11/)    
- [[HOW-TO] How to Install and Configure Apache Web Server](https://vitux.com/debian-apache/) 
- [[HOW-TO] How to Configure .jar.conf Files](https://www.multicraft.org/site/docs/conf)  

-----
🗓 Minecraft versions available
-----

| Versions | ✅ Vanilla | ✅ Spigot | 🔨 PaperSpigot | ☕️ Craftbukkit |
| :--------|:----------:|:---------:|:---------------:|:---------------:|
| Edited by : |[Mojang](https://mojang.com)|[Spigot](https://getbukkit.org)|[PaperMC](https://papermc.io)|[BukkitMC](https://getbukkit.org)| 
| `Last`| 1.18.1 | 1.18.1 | 1.18.1 | 1.18.1 |
| `First`| 1.4.7 | 1.4.7 | 1.12.2 | 1.13.2 |

# ChangeLog (All the history [HERE](https://github.com/) )

-----
 MC 1.18 + Java change AGAIN (November-2021 Update)
-----

MC 1.18 > 1.18.1 > 1.18 are now using JAVA 17 (from Zulu since AdoptOpenJDK ceased activity and Adoptium is doing nothing to be user friendly)

[start]
command = "{JAVA}" -Xmx{MAX_MEMORY}M -Xms{START_MEMORY}M -Djline.terminal=jline.UnsupportedTerminal -jar "{JAR}" nogui {PARAMS}

Vanilla 1.18 is now available too.

-----
🆕 New release v0.1-beta-final (End-September 2021)
-----

In order to prepare a new organization, it seemed important to create a milestone of the last 4 years evolutions.
Things will change a lot till the next release.

-----
⚠️ Java change AGAIN (June-2021 Update)
-----

Mojang decided to unilaterally move from JAVA 11 > JAVA 16 (yup a jump of 5 versions and the use of a no LTS, ...).     
Since Vanilla 1.17, there is the need to use a new JVM so for now this repo isn't natively compatible with 1.17 (as the 8th of June).

## NOT READY FOR Vanilla 1.18 " YET " !!!!

Temporary use of a JAVA NO LTS version : "{JAVA}" for the Vanilla 1.18 profile already available.

-----
⚠️⚠️⚠️ You find a bug? Want to contribute?
-----
Don't be afraid to open an issue!    
Or to send a patch proposal :D    

-----
NB : JAR files, links or anything else of the textual content are not mine but property of respective editors.
© 2017 - 2021
