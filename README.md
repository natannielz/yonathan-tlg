<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV Yonathan Hezron</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: rgb(240, 240, 240);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        .cv-container {
            max-width: 900px;
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
            border-top: 10px solid rgb(200, 16, 46);
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
        }
        .cv-header {
            text-align: center;
        }
        .cv-header h1 {
            color: rgb(200, 16, 46);
        }
        .photo-wrapper {
            text-align: center;
        }
        .profile-photo {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid rgb(200, 16, 46);
        }
        .cv-section {
            background: rgb(255, 240, 240);
            padding: 15px;
            border-radius: 5px;
            border-left: 5px solid rgb(200, 16, 46);
        }
        .cv-section h2 {
            color: rgb(200, 16, 46);
            border-bottom: 2px solid rgb(200, 16, 46);
            display: inline-block;
            padding-bottom: 5px;
        }
        .contact-info {
            text-align: center;
            font-size: 14px;
            color: rgb(50, 50, 50);
            background: rgb(255, 240, 240);
            padding: 10px;
            border-radius: 5px;
            border-left: 5px solid rgb(200, 16, 46);
        }
        .grid-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 10px;
        }
        .grid-item {
            background: rgb(255, 255, 255);
            padding: 10px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body>
    <div class="cv-container">
        <div class="cv-header">
            <div class="photo-wrapper">
              <img id="profilePhoto" src="images/daddadd.jpg" alt="Foto Yonathan Hezron" class="profile-photo">
            </div>
            <h1>Yonathan Hezron</h1>
            <p>Mahasiswa Sistem Informasi di Telkom University dengan minat dalam teknologi, analisis data, serta pengembangan perangkat lunak.</p>
        </div>
        
        <div class="contact-info">
            <p><strong>Alamat:</strong> Tunas Regency Cluster Amarylis Block A No 1</p>
            <p><strong>WhatsApp:</strong> 081267061570</p>
            <p><strong>Email:</strong> stghezron@gmail.com</p>
        </div>
        
        <div class="cv-section">
            <h2>Pengalaman Organisasi</h2>
            <div class="grid-container">
                <div class="grid-item">Koordinator Logistik Natal 2023</div>
                <div class="grid-item">Koordinator Logistik Paskah 2024</div>
                <div class="grid-item">Koordinator Logistik Bansos 2024</div>
            </div>
        </div>
        
        <div class="cv-section">
            <h2>Soft Skills</h2>
            <div class="grid-container">
                <div class="grid-item">Komunikasi yang efektif</div>
                <div class="grid-item">Kepemimpinan dan manajemen tim</div>
                <div class="grid-item">Berpikir kritis dan pemecahan masalah</div>
                <div class="grid-item">Manajemen waktu dan organisasi</div>
                <div class="grid-item">Kemampuan adaptasi dan fleksibilitas</div>
            </div>
        </div>
        
        <div class="cv-section">
            <h2>Pendidikan</h2>
            <div class="grid-container">
                <div class="grid-item">Telkom University (2023 - 2025)</div>
                <div class="grid-item">SMA Negeri 19 (2020 - 2023)</div>
                <div class="grid-item">SMP Putra Batam (2017 - 2020)</div>
            </div>
        </div>
        
        <div class="cv-section">
            <h2>Hobi</h2>
            <div class="grid-container">
                <div class="grid-item">Membaca buku psikologi</div>
                <div class="grid-item">Mancing amarah netizen</div>
                <div class="grid-item">Dengar musik</div>
            </div>
        </div>
    </div>
</body>
</html>
