<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Souhail Fellaki's GitHub Profile</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/chart.js@3.9.1/dist/chart.min.js"></script>
</head>
<body class="bg-gray-900 text-white font-sans">
    <div class="container mx-auto p-6 max-w-4xl">
        <h1 class="text-4xl font-bold text-center mb-4">Hey 👋, I'm <span class="text-purple-400">Souhail Fellaki</span></h1>
        <p class="text-center mb-4">
            <img src="https://komarev.com/ghpvc/?username=souhailfl&label=Profile%20views&color=0e75b6&style=flat" alt="souhailfl" />
        </p>
        <div class="flex justify-center mb-6">
            <img src="https://i.ibb.co/5rXx2RH/329566101-727748832355184-5866501581331802860-n.jpg" alt="Souhail" class="rounded-full w-48 h-48 object-cover shadow-lg" />
        </div>
        <h2 class="text-2xl font-semibold text-center mb-6">A passionate IT lover from Morocco 😍💻</h2>
        <div class="flex justify-center mb-6">
            <img src="https://i.ibb.co/d2DC1Sn/animesher-com-code-computer-html-197855.gif" alt="Coding GIF" class="w-64" />
        </div>
        <div class="flex justify-center mb-6">
            <a href="https://git.io/streak-stats">
                <img src="https://github-readme-streak-stats.herokuapp.com?user=SouhailFl&theme=shadow-purple&border_radius=30" alt="GitHub Streak" class="shadow-md" />
            </a>
        </div>
        <div class="flex justify-center mb-6">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=SouhailFl&layout=compact" alt="Top Languages" class="shadow-md" />
        </div>
        <div class="bg-gray-800 p-6 rounded-lg shadow-lg mb-6">
            <h3 class="text-xl font-semibold mb-4 text-center">GitHub Activity Graph</h3>
            <canvas id="activityChart" class="w-full h-64"></canvas>
        </div>
        <p class="text-center mb-6">
            📫 How to reach me: <a href="mailto:souhailfellaki@gmail.com" class="text-purple-400 hover:underline">souhailfellaki@gmail.com</a>
        </p>
        <hr class="border-gray-700 mb-6">
        <h3 class="text-xl font-semibold text-center mb-4">Connect with me:</h3>
        <div class="flex justify-center space-x-4">
            <a href="https://www.linkedin.com/in/souhail-fellaki-1b1759262/" class="hover:opacity-80">
                <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="LinkedIn" class="w-10 h-10" />
            </a>
            <a href="https://facebook.com/souhailfellaki" class="hover:opacity-80">
                <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="Facebook" class="w-10 h-10" />
            </a>
            <a href="https://instagram.com/souhail_fl" class="hover:opacity-80">
                <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="Instagram" class="w-10 h-10" />
            </a>
            <a href="https://discord.com/users/souhail_fl" class="hover:opacity-80">
                <img src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="Discord" class="w-10 h-10" />
            </a>
        </div>
    </div>
    <script>
        const ctx = document.getElementById('activityChart').getContext('2d');
        new Chart(ctx, {
            type: 'bar',
            data: {
                labels: ['Jan', 'Feb', 'Mar', 'Apr', 'May', 'Jun'],
                datasets: [
                    {
                        label: 'Commits',
                        data: [120, 150, 100, 180, 200, 170],
                        backgroundColor: 'rgba(139, 92, 246, 0.5)',
                        borderColor: 'rgba(139, 92, 246, 1)',
                        borderWidth: 1
                    },
                    {
                        label: 'Pull Requests',
                        data: [10, 15, 8, 12, 20, 18],
                        backgroundColor: 'rgba(236, 72, 153, 0.5)',
                        borderColor: 'rgba(236, 72, 153, 1)',
                        borderWidth: 1
                    }
                ]
            },
            options: {
                scales: {
                    y: {
                        beginAtZero: true,
                        title: {
                            display: true,
                            text: 'Count',
                            color: '#ffffff'
                        },
                        ticks: { color: '#ffffff' }
                    },
                    x: {
                        title: {
                            display: true,
                            text: 'Month',
                            color: '#ffffff'
                        },
                        ticks: { color: '#ffffff' }
                    }
                },
                plugins: {
                    legend: {
                        labels: { color: '#ffffff' }
                    }
                }
            }
        });
    </script>
</body>
</html>
