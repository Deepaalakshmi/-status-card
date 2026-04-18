# -status-card
HTML and Machine status card


!DOCTYPE html>
<html>
<head>
  
  <title>Machine Status</title>
  <style>
    body {
      display: flex;
      gap: 60px;
      padding: 220px;
      font-family: georgia;
      justify-content: center;
    }

    .card {
      width: 220px;
      border: 2px solid #ccc;
      border-radius: 5px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      overflow: hidden;
    }

    .card:hover {
      transform: scale(1.05);
      transition: 0.3s;
    }

    .card h3 {
      margin: 0;
      padding: 15px;
      border-bottom: 1px solid #ddd;
      background-color: #f5f5f5;
    }

    .status {
      padding: 15px;
      text-align: center;
      font-size: 18px;
      font-weight: lighter;
    }

    .running {
      color: rgb(0, 128, 64);
    }

    .stopped {
      color: red;
    }
  </style>
</head>
<body>

<div class="card">
  <h3>PLC_CUT_SECTOR1</h3>
  <div class="status running">Running 🟢</div>
</div>


</body>
</html>
