[index.html](https://github.com/user-attachments/files/28410764/index.html)
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coketown Tycoon - Menú Principal</title>
    <!-- Usamos Tailwind CSS para mantener el diseño moderno -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Cinzel:wght@700;800&family=Plus+Jakarta+Sans:wght@400;600;700&display=swap');
        body { font-family: 'Plus Jakarta Sans', sans-serif; background-color: #12100e; }
        .serif-title { font-family: 'Cinzel', serif; }
    </style>
</head>
<body class="text-slate-100 min-h-screen flex flex-col justify-center items-center p-4 selection:bg-amber-600 selection:text-white">

    <div class="max-w-2xl w-full bg-[#1e1b18] border border-[#5c534c] rounded-2xl p-6 md:p-10 shadow-2xl text-center relative overflow-hidden">
        
        <!-- Encabezado Principal -->
        <header class="mb-8 border-b border-[#3a3530] pb-6">
            <h1 class="text-3xl md:text-5xl font-extrabold serif-title tracking-wider text-amber-500 mb-2">COKETOWN TYCOON</h1>
            <p class="text-xs md:text-sm text-slate-400 uppercase tracking-widest font-semibold">Simulador Didáctico de la Revolución Industrial</p>
        </header>

        <p class="text-slate-300 text-sm md:text-base leading-relaxed mb-8">
            Bienvenido al panel central de simulación. Selecciona la perspectiva económica e histórica bajo la cual deseas gestionar el desarrollo urbano, social y financiero de la ciudad de Coketown (1760 - 1850).
        </p>

        <!-- Botones de Acceso a los Juegos -->
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4 max-w-lg mx-auto">
            
            <!-- Botón Versión Capitalista -->
            <a href="coketown_tycoon capitalista.html" class="flex flex-col items-center justify-between p-5 bg-[#111827] border border-[#3a3530] hover:border-amber-500 rounded-xl transition-all duration-300 hover:scale-105 group text-center">
                <div class="text-3xl mb-2">🪙</div>
                <span class="font-extrabold text-slate-100 group-hover:text-amber-500 transition-colors text-lg">Enfoque Capitalista</span>
                <span class="text-xs text-slate-400 mt-2">Basado en la propiedad privada y la Escuela Clásica / Liberal.</span>
            </a>

            <!-- Botón Versión Socialista -->
            <a href="coketown_tycoon socialista.html" class="flex flex-col items-center justify-between p-5 bg-[#111827] border border-[#3a3530] hover:border-rose-500 rounded-xl transition-all duration-300 hover:scale-105 group text-center">
                <div class="text-3xl mb-2">🚩</div>
                <span class="font-extrabold text-slate-100 group-hover:text-rose-400 transition-colors text-lg">Enfoque Socialista</span>
                <span class="text-xs text-slate-400 mt-2">Enfocado en las tensiones de clase, regulación y derechos obreros.</span>
            </a>

        </div>

        <!-- Sección de Ayuda Docente abajo -->
        <footer class="mt-10 pt-4 border-t border-[#3a3530] text-left text-xs text-slate-500">
            <p class="font-bold text-amber-500/80 mb-1">💡 Sugerencia Pedagógica:</p>
            <p class="leading-relaxed">Ideal para proyectar en el aula, permitiendo comparar los impactos de las regulaciones estatales frente al libre mercado sobre las variables de Capital, Bienestar Obrero y Ecología.</p>
        </footer>
    </div>

</body>
</html>
