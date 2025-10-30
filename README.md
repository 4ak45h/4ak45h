<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Akash | GitHub Projects</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    /* Animated gradient background */
    body {
      background: linear-gradient(120deg, #0d0d0d, #1a1a1a, #0f2027, #203a43, #2c5364);
      background-size: 400% 400%;
      animation: gradientMove 12s ease infinite;
    }
    @keyframes gradientMove {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    /* Frosted glass effect */
    .glass-card {
      background: rgba(255, 255, 255, 0.08);
      backdrop-filter: blur(15px);
      border: 1px solid rgba(255, 255, 255, 0.2);
      border-radius: 1.5rem;
      box-shadow: 0 4px 30px rgba(0, 0, 0, 0.4);
      transition: all 0.3s ease-in-out;
    }
    .glass-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 40px rgba(0, 0, 0, 0.6);
    }
  </style>
</head>

<body class="flex items-center justify-center min-h-screen text-gray-100 font-sans">
  <div class="glass-card p-10 text-center max-w-md">
    <img src="https://avatars.githubusercontent.com/u/yourgithubid?v=4" 
         alt="Akash" 
         class="w-24 h-24 mx-auto rounded-full border-2 border-gray-400 shadow-md mb-6">
    
    <h1 class="text-3xl font-bold mb-2 tracking-wide">Akash Jatikart</h1>
    <p class="text-gray-400 mb-4 text-sm uppercase tracking-widest">AI | Data Science | Full Stack Enthusiast</p>

    <div class="space-y-2">
      <a href="https://github.com/4ak45h" target="_blank" 
         class="block bg-[#161b22] hover:bg-[#0d1117] text-white py-3 rounded-lg shadow-md hover:shadow-xl transition">
        Visit My GitHub Profile
      </a>
      <a href="https://github.com/4ak45h/smart_finance_dashboard" target="_blank" 
         class="block border border-gray-600 hover:border-gray-300 py-3 rounded-lg text-gray-300 hover:text-white transition">
        Smart Asset & Finance Dashboard
      </a>
      <a href="https://github.com/4ak45h/fashion-fusion" target="_blank" 
         class="block border border-gray-600 hover:border-gray-300 py-3 rounded-lg text-gray-300 hover:text-white transition">
        Fashion Fusion Project
      </a>
    </div>

    <div class="mt-6 text-sm text-gray-500">
      <p>“Code. Create. Contribute.”</p>
    </div>
  </div>
</body>
</html>
