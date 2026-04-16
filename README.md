<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Memory Lane - Angkatan 2026</title>
    <style>
        /* --- CSS DASAR & BACKGROUND --- */
        body {
            margin: 0;
            padding: 0;
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), 
                        url('https://images.unsplash.com/photo-1441974231531-c6227db76b6e?q=80&w=2071&auto=format&fit=crop');
            background-size: cover;
            background-attachment: fixed;
            background-position: center;
            color: #fff;
            overflow-x: hidden;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 40px 20px;
            position: relative;
            z-index: 2;
        }

        h1, h2 {
            text-align: center;
            text-transform: uppercase;
            letter-spacing: 3px;
            text-shadow: 2px 4px 10px rgba(0,0,0,0.5);
        }

        h1 { font-size: 3.5rem; color: #a8e063; margin-bottom: 50px; }
        h2 { font-size: 2rem; margin: 60px 0 30px; border-bottom: 2px solid #56ab2f; display: inline-block; width: 100%; padding-bottom: 10px; }

        /* --- GRID SYSTEM (3 FOTO BERJEJER) --- */
        .photo-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr); /* 3 Kolom Berjejer */
            gap: 25px;
        }

        /* --- STYLING KARTU FOTO --- */
        .card {
            background: rgba(255, 255, 255, 0.1);
            backdrop-filter: blur(8px);
            border-radius: 15px;
            padding: 15px;
            text-align: center;
            border: 1px solid rgba(255, 255, 255, 0.2);
            transition: transform 0.3s ease;
        }

        .card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.3);
        }

        .card img, .card video {
            width: 100%;
            border-radius: 10px;
            object-fit: cover;
            display: block;
        }

        /* --- UKURAN RASIO --- */
        .ratio-3-4 img, .ratio-3-4 video { aspect-ratio: 3 / 4; }
        .ratio-16-9 img { aspect-ratio: 16 / 9; }

        .name-label {
            margin-top: 15px;
            font-weight: 600;
            color: #d1ffd6;
            font-size: 1.1rem;
        }

        /* --- AUDIO PLAYER --- */
        .music-box {
            position: fixed;
            bottom: 20px;
            right: 20px;
            z-index: 100;
            background: rgba(0,0,0,0.8);
            padding: 10px;
            border-radius: 50px;
        }

        /* --- ANIMASI DAUN JATUH --- */
        .leaf {
            position: fixed;
            top: -10vh;
            pointer-events: none;
            z-index: 1;
            animation: fall linear infinite;
        }

        @keyframes fall {
            to {
                transform: translateY(110vh) rotate(360deg);
            }
        }

        /* Responsive Mobile */
        @media (max-width: 768px) {
            .photo-grid { grid-template-columns: repeat(2, 1fr); }
            h1 { font-size: 2rem; }
        }
    </style>
</head>
<body>

    <div class="music-box">
        <audio id="bgMusic" controls loop>
            <source src="ssstik.io_1728882590977.mp3" type="audio/mpeg">
            Your browser does not support the audio element.
        </audio>
    </div>

    <div class="container">
        <h1>MEMORY POTHOS 2023-2026</h1>

        <h2>Foto Angkatan 2026</h2>
        <div class="photo-grid ratio-3-4">
            <div class="card"><img src="IMG_1522.JPG" alt=""><div class="name-label">MOH ANTON</div></div>
            <div class="card"><img src="IMG_1523.JPG" alt=""><div class="name-label">AHMAD ABIL JA'FAR SODIQ'</div></div>
            <div class="card"><img src="IMG_1525.JPG" alt=""><div class="name-label">AHMAD WIDAD NAUVAL</div></div>
            <div class="card"><img src="IMG_1526.JPG" alt=""><div class="name-label">MOH RONI</div></div>
            <div class="card"><img src="IMG_1527.JPG" alt=""><div class="name-label">DAVIN BAHTIAR SAPUTRA</div></div>
            <div class="card"><img src="IMG_1528.JPG" alt=""><div class="name-label">MOH NURUL ABDI</div></div>
            <div class="card"><img src="IMG_1529.JPG" alt=""><div class="name-label">HAFIZAL HAWWAZ</div></div>
            <div class="card"><img src="IMG_1530.JPG" alt=""><div class="name-label">FITRA ALFAWWAZ</div></div>
            <div class="card"><img src="IMG_1531.JPG" alt=""><div class="name-label">FAZRUR ROHMAN ASSALABI</div></div>
            <div class="card"><img src="IMG_1532.JPG" alt=""><div class="name-label">AINUL WAFI</div></div>
            <div class="card"><img src="IMG_1533.JPG" alt=""><div class="name-label">FAISAL AFDHAL AULIA</div></div>
            <div class="card"><img src="IMG_1534.JPG" alt=""><div class="name-label">AGUNG PRASETYO</div></div>
            <div class="card"><img src="IMG_1535.JPG" alt=""><div class="name-label">TOBY AHMAD MUNAJAH</div></div>
            <div class="card"><img src="IMG_1536.JPG" alt=""><div class="name-label">MOHAMMAD FARIZQI AZMI</div></div>
            <div class="card"><img src="IMG_1537.JPG" alt=""><div class="name-label">RAYYAN AQSA RADITYA</div></div>
            <div class="card"><img src="IMG_1538.JPG" alt=""><div class="name-label">MOHAMMAD 'A-ISY IBNU NIZAR'</div></div>
            <div class="card"><img src="IMG_1539.JPG" alt=""><div class="name-label">ALFIAN BAGUZ ZURIAT</div></div>
            <div class="card"><img src="IMG_1540.JPG" alt=""><div class="name-label">ANDRA NICOLA SAPUTRA</div></div>
            <div class="card"><img src="IMG_1541.JPG" alt=""><div class="name-label">EGIET</div></div>
            <div class="card"><img src="IMG_1542.JPG" alt=""><div class="name-label">FAJRIL FALACH 20</div></div>
            <div class="card"><img src="IMG_1544.JPG" alt=""><div class="name-label">MOHAMMAD NASRUL MAHASIN</div></div>
            <div class="card"><img src="IMG_1545.JPG" alt=""><div class="name-label">ZAMMI</div></div>
            <div class="card"><img src="IMG_1546.JPG" alt=""><div class="name-label">NAWWAL SAYYIDATUL KARIMAH</div></div>
            <div class="card"><img src="IMG_1547.JPG" alt=""><div class="name-label">NUR FITRI RIZQIYAH</div></div>
            <div class="card"><img src="IMG_1549.JPG" alt=""><div class="name-label">SAADATUN NADHIVA</div></div>
            <div class="card"><img src="IMG_1550.JPG" alt=""><div class="name-label">SYAFIRA AKMAL LABIBAH</div></div>
            <div class="card"><img src="IMG_1551.JPG" alt=""><div class="name-label">SYIFAUR RAHMAH</div></div>
            <div class="card"><img src="IMG_1553.JPG" alt=""><div class="name-label">AFFIKA SALSABILA</div></div>
            <div class="card"><img src="IMG_1554.JPG" alt=""><div class="name-label">BELLA</div></div>
            <div class="card"><img src="IMG_1555.JPG" alt=""><div class="name-label">NANDA</div></div>
        </div>

        <h2>Kenangan Kelas X-XII</h2>
        <div class="photo-ratio-16-9">
            <div class="card"><img src="IMG-20260416-WA0092.jpg" alt=""></div>
            <div class="card"><img src="IMG-20260416-WA0080.jpg" alt=""></div>
            <div class="card"><img src="IMG-20260411-WA0013.jpg" alt=""></div>
            <div class="card"><img src="IMG-20260411-WA0022.jpg" alt=""></div>
            <div class="card"><img src="IMG-20260416-WA0173.jpg" alt=""></div>
            <div class="card"><img src="IMG-20260416-WA0156.jpg" alt=""></div>
            <div class="card"><img src="IMG-20260416-WA0163.jpg" alt=""></div>
            <div class="card"><img src="IMG-20260416-WA0162.jpg" alt=""></div>
            <div class="card"><img src="IMG-20260416-WA0222.jpg" alt=""></div>
            <div class="card"><img src="IMG-20260416-WA0207.jpg" alt=""></div>
        </div>

        <h2>Foto Random</h2>
        <div class="photo-grid ratio-3-4">
            <div class="card"><img src="IMG-20260416-WA0147.jpg" alt=""></div>
            <div class="card"><img src="IMG-20260416-WA0240.jpg" alt=""></div>
            <div class="card"><img src="IMG-20260416-WA0146.jpg" alt=""></div>
            <div class="card"><img src="IMG-20260416-WA0129.jpg" alt=""></div>
            <div class="card"><img src="IMG-20250215-WA0013.jpg"=""></div>
            <div class="card"><img src="IMG-20250215-WA0011.jpg" alt=""></div>
            <div class="card"><img src="IMG-20260416-WA0208.jpg" alt=""></div>
            <div class="card"><img src="IMG-20260416-WA0153.jpg" alt=""></div>
            <div class="card"><img src="IMG-20260416-WA0220.jpg" alt=""></div>
            <div class="card"><img src="IMG-20260416-WA0255.jpg" alt=""></div>
        </div>

        <h2>Video Random</h2>
        <div class="photo-ratio-3-4">
            <div class="card"><video controls><source src="VID-20260416-WA0199.mp4" type="video/mp4"></video></div>
            <div class="card"><video controls><source src="VID-20260416-WA0256.mp4" type="video/mp4"></video></div>
            <div class="card"><video controls><source src="VID-20260416-WA0251.mp4" type="video/mp4"></video></div>
            <div class="card"><video controls><source src="VID-20260416-WA0261.mp4" type="video/mp4"></video></div>
            <div class="card"><video controls><source src="VID-20260416-WA0264.mp4" type="video/mp4"></video></div>
            <div class="card"><video controls><source src="VID-20260416-WA0071.mp4" type="video/mp4"></video></div>
            <div class="card"><video controls><source src="VID-20260416-WA0072.mp4" type="video/mp4"></video></div>
            <div class="card"><video controls><source src="VID-20260416-WA0117.mp4" type="video/mp4"></video></div>
            <div class="card"><video controls><source src="VID-20260416-WA0198.mp4" type="video/mp4"></video></div>
            <div class="card"><video controls><source src="VID-20260416-WA0260.mp4" type="video/mp4"></video></div>
        </div>
    </div>

    <script>
        function createLeaf() {
            const leaf = document.createElement('div');
            leaf.classList.add('leaf');
            leaf.innerHTML = '🍃'; // Karakter daun
            leaf.style.left = Math.random() * 100 + 'vw';
            leaf.style.animationDuration = Math.random() * 3 + 2 + 's'; 
            leaf.style.opacity = Math.random();
            leaf.style.fontSize = Math.random() * 20 + 10 + 'px';
            leaf.style.color = "#7cfc00";
            
            document.body.appendChild(leaf);

            setTimeout(() => {
                leaf.remove();
            }, 5000);
        }

        setInterval(createLeaf, 200); // Munculkan daun setiap 0.2 detik
    </script>
</body>
</html>
