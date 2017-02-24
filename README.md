# List of Sites affected by Cloudflare's #Cloudbleed HTTPS Traffic Leak

This is a (work-in-progress) list of domains affected by the [CloudBleed HTTPS traffic leak](https://blog.cloudflare.com/incident-report-on-memory-leak-caused-by-cloudflare-parser-bug/).  
Original vuln [thread](https://bugs.chromium.org/p/project-zero/issues/detail?id=1139) by Google Project Zero.

Cloudflare has not provided an official list of affected domains, and likely will not due to privacy concerns.  I'm compiling an unofficial list here so you know what passwords to change.

## Impact

Passwords, private messages, API keys, and other sensitive data were leaked by cloudflare to random requesters between these dates: **2016-09-22 - 2017-02-18 **.
Data may be cached by search engines, or collected by random adversaries over the past few months.

 "The greatest period of impact was from February 13 and February 18 with around 1 in every 3,300,000 HTTP requests through Cloudflare potentially resulting in memory leakage (that’s about 0.00003% of requests), potential of 100k-200k paged with private data leaked every day" -- [source](https://news.ycombinator.com/item?id=13719518)

## What should I do?

Check your password managers and **change all your passwords**, especially those on these affected sites.  
Rotate API keys & secrets, and confirm you have 2-FA set up for important accounts.
Theoretically sites not in this list can also be affected (because an affected site could have made an API request to a non-affected one), so to be safe you should probably change all your important passwords.

**Submit PR's to add domains that you know are using cloudflare**

I'm working on running a DNS scraper that will add thousands more domains to this list automatically, so check back periodically for updates as we find more domains.

Some sources:
 - https://stackshare.io/cloudflare
 - https://wappalyzer.com/applications/cloudflare
 - DNS scraper I'm running on Alexa top 10,000 sites (grepping for cloudflare in results)
 - https://www.cloudflare.com/ips/  (going to find sites that resolve to these IPs next)
 - http://www.crimeflare.com/cfs.html (scrape of all cloudflare customers)

==============

- news.ycombinator.com
- coinbase.com
- reddit.com
- 4chan.org
- yelp.com
- okcupid.com
- digitalocean.com
- zendesk.com
- fastmail.com (does not proxy TLS, probably safe from this attack)
- reddit.com
- uber.com
- lyft.com
- upwork.com
- codepen.io
- medium.com
- fiverr.com
- thepiratebay.org
- extratorrent.com
- getbootstrap.com
- jquery.com
- laravel.com
- laracasts.com
- seriouseats.com
- bitdefender.com
- ziprecruiter.com
- glassdoor.com
- pastebin.com
- stackoverflow.com
- fitbit.com
- discord.com
- change.org
- feedly.com
- zoho.com
- patreon.com
- producthunt.com
- bitpay.com
- irccloud.com

------

(sorry theres a lot of porn sites in the full list, I dont have time to filter them out manually)

- adf.ly
- fiverr.com
- blogfa.com
- statcounter.com
- taringa.net
- gamer.com.tw
- avito.ru
- hardsextube.com
- clickbank.com
- linkbucks.com
- putlocker.com
- beeg.com
- odesk.com
- hdfcbank.com
- drudgereport.com
- 4dsply.com
- feedly.com
- blackhatworld.com
- webs.com
- typepad.com
- eyny.com
- ck101.com
- elance.com
- subscene.com
- searchengines.ru
- youm7.com
- shareasale.com
- extratorrent.cc
- 2ch.net
- clixsense.com
- hubpages.com
- free-tv-video-online.me
- jquery.com
- templatemonster.com
- ero-advertising.com
- traidnt.net
- life.com.tw
- mp3skull.com
- tutsplus.com
- spotscenered.info
- porntube.com
- movie4k.to
- likes.com
- glassdoor.com
- 4chan.org
- addmefast.com
- myegy.com
- systweak.com
- brainyquote.com
- r10.net
- dx.com
- jvzoo.com
- hespress.com
- bitshare.com
- fatakat.com
- digitalpoint.com
- bestblackhatforum.com
- 4tube.com
- webhostingtalk.com
- digikala.com
- pornerbros.com
- largeporntube.com
- primewire.ag
- nmisr.com
- youtube-mp3.org
- mangareader.net
- infolinks.com
- slimspots.com
- getbootstrap.com
- pingdom.com
- wmmail.ru
- eztv.it
- prntscr.com
- nairaland.com
- pastebin.com
- forobeta.com
- topix.com
- smallseotools.com
- lapatilla.com
- kinox.to
- livememe.com
- filgoal.com
- zwaar.net
- thedailybeast.com
- plugrush.com
- banglanews24.com
- privatehomeclips.com
- statscrop.com
- fanpop.com
- crunchbase.com
- extratorrent.com
- bab.la
- h2porn.com
- seriesyonkis.com
- bubblews.com
- vodly.to
- atwiki.jp
- stagram.com
- clickbank.net
- freakshare.com
- t411.me
- mangafox.me
- nyaa.se
- opencart.com
- blankrefer.com
- 4pda.ru
- imagetwist.com
- games.la
- watchseries.lt
- sabq.org
- cloudflare.com
- bufferapp.com
- clip.vn
- christian-dogma.com
- internethaber.com
- socialmediatoday.com
- sourtimes.org
- washingtontimes.com
- chomikuj.pl
- warriorplus.com
- dailycaller.com
- elwatannews.com
- megashare.info
- gyazo.com
- resellerclub.com
- yam.com
- index-of-mp3s.com
- viralnova.com
- bitsnoop.com
- fishki.net
- tecmundo.com.br
- androidcentral.com
- skyscrapercity.com
- el-wlid.com
- blekko.com
- elheddaf.com
- etxt.ru
- dizi-mag.com
- ashleyrnadison.com
- zone-telechargement.com
- advfn.com
- infibeam.com
- sheknows.com
- adult-empire.com
- warez-bb.org
- kwejk.pl
- mangahere.com
- haivl.com
- jqueryui.com
- almasryalyoum.com
- proboards.com
- rapgenius.com
- ads-id.com
- hugedomains.com
- vanguardngr.com
- udemy.com
- el-balad.com
- avaaz.org
- creativecommons.org
- uptobox.com
- socialmediaexaminer.com
- xxxbunker.com
- tubeplus.me
- dpstream.net
- gamme.com.tw
- jang.com.pk
- identi.li
- whirlpool.net.au
- 1stwebdesigner.com
- dawanda.com
- elfagr.org
- listcovery.com
- all.biz
- zoominfo.com
- allmyvideos.net
- grindtv.com
- songspk.name
- mediatakeout.com
- celebuzz.com
- cpasbien.me
- 000webhost.com
- khabarfarsi.com
- hotukdeals.com
- index.hr
- kinozal.tv
- sergey-mavrodi.com
- gfy.com
- armorgames.com
- bigrock.in
- popcash.net
- foundationapi.com
- ryushare.com
- n4g.com
- forocoches.com
- bc.vc
- wpengine.com
- iconarchive.com
- the-bux.net
- avazutracking.net
- samanyoluhaber.com
- indowebster.com
- myorderbox.com
- gfxtra.com
- mangapanda.com
- 2ch-c.net
- skladchik.com
- anitube.se
- opensubtitles.org
- mysmartprice.com
- iptorrents.com
- punchng.com
- econsultancy.com
- openclassrooms.com
- mazika2day.com
- webdesignerdepot.com
- theregister.co.uk
- inquirer.net
- tfl.gov.uk
- peliculasyonkis.com
- musavat.com
- fux.com
- ranker.com
- nationalreview.com
- goldenline.pl
- tn.com.ar
- played.to
- gigaom.com
- bezaat.com
- yepi.com
- shorouknews.com
- tineye.com
- justunfollow.com
- wpmu.org
- elkhabar.com
- express.com.pk
- godvine.com
- imgchili.net
- mydealz.de
- zemtv.com
- source-wave.com
- attracta.com
- menshealth.com
- inlinkz.com
- instantcheckmate.com
- almesryoon.com
- light-dark.net
- maultalk.com
- sergeymavrodi.com
- hihi2.com
- fontspace.com
- intercambiosvirtuales.org
- demotywatory.pl
- 1news.az
- rassd.com
- thaqafnafsak.com
- abs-cbnnews.com
- realitatea.net
- argentinawarez.com
- kinogo.net
- ninisite.com
- alwafd.org
- desi-tashan.com
- joomlart.com
- forosdelweb.com
- memecenter.com
- poringa.net
- hamariweb.com
- wattpad.com
- seemorgh.com
- trafficfactory.biz
- template-help.com
- katproxy.com
- moneymakergroup.com
- col3negoriginal.lk
- rawstory.com
- torrentreactor.net
- sedty.com
- 2ip.ru
- pcadvisor.co.uk
- filelist.ro
- qafqazinfo.az
- newgrounds.com
- ashleymadison.com
- blackhatteam.com
- shoutmeloud.com
- elespectador.com
- wiziwig.tv
- extabit.com
- sdpnoticias.com
- dl-protect.com
- dumpert.nl
- add-anime.net
- fansshare.com
- scriptmafia.org
- problogger.net
- torrenthound.com
- mobafire.com
- buzztheme.net
- members.webs.com
- minecraftforum.net
- peerfly.com
- geenstijl.nl
- tinhte.vn
- mafiashare.net
- searchquotes.com
- whatismyip.com
- funnyjunk.com
- runetki.com
- webgains.com
- libertagia.com
- jutarnji.hr
- amarujala.com
- sitetalk.com
- yeslibertin.com
- mixcloud.com
- efukt.com
- game321.com
- freekaamaal.com
- persiantools.com
- ptt.cc
- heavy-r.com
- dawn.com
- yuku.com
- joemonster.org
- india-forums.com
- informationng.com
- alrakoba.net
- codepen.io
- pirateproxy.se
- deadline.com
- iol.co.za
- hackforums.net
- omegle.com
- wplocker.com
- forbes.ru
- cyberpresse.ca
- mysavings.com
- ripoffreport.com
- vid2c.com
- b1.org
- naij.com
- someecards.com
- wikiwiki.jp
- watchcartoononline.com
- gooddrama.net
- gezinti.com
- desirulez.net
- wjunction.com
- tukif.com
- solidtrustpay.com
- discuss.com.hk
- redbubble.com
- zaman.com.tr
- x-art.com
- videarn.com
- pixhost.org
- proceso.com.mx
- billionuploads.com
- listverse.com
- wayn.com
- crunchyroll.com
- edublogs.org
- tradetracker.com
- adfoc.us
- nguoiduatin.vn
- pornbb.org
- drakulastream.eu
- doisongphapluat.com
- desidime.com
- dsdomination.com
- ioffer.com
- filmifullizle.com
- monova.org
- e-monsite.com
- greenwichmeantime.com
- uploadboy.com
- crackberry.com
- torrentfreak.com
- 1sale.com
- shahvani.com
- ilyke.net
- jusbrasil.com.br
- jne.co.id
- sprashivai.ru
- morguefile.com
- androidpolice.com
- malaysiakini.com
- imgserve.net
- ciudad.com.ar
- vetogate.com
- onlinesoccermanager.com
- priyo.com
- tribune.com.pk
- stargazete.com
- thesuperficial.com
- townhall.com
- sia.az
- siliconrus.com
- worthofweb.com
- radiojavan.com
- freepornvs.com
- barstoolsports.com
- trafficbroker.com
- puu.sh
- 24sata.hr
- zurb.com
- scamadviser.com
- geo.tv
- yoo7.com
- watchseries-online.eu
- howtoforge.com
- 800notes.com
- holiday-weather.com
- utrace.de
- series.ly
- standardmedia.co.ke
- ijreview.com
- webdesignledger.com
- explosm.net
- animeflv.net
- addtoany.com
- like4like.org
- almaany.com
- alfavita.gr
- digitalocean.com
- pdfonline.com
- pubdirecte.com
- tv-series.me
- frmtr.com
- dev-point.com
- publika.az
- classifiedads.com
- allanalpass.com
- smartpassiveincome.com
- watchfreemovies.ch
- jotform.com
- humblebundle.com
- petapixel.com
- q.gs
- aristeguinoticias.com
- anime44.com
- shiftdelete.net
- medium.com
- stream-tv.me
- watch32.com
- imore.com
- idlebrain.com
- alltop.com
- wpcentral.com
- colourlovers.com
- webconfs.com
- filenuke.com
- torrentday.com
- twitchy.com
- cancan.ro
- playxn.com
- kanui.com.br
- tunisia-sat.com
- sipse.com
- ikman.lk
- natunbarta.com
- ce4arab.com
- hizliresim.com
- stansberryresearch.com
- dardarkom.com
- anipo.jp
- alternet.org
- blockchain.info
- pccomponentes.com
- uwants.com
- globalewallet.com
- forumactif.com
- mybroadband.co.za
- teespring.com
- novafile.com
- j.gs
- on.cc
- vcommission.com
- mitbbs.com
- fok.nl
- thisav.com
- davidwalsh.name
- uludagsozluk.com
- blogs.com
- nur.kz
- siasat.pk
- orgasmatrix.com
- storenvy.com
- ezilon.com
- hotair.com
- hawamer.com
- erepublik.com
- hir.ma
- bleepingcomputer.com
- authorstream.com
- vecernji.hr
- camplace.com
- funnymama.com
- mmo-champion.com
- fullhdfilmizle.org
- nullrefer.com
- jquerymobile.com
- alwatanvoice.com
- weloveshopping.com
- fuckbooknet.net
- thetoptens.com
- offervault.com
- globovision.com
- premiumwp.com
- share-links.biz
- readms.com
- futhead.com
- elbotola.com
- tamindir.com
- mymodernmet.com
- skidrowgames.net
- dashnet.org
- dnevnik.hr
- micromaxinfo.com
- namepros.com
- mydigitallife.info
- mindmeister.com
- lolinez.com
- lolnexus.com
- fotolog.net
- defencenet.gr
- network-tools.com
- alexaboostup.com
- tuvaro.com
- whoishostingthis.com
- imgtiger.com
- gsmhosting.com
- surveygizmo.com
- serienjunkies.org
- digital-photography-school.com
- vozforums.com
- spi0n.com
- graaam.com
- z6.com
- gofuckbiz.com
- imageporter.com
- tutorialzine.com
- softarchive.net
- 3bmeteo.com
- downloadatoz.com
- fenopy.se
- shoghlanty.com
- super.ae
- tracklab101.com
- twentytwowords.com
- crictime.com
- archive.is
- slate.fr
- share-online.biz
- xxxkinky.com
- gamestorrents.com
- rozee.pk
- yola.com
- whatculture.com
- bronto.com
- optimizepress.com
- xenforo.com
- freeonlinegames.com
- ziprecruiter.com
- residentadvisor.net
- getfireshot.com
- stocktwits.com
- informe21.com
- kure.tv
- bizsugar.com
- ncrypt.in
- streamhunter.eu
- klicktel.de
- qatarliving.com
- sergey-mavrodi-mmm.net
- bikroy.com
- gogoanime.com
- ahlamontada.com
- stuffgate.com
- penny-arcade.com
- bakufu.jp
- torrentcrazy.com
- pirateproxy.net
- korben.info
- picstopin.com
- cleanfiles.net
- dhakatimes24.com
- gigporno.com
- jeanmarcmorandini.com
- torrentleech.org
- appstorm.net
- gtaforums.com
- playvid.com
- forumotion.com
- androidauthority.com
- gun.az
- piratestreaming.tv
- webmastersitesi.com
- italiafilm.tv
- snapwidget.com
- niusnews.com
- hostgator.in
- marathonbet.com
- notebookcheck.net
- fun698.com
- minutebuzz.com
- apne.tv
- expatriates.com
- hvg.hu
- trndsys.co
- naosalvo.com.br
- planetminecraft.com
- nexusmods.com
- 101greatgoals.com
- avito.ma
- pjmedia.com
- karnaval.com
- blinklist.com
- defaultsear.ch
- themelock.com
- penguinvids.com
- diary.ru
- wiziq.com
- xat.com
- tgju.org
- sm3na.com
- binsearch.info
- ixl.com
- ittefaq.com.bd
- torrentdownloads.me
- pagina12.com.ar
- smartprix.com
- hostgator.com.br
- rghost.ru
- divxplanet.com
- imgchili.com
- tipsandtricks-hq.com
- laughingsquid.com
- theme-fusion.com
- m5zn.com
- impiego24.it
- matchesfashion.com
- healthkart.com
- gaaks.com
- simplyrecipes.com
- ojooo.com
- behindwoods.com
- blip.tv
- neswangy.net
- frandroid.com
- smosh.com
- mylikes.com
- seriouseats.com
- filesfetcher.com
- hiphopdx.com
- bdr130.net
- appbrain.com
- rus.ec
- paperblog.com
- bancdebinary.com
- hobbyking.com
- kingworldnews.com
- linkcollider.com
- divxstage.eu
- fabthemes.com
- btc-e.com
- telelistas.net
- gossiplankanews.com
- xbmc.org
- raventools.com
- thefrisky.com
- brooonzyah.net
- klix.ba
- zamalekfans.com
- pimpandhost.com
- elbilad.net
- theme-junkie.com
- patient.co.uk
- pandodaily.com
- ofreegames.com
- pcinpact.com
- prefiles.com
- mygully.com
- premiere.fr
- lik.cl
- dostor.org
- whatsmyserp.com
- 5giay.vn
- teamliquid.net
- hammihan.com
- moodle.org
- serviporno.com
- q-ask.com
- foro20.com
- dreamincode.net
- ethnos.gr
- fsiblog.com
- 123telugu.com
- express.pk
- latribune.fr
- socialtriggers.com
- smartinsights.com
- spankbang.com
- seozenlaunch.com
- womenshealthmag.com
- doityourself.com
- microworkers.com
- e-estekhdam.com
- deutsche-wirtschafts-nachrichten.de
- boards.ie
- wearehairy.com
- limetorrents.com
- mathsisfun.com
- hugefiles.net
- cima4u.com
- fap.to
- zero10.net
- tmart.com
- mobilism.org
- boo-box.com
- rahnama.com
- fakku.net
- sinembargo.mx
- el-ahly.com
- nicozon.net
- kalahari.com
- youtradefx.com
- random.org
- animeid.tv
- egyup.com
- iphoneogram.com
- alternativeto.net
- filmey.com
- daisycon.com
- indianpornvideos.com
- hibapress.com
- techinasia.com
- insight.ly
- gamefront.com
- designboom.com
- nrc.nl
- looti.net
- iphones.ru
- designtaxi.com
- mangastream.com
- cyberchimps.com
- themalaysianinsider.com
- soccersuck.com
- crosswalk.com
- notdoppler.com
- socialadr.com
- liilas.com
- pcgameshardware.de
- adxpansion.com
- socialblade.com
- atlas.sk
- portalnet.cl
- keep2share.cc
- ssense.com
- thenationonlineng.net
- getglue.com
- ffffound.com
- tvrage.com
- allkpop.com
- prevention.com
- th3professional.com
- trojmiasto.pl
- phpbb.com
- noticierodigital.com
- thethao247.vn
- goldporntube.com
- excellentbux.net
- cucirca.eu
- seslisozluk.net
- rubias19.com
- psychcentral.com
- compucalitv.com
- clasicooo.com
- dreamteammoney.com
- layalina.com
- mybb.com
- vivas.fi
- saaid.net
- freepatriot.org
- fakenamegenerator.com
- imagecurl.org
- sankakucomplex.com
- zetaboards.com
- cricfree.tv
- te3p.com
- trafficestimate.com
- hottube.me
- myvidster.com
- videoyoum7.com
- thenews.com.pk
- iitv.info
- soccermanager.com
- trafficg.com
- reduxmediia.com
- gottabemobile.com
- noticiaaldia.com
- web-opinions.com
- emailmeform.com
- slaati.com
- crocko.com
- oodle.com
- kora-online.tv
- cbox.ws
- free-press-release.com
- feedio.net
- foroactivo.com
- gsmspain.com
- cpasbien.com
- addictinginfo.org
- nowgamez.com
- semprot.com
- burnews.com
- elshaab.org
- animenewsnetwork.com
- destructoid.com
- davidicke.com
- gamevicio.com
- tielabs.com
- elephantjournal.com
- ktonanovenkogo.ru
- freewebs.com
- pornper.com
- burbuja.info
- ghost.org
- uppit.com
- top-channel.tv
- jonloomer.com
- lenskart.com
- fresherslive.com
- curse.com
- matthewwoodward.co.uk
- aftabir.com
- mediapart.fr
- sethgodin.typepad.com
- grasscity.com
- thebump.com
- tomshw.it
- johnchow.com
- peb.pl
- elitetorrent.net
- jagobd.com
- forumophilia.com
- fansided.com
- 1jux.net
- postplanner.com
- hkgolden.com
- promiflash.de
- prlog.ru
- torrents.net
- dota2lounge.com
- car.gr
- frombar.com
- hotarabchat.com
- puls24.mk
- abidjan.net
- djmaza.info
- brusheezy.com
- seenive.com
- englishforums.com
- desitorrents.com
- zalukaj.tv
- zakon.kz
- it-ebooks.info
- wphub.com
- egaliteetreconciliation.fr
- gulli.com
- sa.ae
- ilbe.com
- runnersworld.com
- interpals.net
- webresourcesdepot.com
- eldia.com.ar
- getcashforsurveys.com
- torrentbutler.eu
- aksam.com.tr
- paxum.com
- whocallsme.com
- slashfilm.com
- dicelacancion.com
- intereconomia.com
- bitcoincharts.com
- yazete.com
- theelevationgroup.com
- fotka.pl
- porntubevidz.com
- icefilms.info
- ap7am.com
- gametracker.com
- truthaboutabs.com
- chinavasion.com
- tech-wd.com
- trueactivist.com
- subtitulos.es
- azyya.com
- relink.us
- haqqin.az
- gameblog.fr
- dreamamateurs.com
- emoneyspace.com
- smallbiztrends.com
- bbspink.com
- torlock.com
- kaban.tv
- re-direcciona.me
- mp3xd.com
- vecteezy.com
- nulled.cc
- sexytube.me
- brainpickings.org
- questionablecontent.net
- realfarmacy.com
- joomla.fr
- indiafreestuff.in
- utusan.com.my
- cssdeck.com
- freshdesignweb.com
- experts-exchange.com
- designfloat.com
- haivl.tv
- fanswong.com
- voetbalzone.nl
- pik.ba
- antyweb.pl
- amino.dk
- tickld.com
- pornup.me
- kleiderkreisel.de
- serials.ws
- stereogum.com
- lebuteur.com
- indiangilma.com
- fssnet.co.in
- theladbible.com
- hawkhost.com
- arouraios.gr
- gezginler.net
- wehkamp.nl
- ebs.in
- alphacoders.com
- azertag.com
- sitedeals.nl
- linkcrypt.ws
- movieweb.com
- pijamasurf.com
- n4hr.com
- lewrockwell.com
- putlocker.bz
- 1001freefonts.com
- racing-games.com
- saharareporters.com
- addicted2success.com
- yucatan.com.mx
- rosbalt.ru
- zoomit.ir
- video.az
- nuevoloquo.com
- managewp.com
- meme-lol.com
- javascript.ru
- joomshaper.com
- dryicons.com
- aktifhaber.com
- sudaneseonline.com
- thestudentroom.co.uk
- charter97.org
- goldprice.org
- hardwareluxx.de
- mkyong.com
- plus28.com
- weknowmemes.com
- topdocumentaryfilms.com
- imgdino.com
- pcgames.de
- wed168.com.tw
- tnr.com
- ahlynews.com
- businessforhome.org
- appadvice.com
- gmane.org
- binaryoptionsnewbies.com
- ghanaweb.com
- somuch.com
- usingenglish.com
- dlink.com
- whoismind.com
- seneweb.com
- movie-blog.org
- agilebits.com
- inews.gr
- minijuegos.com
- sadistic.pl
- socialmediabar.com
- forexpeacearmy.com
- stadelahly.com
- definebabe.com
- elpais.com.uy
- shortp.com
- apherald.com
- business2blogger.com
- alweeam.com.sa
- mstaml.com
- tw116.com
- catracalivre.com.br
- cyanogenmod.org
- ocioso.com.br
- runetki.tv
- soompi.com
- filecloud.io
- chatrandom.com
- unitezz.com
- todayhumor.co.kr
- statmyweb.com
- talkarcades.com
- cs-cart.com
- hostingflame.org
- belboon.com
- moveon.org
- rockpapershotgun.com
- hitleap.com
- thisoldhouse.com
- brasil247.com
- spin.com
- vr-zone.com
- downloads.nl
- hotfrog.com
- mg.co.za
- yougetsignal.com
- malwaretips.com
- islammemo.cc
- memedad.com
- sayidaty.net
- krucil.net
- gistmania.com
- indiansexstories.net
- comicbookmovie.com
- videopremium.tv
- worldtimebuddy.com
- aleqt.com
- amadershomoybd.com
- netbarg.com
- e-cigarette-forum.com
- robtex.com
- hayah.cc
- game-debate.com
- inbound.org
- annunci69.it
- antena3.ro
- siyahgazete.com
- duedil.com
- sopitas.com
- alnaharegypt.com
- bukkit.org
- webhostbox.net
- marketglory.com
- avn.info.ve
- khmerload.com
- broadwayworld.com
- dreamtemplate.com
- purpleporno.com
- cmse.ru
- inkedmag.com
- ipiccy.com
- korabia.com
- worldtimeserver.com
- aflamneek.com
- forex4you.org
- 10minutemail.com
- promptfile.com
- genteflow.com
- deperu.com
- sportcategory.com
- goodsearch.com
- sportdog.gr
- news.am
- 1hhhh.net
- bicaps.com
- enjoydressup.com
- mindtools.com
- anandabazar.com
- epidemz.net
- babyoye.com
- encuentra24.com
- blogcatalog.com
- angloinfo.com
- thehackernews.com
- vidspot.net
- likesasap.com
- humoron.com
- 2ch.hk
- osdir.com
- onlinekhabar.com
- waveapps.com
- makezine.com
- reactiongifs.com
- songlyrics.com
- thepoke.co.uk
- proprofs.com
- theync.com
- opposingviews.com
- yeppudaa.com
- mynewsdesk.com
- linkconnector.com
- careers360.com
- doostiha.ir
- stadt-bremerhaven.de
- elitepvpers.com
- somethingawful.com
- vavel.com
- putlocker.ws
- manoto1.com
- forgifs.com
- dramasonline.com
- searchere.info
- thejournal.ie
- songspk.cc
- online-stopwatch.com
- alistapart.com
- themobileindian.com
- droid-life.com
- peliculas4.com
- desmotivaciones.es
- adafruit.com
- arioo.com
- yougetpaidfast.com
- cpalead.com
- sunmaker.com
- aporrea.org
- komikid.com
- downloadming.me
- aflam4you.tv
- freelanceswitch.com
- moddb.com
- toprankblog.com
- sooperarticles.com
- opinionlab.com
- diario.mx
- de10.com.mx
- thenewstribe.com
- brandyourself.com
- propakistani.pk
- vladtv.com
- skidrowcrack.com
- forumactif.org
- codeschool.com
- fragrantica.com
- nodejs.org
- coinbase.com
- tureng.com
- alfajertv.com
- aitnews.com
- fantasy8.com
- legiaodosherois.com.br
- copacet.com
- hightrafficacademy.com
- makeameme.org
- backlinks.com
- avaz.ba
- cda.pl
- maxicep.com
- good.is
- q8yat.com
- phimvang.com
- w4.com
- newtvworld.com
- levelup.com
- waseet.net
- qaynar.info
- laravel.com
- mixedmartialarts.com
- dangerousminds.net
- doba.com
- boxden.com
- kn3.net
- w3resource.com
- alison.com
- 96down.com
- swalif.net
- stepashka.com
- starsue.net
- zenhabits.net
- lankacnews.com
- lumfile.com
- thingiverse.com
- onedio.com
- hockeysfuture.com
- pbagora.com.br
- clubedohardware.com.br
- vodonet.net
- enwdgts.com
- roro44.com
- videomega.tv
- antarvasna.com
- forum.hr
- stopforumspam.com
- techdirt.com
- ahnegao.com.br
- say7.info
- billiger.de
- fuskator.com
- rapradar.com
- aljaras.com
- diffen.com
- diariocontraste.com
- zemanta.com
- demandforce.com
- makeupandbeauty.com
- boxingscene.com
- tvboxnow.com
- taxheaven.gr
- optionbit.com
- 24horas.cl
- yourbittorrent.com
- mediatraffic.com
- merca20.com
- briian.com
- linksmanagement.com
- aznews.az
- any.gs
- diariodemorelos.com
- mforos.com
- ann.az
- maplestage.com
- submissionwebdirectory.com
- naijapals.com
- al-akhbar.com
- alhilal.com
- eatlocalgrown.com
- stafaband.info
- marunadanmalayali.com
- goldesel.to
- articlesnatch.com
- arabsh.com
- cheathappens.com
