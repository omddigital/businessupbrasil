<!DOCTYPE html> 
<html lang="pt-BR"> 
<head> 
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
    <title>BusinessUp Brasil - Potencialize Seu Negócio com IA</title> 
    <script src="https://cdn.tailwindcss.com"></script> 
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"> 
    <style> 
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800;900&display=swap'); 
                 
        body { 
            font-family: 'Poppins', sans-serif; 
            background-color: #0a0a0a; 
            color: #ffffff; 
            scroll-behavior: smooth; 
        } 
                 
        .gradient-bg { 
            background: linear-gradient(135deg, #1a1a2e 0%, #16213e 50%, #0f3460 100%); 
        } 
                 
        .btn-glow { 
            box-shadow: 0 0 15px rgba(74, 222, 128, 0.6); 
            transition: all 0.3s ease; 
        } 
                 
        .btn-glow:hover { 
            box-shadow: 0 0 25px rgba(74, 222, 128, 0.9); 
            transform: translateY(-2px); 
        } 
                 
        .testimonial-card { 
            background: rgba(255, 255, 255, 0.05); 
            backdrop-filter: blur(10px); 
            border: 1px solid rgba(255, 255, 255, 0.1); 
            transition: all 0.3s ease; 
        } 
                 
        .testimonial-card:hover { 
            transform: translateY(-5px); 
            border-color: rgba(74, 222, 128, 0.5); 
        } 
                 
        .pricing-card { 
            background: rgba(15, 23, 42, 0.7); 
            border: 1px solid rgba(74, 222, 128, 0.3); 
            transition: all 0.3s ease; 
        } 
                 
        .pricing-card:hover { 
            transform: scale(1.03); 
            border-color: rgba(74, 222, 128, 0.7); 
            box-shadow: 0 10px 25px rgba(74, 222, 128, 0.2); 
        } 
                 
        .hero-video { 
            border-radius: 12px; 
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.5); 
        } 
                 
        .ai-feature-icon { 
            background: rgba(74, 222, 128, 0.1); 
            border: 1px solid rgba(74, 222, 128, 0.3); 
        } 
    </style> 
</head> 
<body class="antialiased"> 
    <!-- Navigation --> 
    <nav class="gradient-bg fixed w-full z-50 py-4 px-6 shadow-lg"> 
        <div class="max-w-7xl mx-auto flex justify-between items-center"> 
            <div class="flex items-center space-x-2"> 
                <div class="w-10 h-10 bg-green-500 rounded-full flex items-center justify-center"> 
                    <i class="fas fa-arrow-up text-white text-lg"></i> 
                </div> 
                <span class="text-2xl font-bold bg-clip-text text-transparent bg-gradient-to-r from-green-400 to-blue-500">BusinessUp</span> 
                <span class="text-sm font-medium text-gray-300">Brasil</span> 
            </div> 
                         
            <div class="hidden md:flex space-x-8"> 
                <a href="#home" class="text-gray-300 hover:text-green-400 transition">Início</a> 
                <a href="#lucia" class="text-gray-300 hover:text-green-400 transition">Conheça Lúcia</a> 
                <a href="#beneficios" class="text-gray-300 hover:text-green-400 transition">Benefícios</a> 
                <a href="#planos" class="text-gray-300 hover:text-green-400 transition">Planos</a> 
                <a href="#depoimentos" class="text-gray-300 hover:text-green-400 transition">Depoimentos</a> 
            </div> 
                         
            <div class="flex items-center space-x-4"> 
                <a href="https://elevenlabs.io/app/talk-to?agent_id=agent_0101k0yb0wc6ef6a5p83ybqs8hyh" class="bg-green-500 hover:bg-green-600 text-white px-4 py-2 rounded-full font-medium btn-glow flex items-center"> 
                    <i class="fas fa-phone-alt mr-2"></i> FALE COM A LÚCIA! 
                </a> 
                <div class="md:hidden"> 
                    <button class="text-gray-300 focus:outline-none"> 
                        <i class="fas fa-bars text-2xl"></i> 
                    </button> 
                </div> 
            </div> 
        </div> 
    </nav> 

    <!-- Hero Section --> 
    <section id="home" class="pt-32 pb-20 px-6 gradient-bg"> 
        <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-12 items-center"> 
            <div> 
                <h1 class="text-4xl md:text-6xl font-bold leading-tight mb-6"> 
                    Transforme seu negócio com <span class="bg-clip-text text-transparent bg-gradient-to-r from-green-400 to-blue-500">Lúcia</span>, a IA que vende 24h por dia 
                </h1> 
                <p class="text-xl text-gray-300 mb-8"> 
                    A primeira assistente de inteligência artificial sem limites de conhecimento, capaz de impulsionar seus resultados em qualquer área do seu negócio. 
                </p> 
                <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-6"> 
                    <a href="#planos" class="bg-green-500 hover:bg-green-600 text-white px-8 py-4 rounded-full font-bold text-lg btn-glow flex items-center justify-center"> 
                        <i class="fas fa-rocket mr-2"></i> CONTRATAR AGORA 
                    </a> 
                    <a href="#lucia" class="border-2 border-green-500 text-green-400 hover:bg-green-500 hover:text-white px-8 py-4 rounded-full font-bold text-lg flex items-center justify-center transition"> 
                        <i class="fas fa-info-circle mr-2"></i> SAIBA MAIS 
                    </a> 
                </div> 
            </div> 
            <div class="relative"> 
                <div class="hero-video overflow-hidden"> 
                    <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Empresário sorrindo" class="w-full h-auto rounded-xl"> 
                </div> 
                <div class="absolute -bottom-6 -left-6 bg-green-500 text-white px-4 py-2 rounded-lg shadow-lg"> 
                    <div class="flex items-center"> 
                        <div class="w-10 h-10 bg-white rounded-full flex items-center justify-center mr-2"> 
                            <i class="fas fa-headphones text-green-500"></i> 
                        </div> 
                        <div> 
                            <p class="text-xs">FALE AGORA COM</p> 
                            <p class="font-bold">LÚCIA</p> 
                        </div> 
                    </div> 
                </div> 
            </div> 
        </div> 
    </section> 

    <!-- Clients Logo Carousel --> 
    <section class="py-12 bg-gray-900"> 
        <div class="max-w-7xl mx-auto px-6"> 
            <h2 class="text-center text-2xl font-bold mb-12">Empresas que já transformaram seus resultados</h2> 
            <div class="flex overflow-x-auto space-x-12 py-4 px-2"> 
                <img src="https://via.placeholder.com/150x60/1a1a2e/ffffff?text=EMPRESA+A" alt="Logo Empresa A" class="h-12 opacity-70 hover:opacity-100 transition"> 
                <img src="https://via.placeholder.com/150x60/1a1a2e/ffffff?text=EMPRESA+B" alt="Logo Empresa B" class="h-12 opacity-70 hover:opacity-100 transition"> 
                <img src="https://via.placeholder.com/150x60/1a1a2e/ffffff?text=EMPRESA+C" alt="Logo Empresa C" class="h-12 opacity-70 hover:opacity-100 transition"> 
                <img src="https://via.placeholder.com/150x60/1a1a2e/ffffff?text=EMPRESA+D" alt="Logo Empresa D" class="h-12 opacity-70 hover:opacity-100 transition"> 
                <img src="https://via.placeholder.com/150x60/1a1a2e/ffffff?text=EMPRESA+E" alt="Logo Empresa E" class="h-12 opacity-70 hover:opacity-100 transition"> 
                <img src="https://via.placeholder.com/150x60/1a1a2e/ffffff?text=EMPRESA+F" alt="Logo Empresa F" class="h-12 opacity-70 hover:opacity-100 transition"> 
            </div> 
        </div> 
    </section> 

    <!-- Meet Lucia Section --> 
    <section id="lucia" class="py-20 px-6 bg-gray-900"> 
        <div class="max-w-7xl mx-auto"> 
            <div class="text-center mb-16"> 
                <span class="text-green-400 font-bold">REVOLUÇÃO EM IA</span> 
                <h2 class="text-4xl font-bold mt-2 mb-4">Conheça Lúcia, sua nova assistente digital</h2> 
                <p class="text-xl text-gray-400 max-w-3xl mx-auto"> 
                    A primeira IA do mercado sem limites de conhecimento, capaz de atuar em qualquer área do seu negócio com excelência. 
                </p> 
            </div> 
                         
            <div class="grid md:grid-cols-2 gap-12 items-center"> 
                <div class="relative"> 
                    <img src="https://images.unsplash.com/photo-1573497019940-1c28c88b4f3e?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=687&q=80" alt="Assistente virtual" class="rounded-xl w-full"> 
                    <div class="absolute -bottom-6 -right-6 bg-blue-500 text-white p-4 rounded-xl shadow-xl"> 
                        <div class="flex items-center"> 
                            <i class="fas fa-globe text-2xl mr-3"></i> 
                            <div> 
                                <p class="text-xs">FALA MAIS DE</p> 
                                <p class="font-bold text-lg">50 IDIOMAS</p> 
                            </div> 
                        </div> 
                    </div> 
                </div> 
                                 
                <div> 
                    <div class="mb-8"> 
                        <h3 class="text-2xl font-bold mb-4">Por que sua empresa precisa da Lúcia?</h3> 
                        <p class="text-gray-400"> 
                            Lúcia não é apenas uma assistente virtual comum. Ela é uma inteligência artificial avançada que combina o melhor do aprendizado de máquina com conhecimento especializado em diversas áreas profissionais. 
                        </p> 
                    </div> 
                                         
                    <div class="grid grid-cols-2 gap-6"> 
                        <div class="ai-feature-icon p-4 rounded-lg"> 
                            <i class="fas fa-bolt text-green-400 text-2xl mb-3"></i> 
                            <h4 class="font-bold mb-2">Respostas Instantâneas</h4> 
                            <p class="text-sm text-gray-400">Atendimento 24/7 sem tempo de espera</p> 
                        </div> 
                        <div class="ai-feature-icon p-4 rounded-lg"> 
                            <i class="fas fa-chart-line text-green-400 text-2xl mb-3"></i> 
                            <h4 class="font-bold mb-2">Vendas Constantes</h4> 
                            <p class="text-sm text-gray-400">Conversão aumentada em até 300%</p> 
                        </div> 
                        <div class="ai-feature-icon p-4 rounded-lg"> 
                            <i class="fas fa-graduation-cap text-green-400 text-2xl mb-3"></i> 
                            <h4 class="font-bold mb-2">Conhecimento Ilimitado</h4> 
                            <p class="text-sm text-gray-400">Domínio de todas as áreas profissionais</p> 
                        </div> 
                        <div class="ai-feature-icon p-4 rounded-lg"> 
                            <i class="fas fa-robot text-green-400 text-2xl mb-3"></i> 
                            <h4 class="font-bold mb-2">Integração Total</h4> 
                            <p class="text-sm text-gray-400">Conecta-se a todos os seus sistemas</p> 
                        </div> 
                    </div> 
                                         
                    <div class="mt-8 flex items-center"> 
                        <a href="https://elevenlabs.io/app/talk-to?agent_id=agent_0101k0yb0wc6ef6a5p83ybqs8hyh" class="bg-green-500 hover:bg-green-600 text-white px-6 py-3 rounded-full font-medium btn-glow flex items-center"> 
                            <i class="fas fa-phone-alt mr-2"></i> FALE COM A LÚCIA! 
                        </a> 
                        <div class="ml-4 flex items-center"> 
                            <i class="fas fa-phone-volume text-green-400 mr-2"></i> 
                            <span class="text-gray-400">Conversa por áudio</span> 
                        </div> 
                    </div> 
                </div> 
            </div> 
        </div> 
    </section> 

    <!-- Video Demo Section --> 
    <section class="py-20 px-6 bg-gray-800"> 
        <div class="max-w-7xl mx-auto"> 
            <div class="text-center mb-16"> 
                <span class="text-green-400 font-bold">DEMONSTRAÇÃO</span> 
                <h2 class="text-4xl font-bold mt-2 mb-4">Veja Lúcia em ação</h2> 
                <p class="text-xl text-gray-400 max-w-3xl mx-auto"> 
                    Assista como nossa IA revolucionária pode transformar o atendimento e vendas da sua empresa. 
                </p> 
            </div> 
                         
            <div class="relative"> 
                <div class="aspect-w-16 aspect-h-9 bg-black rounded-xl overflow-hidden"> 
                    <img src="https://images.unsplash.com/photo-1551288049-bebda4e38f71?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" alt="Video demonstrativo" class="w-full h-full object-cover"> 
                </div> 
                <div class="absolute inset-0 flex items-center justify-center"> 
                    <button class="w-20 h-20 bg-green-500 rounded-full flex items-center justify-center hover:bg-green-600 transition transform hover:scale-110"> 
                        <i class="fas fa-play text-white text-2xl"></i> 
                    </button> 
                </div> 
            </div> 
        </div> 
    </section> 

    <!-- Benefits Section --> 
    <section id="beneficios" class="py-20 px-6 bg-gray-900"> 
        <div class="max-w-7xl mx-auto"> 
            <div class="text-center mb-16"> 
                <span class="text-green-400 font-bold">VANTAGENS COMPETITIVAS</span> 
                <h2 class="text-4xl font-bold mt-2 mb-4">O que Lúcia faz pelo seu negócio?</h2> 
                <p class="text-xl text-gray-400 max-w-3xl mx-auto"> 
                    Descubra como nossa IA pode elevar sua empresa a outro patamar de resultados. 
                </p> 
            </div> 
                         
            <div class="grid md:grid-cols-3 gap-8"> 
                <div class="bg-gray-800 p-8 rounded-xl hover:border-green-500 border border-gray-700 transition"> 
                    <div class="w-16 h-16 bg-green-500 bg-opacity-20 rounded-full flex items-center justify-center mb-6"> 
                        <i class="fas fa-comments text-green-400 text-2xl"></i> 
                    </div> 
                    <h3 class="text-xl font-bold mb-4">Atendimento Personalizado</h3> 
                    <p class="text-gray-400 mb-6"> 
                        Lúcia oferece um atendimento humanizado e personalizado para cada cliente, criando conexões reais que aumentam a satisfação e fidelização. 
                    </p> 
                    <ul class="space-y-3"> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check-circle text-green-400 mr-2"></i> 
                            <span>24 horas por dia, 7 dias por semana</span> 
                        </li> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check-circle text-green-400 mr-2"></i> 
                            <span>Respostas instantâneas e precisas</span> 
                        </li> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check-circle text-green-400 mr-2"></i> 
                            <span>Tom de voz adaptável ao cliente</span> 
                        </li> 
                    </ul> 
                </div> 
                                 
                <div class="bg-gray-800 p-8 rounded-xl hover:border-green-500 border border-gray-700 transition"> 
                    <div class="w-16 h-16 bg-green-500 bg-opacity-20 rounded-full flex items-center justify-center mb-6"> 
                        <i class="fas fa-shopping-cart text-green-400 text-2xl"></i> 
                    </div> 
                    <h3 class="text-xl font-bold mb-4">Vendas Automatizadas</h3> 
                    <p class="text-gray-400 mb-6"> 
                        Transforme visitantes em clientes com uma máquina de vendas que nunca dorme, com argumentação perfeita e persuasão científica. 
                    </p> 
                    <ul class="space-y-3"> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check-circle text-green-400 mr-2"></i> 
                            <span>Conversão aumentada em até 300%</span> 
                        </li> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check-circle text-green-400 mr-2"></i> 
                            <span>Upselling e cross-selling inteligente</span> 
                        </li> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check-circle text-green-400 mr-2"></i> 
                            <span>Abordagem adaptada a cada perfil</span> 
                        </li> 
                    </ul> 
                </div> 
                                 
                <div class="bg-gray-800 p-8 rounded-xl hover:border-green-500 border border-gray-700 transition"> 
                    <div class="w-16 h-16 bg-green-500 bg-opacity-20 rounded-full flex items-center justify-center mb-6"> 
                        <i class="fas fa-brain text-green-400 text-2xl"></i> 
                    </div> 
                    <h3 class="text-xl font-bold mb-4">Conhecimento Ilimitado</h3> 
                    <p class="text-gray-400 mb-6"> 
                        Acesse todo o conhecimento profissional necessário para seu negócio, com respostas precisas em qualquer área de atuação. 
                    </p> 
                    <ul class="space-y-3"> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check-circle text-green-400 mr-2"></i> 
                            <span>Domínio de todas as áreas profissionais</span> 
                        </li> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check-circle text-green-400 mr-2"></i> 
                            <span>Atualização constante de informações</span> 
                        </li> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check-circle text-green-400 mr-2"></i> 
                            <span>Capacidade de aprendizado contínuo</span> 
                        </li> 
                    </ul> 
                </div> 
            </div> 
        </div> 
    </section> 

    <!-- Pricing Section --> 
    <section id="planos" class="py-20 px-6 bg-gray-800"> 
        <div class="max-w-7xl mx-auto"> 
            <div class="text-center mb-16"> 
                <span class="text-green-400 font-bold">INVESTIMENTO</span> 
                <h2 class="text-4xl font-bold mt-2 mb-4">Planos que cabem no seu negócio</h2> 
                <p class="text-xl text-gray-400 max-w-3xl mx-auto"> 
                    Escolha o pacote ideal para o tamanho e necessidades da sua empresa. 
                </p> 
            </div> 
                         
            <div class="grid md:grid-cols-3 gap-8 max-w-5xl mx-auto"> 
                <!-- Plano Básico --> 
                <div class="pricing-card p-8 rounded-xl"> 
                    <div class="text-center mb-6"> 
                        <h3 class="text-2xl font-bold mb-2">Básico</h3> 
                        <p class="text-gray-400">Ideal para pequenos negócios</p> 
                    </div> 
                    <div class="text-center mb-8"> 
                        <span class="text-5xl font-bold">R$ 650</span> 
                        <span class="text-gray-400">/mês</span> 
                    </div> 
                    <ul class="space-y-4 mb-8"> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check text-green-400 mr-3"></i> 
                            <span>Atendimento 24h/dia</span> 
                        </li> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check text-green-400 mr-3"></i> 
                            <span>1 idioma (Português)</span> 
                        </li> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check text-green-400 mr-3"></i> 
                            <span>Suporte por e-mail</span> 
                        </li> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check text-green-400 mr-3"></i> 
                            <span>Até 100 interações/dia</span> 
                        </li> 
                    </ul> 
                    <a href="#contact" class="block text-center bg-gray-700 hover:bg-gray-600 text-white py-3 rounded-lg font-medium transition">Contratar</a> 
                </div> 
                                 
                <!-- Plano Profissional (Destaque) --> 
                <div class="pricing-card p-8 rounded-xl relative border-2 border-green-500 transform scale-105"> 
                    <div class="absolute top-0 right-0 bg-green-500 text-white px-4 py-1 rounded-bl-lg rounded-tr-lg font-bold text-sm"> 
                        MAIS POPULAR 
                    </div> 
                    <div class="text-center mb-6"> 
                        <h3 class="text-2xl font-bold mb-2">Profissional</h3> 
                        <p class="text-gray-400">Para empresas em crescimento</p> 
                    </div> 
                    <div class="text-center mb-8"> 
                        <span class="text-5xl font-bold">R$ 1.250</span> 
                        <span class="text-gray-400">/mês</span> 
                    </div> 
                    <ul class="space-y-4 mb-8"> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check text-green-400 mr-3"></i> 
                            <span>Atendimento 24h/dia</span> 
                        </li> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check text-green-400 mr-3"></i> 
                            <span>3 idiomas</span> 
                        </li> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check text-green-400 mr-3"></i> 
                            <span>Suporte prioritário</span> 
                        </li> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check text-green-400 mr-3"></i> 
                            <span>Até 500 interações/dia</span> 
                        </li> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check text-green-400 mr-3"></i> 
                            <span>Relatórios mensais</span> 
                        </li> 
                    </ul> 
                    <a href="https://wa.me/5538999857924" class="block text-center bg-green-500 hover:bg-green-600 text-white py-3 rounded-lg font-medium btn-glow">Contratar</a> 
                </div> 
                                 
                <!-- Plano Enterprise --> 
                <div class="pricing-card p-8 rounded-xl"> 
                    <div class="text-center mb-6"> 
                        <h3 class="text-2xl font-bold mb-2">Enterprise</h3> 
                        <p class="text-gray-400">Para grandes corporações</p> 
                    </div> 
                    <div class="text-center mb-8"> 
                        <span class="text-5xl font-bold">R$ 2.500</span> 
                        <span class="text-gray-400">/mês</span> 
                    </div> 
                    <ul class="space-y-4 mb-8"> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check text-green-400 mr-3"></i> 
                            <span>Atendimento 24h/dia</span> 
                        </li> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check text-green-400 mr-3"></i> 
                            <span>Idiomas ilimitados</span> 
                        </li> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check text-green-400 mr-3"></i> 
                            <span>Suporte dedicado 24/7</span> 
                        </li> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check text-green-400 mr-3"></i> 
                            <span>Interações ilimitadas</span> 
                        </li> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check text-green-400 mr-3"></i> 
                            <span>Relatórios em tempo real</span> 
                        </li> 
                        <li class="flex items-center"> 
                            <i class="fas fa-check text-green-400 mr-3"></i> 
                            <span>Integrações customizadas</span> 
                        </li> 
                    </ul> 
                    <a href="#contact" class="block text-center bg-gray-700 hover:bg-gray-600 text-white py-3 rounded-lg font-medium transition">Contratar</a> 
                </div> 
            </div> 
                         
            <div class="mt-12 text-center"> 
                <p class="text-gray-400 mb-4">Precisa de um plano personalizado?</p> 
                <a href="https://wa.me/5538999857924" class="inline-block border-2 border-green-500 text-green-400 hover:bg-green-500 hover:text-white px-6 py-3 rounded-full font-medium transition"> 
                    Fale com nosso time 
                </a> 
            </div> 
        </div> 
    </section> 

    <!-- Testimonials Section --> 
    <section id="depoimentos" class="py-20 px-6 bg-gray-900"> 
        <div class="max-w-7xl mx-auto"> 
            <div class="text-center mb-16"> 
                <span class="text-green-400 font-bold">DEPOIMENTOS</span> 
                <h2 class="text-4xl font-bold mt-2 mb-4">O que nossos clientes dizem</h2> 
                <p class="text-xl text-gray-400 max-w-3xl mx-auto"> 
                    Empresários de diversos segmentos que já transformaram seus negócios com Lúcia. 
                </p> 
            </div> 
                         
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Depoimento 1 -->
                <div class="testimonial-card p-8 rounded-xl">
                    <div class="flex items-center mb-6">
                        <img src="https://images.unsplash.com/photo-1560250097-0b93528c311a?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=687&q=80" alt="Carlos Silva" class="w-16 h-16 rounded-full object-cover mr-4">
                        <div>
                            <h4 class="font-bold">Carlos Silva</h4>
                            <p class="text-green-400 text-sm">CEO - Varejo Plus</p>
                        </div>
                    </div>
                    <p class="text-gray-400 mb-6">
                        "Desde que implementamos a Lúcia em nosso e-commerce, nossas vendas noturnas aumentaram em 180%. Ela atende os clientes com uma eficiência impressionante e nunca deixa uma oportunidade passar."
                    </p>
                    <div class="flex text-yellow-400">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>

                <!-- Depoimento 2 -->
                <div class="testimonial-card p-8 rounded-xl">
                    <div class="flex items-center mb-6">
                        <img src="https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=688&q=80" alt="Ana Beatriz" class="w-16 h-16 rounded-full object-cover mr-4">
                        <div>
                            <h4 class="font-bold">Ana Beatriz</h4>
                            <p class="text-green-400 text-sm">Diretora - Clínica Saúde Total</p>
                        </div>
                    </div>
                    <p class="text-gray-400 mb-6">
                        "A Lúcia revolucionou nosso atendimento. Ela agenda consultas, responde dúvidas médicas básicas e ainda consegue vender nossos pacotes de saúde 24 horas por dia. Nossos pacientes adoraram!"
                    </p>
                    <div class="flex text-yellow-400">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                    </div>
                </div>

                <!-- Depoimento 3 -->
                <div class="testimonial-card p-8 rounded-xl">
                    <div class="flex items-center mb-6">
                        <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=687&q=80" alt="Ricardo Almeida" class="w-16 h-16 rounded-full object-cover mr-4">
                        <div>
                            <h4 class="font-bold">Ricardo Almeida</h4>
                            <p class="text-green-400 text-sm">Fundador - TechSolutions</p>
                        </div>
                    </div>
                    <p class="text-gray-400 mb-6">
                        "Como empresa de tecnologia, somos exigentes com soluções de IA. A Lúcia superou todas as expectativas, atendendo clientes internacionais em múltiplos idiomas e integrando-se perfeitamente aos nossos sistemas."
                    </p>
                    <div class="flex text-yellow-400">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 border-t border-gray-800 py-12 px-6">
        <div class="max-w-7xl mx-auto">
            <div class="grid md:grid-cols-4 gap-12">
                <div>
                    <div class="flex items-center space-x-2 mb-4">
                        <div class="w-10 h-10 bg-green-500 rounded-full flex items-center justify-center">
                            <i class="fas fa-arrow-up text-white text-lg"></i>
                        </div>
                        <span class="text-xl font-bold bg-clip-text text-transparent bg-gradient-to-r from-green-400 to-blue-500">BusinessUp</span>
                    </div>
                    <p class="text-gray-400">
                        Potencializando negócios com inteligência artificial de última geração.
                    </p>
                </div>
                
                <div>
                    <h4 class="text-lg font-bold mb-4">Links Rápidos</h4>
                    <ul class="space-y-2">
                        <li><a href="#home" class="text-gray-400 hover:text-green-400 transition">Início</a></li>
                        <li><a href="#lucia" class="text-gray-400 hover:text-green-400 transition">Conheça Lúcia</a></li>
                        <li><a href="#beneficios" class="text-gray-400 hover:text-green-400 transition">Benefícios</a></li>
                        <li><a href="#planos" class="text-gray-400 hover:text-green-400 transition">Planos</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-bold mb-4">Contato</h4>
                    <ul class="space-y-2 text-gray-400">
                        <li class="flex items-center">
                            <i class="fas fa-envelope mr-2 text-green-400"></i>
                            oliveiramarketing28@gmail.com
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-phone-alt mr-2 text-green-400"></i>
                            (38) 99985-7924
                        </li>
                        <li class="flex items-center">
                            <i class="fab fa-whatsapp mr-2 text-green-400"></i>
                            <a href="https://wa.me/5538999857924" class="hover:text-green-400">WhatsApp</a>
                        </li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-bold mb-4">Redes Sociais</h4>
                    <div class="flex space-x-4">
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-green-500 transition">
                            <i class="fab fa-instagram"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-gray-800 rounded-full flex items-center justify-center hover:bg-green-500 transition">
                            <i class="fab fa-facebook-f"></i>
                        </a>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-gray-800 mt-12 pt-8 text-center text-gray-500">
                <p>&copy; 2023 BusinessUp Brasil. Todos os direitos reservados.</p>
            </div>
        </div>
    </footer>
</body>
</html>
