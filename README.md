Sobre o Projeto

O RBLtransfer Executivo é um site institucional desenvolvido com o objetivo de apresentar os serviços de transporte executivo da empresa, destacando seus diferenciais, formas de contato e áreas de atuação.
O projeto foi construído utilizando tecnologias web fundamentais (HTML5, CSS3 e JavaScript) com foco em:

Experiência do usuário (UX)
Design moderno e responsivo
Performance em dispositivos móveis
Facilidade de contato com o cliente


Objetivo do Projeto

O principal objetivo do site é:

Apresentar a empresa de forma profissional
Gerar leads através de formulário e WhatsApp
Facilitar o contato direto com clientes
Transmitir confiança, conforto e segurança
Tecnologias Utilizadas
HTML5 → Estrutura do site
CSS3 → Estilização e responsividade
JavaScript (Vanilla) → Interações básicas
Google Fonts → Tipografia (Raleway)
Font Awesome → Ícones
FormSubmit → Envio de formulário sem backend
Google Maps Embed → Localização
Vercel → Deploy e hospedagem


projeto-rbltransfer
│
├── index.html
├── style.css
├── obrigado.html
├── favicon.ico / favicon.png
├── logorbl.jpg
├── carroexecutivo.jpg
├── interno.jpg
Estrutura do HTML

O HTML foi organizado em seções bem definidas para melhorar a leitura e manutenção:

Header (Topo)
Logo da empresa
Menu de navegação
Botão mobile (hambúrguer)

Destaque técnico:

Header fixo (position: fixed)
Alteração de estilo ao rolar a página (via JavaScript)
Seção "Início"
Área inicial com fundo escuro para destaque visual
Introdução da marca
Sobre a Empresa
Texto institucional
Imagem ilustrativa (carro executivo)
Serviços
Lista detalhada dos serviços oferecidos
Estrutura simples com foco em leitura clara
Regiões
Integração com Google Maps via <iframe>
Mostra área de atuação (São Paulo)
Contato
Botão WhatsApp
Link direto para conversa
Alta conversão de contato
Formulário
Nome
Email
Assunto
Mensagem

Integração:

Utiliza FormSubmit (sem backend próprio)
Redirecionamento após envio (_next)
Página de Confirmação (obrigado.html)
Feedback visual para o usuário
Confirma envio da mensagem
Botão de retorno ao site
Footer
Informações da empresa
Contato direto (telefone, email, WhatsApp)
Redes sociais
Direitos autorais


Estilização (CSS)

O CSS foi desenvolvido com foco em:

✔ Layout Responsivo
Uso de flexbox
Media queries para dispositivos móveis
Menu adaptado para mobile
✔ Identidade Visual
Fundo escuro (#000)
Destaques em vermelho (#e43535)
Botões chamativos (WhatsApp verde)
✔ Componentes Importantes
Header dinâmico
.topo.scrolled {
    background: #000;
}
Menu Mobile
.menu.active {
    display: flex;
}
Botão WhatsApp
Centralizado
Chamativo
Alta usabilidade JavaScript Utilizado
 1. Efeito no Header ao rolar
window.addEventListener("scroll", function() {
    const header = document.querySelector(".topo");
    header.classList.toggle("scrolled", window.scrollY > 50);
});

✔ Melhora a experiência do usuário
✔ Deixa o site mais moderno

2. Menu Mobile
toggle.addEventListener("click", () => {
    menu.classList.toggle("active");
});

Permite abrir/fechar o menu no celular

Responsividade:

O site foi otimizado para:

Celulares
Tablets
Desktop
Técnicas utilizadas:
Media Queries (max-width: 768px)
Layout flexível
Menu adaptativo
Performance

Algumas decisões importantes:

Imagens otimizadas 
Código simples 
Uso de CDN 

Implementações realizadas:

- Meta description
- Title otimizado
- Google Search Console verificado
- Favicon configurado
- Estrutura semântica básica
- <meta name="description" content="...">
- Segurança e Boas Práticas
- Uso de formulário externo (FormSubmit)
- Sem exposição de backend
- Links seguros (target="_blank")
- Deploy

O site foi publicado utilizando:
Vercel

Vantagens:
- Deploy rápido
- HTTPS automático
- Alta performance
- Melhorias Futuras
- Otimização de imagens (WebP)
- Animações mais avançadas
- SEO mais aprofundado
- Página de serviços individual
- Integração com backend próprio
- Google Analytics

Autores:
- Desenvolvido por, Ana Cavalcanti Lopes e Rafel Gedeão Eduardo de Santana 

📞 Contato
WhatsApp: (11) 96301-3579
Email: rbltransferleonardo@gmail.com
