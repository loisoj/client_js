# client_js
ClientJS по Русски
официальный репозиторий разработчика: https://github.com/jackspirou/clientjs
***
новый ClientJS ()

ClientJS, который инициирует данные и возвращает объект клиента.

<script> var client = new ClientJS(); // Create A New Client Object </script> 
***
***
getSoftwareVersion

Получите версию программного обеспечения. Верните строку, содержащую этот номер версии программного обеспечения.

<script> var client = new ClientJS(); // Create A New Client Object var softwareVersion = client.getSoftwareVersion(); // Get ClientJS Software Version console.log( softwareVersion ); </script> 
***
***
getFingerprint ()

Получите отпечаток пальца. Верните 32-битное целое число, отображающее отпечаток браузера.

<script> var client = new ClientJS(); // Create A New Client Object var fingerprint = client.getFingerprint(); // Get Client's Fingerprint console.log( fingerprint ); </script> 
***
***
getCustomFingerprint ()

Получите пользовательский отпечаток пальца. Возьмите строку данных и верните 32-битное целое число, отображающее отпечаток браузера.

<script> var client = new ClientJS(); // Create A New Client Object var ua = client.getBrowserData().ua; var canvasPrint = client.getCanvasPrint(); var fingerprint = client.getCustomFingerprint(ua, canvasPrint); console.log( fingerprint ); </script> 
***
Методы UserAgent

Пользовательский агент - это любое программное обеспечение, которое извлекает и представляет веб-контент для конечных пользователей или реализуется с использованием веб-технологий.

getUserAgent ()

Получить агента пользователя. Возвращает строку, содержащую непроверенный пользовательский агент.

<script> var client = new ClientJS(); // Create A New Client Object var userAgent = client.getUserAgent(); // Get User Agent String console.log( userAgent ); </script> 
***
getUserAgentLowerCase ()

Получить нижний регистр агента пользователя. Верните строчную строку, содержащую пользовательский агент.

<script> var client = new ClientJS(); // Create A New Client Object var userAgentLowerCase = client.getUserAgentLowerCase(); // Get User Agent String console.log( userAgentLowerCase ); </script> 
***
Методы браузера

Узнайте имя и версию клиентского браузера.

getBrowser ()

Получить браузер. Верните строку, содержащую имя браузера.

<script> var client = new ClientJS(); // Create A New Client Object var browser = client.getBrowser(); // Get Browser console.log( browser ); </script> 
***
getBrowserVersion ()

Получить версию браузера. Верните строку, содержащую версию браузера.

<script> var client = new ClientJS(); // Create A New Client Object var browserVersion = client.getBrowserVersion(); // Get Browser Version console.log( browserVersion ); </script> 
***
getBrowserMajorVersion ()

Получить основную версию браузера. Верните строку, содержащую основную версию браузера.

<script> var client = new ClientJS(); // Create A New Client Object var browserMajorVersion = client.getBrowserMajorVersion(); // Get Browser's Major Version console.log( browserMajorVersion ); </script> 
***
isIE ()

Это IE. Проверьте, является ли браузер IE.

<script> var client = new ClientJS(); // Create A New Client Object var isIE = client.isIE(); // Check For IE console.log( isIE ); </script> 

True||False
***
isChrome ()

Есть Chrome. Проверьте, включен ли браузер Chrome.

<script> var client = new ClientJS(); // Create A New Client Object var isChrome = client.isChrome(); // Check For Chrome console.log( isChrome ); </script> 
***
isFirefox ()

Это Firefox. Проверьте, является ли браузер Firefox.

<script> var client = new ClientJS(); // Create A New Client Object var isFirefox = client.isFirefox(); // Check For Firefox console.log( isFirefox ); </script> 
***
isSafari ()

Является Сафари. Проверьте, является ли браузер Safari.

<script> var client = new ClientJS(); // Create A New Client Object var isSafari = client.isSafari(); // Check For Safari console.log( isSafari ); </script> 
***
isOpera ()

Это Opera. Проверьте, является ли браузер Opera.

<script> var client = new ClientJS(); // Create A New Client Object var isOpera = client.isOpera(); // Check For Opera console.log( isOpera ); </script> 
***
isMobileSafari ()

Это MobileSafari. Проверьте, является ли браузер Mobile Safari.

<script> var client = new ClientJS(); // Create A New Client Object var isMobileSafari = client.isMobileSafari(); // Check For Mobile Safari console.log( isMobileSafari ); </script> 
***
Методы двигателя

Механизм веб-браузера - это программный компонент, который отображает информацию о содержимом и форматировании и отображает форматированный контент на экране.

getEngine ()

Получить двигатель. Верните строку, содержащую движок браузера.

<script> var client = new ClientJS(); // Create A New Client Object var engine = client.getEngine(); // Get Engine console.log( engine ); </script> 
***
getEngineVersion ()

Получить версию двигателя. Верните строку, содержащую версию браузера.

<script> var client = new ClientJS(); // Create A New Client Object var engineVersion = client.getEngineVersion(); // Get Engine Version console.log( engineVersion ); </script> 
***
Методы ОС

Операционная система (ОС) представляет собой набор программного обеспечения, которое управляет компьютерными компьютерными ресурсами и предоставляет общие службы для компьютерных программ.

getOS ()

Получите ОС. Верните строку, содержащую ОС.

<script> var client = new ClientJS(); // Create A New Client Object var OS = client.getOS(); // Get OS Version console.log( OS ); </script> 
***
getOSVersion ()

Получите версию ОС. Верните строку, содержащую версию ОС.

<script> var client = new ClientJS(); // Create A New Client Object var osVersion = client.getOSVersion(); // Get OS Version console.log( osVersion ); </script> 
***
Проверка на ОС True || False
***
isWindows ()

Это Windows. Проверьте, является ли ОС Windows.

<script> var client = new ClientJS(); // Create A New Client Object var isWindows = client.isWindows(); // Check For Windows console.log( isWindows ); </script> 
***
isMac ()

Есть Mac. Проверьте, является ли ОС Mac.

<script> var client = new ClientJS(); // Create A New Client Object var isMac = client.isMac(); // Check For Mac console.log( isMac ); </script> 
***
isLinux ()

Является ли Linux. Проверьте, является ли ОС Linux.

<script> var client = new ClientJS(); // Create A New Client Object var isLinux = client.isLinux(); // Check For Linux console.log( isLinux ); </script> 
***
isUbuntu ()

Является Ubuntu. Проверьте, является ли ОС Ubuntu.

<script> var client = new ClientJS(); // Create A New Client Object var isUbuntu = client.isUbuntu(); // Check For Ubuntu console.log( isUbuntu ); </script> 
***
isSolaris ()

Является Solaris. Проверьте, является ли ОС Solaris.

<script> var client = new ClientJS(); // Create A New Client Object var isSolaris = client.isSolaris(); // Check For Solaris console.log( isSolaris ); </script>
***
Проверка устройства
***
Методы устройства

Под устройством мы понимаем персональный компьютер пользователя. Персональный компьютер (ПК) - это компьютер общего назначения, размер, возможности которого и оригинальная цена продажи делают его полезным для отдельных лиц, и который может быть настольным, мобильным, планшетам или ноутбуком.

getDevice ()

Получить устройство. Верните строку, содержащую устройство.

<script> var client = new ClientJS(); // Create A New Client Object var device = client.getDevice(); // Get Device console.log( device ); </script> 
***
getDeviceType ()

Получить тип устройства. Верните строку, содержащую тип устройства.

<script> var client = new ClientJS(); // Create A New Client Object var deviceType = client.getDeviceType(); // Get Device Type console.log( deviceType ); </script> 
***
getDeviceVendor ()

Получить поставщика устройств. Верните строку, содержащую поставщика устройства.

<script> var client = new ClientJS(); // Create A New Client Object var deviceVendor = client.getDeviceVendor(); // Get Device Vendor console.log( deviceVendor ); </script> 
***
Проверка процессора
***
Процессоры

Центральным процессором (ЦП), также называемым центральным процессорным блоком, является аппаратное обеспечение компьютера, которое выполняет инструкции компьютерной программы, выполняя основные арифметические, логические и операции ввода / вывода системы.

getCPU ()

Получить CPU. Верните строку, содержащую архитектуру ЦП.

<script> var client = new ClientJS(); // Create A New Client Object var CPU = client.getCPU(); // Get CPU Architecture console.log( CPU ); </script> 
***
Мобильные методы
***
isMobile ()

Мобильный. Проверьте, находится ли браузер на мобильном устройстве.

<script> var client = new ClientJS(); // Create A New Client Object var isMobile = client.isMobile(); // Check For Mobile console.log( isMobile ); </script> 
***
isMobileMajor ()

Мобильный майор. Проверьте, находится ли браузер на основном мобильном устройстве.

<script> var client = new ClientJS(); // Create A New Client Object var isMobileMajor = client.isMobileMajor(); // Check For Mobile Major console.log( isMobileMajor ); </script> 
***
isMobileAndroid ()

Мобильный Android. Проверьте, находится ли браузер на мобильном устройстве Android.

<script> var client = new ClientJS(); // Create A New Client Object var isMobileAndroid = client.isMobileAndroid(); // Check For Mobile Android console.log( isMobileAndroid ); </script> 
***
isMobileOpera ()

Это мобильная опера. Проверьте, находится ли браузер в операционном мобильном устройстве.

<script> var client = new ClientJS(); // Create A New Client Object var isMobileOpera = client.isMobileOpera(); // Check For Mobile Opera console.log( isMobileOpera ); </script> 
***
isMobileWindows ()

Является мобильной Windows. Проверьте, находится ли браузер на мобильном устройстве Windows.

<script> var client = new ClientJS(); // Create A New Client Object var isMobileWindows = client.isMobileWindows(); // Check For Mobile Windows console.log( isMobileWindows ); </script> 
***
isMobileBlackBerry ()

Мобильный BlackBerry. Проверьте, находится ли браузер на мобильном устройстве Blackberry.

<script> var client = new ClientJS(); // Create A New Client Object var isMobileBlackBerry = client.isMobileBlackBerry(); // Check For Mobile Blackberry console.log( isMobileBlackBerry ); </script> 
***
Методы яблока(iOS)
***
Методы iOS

iOS (ранее iPhone OS) - это мобильная операционная система, разработанная и распространяемая Apple Inc.

isMobileIOS ()

Является мобильным iOS. Проверьте, находится ли браузер на устройстве Apple iOS.

<script> var client = new ClientJS(); // Create A New Client Object var isMobileIOS = client.isMobileIOS(); // Check For Mobile iOS console.log( isMobileIOS ); </script> 
***
isIphone ()

Является Iphone. Проверьте, находится ли браузер на Apple iPhone.

<script> var client = new ClientJS(); // Create A New Client Object var isIphone = client.isIphone(); // Check For iPhone console.log( isIphone ); </script> 
***
isIpad ()

Это Ipad. Проверьте, находится ли браузер на iPad Apple.

<script> var client = new ClientJS(); // Create A New Client Object var isIpad = client.isIpad(); // Check For iPad console.log( isIpad ); </script> 
***
isIpod ()

Это Ipod. Проверьте, включен ли браузер на Apple iPod.

<script> var client = new ClientJS(); // Create A New Client Object var isIpod = client.isIpod(); // Check For iPod console.log( isIpod ); </script> 
***
Экранные методы
***
Электронный визуальный дисплей для компьютеров. Экранный монитор содержит устройство отображения, схему и корпус.

getScreenPrint ()

Получите экранную печать. Верните строку, содержащую экранную информацию.

<script> var client = new ClientJS(); // Create A New Client Object var screenPrint = client.getScreenPrint(); // Get Screen Print console.log( screenPrint ); </script> 
***
getColorDepth ()

Получите цветовую глубину. Верните строку, содержащую глубину цвета.

<script> var client = new ClientJS(); // Create A New Client Object var colorDepth = client.getColorDepth(); // Get Color Depth console.log( colorDepth ); </script> 
***
getCurrentResolution ()

Получить текущее разрешение. Верните строку, содержащую текущее разрешение.

<script> var client = new ClientJS(); // Create A New Client Object var currentResolution = client.getCurrentResolution(); // Get Current Resolution console.log( currentResolution ); </script> 
***
getAvailableResolution ()

Получить доступное разрешение. Верните строку, содержащую доступное разрешение.

<script> var client = new ClientJS(); // Create A New Client Object var availableResolution = client.getAvailableResolution(); // Get Available Resolution console.log( availableResolution ); </script> 
***
getDeviceXDPI ()

Получить устройство XPDI. Верните строку, содержащую устройство XPDI.

<script> var client = new ClientJS(); // Create A New Client Object var deviceXDPI = client.getDeviceXDPI(); // Get Device XDPI console.log( deviceXDPI ); </script> 
***
getDeviceYDPI ()

Получить устройство YDPI. Возвращает строку, содержащую устройство YDPI.

<script> var client = new ClientJS(); // Create A New Client Object var deviceYDPI = client.getDeviceYDPI(); // Get Device YDPI console.log( deviceYDPI ); </script> 
***
Проверка способов подключения
***
getPlugins ()

Получите плагины. Верните строку, содержащую список установленных плагинов.

<script> var client = new ClientJS(); // Create A New Client Object var plugins = client.getPlugins(); // Get Plugins console.log( plugins ); </script> 
***
isJava ()

Является Java. Проверьте, установлена ​​ли Java.

<script> var client = new ClientJS(); // Create A New Client Object var isJava = client.isJava(); // Check For Java console.log( isJava ); </script> 
***
getJavaVersion ()

Получить версию Java. Верните строку, содержащую версию Java.

<script> var client = new ClientJS(); // Create A New Client Object var javaVersion = client.getJavaVersion(); // Get Java Version console.log( javaVersion ); </script> 
***
isFlash ()

Является Flash. Проверьте, установлена ​​ли Flash.

<script> var client = new ClientJS(); // Create A New Client Object var isFlash = client.isFlash(); // Check For Flash console.log( isFlash ); </script> 
***
getFlashVersion ()

Получите версию Flash. Верните строку, содержащую версию Flash.

<script> var client = new ClientJS(); // Create A New Client Object var flashVersion = client.getFlashVersion(); // GET Flash Version console.log( flashVersion ); </script> 
***
isSilverlight ()

Является Silverlight. Проверьте, установлен ли Silverlight.

<script> var client = new ClientJS(); // Create A New Client Object var isSilverlight = client.isSilverlight(); // Check For Silverlight console.log( isSilverlight ); </script> 
***
getSilverlightVersion ()

Получите версию Silverlight. Верните строку, содержащую версию Silverlight.

<script> var client = new ClientJS(); // Create A New Client Object var silverlightVersion = client.getSilverlightVersion(); // GET Silverlight Version console.log( silverlightVersion ); </script> 
***
Методы типа Mime
***
Тип интернет-носителя - это стандартный идентификатор, используемый в Интернете для указания типа данных, которые содержит файл. Идентификаторы были первоначально определены в RFC 2046 и назывались типами MIME, потому что они ссылались на части сообщений электронной почты, отличные от ASCII, которые были составлены с использованием спецификации MIME (многоцелевые расширения электронной почты Интернета). Они также иногда называются типами контента.
***
isMimeTypes ()

Является типом Mime. Проверьте, установлены ли типы mime.

<script> var client = new ClientJS(); // Create A New Client Object var isMimeTypes = client.isMimeTypes(); // Check For Mime Types console.log( isMimeTypes ); </script>
***
getMimeTypes ()

Получите типы Mime. Возвращает строку, содержащую список установленных типов mime.

<script> var client = new ClientJS(); // Create A New Client Object var mimeTypes = client.getMimeTypes(); // Get Mime Types console.log( mimeTypes ); </script> 
***
Методы шрифтов
***
Компьютерный шрифт (или шрифт) - это электронный файл данных, содержащий набор символов, символов или символов, таких как dingbats. Хотя термин шрифт сначала относился к набору типов металлического типа в одном стиле и размере, с 1990-х годов он обычно используется для обозначения масштабируемого набора цифровых фигур, которые могут быть напечатаны на разных размерах.
***
isFont (шрифт)

Есть шрифт. Проверьте, установлен ли шрифт.

<script> var client = new ClientJS(); // Create A New Client Object var font = "Times New Roman"; // Set Font String var isFont = client.isFont(font); // Check For A Font console.log( isFont ); </script> 
***
getFonts ()

Получите шрифты. Верните строку, содержащую список установленных шрифтов.

<script> var client = new ClientJS(); // Create A New Client Object var fonts = client.getFonts(); // Get Fonts console.log( fonts ); </script> 
***
Методы хранения
***
Веб-хранилище поддерживает постоянное хранение данных, подобно файлам cookie, но с значительно увеличенной пропускной способностью и отсутствием информации, хранящейся в заголовке запроса HTTP. Существует два основных типа сетевых хранилищ: локальное хранилище и хранилище сеансов, которые ведут себя аналогично постоянным куки-файлам и сеансовым файлам, соответственно.
***
isLocalStorage ()

Является местным хранилищем. Проверьте, доступно ли местное хранилище.

<script> var client = new ClientJS(); // Create A New Client Object var isLocalStorage = client.isLocalStorage(); // Check For Local Storage console.log( isLocalStorage ); </script> 
***
isSessionStorage ()

Является хранилищем сеансов. Проверьте, доступно ли хранилище сеансов.

<script> var client = new ClientJS(); // Create A New Client Object var isSessionStorage = client.isSessionStorage(); // Check For Session Storage console.log( isSessionStorage ); </script> 
***
isCookie ()

Это Печенье. Проверьте, доступны ли файлы cookie.

<script> var client = new ClientJS(); // Create A New Client Object var isCookie = client.isCookie(); // Check For Cookies console.log( isCookie ); </script>

***
Методы времени
***
Время - это измерение, в котором события могут быть упорядочены из прошлого через настоящее в будущее, а также измерение продолжительности событий и интервалов между ними. Часовой пояс - это регион на Земле, который имеет единое стандартное время для юридических, коммерческих и социальных целей.
***
getTimeZone ()

Получить часовой пояс. Верните строчную строку, содержащую часовой пояс.

<script> var client = new ClientJS(); // Create A New Client Object var timeZone = client.getTimeZone(); // Get Time Zone console.log( timeZone ); </script> 
***
Языковые методы
***
Языковые предпочтения клиентских браузеров.

GetLanguage ()

Получить язык. Верните строчную строку, содержащую пользовательский язык.

<script> var client = new ClientJS(); // Create A New Client Object var language = client.getLanguage(); // Get User Language console.log( language ); </script> 
***
getSystemLanguage ()

Получить SystemLanguage. Верните строчную строку, содержащую системный язык.

<script> var client = new ClientJS(); // Create A New Client Object var systemLanguage = client.SystemLanguage(); // Get System Language console.log( systemLanguage ); </script> 
***
Методы холста
***
Элемент HTML5 <canvas> используется для рисования графики «на лету» с помощью сценариев (обычно JavaScript).
  ***
  isCanvas ()

Это холст. Проверьте, доступен ли элемент холста.

<script> var client = new ClientJS(); // Create A New Client Object var isCanvas = client.isCanvas(); // Check For The Canvas Element console.log( isCanvas ); </script> 
***
getCanvasPrint ()

Получите печать холста. Возвращает строку, содержащую информацию об изображении на холсте.

<script> var client = new ClientJS(); // Create A New Client Object var canvasPrint = client.getCanvasPrint(); // Get Canvas Print console.log( canvasPrint ); </script> 
***
