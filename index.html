<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>連続方向指示アプリ</title>
    <!-- Tailwind CSS を読み込みます。これにより、美しいデザインを簡単に適用できます。 -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fontsから「Inter」フォントを読み込みます。 -->
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-slate-900 text-white flex items-center justify-center min-h-screen">

    <!-- アプリのコンテナ -->
    <div id="app-container" class="bg-gray-800 p-8 md:p-12 rounded-3xl shadow-2xl text-center max-w-sm w-full mx-4 sm:mx-auto">
        <h1 class="text-3xl sm:text-4xl font-bold mb-8 text-indigo-400">反射神経トレーニング</h1>
        
        <!-- カウントダウンや矢印が表示される部分 -->
        <div class="h-48 flex items-center justify-center">
            <div id="display-area" class="text-7xl sm:text-9xl font-extrabold text-indigo-200">
                スタート
            </div>
        </div>

        <!-- コントロールボタン -->
        <div class="mt-8 flex justify-center">
            <button id="start-button" class="bg-indigo-600 hover:bg-indigo-700 text-white font-bold py-3 px-8 rounded-full shadow-lg transition-all duration-300 transform hover:scale-105 active:scale-95 focus:outline-none focus:ring-4 focus:ring-indigo-500 focus:ring-opacity-50">
                スタート
            </button>
            <button id="stop-button" class="bg-red-600 hover:bg-red-700 text-white font-bold py-3 px-8 rounded-full shadow-lg transition-all duration-300 transform hover:scale-105 active:scale-95 focus:outline-none focus:ring-4 focus:ring-red-500 focus:ring-opacity-50 ml-4" style="display: none;">
                ストップ
            </button>
        </div>
    </div>

    <!-- JavaScriptの実装 -->
    <script>
        // DOM要素を取得
        const displayArea = document.getElementById('display-area');
        const startButton = document.getElementById('start-button');
        const stopButton = document.getElementById('stop-button');

        // 矢印と方向の辞書
        const directions = {
            '前': '▲',
            '後': '▼',
            '左': '◀',
            '右': '▶'
        };
        
        // 連続表示のタイマーID
        let intervalId;
        
        // ゲームが実行中かどうかのフラグ
        let isRunning = false;
        
        // ゲームをスタートさせる関数
        function startGame() {
            if (isRunning) return;
            isRunning = true;
            
            startButton.style.display = 'none';
            stopButton.style.display = 'inline-block';
            
            // カウントダウン処理を開始
            startCountdown();
        }
        
        // カウントダウンと矢印表示のサイクルを開始する関数
        function startCountdown() {
            let count = 3;
            displayArea.textContent = count;
            displayArea.style.color = '#9CA3AF'; // カウントダウンの色をグレーに
            
            const countdownInterval = setInterval(() => {
                count--;
                if (count > 0) {
                    displayArea.textContent = count;
                } else {
                    clearInterval(countdownInterval);
                    showRandomDirection();
                }
            }, 1000);
        }

        // ランダムな方向を表示し、再びカウントダウンを開始する関数
        function showRandomDirection() {
            const directionKeys = Object.keys(directions);
            const randomIndex = Math.floor(Math.random() * directionKeys.length);
            const randomKey = directionKeys[randomIndex];
            const randomArrow = directions[randomKey];
            
            displayArea.textContent = randomArrow;
            displayArea.style.color = '#10B981'; // 矢印の色を緑に
            
            // 矢印の表示時間を短縮し、1秒後に次のサイクルを開始
            intervalId = setTimeout(startCountdown, 1000);
        }
        
        // ゲームをストップする関数
        function stopGame() {
            clearTimeout(intervalId); // タイマーをクリア
            isRunning = false;
            displayArea.textContent = 'ストップ';
            displayArea.style.color = '#EF4444'; // ストップの色を赤に
            
            startButton.style.display = 'inline-block';
            stopButton.style.display = 'none';
        }

        // イベントリスナー
        startButton.addEventListener('click', startGame);
        stopButton.addEventListener('click', stopGame);
    </script>

</body>
</html>
