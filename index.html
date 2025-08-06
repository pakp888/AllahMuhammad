<!DOCTYPE html>
<html lang="ur" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>اللہ اور محمد ﷺ کے نام</title>
    <!-- Tailwind CSS for modern styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <!-- Noto Nastaliq Urdu is a great, web-safe font for Nastaliq script -->
    <link href="https://fonts.googleapis.com/css2?family=Noto+Nastaliq+Urdu:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Noto Nastaliq Urdu', serif;
            background: #fdfaf6; /* Light, warm background */
        }
        .bg-islamic {
            background-color: #00695c; /* A deep, spiritual green */
        }
        .text-islamic-gold {
            color: #d4af37; /* A rich gold color */
        }
        .card {
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s, box-shadow 0.2s;
            cursor: pointer;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px rgba(0, 0, 0, 0.2);
        }
        .card:active {
            transform: translateY(0);
        }
        /* Custom scrollbar for a spiritual feel */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #f1f1f1;
        }
        ::-webkit-scrollbar-thumb {
            background: #d4af37;
            border-radius: 4px;
        }

        /* Custom Modal for alerts */
        .modal {
            position: fixed;
            z-index: 1000;
            left: 0;
            top: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0,0,0,0.4);
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .modal-content {
            background-color: #fefefe;
            padding: 20px;
            border-radius: 10px;
            width: 80%;
            max-width: 400px;
            text-align: center;
        }
    </style>
</head>
<body class="min-h-screen flex flex-col items-center p-4">

    <!-- Audio Element to play sounds -->
    <audio id="audioPlayer"></audio>

    <!-- Custom Modal for Alerts -->
    <div id="customModal" class="modal hidden">
      <div class="modal-content">
        <p id="modalMessage" class="text-xl text-gray-700"></p>
        <button id="closeModalBtn" class="mt-4 bg-islamic hover:bg-teal-700 text-white font-bold py-2 px-4 rounded-full">
          ٹھیک ہے
        </button>
      </div>
    </div>

    <!-- Main App Container -->
    <div id="app" class="w-full max-w-4xl text-center">

        <!-- Front Page -->
        <div id="homePage" class="transition-opacity duration-500">
            <header class="mb-10 p-6 bg-islamic rounded-xl shadow-lg">
                <h1 class="text-4xl sm:text-5xl md:text-6xl text-islamic-gold font-bold mb-4">
                    بسم اللہ الرحمن الرحیم
                </h1>
                <h2 class="text-xl sm:text-2xl text-white">
                    اللہ اور محمد ﷺ کے صفاتی نام
                </h2>
            </header>

            <div class="flex flex-col sm:flex-row justify-center space-y-6 sm:space-y-0 sm:space-x-6">
                <button id="allahBtn" class="bg-islamic hover:bg-teal-700 text-islamic-gold font-bold py-4 px-8 rounded-full shadow-lg transition-colors duration-300 transform hover:scale-105">
                    اللہ ﷻ کے 99 نام
                </button>
                <button id="muhammadBtn" class="bg-islamic hover:bg-teal-700 text-islamic-gold font-bold py-4 px-8 rounded-full shadow-lg transition-colors duration-300 transform hover:scale-105">
                    محمد ﷺ کے 99 نام
                </button>
            </div>
        </div>

        <!-- Names Page -->
        <div id="namesPage" class="hidden transition-opacity duration-500 mt-10">
            <header class="mb-8 p-4 bg-islamic rounded-xl shadow-lg flex justify-between items-center">
                <h2 id="pageTitle" class="flex-grow text-2xl sm:text-3xl text-islamic-gold font-bold text-center"></h2>
                <button id="backBtn" class="bg-islamic-gold text-white font-bold py-2 px-4 rounded-full hover:bg-yellow-600 transition-colors duration-300">
                    واپس
                </button>
            </header>
            <div id="namesGrid" class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 gap-6 p-4">
                <!-- Names will be dynamically inserted here -->
            </div>
        </div>

    </div>

    <script>
        // Use a single custom alert function instead of the built-in alert()
        const showAlert = (message) => {
          const modal = document.getElementById('customModal');
          const modalMessage = document.getElementById('modalMessage');
          modalMessage.textContent = message;
          modal.classList.remove('hidden');
        };

        document.getElementById('closeModalBtn').addEventListener('click', () => {
          document.getElementById('customModal').classList.add('hidden');
        });

        // Data for the 99 names of Allah and Muhammad (ﷺ).
        // IMPORTANT: Replace the empty string " " with a direct link to an MP3 or WAV audio file for each name.
        // A YouTube video URL will NOT work here.
        const allahNames = [
            { name: "اللہ", translation: "وہ ذات جس کے سوا کوئی عبادت کے لائق نہیں", audio: "" },
            { name: "الرحمن", translation: "نہایت مہربان", audio: "" },
            { name: "الرحیم", translation: "رحم کرنے والا", audio: "" },
            { name: "الملک", translation: "بادشاہ", audio: "" },
            { name: "القدوس", translation: "پاک", audio: "" },
            { name: "السلام", translation: "سلامتی والا", audio: "" },
            { name: "المؤمن", translation: "امن دینے والا", audio: "" },
            { name: "المهيمن", translation: "نگہبان", audio: "" },
            { name: "العزيز", translation: "غالب", audio: "" },
            { name: "الجبار", translation: "زبردست", audio: "" },
            { name: "المتكبر", translation: "بڑائی والا", audio: "" },
            { name: "الخالق", translation: "پیدا کرنے والا", audio: "" },
            { name: "البارئ", translation: "وجود بخشنے والا", audio: "" },
            { name: "المصور", translation: "صورتیں بنانے والا", audio: "" },
            { name: "الغفار", translation: "بہت بخشنے والا", audio: "" },
            { name: "القهار", translation: "زبردست", audio: "" },
            { name: "الوهاب", translation: "بغیر عوض کے دینے والا", audio: "" },
            { name: "الرزاق", translation: "روزی دینے والا", audio: "" },
            { name: "الفتاح", translation: "کھولنے والا", audio: "" },
            { name: "العليم", translation: "جاننے والا", audio: "" },
            { name: "القابض", translation: "روکنے والا", audio: "" },
            { name: "الباسط", translation: "پھیلانے والا", audio: "" },
            { name: "الخافض", translation: "پست کرنے والا", audio: "" },
            { name: "الرافع", translation: "بلند کرنے والا", audio: "" },
            { name: "المعز", translation: "عزت دینے والا", audio: "" },
            { name: "المذل", translation: "ذلت دینے والا", audio: "" },
            { name: "السميع", translation: "سننے والا", audio: "" },
            { name: "البصير", translation: "دیکھنے والا", audio: "" },
            { name: "الحكم", translation: "فیصلہ کرنے والا", audio: "" },
            { name: "العدل", translation: "انصاف کرنے والا", audio: "" },
            { name: "اللطيف", translation: "لطف کرنے والا", audio: "" },
            { name: "الخبير", translation: "خبر رکھنے والا", audio: "" },
            { name: "الحليم", translation: "بردبار", audio: "" },
            { name: "العظيم", translation: "بزرگی والا", audio: "" },
            { name: "الغفور", translation: "بخشنے والا", audio: "" },
            { name: "الشكور", translation: "قدردان", audio: "" },
            { name: "العلي", translation: "بلند مرتبہ", audio: "" },
            { name: "الكبير", translation: "بڑا", audio: "" },
            { name: "الحفيظ", translation: "حفاظت کرنے والا", audio: "" },
            { name: "المقيت", translation: "روزی دینے والا", audio: "" },
            { name: "الحسيب", translation: "حساب لینے والا", audio: "" },
            { name: "الجليل", translation: "جلیل القدر", audio: "" },
            { name: "الكريم", translation: "سخی", audio: "" },
            { name: "الرقيب", translation: "نگران", audio: "" },
            { name: "المجيب", translation: "قبول کرنے والا", audio: "" },
            { name: "الواسع", translation: "وسعت والا", audio: "" },
            { name: "الحكيم", translation: "حکمت والا", audio: "" },
            { name: "الودود", translation: "محبت کرنے والا", audio: "" },
            { name: "المجيد", translation: "بزرگی والا", audio: "" },
            { name: "الباعث", translation: "اٹھانے والا", audio: "" },
            { name: "الشهيد", translation: "گواہ", audio: "" },
            { name: "الحق", translation: "حق", audio: "" },
            { name: "الوكيل", translation: "وکیل", audio: "" },
            { name: "القوي", translation: "قوت والا", audio: "" },
            { name: "المتين", translation: "مضبوط", audio: "" },
            { name: "الولي", translation: "مددگار", audio: "" },
            { name: "الحميد", translation: "قابل تعریف", audio: "" },
            { name: "المحصي", translation: "شمار کرنے والا", audio: "" },
            { name: "المبدئ", translation: "ابتداء کرنے والا", audio: "" },
            { name: "المعيد", translation: "دوبارہ پیدا کرنے والا", audio: "" },
            { name: "المحيي", translation: "زندہ کرنے والا", audio: "" },
            { name: "المميت", translation: "موت دینے والا", audio: "" },
            { name: "الحي", translation: "زندہ", audio: "" },
            { name: "القيوم", translation: "قائم رکھنے والا", audio: "" },
            { name: "الواجد", translation: "پانے والا", audio: "" },
            { name: "الماجد", translation: "بزرگی والا", audio: "" },
            { name: "الواحد", translation: "ایک", audio: "" },
            { name: "الصمد", translation: "بے نیاز", audio: "" },
            { name: "القادر", translation: "قدرت والا", audio: "" },
            { name: "المقتدر", translation: "سب پر قدرت والا", audio: "" },
            { name: "المقدم", translation: "آگے بڑھانے والا", audio: "" },
            { name: "المؤخر", translation: "پیچھے کرنے والا", audio: "" },
            { name: "الأول", translation: "پہلا", audio: "" },
            { name: "الآخر", translation: "آخری", audio: "" },
            { name: "الظاهر", translation: "ظاہر", audio: "" },
            { name: "الباطن", translation: "پوشیدہ", audio: "" },
            { name: "الوالي", translation: "مالک", audio: "" },
            { name: "المتعالي", translation: "بلند و بالا", audio: "" },
            { name: "البر", translation: "نیکی کرنے والا", audio: "" },
            { name: "التواب", translation: "توبہ قبول کرنے والا", audio: "" },
            { name: "المنتقم", translation: "انتقام لینے والا", audio: "" },
            { name: "العفو", translation: "معاف کرنے والا", audio: "" },
            { name: "الرءوف", translation: "شفقت کرنے والا", audio: "" },
            { name: "مالك الملك", translation: "بادشاہی کا مالک", audio: "" },
            { name: "ذوالجلال والإكرام", translation: "عظمت اور بزرگی والا", audio: "" },
            { name: "المقسط", translation: "انصاف کرنے والا", audio: "" },
            { name: "الجامع", translation: "جمع کرنے والا", audio: "" },
            { name: "الغني", translation: "بے نیاز", audio: "" },
            { name: "المغني", translation: "غنی کرنے والا", audio: "" },
            { name: "المانع", translation: "روکنے والا", audio: "" },
            { name: "الضار", translation: "نقصان پہنچانے والا", audio: "" },
            { name: "النافع", translation: "نفع دینے والا", audio: "" },
            { name: "النور", translation: "نور", audio: "" },
            { name: "الهادي", translation: "ہدایت دینے والا", audio: "" },
            { name: "البديع", translation: "انوکھا", audio: "" },
            { name: "الباقي", translation: "باقی رہنے والا", audio: "" },
            { name: "الوارث", translation: "وارث", audio: "" },
            { name: "الرشيد", translation: "راہ راست دکھانے والا", audio: "" },
            { name: "الصبور", translation: "صبر کرنے والا", audio: "" },
        ];

        const muhammadNames = [
            { name: "محمد", translation: "بہت تعریف کیا گیا", audio: "" },
            { name: "احمد", translation: "بہت تعریف کرنے والا", audio: "" },
            { name: "حامد", translation: "حمد کرنے والا", audio: "" },
            { name: "ماحی", translation: "مٹانے والا", audio: "" },
            { name: "عاقب", translation: "بعد میں آنے والا", audio: "" },
            { name: "فاتح", translation: "فتح کرنے والا", audio: "" },
            { name: "قاسم", translation: "تقسیم کرنے والا", audio: "" },
            { name: "صادق", translation: "سچا", audio: "" },
            { name: "امین", translation: "امانت دار", audio: "" },
            { name: "نور", translation: "روشنی", audio: "" },
            { name: "سراج", translation: "چراغ", audio: "" },
            { name: "نذیر", translation: "ڈرانے والا", audio: "" },
            { name: "منیر", translation: "روشن کرنے والا", audio: "" },
            { name: "ہادی", translation: "ہدایت دینے والا", audio: "" },
            { name: "فتاح", translation: "کھولنے والا", audio: "" },
            { name: "متوکل", translation: "اللہ پر بھروسہ کرنے والا", audio: "" },
            { name: "مصطفیٰ", translation: "چنا ہوا", audio: "" },
            { name: "مرتضیٰ", translation: "پسندیدہ", audio: "" },
            { name: "مجتبیٰ", translation: "چنا ہوا", audio: "" },
            { name: "مختار", translation: "اختیار والا", audio: "" },
            { name: "طاہر", translation: "پاک", audio: "" },
            { name: "مطہر", translation: "پاک کرنے والا", audio: "" },
            { name: "طیب", translation: "پاکیزہ", audio: "" },
            { name: "طٰہٰ", translation: "قرآن میں ایک نام", audio: "" },
            { name: "یس", translation: "قرآن میں ایک نام", audio: "" },
            { name: "رسول", translation: "پیغام پہنچانے والا", audio: "" },
            { name: "نبی", translation: "خبر دینے والا", audio: "" },
            { name: "اُمّی", translation: "ان پڑھ", audio: "" },
            { name: "مدنی", translation: "مدینہ سے تعلق رکھنے والا", audio: "" },
            { name: "مکی", translation: "مکہ سے تعلق رکھنے والا", audio: "" },
            { name: "عربی", translation: "عرب کا رہنے والا", audio: "" },
            { name: "قریشی", translation: "قریش قبیلے سے تعلق رکھنے والا", audio: "" },
            { name: "سید", translation: "سردار", audio: "" },
            { name: "امام", translation: "پیشوا", audio: "" },
            { name: "خطیب", translation: "خطبہ دینے والا", audio: "" },
            { name: "مجاہد", translation: "جہاد کرنے والا", audio: "" },
            { name: "غازی", translation: "فتح مند", audio: "" },
            { name: "صابر", translation: "صبر کرنے والا", audio: "" },
            { name: "شاکر", translation: "شکر کرنے والا", audio: "" },
            { name: "قانت", translation: "اطاعت گزار", audio: "" },
            { name: "طٰہٰ", translation: "طہ", audio: "" },
            { name: "یس", translation: "یاسین", audio: "" },
            { name: "نجم", translation: "ستارہ", audio: "" },
            { name: "جمال", translation: "خوبصورتی", audio: "" },
            { name: "كمال", translation: "کمال", audio: "" },
            { name: "حبیب", translation: "محبوب", audio: "" },
            { name: "عزیز", translation: "عزت والا", audio: "" },
            { name: "شفیق", translation: "شفقت کرنے والا", audio: "" },
            { name: "جمیل", translation: "خوبصورت", audio: "" },
            { name: "سلیم", translation: "سلامتی والا", audio: "" },
            { name: "کریم", translation: "سخی", audio: "" },
            { name: "شاہد", translation: "گواہ", audio: "" },
            { name: "مبشر", translation: "خوشخبری سنانے والا", audio: "" },
            { name: "منذر", translation: "ڈرانے والا", audio: "" },
            { name: "حسیب", translation: "حساب لینے والا", audio: "" },
            { name: "بشیر", translation: "خوشخبری دینے والا", audio: "" },
            { name: "سراج", translation: "چراغ", audio: "" },
            { name: "نذیر", translation: "ڈرانے والا", audio: "" },
            { name: "مذکر", translation: "یاد دلانے والا", audio: "" },
            { name: "شفیع", translation: "شفاعت کرنے والا", audio: "" },
            { name: "مشفع", translation: "جس کی شفاعت قبول کی جائے", audio: "" },
            { name: "قدوہ", translation: "نمونہ", audio: "" },
            { name: "رحیم", translation: "رحم کرنے والا", audio: "" },
            { name: "رحمان", translation: "نہایت مہربان", audio: "" },
            { name: "غوث", translation: "فریاد سننے والا", audio: "" },
            { name: "مستغیث", translation: "جس سے فریاد کی جائے", audio: "" },
            { name: "ولی", translation: "دوست", audio: "" },
            { name: "نصیر", translation: "مددگار", audio: "" },
            { name: "حفیظ", translation: "حفاظت کرنے والا", audio: "" },
            { name: "نبی التوبہ", translation: "توبہ کا نبی", audio: "" },
            { name: "نبی الرحمة", translation: "رحمت کا نبی", audio: "" },
            { name: "صاحب", translation: "دوست", audio: "" },
            { name: "طیب", translation: "پاکیزہ", audio: "" },
            { name: "طه", translation: "طہ", audio: "" },
            { name: "یس", translation: "یاسین", audio: "" },
            { name: "حسین", translation: "خوبصورت", audio: "" },
            { name: "حسن", translation: "خوبصورت", audio: "" },
            { name: "کامل", translation: "مکمل", audio: "" },
            { name: "حسیب", translation: "حساب لینے والا", audio: "" },
            { name: "مقدم", translation: "آگے بڑھنے والا", audio: "" },
            { name: "مکرّم", translation: "عزت والا", audio: "" },
            { name: "مبشر", translation: "خوشخبری دینے والا", audio: "" },
            { name: "نور", translation: "روشنی", audio: "" },
            { name: "منیر", translation: "روشن کرنے والا", audio: "" },
            { name: "سراج", translation: "چراغ", audio: "" },
            { name: "حکم", translation: "فیصلہ کرنے والا", audio: "" },
            { name: "امین", translation: "امانت دار", audio: "" },
            { name: "مومن", translation: "ایمان والا", audio: "" },
            { name: "مہيمن", translation: "نگران", audio: "" },
            { name: "قوي", translation: "طاقتور", audio: "" },
            { name: "فائق", translation: "فائق", audio: "" },
            { name: "مُختار", translation: "منتخب", audio: "" },
            { name: "ہادی", translation: "ہدایت دینے والا", audio: "" },
            { name: "ذکر", translation: "ذکر", audio: "" },
            { name: "حق", translation: "حق", audio: "" },
            { name: "حکیم", translation: "حکمت والا", audio: "" },
            { name: "مقیم", translation: "مقیم", audio: "" },
            { name: "مستقيم", translation: "سیدھی راہ پر", audio: "" },
            { name: "محمود", translation: "حمد والا", audio: "" },
            { name: "عارف", translation: "عارف", audio: "" },
            { name: "عاقل", translation: "عقلمند", audio: "" },
            { name: "شاکر", translation: "شکر کرنے والا", audio: "" },
            { name: "صالح", translation: "نیک", audio: "" },
            { name: "طٰہٰ", translation: "طہ", audio: "" },
            { name: "یس", translation: "یاسین", audio: "" },
        ];
        
        // Get the main elements
        const homePage = document.getElementById('homePage');
        const namesPage = document.getElementById('namesPage');
        const allahBtn = document.getElementById('allahBtn');
        const muhammadBtn = document.getElementById('muhammadBtn');
        const backBtn = document.getElementById('backBtn');
        const namesGrid = document.getElementById('namesGrid');
        const pageTitle = document.getElementById('pageTitle');
        const audioPlayer = document.getElementById('audioPlayer');

        // Function to play audio
        const playAudio = (audioUrl) => {
            if (audioUrl && audioUrl.trim() !== '') {
                audioPlayer.src = audioUrl;
                audioPlayer.play();
            } else {
                showAlert("اس نام کے لیے کوئی آڈیو فائل منسلک نہیں ہے۔ براہ کرم آڈیو URL شامل کریں۔");
            }
        };

        // Function to render names on the grid
        const renderNames = (namesArray, title) => {
            pageTitle.textContent = title;
            namesGrid.innerHTML = ''; // Clear previous names
            namesArray.forEach(nameData => {
                const card = document.createElement('div');
                card.classList.add('card', 'bg-white', 'p-4', 'rounded-lg', 'text-center');
                
                const nameHeading = document.createElement('h3');
                nameHeading.classList.add('text-3xl', 'sm:text-4xl', 'font-bold', 'text-islamic');
                nameHeading.textContent = nameData.name;
                
                const translationPara = document.createElement('p');
                translationPara.classList.add('text-lg', 'text-gray-600', 'mt-2');
                translationPara.textContent = nameData.translation;
                
                const playBtn = document.createElement('button');
                playBtn.classList.add('mt-4', 'bg-islamic-gold', 'text-white', 'py-2', 'px-4', 'rounded-full', 'hover:bg-yellow-600', 'transition-colors', 'duration-300');
                playBtn.textContent = 'آڈیو چلائیں';
                
                playBtn.addEventListener('click', () => {
                    playAudio(nameData.audio);
                });
                
                card.appendChild(nameHeading);
                card.appendChild(translationPara);
                card.appendChild(playBtn);
                
                namesGrid.appendChild(card);
            });
            
            // Show the names page
            homePage.classList.add('hidden');
            namesPage.classList.remove('hidden');
        };

        // Event listeners for the main buttons
        allahBtn.addEventListener('click', () => {
            renderNames(allahNames, 'اللہ ﷻ کے 99 نام');
        });
        
        muhammadBtn.addEventListener('click', () => {
            renderNames(muhammadNames, 'محمد ﷺ کے صفاتی نام');
        });
        
        // Event listener for the back button
        backBtn.addEventListener('click', () => {
            namesPage.classList.add('hidden');
            homePage.classList.remove('hidden');
        });

    </script>
</body>
</html>
