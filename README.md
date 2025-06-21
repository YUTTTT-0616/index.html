<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SAOまとめサイト - Sword Art Online Fan Summary</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts - Inter for clean typography -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f0f2f5; /* Light gray background */
            color: #333; /* Dark text color */
        }
        .container {
            max-width: 1200px;
        }
        /* Custom scrollbar for better aesthetics */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #e0e0e0;
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb {
            background: #888;
            border-radius: 10px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #555;
        }
    </style>
</head>
<body class="antialiased">
    <!-- ヘッダーセクション -->
    <header class="bg-gradient-to-r from-blue-700 to-purple-600 text-white shadow-lg py-6">
        <div class="container mx-auto px-4 flex flex-col md:flex-row justify-between items-center">
            <h1 class="text-4xl font-bold mb-2 md:mb-0">
                <span class="block">SAO</span>
                <span class="block text-xl">ソードアート・オンライン まとめサイト</span>
            </h1>
            <nav class="mt-4 md:mt-0">
                <ul class="flex space-x-6">
                    <li><a href="#overview" class="hover:text-blue-200 transition duration-300 font-semibold">概要</a></li>
                    <li><a href="#characters" class="hover:text-blue-200 transition duration-300 font-semibold">主要キャラクター</a></li>
                    <li><a href="#arcs" class="hover:text-blue-200 transition duration-300 font-semibold">アーク</a></li>
                    <li><a href="#gallery" class="hover:text-blue-200 transition duration-300 font-semibold">ギャラリー</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- メインコンテンツセクション -->
    <main class="container mx-auto px-4 py-8 md:py-12">
        <!-- 概要セクション -->
        <section id="overview" class="bg-white rounded-xl shadow-lg p-6 md:p-8 mb-12">
            <h2 class="text-3xl font-bold text-gray-800 mb-6 border-b-2 border-blue-500 pb-2">SAOとは？</h2>
            <div class="flex flex-col md:flex-row items-center md:space-x-8">
                <div class="md:w-1/2 mb-6 md:mb-0">
                    <img src="https://placehold.co/600x400/3182CE/FFFFFF?text=SAO+Login+Screen" alt="SAO Login Screen" class="rounded-lg shadow-md w-full">
                </div>
                <div class="md:w-1/2 text-lg leading-relaxed text-gray-700">
                    <p class="mb-4">
                        『ソードアート・オンライン』（SAO）は、川原礫による日本のライトノベルを原作としたメディアミックス作品です。
                        仮想現実（VR）を舞台に、プレイヤーが命を懸けて戦う壮大な物語が描かれています。
                    </p>
                    <p class="mb-4">
                        2022年、VRMMORPG「ソードアート・オンライン」の正式サービスが開始されます。しかし、開発者である茅場晶彦の宣言により、
                        プレイヤーたちはゲームに閉じ込められ、ゲームオーバーは現実世界での死を意味することになります。
                        ゲームをクリアする唯一の方法は、デスゲームの舞台である浮遊城アインクラッドの全100層を攻略することでした。
                    </p>
                    <p>
                        主人公のキリトは、ソロプレイヤーとして最前線で戦いながら、アインクラッドからの脱出を目指します。
                        彼が出会う仲間たちとの絆、そして過酷なデスゲームの中での成長が、この物語の核となっています。
                    </p>
                </div>
            </div>
        </section>

        <!-- 主要キャラクターセクション -->
        <section id="characters" class="bg-white rounded-xl shadow-lg p-6 md:p-8 mb-12">
            <h2 class="text-3xl font-bold text-gray-800 mb-6 border-b-2 border-purple-500 pb-2">主要キャラクター</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- キリト -->
                <div class="bg-gray-50 rounded-lg shadow-md p-6 flex flex-col items-center transform transition-transform hover:scale-105 duration-300">
                    <img src="https://placehold.co/200x200/D53F8C/FFFFFF?text=Kirito" alt="キリト" class="w-32 h-32 rounded-full object-cover mb-4 border-4 border-blue-400">
                    <h3 class="text-xl font-semibold text-gray-900 mb-2">キリト (桐ヶ谷和人)</h3>
                    <p class="text-gray-600 text-center">
                        SAOの主人公。SAOの最前線で戦うソロプレイヤー。二刀流のスキルを持つ。
                        冷静沈着で優しい性格。
                    </p>
                </div>
                <!-- アスナ -->
                <div class="bg-gray-50 rounded-lg shadow-md p-6 flex flex-col items-center transform transition-transform hover:scale-105 duration-300">
                    <img src="https://placehold.co/200x200/ED8936/FFFFFF?text=Asuna" alt="アスナ" class="w-32 h-32 rounded-full object-cover mb-4 border-4 border-pink-400">
                    <h3 class="text-xl font-semibold text-gray-900 mb-2">アスナ (結城明日奈)</h3>
                    <p class="text-gray-600 text-center">
                        ヒロイン。血盟騎士団の副団長を務める実力者。
                        料理上手で、キリトの良きパートナーとなる。
                    </p>
                </div>
                <!-- リーファ -->
                <div class="bg-gray-50 rounded-lg shadow-md p-6 flex flex-col items-center transform transition-transform hover:scale-105 duration-300">
                    <img src="https://placehold.co/200x200/4299E1/FFFFFF?text=Leafa" alt="リーファ" class="w-32 h-32 rounded-full object-cover mb-4 border-4 border-green-400">
                    <h3 class="text-xl font-semibold text-gray-900 mb-2">リーファ (桐ヶ谷直葉)</h3>
                    <p class="text-gray-600 text-center">
                        キリトの妹（従妹）。ALOでは風の妖精族の剣士として活躍。
                        兄を慕う気持ちが強い。
                    </p>
                </div>
                <!-- シノン -->
                <div class="bg-gray-50 rounded-lg shadow-md p-6 flex flex-col items-center transform transition-transform hover:scale-105 duration-300">
                    <img src="https://placehold.co/200x200/9F7AEA/FFFFFF?text=Sinon" alt="シノン" class="w-32 h-32 rounded-full object-cover mb-4 border-4 border-teal-400">
                    <h3 class="text-xl font-semibold text-gray-900 mb-2">シノン (朝田詩乃)</h3>
                    <p class="text-gray-600 text-center">
                        GGOの凄腕スナイパー。銃への恐怖を克服するためダイブする。
                        クールな性格だが、情に厚い一面も。
                    </p>
                </div>
                <!-- ユウキ -->
                <div class="bg-gray-50 rounded-lg shadow-md p-6 flex flex-col items-center transform transition-transform hover:scale-105 duration-300">
                    <img src="https://placehold.co/200x200/F6AD55/FFFFFF?text=Yuuki" alt="ユウキ" class="w-32 h-32 rounded-full object-cover mb-4 border-4 border-red-400">
                    <h3 class="text-xl font-semibold text-gray-900 mb-2">ユウキ (紺野木綿季)</h3>
                    <p class="text-gray-600 text-center">
                        「絶剣」の異名を持つALO最強の剣士。
                        明るく前向きな性格で、アスナに大きな影響を与える。
                    </p>
                </div>
                 <!-- アリス -->
                 <div class="bg-gray-50 rounded-lg shadow-md p-6 flex flex-col items-center transform transition-transform hover:scale-105 duration-300">
                    <img src="https://placehold.co/200x200/A0AEC0/FFFFFF?text=Alice" alt="アリス" class="w-32 h-32 rounded-full object-cover mb-4 border-4 border-indigo-400">
                    <h3 class="text-xl font-semibold text-gray-900 mb-2">アリス (アリス・ツーベルク)</h3>
                    <p class="text-gray-600 text-center">
                        アンダーワールドの住人。整合騎士となる。
                        凛とした性格で、キリトと共にアンダーワールドを救うために戦う。
                    </p>
                </div>
            </div>
        </section>

        <!-- アークセクション -->
        <section id="arcs" class="bg-white rounded-xl shadow-lg p-6 md:p-8 mb-12">
            <h2 class="text-3xl font-bold text-gray-800 mb-6 border-b-2 border-pink-500 pb-2">主なアーク（章）</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- アインクラッド -->
                <div class="bg-blue-50 rounded-lg shadow-md p-6">
                    <h3 class="text-2xl font-bold text-blue-700 mb-3">アインクラッド</h3>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        デスゲームと化したVRMMORPG「ソードアート・オンライン」からの脱出を目指す物語。
                        キリトとアスナの出会い、そしてアインクラッドの100層攻略を目指す戦いが描かれます。
                    </p>
                    <img src="https://placehold.co/500x300/63B3ED/FFFFFF?text=Aincrad+Castle" alt="アインクラッド城" class="rounded-lg shadow-sm w-full">
                </div>
                <!-- フェアリィ・ダンス -->
                <div class="bg-purple-50 rounded-lg shadow-md p-6">
                    <h3 class="text-2xl font-bold text-purple-700 mb-3">フェアリィ・ダンス</h3>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        SAOから帰還したキリトが、まだ意識を取り戻さないアスナを救うため、
                        新たなVRMMORPG「アルヴヘイム・オンライン（ALO）」に挑む章。
                        現実世界と仮想世界での兄妹の絆が描かれます。
                    </p>
                    <img src="https://placehold.co/500x300/A78BFA/FFFFFF?text=ALFheim+Online" alt="アルヴヘイム・オンライン" class="rounded-lg shadow-sm w-full">
                </div>
                <!-- ファントム・バレット -->
                <div class="bg-green-50 rounded-lg shadow-md p-6">
                    <h3 class="text-2xl font-bold text-green-700 mb-3">ファントム・バレット</h3>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        VRMMO「ガンゲイル・オンライン（GGO）」で発生した謎の連続死事件「デス・ガン」の調査のため、
                        キリトがGGOにログインする章。スナイパーのシノンとの出会いが中心です。
                    </p>
                    <img src="https://placehold.co/500x300/48BB78/FFFFFF?text=Gun+Gale+Online" alt="ガンゲイル・オンライン" class="rounded-lg shadow-sm w-full">
                </div>
                <!-- マザーズ・ロザリオ -->
                <div class="bg-yellow-50 rounded-lg shadow-md p-6">
                    <h3 class="text-2xl font-bold text-yellow-700 mb-3">マザーズ・ロザリオ</h3>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        ALOを舞台に、アスナと「絶剣」と呼ばれるユウキとの出会い、
                        そして彼女たちが率いるギルド「スリーピング・ナイツ」の物語が描かれます。
                        感動的な友情と困難への挑戦がテーマです。
                    </p>
                    <img src="https://placehold.co/500x300/ECC94B/FFFFFF?text=Mother's+Rosario" alt="マザーズ・ロザリオ" class="rounded-lg shadow-sm w-full">
                </div>
                <!-- アリシゼーション -->
                <div class="bg-red-50 rounded-lg shadow-md p-6 col-span-1 md:col-span-2">
                    <h3 class="text-2xl font-bold text-red-700 mb-3">アリシゼーション</h3>
                    <p class="text-700 leading-relaxed mb-4">
                        現実世界で襲撃され意識を失ったキリトが、謎の仮想世界「アンダーワールド」で目覚める章。
                        「魂（フラクトライト）」を扱う新技術と、世界の真実を巡る壮大な戦いが繰り広げられます。
                    </p>
                    <img src="https://placehold.co/1000x400/F56565/FFFFFF?text=Underworld" alt="アンダーワールド" class="rounded-lg shadow-sm w-full">
                </div>
            </div>
        </section>

        <!-- ギャラリーセクション -->
        <section id="gallery" class="bg-white rounded-xl shadow-lg p-6 md:p-8 mb-12">
            <h2 class="text-3xl font-bold text-gray-800 mb-6 border-b-2 border-teal-500 pb-2">ギャラリー</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
                <div class="relative group rounded-lg overflow-hidden shadow-md">
                    <img src="https://placehold.co/400x300/C05621/FFFFFF?text=Kirito+%26+Asuna" alt="キリトとアスナ" class="w-full h-48 object-cover transform transition-transform group-hover:scale-110 duration-300">
                    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-lg font-semibold">キリトとアスナ</p>
                    </div>
                </div>
                <div class="relative group rounded-lg overflow-hidden shadow-md">
                    <img src="https://placehold.co/400x300/667EEA/FFFFFF?text=SAO+Group" alt="SAOグループ" class="w-full h-48 object-cover transform transition-transform group-hover:scale-110 duration-300">
                    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-lg font-semibold">SAO仲間たち</p>
                    </div>
                </div>
                <div class="relative group rounded-lg overflow-hidden shadow-md">
                    <img src="https://placehold.co/400x300/38A169/FFFFFF?text=Alicization+Scene" alt="アリシゼーションシーン" class="w-full h-48 object-cover transform transition-transform group-hover:scale-110 duration-300">
                    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-lg font-semibold">アンダーワールド</p>
                    </div>
                </div>
                <div class="relative group rounded-lg overflow-hidden shadow-md">
                    <img src="https://placehold.co/400x300/D69E2E/FFFFFF?text=SAO+Artwork" alt="SAOアートワーク" class="w-full h-48 object-cover transform transition-transform group-hover:scale-110 duration-300">
                    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-lg font-semibold">アートワーク</p>
                    </div>
                </div>
                <div class="relative group rounded-lg overflow-hidden shadow-md">
                    <img src="https://placehold.co/400x300/4299E1/FFFFFF?text=Kirito+Duel" alt="キリトの決闘" class="w-full h-48 object-cover transform transition-transform group-hover:scale-110 duration-300">
                    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-lg font-semibold">キリトの決闘</p>
                    </div>
                </div>
                <div class="relative group rounded-lg overflow-hidden shadow-md">
                    <img src="https://placehold.co/400x300/ECC94B/FFFFFF?text=Asuna+Fighting" alt="戦うアスナ" class="w-full h-48 object-cover transform transition-transform group-hover:scale-110 duration-300">
                    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-lg font-semibold">戦うアスナ</p>
                    </div>
                </div>
                <div class="relative group rounded-lg overflow-hidden shadow-md">
                    <img src="https://placehold.co/400x300/9F7AEA/FFFFFF?text=Sinon+Sniping" alt="シノンの狙撃" class="w-full h-48 object-cover transform transition-transform group-hover:scale-110 duration-300">
                    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-lg font-semibold">シノンの狙撃</p>
                    </div>
                </div>
                <div class="relative group rounded-lg overflow-hidden shadow-md">
                    <img src="https://placehold.co/400x300/D53F8C/FFFFFF?text=Leafa+Flight" alt="リーファの飛行" class="w-full h-48 object-cover transform transition-transform group-hover:scale-110 duration-300">
                    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-lg font-semibold">リーファの飛行</p>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- フッターセクション -->
    <footer class="bg-gray-800 text-white py-6 mt-8">
        <div class="container mx-auto px-4 text-center">
            <p>&copy; 2025 SAOまとめサイト. すべての権利はそれぞれの原著作者に帰属します。</p>
            <p class="mt-2 text-sm">このサイトはファンによる非公式のまとめサイトです。</p>
        </div>
    </footer>
</body>
</html>

