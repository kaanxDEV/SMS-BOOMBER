

--------------------
	TR
--------------------


**GÜVENLİK VE YASAL UYARI**

Bu araç, yalnızca eğitim amaçlı ve yetkili sızma testleri için tasarlanmıştır. Bu yazılımın herhangi bir kişi veya sisteme karşı, ilgili tarafın açık rızası olmaksızın kullanılması kesinlikle yasaktır.

Sorumluluk: Bu aracı kullanarak oluşabilecek her türlü hukuki ve etik sorumluluk tamamen kullanıcıya aittir. Yazılımcı (kaannx00), aracın kötüye kullanımından veya neden olabileceği zararlardan hiçbir şekilde sorumlu tutulamaz.

Etik Kullanım: Araç yalnızca kendi sistemlerinizde veya izin aldığınız ortamlarda test amaçlı kullanılmalıdır.

Token Güvenliği: Discord Selfbot kullanımında paylaştığınız Token, hesabınızın tamamen ele geçirilmesine neden olabilir. Token'ınızı kimseyle paylaşmayınız ve güvenilir olmayan ortamlarda çalıştırmayınız.


<h2>Kurulum</h2>

```console
cd kaannx00-sms-boomber
pip3 install -r requirements.txt
python3 kaan.py
```


<h2>Discord</h2>

Bot'un çalışabilmesi için 'Privileged Gateway Intents' seçeneklerinin hepsinin aktif olması gerekmektedir.

<h2>Discord Selfbot</h2>

**Token bulma:**

1- Tarayıcıdan bot olarak kullanacağınız Discord hesabına giriniz.<br>
2- Tarayıcı konsolunu açınız.<br>
3- Ağ trafiği izleme bölümüne geliniz.<br>
4- Konsolu kapatmadan, Discord'da bu oturum boyunca tıklamadığınız bir sohbete tıklayınız.<br>
5- Sonu *messages?limit=50* ile biten isteğe tıklayınız.<br>
6- İsteğin *Header* kısmındaki *Authorization* değeri sizin token'ınızdır.<br>
7- Bu token'ı *discord-selfbot-kaan.py*'de *token* kısmına yazınız. (str olarak)<br>

**Chat Id Bulma:**

1- Bot hesabı ile mesajlaşacağınız kendi orijinal hesabınızdan bot'a bir tane mesaj atınız.<br>
2- Tarayıcıda Discord'u açın ve bot hesabına giriş yapınız, ardından gerçek hesabınızın üzerine tıklayın.<br>
3- Url'deki *@me*'den sonraki sayı sizin sohbet id'nizdir.<br>
4- Bu id'yi *discord-selfbot-kaan.py*'de *chat_id* kısmına yazınız. (int olarak)<br><br>
**Not:** Eğer bot'u Discord sunucusunda kullanacaksanız, *channels*'dan sonra gelen, taksim ile ayrılmış iki sayıdan ikincisi sohbet id'nizdir.
<br><br>

**CREDİT**
Kodlar tingirifistik adlı kullanıcının daha fazla güncelleme yapmayacağını ve sms-boomber'ın bu şekilde kalacağını söylemesinden dolayı bir kısmı ondan alınıp düzenlenmiştir
kendisinin github adresini bıraktığım linkten bulabilirsiniz. 

https://github.com/tingirifistik



--------------------
	EN
--------------------


**SECURITY AND LEGAL DISCLAIMER**

This tool is intended strictly for educational purposes and authorized penetration testing only. Using this software against any person or system without the explicit consent of the involved party is strictly prohibited.

Liability: All legal and ethical responsibility arising from the use of this tool lies entirely with the user. The developer (kaannx00) cannot be held responsible for any misuse of this tool or any damages it may cause.

Ethical Use: This tool must be used only in your own systems or environments where you have received explicit authorization for testing.

Token Security: When using a Discord Selfbot, the Token you provide can lead to your account being completely compromised. Do not share your token with anyone and do not run it in untrusted environments.

<h2> Installation </h2>
```Shell
cd kaannx00-sms-boomber
pip3 install -r requirements.txt
python3 kaan.py```

<h2>Discord</h2>

For the bot to function correctly, all 'Privileged Gateway Intents' options must be enabled in the Discord Developer Portal.

<h2>Discord Selfbot</h2>

**Finding your Token:**

1- Log in to the Discord account you will use as the bot in your browser.

2- Open the browser console (F12).

3- Go to the Network tab.

4- Without closing the console, click on a chat in Discord that you have not interacted with during this session.

5- Click on the request ending in messages?limit=50.

6- The Authorization value in the request Header section is your token.

7- Paste this token into the token field in discord-selfbot-enough.py (as a string).


**Finding your Chat ID:**

1- Send a message to your bot account from your original personal account.

2- Open Discord in your browser, log in to the bot account, and click on your personal account.

3- The number appearing after @me in the URL is your chat ID.

4- Paste this ID into the chat_id field in discord-selfbot-enough.py (as an integer).


Note: If you are using the bot in a Discord server, the chat ID is the second number following channels, separated by a slash.

CREDIT
Part of the code has been adapted and refactored from the user "tingirifistik," as they stated they would no longer provide updates and the SMS-bomber would remain in its current state.
You can find their GitHub profile via the link below:

https://github.com/tingirifistik
