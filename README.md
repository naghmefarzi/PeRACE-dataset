# PeRACE-dataset
Persian automatic translation of RACE dataset (multiple-choice machine reading comprehension dataset) using GNMT


PeRACE is an automatic Persian translation of the RACE dataset, which consists of RACE-M and RACE-H, using Google Neural Machine Translation. According to the errors of machine translation, we consider PeRACE as the noisy data. PeRACE consists of PeRACE-M and PeRACE-H, respectively; the statistics are listed below.



|     Dataset   | |PeRACE-M |  |   |PeRACE-H |   |
| ------------- | :---:|:---:|:---: | :---:|:---:|:---: |
|   |  train|   dev  | test   |   train  | dev | test  |
| #questions    | 25,421 | 1,436  | 1,436  |  62,445 | 3,451 | 3,498  |

PeRACE.zip file contains PeRACE-H and PeRACE-M, including train, dev, and test files. The data.csv files in each of them contain seven columns of information, including text, options [from 0 to 3], queries, and answers [A, B, C, or D]. Below is a sample from PeRACE-H/dev.


|     text   | option 0| option1| option2 |  option3    |query |  ans |
| ------------- | :---:|:---:|:---: | :---:|:---:|:---: |
|'من یک روانشناس هستم. من اولین بار با تیموتی، پسر یازده ساله ساکت و چاق، وقتی مادرش او را نزد من آورد تا در مورد نمرات کاهش یافته اش صحبت کنم. چند دقیقه با تیموتی کافی بود تا تأیید کنیم که عزت نفس و شادی عمومی او نیز همراه با _ . درباره روزهای معمولی تیموتی پرسیدم. او هر روز صبح ساعت شش و نیم از خواب بیدار می شد تا بتواند ساعت هشت به مدرسه خود برسد و هر روز حدود ساعت چهار و نیم بعد از ظهر به خانه می رسید. او سپس یک میان وعده سریع میل کرد و به دنبال آن یک درس پیانو یا یک درس با معلم ریاضی خود داشت. ساعت 7 بعد از ظهر شام را تمام کرد و بعد دو تا سه ساعت به انجام تکالیف نشست. با انجام محاسبات در ذهنم، متوجه شدم که تیموتی به طور متوسط سیزده ساعت در روز را پشت میز تحریر می گذراند. چه می شد اگر تیموتی سیزده ساعت در روز را به جای میز پشت چرخ خیاطی صرف می کرد؟ ما بلافاصله شوکه می شویم، زیرا به این میگویند با کودکان بدرفتاری وحشتناکی می شود. تیموتی به دور از بدرفتاری بود، اما انبوهی از تکالیف که روزانه با او مواجه می شد نتیجه ای مشابه داشت - دوران کودکی اش را ربودند. در واقع، تیموتی زمانی برای انجام هر کاری که واقعاً از آن لذت می برد، نداشت، مانند بازی های ویدیویی، تماشای فیلم، یا بازی های رومیزی با دوستانش. با این حال، بازی بخش مهمی از رشد سالم کودک است. بر خلاقیت کودکان، مهارت های اجتماعی و حتی رشد مغز آنها تأثیر می گذارد. فقدان بازی، ورزش بدنی و عاری از تعامل اجتماعی آسیب جدی به بسیاری از کودکان وارد می کند. همچنین می تواند باعث مشکلات سلامتی قابل توجهی مانند چاقی دوران کودکی، مشکلات خواب و افسردگی شود. کارشناسان در این زمینه توصیه می کنند دقایقی که کودکان برای انجام تکالیف خود صرف می کنند نباید بیش از ده برابر سطح کلاس آنها باشد. به عنوان یک دانش آموز کلاس پنجمی، تیموتی نباید بیش از پنجاه دقیقه در روز تکالیف داشته باشد (به جای سه برابر این مقدار). داشتن دو ساعت بیشتر در شب برای بازی، استراحت، یا دیدن یک دوست، به خوبی برای کیفیت زندگی هر کودکی مفید است.'|تیموتی بسیار سخت کوش بود.|با تیموتی بدرفتاری می شد.|تیموتی بار سنگینی داشت.|تیموتی از کودکی خود لذت می برد.|'نویسنده پس از اطلاع از روزهای معمول تیموتا، درباره او چه فکری کرد؟'|C|
