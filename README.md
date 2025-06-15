
<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Maafkan Aku</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(to right, #f9d3d3, #ffd6e0);
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      text-align: center;
    }

    h1 {
      font-size: 3rem;
      color: #d7263d;
      margin-bottom: 1rem;
    }

    p {
      font-size: 1.2rem;
      color: #333;
      max-width: 600px;
    }

    .heart {
      font-size: 4rem;
      animation: beat 1s infinite;
    }

    @keyframes beat {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }

    .btn {
      margin-top: 30px;
      padding: 12px 24px;
      background-color: #d7263d;
      color: white;
      border: none;
      border-radius: 12px;
      font-size: 1rem;
      cursor: pointer;
      transition: background 0.3s;
    }

    .btn:hover {
      background-color: #a51b2e;
    }
  </style>
</head>
<body>
  <div class="heart">❤️</div>
  <h1>Maafkan Aku, Sayang</h1>
  <p>
    <p>
  Mungkin aku tak pandai mengungkapkan, tapi hatiku sungguh menyesal atas semua yang terjadi.  
  Aku tahu aku telah menyakitimu, dan itu hal terakhir yang pernah aku inginkan.  
  Aku hanya ingin kamu tahu, cintaku padamu tidak pernah berubah.  
  Beri aku kesempatan untuk memperbaiki semuanya dan menunjukkan bahwa aku benar-benar tulus mencintaimu.
</p>
.
  </p>
  <button class="btn" onclick="alert('Terima kasih sudah memaafkanku. Aku janji akan jadi lebih baik. 💖')">Aku Minta Maaf</button>
</body>
</html>
