    <!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Untuk Brenda</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        #page1 {
            background: url('https://raw.githubusercontent.com/Makizzz25/makiz/refs/heads/main/IMG_E0539.JPG') no-repeat center center/cover;
            width: 100%;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
        #page2 {
            background: url('https://github.com/Makizzz25/makiz/blob/main/1746596780569.jpg?raw=true') no-repeat center center/cover;
            width: 100vw;
            min-height: 150vh;
            position: absolute;
            top: 0;
            left: 0;
            display: none;
            flex-direction: column;
            justify-content: flex-start;
            align-items: center;
            overflow-y: auto;
            padding: 20px;
            box-sizing: border-box;
        }

        .box {
            background: rgba(255, 255, 255, 0.4); 
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            max-width: 80%;
            word-wrap: break-word;
            text-align: center;
        }

        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .button {
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 18px;
            color: white;
            background-color: rgb(235, 133, 0);
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
        }
        .button:hover {
            background-color: rgb(255, 187, 0);
        }
    </style>
</head>
<body>
    <div id="page1">
        <div class="box">
            <h1>🥳Happy Graduation Sayanggg ku Brendaaa
                🥳🧡
                💖
                🧡
</h1>
        </div>
        <a href="#" class="button" onclick="nextPage()">for you sayanggg 🤍</a>
    </div>
    
    <div id="page2">
        <div class="box">
            <h2>Happy Graduation Sayanggg 🥳🤍✨🌹💍

            </h2>
            <p>hai sayang, hari ini jumat 9 mei 2025, datang nk untuk hadiri juga graduation mu, selamat sayang atas graduation mu, akhirnya bisa miko lulus dari lentera, bangga sekali nk sama kau sudah selesaikan sma mu di lentera, berbagai macam masalah mulai dari tugas, pertemanan, guru yang selalu carikan ko masalah, sampai masalah diluarnya bisa ko lewati semua karna percaya nk sama kau kalau kuat ko, semoga hasil mu dari sma bisa buat ko berkembang untuk kedepannya, sekali lagi congratulation sayang. semoga hasil belajar mu dari utbk kemarin bisa membuahkan hasil, bisa lulus di universitas pilihan mu, doa yang terbaik nk untuk kau sayang 🤍🌹✨💍. jujur kalo disuruh nk rangkai kata2 kayak begini sebenarnya ndk ku tau apa2 yang harus di bilang, tapi berdoa nk yang terbaik untuk kau sayang, semoga kedepannya bisa jadi anak yg lebih baik, jadi pasangan yang lebih baik, sehat selalu, bahagia selalu. btw kangen liu nk sama kau, kek tinggal kik sebulan sama, mulai dari bangun sampe tidur sama2 kik, lapar sama2, haus sama2, jalan2 sama2, kepedisan sama2 hahahaha, pokoknya semuanya sama2 kik, senang sekali nk bisa pacaran sama kau sayang, ku syukuri sekali, sebaik itu ko, se sayang itu ko, ndk akan nk sia siakan orang kek kau sayang. mungkin itu dari saya, ku ucapkan semua yang terbaik dalam doa untuk kau sayang 🤍. mungkin itu dari saya sayang, happy graduation sayang, ku sayang sekali ko, ku cintahhhhhhh sekali, love you baby 🤍🌹✨💍


            </p>
        </div>
        <div style="height: 80px;"></div>
        <a href="https://wa.me/6282393486760" class="button">Ayok ngebucin? Ayok jalan jalan sama? siniii......🤍🤍🤍</a>
    </div>
    
    <script>
        function nextPage() {
            document.getElementById('page1').style.display = 'none';
            document.getElementById('page2').style.display = 'flex';
        }
    </script>
</body>
</html>
