# for-barber Wear
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For Barber Wear | Seu Estilo, Suas Regras</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        body { background-color: #0a0a0a; color: #ffffff; font-family: 'Inter', sans-serif; }
        .gold-text { color: #d4af37; }
        .gold-bg { background-color: #d4af37; }
        .card-dark { background-color: #141414; border: 1px solid #222; }
    </style>
</head>
<body>

    <nav class="flex items-center justify-between px-6 py-4 border-b border-gray-800 sticky top-0 bg-[#0a0a0a] z-50">
        <div class="text-2xl font-bold gold-bg text-black px-2 py-1 rounded">FB</div>
        <div class="hidden md:flex gap-8 text-sm uppercase tracking-widest">
            <a href="#" class="hover:text-yellow-500">Produtos</a>
            <a href="#" class="hover:text-yellow-500">Sobre</a>
            <a href="#" class="hover:text-yellow-500">Contato</a>
        </div>
        <div class="flex gap-4 items-center">
            <i class="fa-solid fa-cart-shopping text-xl cursor-pointer"></i>
            <i class="fa-solid fa-bars text-xl md:hidden"></i>
        </div>
    </nav>

    <section class="relative h-[80vh] flex flex-col items-center justify-center text-center px-4 overflow-hidden">
        <div class="absolute inset-0 opacity-40 bg-[url('https://images.unsplash.com/photo-1503951914875-452162b0f3f1?auto=format&fit=crop&q=80')] bg-cover bg-center"></div>
        <div class="relative z-10">
            <span class="text-xs uppercase tracking-[0.3em] mb-4 block text-gray-400">• Cosméticos Profissionais Masculinos</span>
            <h1 class="text-5xl md:text-7xl font-serif font-bold mb-4 leading-tight">
                Seu Estilo <br> <span class="gold-text">Suas Regras</span>
            </h1>
            <p class="max-w-md mx-auto text-gray-400 mb-8">
                Brilho e fixação forte para um visual impecável que dura o dia todo. Produtos desenvolvidos por profissionais para profissionais.
            </p>
            <div class="flex flex-col gap-4 items-center">
                <button class="gold-bg text-black px-10 py-3 font-bold uppercase tracking-tighter hover:bg-yellow-600 transition w-64">
                    Ver Produtos
                </button>
                <button class="border border-gray-600 px-10 py-3 font-bold uppercase tracking-tighter hover:bg-white hover:text-black transition w-64">
                    Conheça a Marca
                </button>
            </div>
        </div>
    </section>

    <section class="py-20 px-6 max-w-7xl mx-auto">
        <div class="text-center mb-16">
            <h2 class="text-4xl font-bold mb-2">Nossos <span class="gold-text">Produtos</span></h2>
            <p class="text-gray-500">Qualidade profissional para resultados extraordinários</p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            
            <div class="card-dark p-4 rounded-lg group">
                <div class="bg-zinc-900 aspect-square mb-4 flex items-center justify-center rounded overflow-hidden relative">
                    <i class="fa-solid fa-bag-shopping text-4xl text-zinc-700 group-hover:scale-110 transition"></i>
                    <div class="absolute top-2 right-2 gold-bg text-black text-xs font-bold px-2 py-1 rounded">R$ 49,90</div>
                </div>
                <h3 class="text-xl font-bold mb-2">Cera Modeladora Tradicional 120G</h3>
                <p class="text-gray-400 text-sm mb-4 line-clamp-2">Fixação forte, acabamento natural e fragrância marcante para todos os tipos de cabelo.</p>
                <button class="w-full border border-yellow-700 text-yellow-600 py-2 hover:bg-yellow-700 hover:text-black transition font-bold">
                    ADICIONAR AO CARRINHO
                </button>
            </div>

            <div class="card-dark p-4 rounded-lg group">
                <div class="bg-zinc-900 aspect-square mb-4 flex items-center justify-center rounded overflow-hidden relative">
                    <i class="fa-solid fa-droplet text-4xl text-zinc-700"></i>
                    <div class="absolute top-2 right-2 gold-bg text-black text-xs font-bold px-2 py-1 rounded">R$ 39,90</div>
                </div>
                <h3 class="text-xl font-bold mb-2">Óleo de Argan para Barba 30ml</h3>
                <p class="text-gray-400 text-sm mb-4 line-clamp-2">Com 5% de Minoxidil, hidrata, fortalece e nutre profundamente a barba.</p>
                <button class="w-full border border-yellow-700 text-yellow-600 py-2 hover:bg-yellow-700 hover:text-black transition font-bold">
                    ADICIONAR AO CARRINHO
                </button>
            </div>

            <div class="card-dark p-4 rounded-lg group">
                <div class="bg-zinc-900 aspect-square mb-4 flex items-center justify-center rounded overflow-hidden relative">
                    <i class="fa-solid fa-wind text-4xl text-zinc-700"></i>
                    <div class="absolute top-2 right-2 gold-bg text-black text-xs font-bold px-2 py-1 rounded">R$ 34,90</div>
                </div>
                <h3 class="text-xl font-bold mb-2">Shampoo 3 em 1 Mentolado</h3>
                <p class="text-gray-400 text-sm mb-4 line-clamp-2">Limpa profundamente, condiciona e combate a caspa. Deixa cabelo e barba macios.</p>
                <button class="w-full border border-yellow-700 text-yellow-600 py-2 hover:bg-yellow-700 hover:text-black transition font-bold">
                    ADICIONAR AO CARRINHO
                </button>
            </div>

        </div>
    </section>

    <footer class="bg-zinc-950 py-12 px-6 border-t border-zinc-800 text-center">
        <div class="text-2xl font-bold gold-text mb-6">FOR BARBER WEAR</div>
        <div class="flex justify-center gap-6 mb-8 text-gray-400">
            <i class="fa-brands fa-instagram text-2xl hover:text-white cursor-pointer"></i>
            <i class="fa-brands fa-whatsapp text-2xl hover:text-white cursor-pointer"></i>
            <i class="fa-brands fa-facebook text-2xl hover:text-white cursor-pointer"></i>
        </div>
        <p class="text-xs text-zinc-600">© 2026 For Barber Wear. Todos os direitos reservados.</p>
    </footer>

</body>
</html>
