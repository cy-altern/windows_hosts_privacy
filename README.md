# windows_hosts_privacy
Ajouts au fichier C:\windows\System32\drivers\hosts pour bloquer les pubs skype et l'envoi des données de télémétrie de Windows 10.
Ces ajouts permettent de rediriger les demandes de connexion de Windows10 ou Skype vers la machine locale '127.0.0.1) ce qui les bloque
Référence pour la télémétrie: https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Cyber-Sicherheit/SiSyPHus/Workpackage4_Telemetry.pdf;jsessionid=8A217E440EEAEB820870B899E1FD97C5.1_cid369?__blob=publicationFile&v=4

```
# blocage des publicités skype 
127.0.0.1 ad-emea.doubleclick.net
127.0.0.1 apps.skype.com
127.0.0.1 secure.skypeassets.com
127.0.0.1 rad.live.com
127.0.0.1 rad.msn.com
127.0.0.1 adnxs.com
127.0.0.1 m.adnxs.com
127.0.0.1 tradedoubler.com
127.0.0.1 bs.serving-sys.com
127.0.0.1 s0.2mdn.net
127.0.0.1 astatic.weborama.net
127.0.0.1 m.eulerian.net
127.0.0.1 smartadserver.com

# blocage des serveurs de télémétrie de Microsoft
127.0.0.1 geo.settings-win.data.microsoft.com.akadns.net
127.0.0.1 db5-eap.settings-win.data.microsoft.com.akadns.net
127.0.0.1 settings-win.data.microsoft.com
127.0.0.1 db5.settings-win.data.microsoft.com.akadns.net
127.0.0.1 asimov-win.settings.data.microsoft.com.akadns.net
127.0.0.1 db5.vortex.data.microsoft.com.akadns.net
127.0.0.1 v10-win.vortex.data.microsoft.com.akadns.net
127.0.0.1 geo.vortex.data.microsoft.com.akadns.net
127.0.0.1 v10.vortex-win.data.microsoft.com
127.0.0.1 us.vortex-win.data.microsoft.com
127.0.0.1 eu.vortex-win.data.microsoft.com
127.0.0.1 vortex-win-sandbox.data.microsoft.com
127.0.0.1 alpha.telemetry.microsoft.com
127.0.0.1 oca.telemetry.microsoft.com
```
