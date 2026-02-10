[index.html](https://github.com/user-attachments/files/25209911/index.html)
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lucas Galvão | Gemini Lab</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@300;400;700&family=Inter:wght@400;700&display=swap');
        body { font-family: 'Inter', sans-serif; background-color: #020617; }
        .mono { font-family: 'JetBrains Mono', monospace; }
        .test-card { transition: all 0.3s ease; border: 1px solid #1e293b; }
        .test-card:hover { border-color: #38bdf8; transform: translateY(-4px); box-shadow: 0 10px 30px -10px rgba(56, 189, 248, 0.2); }
        .gradient-text { background: linear-gradient(90deg, #38bdf8, #818cf8); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
    </style>
</head>
<body class="text-slate-300">

    <header class="border-b border-slate-800 bg-slate-900/50 backdrop-blur-md sticky top-0 z-50">
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <div class="flex items-center gap-3">
                <div class="w-10 h-10 bg-blue-600 rounded-lg flex items-center justify-center text-white font-bold">LG</div>
                <span class="font-bold text-xl text-white tracking-tighter">LUCAS GALVÃO <span class="text-blue-500 underline decoration-2">TESTS</span></span>
            </div>
            <div class="flex gap-4 items-center">
                <span class="hidden md:inline text-xs mono text-emerald-400 bg-emerald-400/10 px-3 py-1 rounded-full border border-emerald-400/20">● Gemini Tester Community</span>
            </div>
        </div>
    </header>

    <main class="max-w-6xl mx-auto px-6 py-12">
        <section class="mb-16">
            <h1 class="text-4xl md:text-6xl font-bold text-white mb-6">Explorando as fronteiras da <br><span class="gradient-text">Inteligência Artificial.</span></h1>
            <p class="max-w-2xl text-lg text-slate-400">
                Este é o meu laboratório vivo. Aqui documento experimentos, prompts complexos e descobertas técnicas realizadas como membro da comunidade de testadores do Gemini.
            </p>
        </section>

        <div class="flex flex-wrap gap-4 mb-10">
            <button class="bg-blue-600 text-white px-4 py-2 rounded-md text-sm font-medium">Todos os Testes</button>
            <button class="bg-slate-800 hover:bg-slate-700 px-4 py-2 rounded-md text-sm font-medium transition">Visão Computacional</button>
            <button class="bg-slate-800 hover:bg-slate-700 px-4 py-2 rounded-md text-sm font-medium transition">Raciocínio Lógico</button>
            <button class="bg-slate-800 hover:bg-slate-700 px-4 py-2 rounded-md text-sm font-medium transition">Multimodalidade</button>
        </div>

        <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
            
            <div class="test-card bg-slate-900/50 p-6 rounded-xl">
                <div class="flex justify-between items-start mb-4">
                    <span class="text-[10px] mono text-blue-400 uppercase tracking-widest">Experimento #001</span>
                    <i data-lucide="flask-conical" class="w-5 h-5 text-slate-500"></i>
                </div>
                <h3 class="text-white font-bold text-xl mb-2">Primeiro Deploy via Gemini</h3>
                <p class="text-slate-400 text-sm mb-4 leading-relaxed">Teste de geração de portfólio profissional com estrutura Tailwind e Lucide Icons.</p>
                <div class="flex gap-2">
                    <span class="text-[10px] bg-slate-800 px-2 py-1 rounded">HTML/JS</span>
                    <span class="text-[10px] bg-slate-800 px-2 py-1 rounded">UI/UX</span>
                </div>
            </div>

            <div class="border border-dashed border-slate-700 p-6 rounded-xl flex flex-col items-center justify-center text-center opacity-60">
                <i data-lucide="plus-circle" class="w-8 h-8 mb-2 text-slate-500"></i>
                <p class="mono text-xs uppercase">Aguardando novo teste...</p>
            </div>

        </div>
    </main>

    <footer class="max-w-6xl mx-auto px-6 py-12 border-t border-slate-800 mt-20 flex flex-col md:flex-row justify-between items-center gap-6">
        <p class="text-sm text-slate-500 mono">© 2026 // LUCAS GALVAO // GEMINI_LAB_ACCESS</p>
        <div class="flex gap-6">
            <a href="#" class="text-slate-500 hover:text-white transition"><i data-lucide="github" class="w-5 h-5"></i></a>
            <a href="#" class="text-slate-500 hover:text-white transition"><i data-lucide="linkedin" class="w-5 h-5"></i></a>
        </div>
    </footer>

    <script>
        lucide.createIcons();
    </script>
</body>
</html>
