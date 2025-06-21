<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SAOまとめサイト - Sword Art Online Fan Summary</title>
    <!-- Tailwind CSS CDNを読み込み、レスポンシブデザインとスタイリングを提供 -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google FontsからInterフォントを読み込み、クリーンなタイポグラフィを実現 -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        /* 全体的なフォント設定と背景色の指定 */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f0f2f5; /* 明るいグレーの背景色 */
            color: #333; /* 暗めのテキスト色 */
        }
        /* コンテンツの最大幅を設定し、中央に配置 */
        .container {
            max-width: 1200px;
        }
        /* カスタムスクロールバーのスタイリング（ウェブサイトの見た目を良くするため） */
        ::-webkit-scrollbar {
            width: 8px; /* スクロールバーの幅 */
        }
        ::-webkit-scrollbar-track {
            background: #e0e0e0; /* トラックの背景色 */
            border-radius: 10px; /* 角を丸くする */
        }
        ::-webkit-scrollbar-thumb {
            background: #888; /* サム（ドラッグする部分）の背景色 */
            border-radius: 10px; /* 角を丸くする */
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #555; /* ホバー時のサムの背景色 */
        }
    </style>
</head>
<body class="antialiased">
    <!-- ヘッダーセクション: サイトのタイトルとナビゲーションメニュー -->
    <header class="bg-gradient-to-r from-blue-700 to-purple-600 text-white shadow-lg py-6">
        <div class="container mx-auto px-4 flex flex-col md:flex-row justify-between items-center">
            <!-- サイトタイトル -->
            <h1 class="text-4xl font-bold mb-2 md:mb-0">
                <span class="block">SAO</span>
                <span class="block text-xl">ソードアート・オンライン まとめサイト</span>
            </h1>
            <!-- ナビゲーションメニュー -->
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

    <!-- メインコンテンツセクション: 各コンテンツブロックを含む -->
    <main class="container mx-auto px-4 py-8 md:py-12">
        <!-- 概要セクション: SAOの基本的な説明とイメージ -->
        <section id="overview" class="bg-white rounded-xl shadow-lg p-6 md:p-8 mb-12">
            <h2 class="text-3xl font-bold text-gray-800 mb-6 border-b-2 border-blue-500 pb-2">SAOとは？</h2>
            <div class="flex flex-col md:flex-row items-center md:space-x-8">
                <div class="md:w-1/2 mb-6 md:mb-0">
                    <!-- プレースホルダー画像: SAOのログイン画面をイメージ -->
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

        <!-- 主要キャラクターセクション: 各キャラクターの紹介 -->
        <section id="characters" class="bg-white rounded-xl shadow-lg p-6 md:p-8 mb-12">
            <h2 class="text-3xl font-bold text-gray-800 mb-6 border-b-2 border-purple-500 pb-2">主要キャラクター</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- キリトのカード -->
                <div class="bg-gray-50 rounded-lg shadow-md p-6 flex flex-col items-center transform transition-transform hover:scale-105 duration-300">
                    <!-- プレースホルダー画像: キリト -->
                    <img src="https://placehold.co/200x200/D53F8C/FFFFFF?text=Kirito" alt="キリト" class="w-32 h-32 rounded-full object-cover mb-4 border-4 border-blue-400">
                    <h3 class="text-xl font-semibold text-gray-900 mb-2">キリト (桐ヶ谷和人)</h3>
                    <p class="text-gray-600 text-center">
                        SAOの主人公。SAOの最前線で戦うソロプレイヤー。二刀流のスキルを持つ。
                        冷静沈着で優しい性格。
                    </p>
                </div>
                <!-- アスナのカード -->
                <div class="bg-gray-50 rounded-lg shadow-md p-6 flex flex-col items-center transform transition-transform hover:scale-105 duration-300">
                    <!-- プレースホルダー画像: アスナ -->
                    <img src="https://placehold.co/200x200/ED8936/FFFFFF?text=Asuna" alt="アスナ" class="w-32 h-32 rounded-full object-cover mb-4 border-4 border-pink-400">
                    <h3 class="text-xl font-semibold text-gray-900 mb-2">アスナ (結城明日奈)</h3>
                    <p class="text-gray-600 text-center">
                        ヒロイン。血盟騎士団の副団長を務める実力者。
                        料理上手で、キリトの良きパートナーとなる。
                    </p>
                </div>
                <!-- リーファのカード -->
                <div class="bg-gray-50 rounded-lg shadow-md p-6 flex flex-col items-center transform transition-transform hover:scale-105 duration-300">
                    <!-- プレースホルダー画像: リーファ -->
                    <img src="https://placehold.co/200x200/4299E1/FFFFFF?text=Leafa" alt="リーファ" class="w-32 h-32 rounded-full object-cover mb-4 border-4 border-green-400">
                    <h3 class="text-xl font-semibold text-gray-900 mb-2">リーファ (桐ヶ谷直葉)</h3>
                    <p class="text-gray-600 text-center">
                        キリトの妹（従妹）。ALOでは風の妖精族の剣士として活躍。
                        兄を慕う気持ちが強い。
                    </p>
                </div>
                <!-- シノンのカード -->
                <div class="bg-gray-50 rounded-lg shadow-md p-6 flex flex-col items-center transform transition-transform hover:scale-105 duration-300">
                    <!-- プレースホルダー画像: シノン -->
                    <img src="https://placehold.co/200x200/9F7AEA/FFFFFF?text=Sinon" alt="シノン" class="w-32 h-32 rounded-full object-cover mb-4 border-4 border-teal-400">
                    <h3 class="text-xl font-semibold text-gray-900 mb-2">シノン (朝田詩乃)</h3>
                    <p class="text-gray-600 text-center">
                        GGOの凄腕スナイパー。銃への恐怖を克服するためダイブする。
                        クールな性格だが、情に厚い一面も。
                    </p>
                </div>
                <!-- ユウキのカード -->
                <div class="bg-gray-50 rounded-lg shadow-md p-6 flex flex-col items-center transform transition-transform hover:scale-105 duration-300">
                    <!-- プレースホルダー画像: ユウキ -->
                    <img src="https://placehold.co/200x200/F6AD55/FFFFFF?text=Yuuki" alt="ユウキ" class="w-32 h-32 rounded-full object-cover mb-4 border-4 border-red-400">
                    <h3 class="text-xl font-semibold text-gray-900 mb-2">ユウキ (紺野木綿季)</h3>
                    <p class="text-gray-600 text-center">
                        「絶剣」の異名を持つALO最強の剣士。
                        明るく前向きな性格で、アスナに大きな影響を与える。
                    </p>
                </div>
                 <!-- アリスのカード -->
                 <div class="bg-gray-50 rounded-lg shadow-md p-6 flex flex-col items-center transform transition-transform hover:scale-105 duration-300">
                    <!-- プレースホルダー画像: アリス -->
                    <img src="https://placehold.co/200x200/A0AEC0/FFFFFF?text=Alice" alt="アリス" class="w-32 h-32 rounded-full object-cover mb-4 border-4 border-indigo-400">
                    <h3 class="text-xl font-semibold text-gray-900 mb-2">アリス (アリス・ツーベルク)</h3>
                    <p class="text-gray-600 text-center">
                        アンダーワールドの住人。整合騎士となる。
                        凛とした性格で、キリトと共にアンダーワールドを救うために戦う。
                    </p>
                </div>
            </div>
        </section>

        <!-- アークセクション: 主要な物語のアークの紹介 -->
        <section id="arcs" class="bg-white rounded-xl shadow-lg p-6 md:p-8 mb-12">
            <h2 class="text-3xl font-bold text-gray-800 mb-6 border-b-2 border-pink-500 pb-2">主なアーク（章）</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- アインクラッドのアーク情報 -->
                <div class="bg-blue-50 rounded-lg shadow-md p-6">
                    <h3 class="text-2xl font-bold text-blue-700 mb-3">アインクラッド</h3>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        デスゲームと化したVRMMORPG「ソードアート・オンライン」からの脱出を目指す物語。
                        キリトとアスナの出会い、そしてアインクラッドの100層攻略を目指す戦いが描かれます。
                    </p>
                    <!-- プレースホルダー画像: アインクラッド城 -->
                    <img src="https://placehold.co/500x300/63B3ED/FFFFFF?text=Aincrad+Castle" alt="アインクラッド城" class="rounded-lg shadow-sm w-full">
                </div>
                <!-- フェアリィ・ダンスのアーク情報 -->
                <div class="bg-purple-50 rounded-lg shadow-md p-6">
                    <h3 class="text-2xl font-bold text-purple-700 mb-3">フェアリィ・ダンス</h3>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        SAOから帰還したキリトが、まだ意識を取り戻さないアスナを救うため、
                        新たなVRMMORPG「アルヴヘイム・オンライン（ALO）」に挑む章。
                        現実世界と仮想世界での兄妹の絆が描かれます。
                    </p>
                    <!-- プレースホルダー画像: アルヴヘイム・オンライン -->
                    <img src="https://placehold.co/500x300/A78BFA/FFFFFF?text=ALFheim+Online" alt="アルヴヘイム・オンライン" class="rounded-lg shadow-sm w-full">
                </div>
                <!-- ファントム・バレットのアーク情報 -->
                <div class="bg-green-50 rounded-lg shadow-md p-6">
                    <h3 class="text-2xl font-bold text-green-700 mb-3">ファントム・バレット</h3>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        VRMMO「ガンゲイル・オンライン（GGO）」で発生した謎の連続死事件「デス・ガン」の調査のため、
                        キリトがGGOにログインする章。スナイパーのシノンとの出会いが中心です。
                    </p>
                    <!-- プレースホルダー画像: ガンゲイル・オンライン -->
                    <img src="https://placehold.co/500x300/48BB78/FFFFFF?text=Gun+Gale+Online" alt="ガンゲイル・オンライン" class="rounded-lg shadow-sm w-full">
                </div>
                <!-- マザーズ・ロザリオのアーク情報 -->
                <div class="bg-yellow-50 rounded-lg shadow-md p-6">
                    <h3 class="text-2xl font-bold text-yellow-700 mb-3">マザーズ・ロザリオ</h3>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        ALOを舞台に、アスナと「絶剣」と呼ばれるユウキとの出会い、
                        そして彼女たちが率いるギルド「スリーピング・ナイツ」の物語が描かれます。
                        感動的な友情と困難への挑戦がテーマです。
                    </p>
                    <!-- プレースホルダー画像: マザーズ・ロザリオ -->
                    <img src="https://placehold.co/500x300/ECC94B/FFFFFF?text=Mother's+Rosario" alt="マザーズ・ロザリオ" class="rounded-lg shadow-sm w-full">
                </div>
                <!-- アリシゼーションのアーク情報 -->
                <div class="bg-red-50 rounded-lg shadow-md p-6 col-span-1 md:col-span-2">
                    <h3 class="text-2xl font-bold text-red-700 mb-3">アリシゼーション</h3>
                    <p class="text-gray-700 leading-relaxed mb-4">
                        現実世界で襲撃され意識を失ったキリトが、謎の仮想世界「アンダーワールド」で目覚める章。
                        「魂（フラクトライト）」を扱う新技術と、世界の真実を巡る壮大な戦いが繰り広げられます。
                    </p>
                    <!-- プレースホルダー画像: アンダーワールド -->
                    <img src="https://placehold.co/1000x400/F56565/FFFFFF?text=Underworld" alt="アンダーワールド" class="rounded-lg shadow-sm w-full">
                </div>
            </div>
        </section>

        <!-- ギャラリーセクション: SAO関連の画像ギャラリー -->
        <section id="gallery" class="bg-white rounded-xl shadow-lg p-6 md:p-8 mb-12">
            <h2 class="text-3xl font-bold text-gray-800 mb-6 border-b-2 border-teal-500 pb-2">ギャラリー</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
                <!-- ギャラリーアイテム例 -->
                <div class="relative group rounded-lg overflow-hidden shadow-md">
                    <!-- プレースホルダー画像: キリトとアスナ -->
                    <img src="https://placehold.co/400x300/C05621/FFFFFF?text=Kirito+%26+Asuna" alt="キリトとアスナ" class="w-full h-48 object-cover transform transition-transform group-hover:scale-110 duration-300">
                    <!-- ホバー時のオーバーレイテキスト -->
                    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-lg font-semibold">キリトとアスナ</p>
                    </div>
                </div>
                <!-- ギャラリーアイテム例 -->
                <div class="relative group rounded-lg overflow-hidden shadow-md">
                    <!-- プレースホルダー画像: SAOグループ -->
                    <img src="https://placehold.co/400x300/667EEA/FFFFFF?text=SAO+Group" alt="SAOグループ" class="w-full h-48 object-cover transform transition-transform group-hover:scale-110 duration-300">
                    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-lg font-semibold">SAO仲間たち</p>
                    </div>
                </div>
                <!-- ギャラリーアイテム例 -->
                <div class="relative group rounded-lg overflow-hidden shadow-md">
                    <!-- プレースホルダー画像: アリシゼーションシーン -->
                    <img src="https://placehold.co/400x300/38A169/FFFFFF?text=Alicization+Scene" alt="アリシゼーションシーン" class="w-full h-48 object-cover transform transition-transform group-hover:scale-110 duration-300">
                    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-lg font-semibold">アンダーワールド</p>
                    </div>
                </div>
                <!-- ギャラリーアイテム例 -->
                <div class="relative group rounded-lg overflow-hidden shadow-md">
                    <!-- プレースホルダー画像: SAOアートワーク -->
                    <img src="https://placehold.co/400x300/D69E2E/FFFFFF?text=SAO+Artwork" alt="SAOアートワーク" class="w-full h-48 object-cover transform transition-transform group-hover:scale-110 duration-300">
                    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-lg font-semibold">アートワーク</p>
                    </div>
                </div>
                <!-- ギャラリーアイテム例 -->
                <div class="relative group rounded-lg overflow-hidden shadow-md">
                    <!-- プレースホルダー画像: キリトの決闘 -->
                    <img src="https://placehold.co/400x300/4299E1/FFFFFF?text=Kirito+Duel" alt="キリトの決闘" class="w-full h-48 object-cover transform transition-transform group-hover:scale-110 duration-300">
                    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-lg font-semibold">キリトの決闘</p>
                    </div>
                </div>
                <!-- ギャラリーアイテム例 -->
                <div class="relative group rounded-lg overflow-hidden shadow-md">
                    <!-- プレースホルダー画像: 戦うアスナ -->
                    <img src="https://placehold.co/400x300/ECC94B/FFFFFF?text=Asuna+Fighting" alt="戦うアスナ" class="w-full h-48 object-cover transform transition-transform group-hover:scale-110 duration-300">
                    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-lg font-semibold">戦うアスナ</p>
                    </div>
                </div>
                <!-- ギャラリーアイテム例 -->
                <div class="relative group rounded-lg overflow-hidden shadow-md">
                    <!-- プレースホルダー画像: シノンの狙撃 -->
                    <img src="https://placehold.co/400x300/9F7AEA/FFFFFF?text=Sinon+Sniping" alt="シノンの狙撃" class="w-full h-48 object-cover transform transition-transform group-hover:scale-110 duration-300">
                    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-lg font-semibold">シノンの狙撃</p>
                    </div>
                </div>
                <!-- ギャラリーアイテム例 -->
                <div class="relative group rounded-lg overflow-hidden shadow-md">
                    <!-- プレースホルダー画像: リーファの飛行 -->
                    <img src="https://placehold.co/400x300/D53F8C/FFFFFF?text=Leafa+Flight" alt="リーファの飛行" class="w-full h-48 object-cover transform transition-transform group-hover:scale-110 duration-300">
                    <div class="absolute inset-0 bg-black bg-opacity-50 flex items-center justify-center opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                        <p class="text-white text-lg font-semibold">リーファの飛行</p>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <!-- フッターセクション: 著作権表示と注意書き -->
    <footer class="bg-gray-800 text-white py-6 mt-8">
        <div class="container mx-auto px-4 text-center">
            <p>&copy; 2025 SAOまとめサイト. すべての権利はそれぞれの原著作者に帰属します。</p>
            <p class="mt-2 text-sm">このサイトはファンによる非公式のまとめサイトです。</p>
        </div>
    </footer>
</body>
</html>
