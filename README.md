<!DOCTYPE html>
<html lang="pt-BR" data-theme="dark">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Potência Serviços Elétricos — Ubá e Região</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@400;600;700;800&family=Barlow:wght@400;500;600&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="css/style.css">
</head>
<body>

<!-- THEME TOGGLE (plug icon) -->
<button class="theme-btn" id="themeBtn" aria-label="Alternar tema">
  <svg class="plug-svg" id="plugSvg" viewBox="0 0 28 28" fill="none" xmlns="http://www.w3.org/2000/svg">
    <!-- plug body -->
    <rect class="plug-body" x="9" y="11" width="10" height="8" rx="1.5"/>
    <!-- prongs -->
    <line class="plug-prong" x1="11.5" y1="11" x2="11.5" y2="7"/>
    <line class="plug-prong" x1="16.5" y1="11" x2="16.5" y2="7"/>
    <!-- cord -->
    <path class="plug-cord" d="M14 19 Q14 23 14 24"/>
    <!-- socket holes -->
    <rect x="11" y="13.5" width="2" height="3" rx="0.5" fill="#0D0D0D" opacity="0.5"/>
    <rect x="15" y="13.5" width="2" height="3" rx="0.5" fill="#0D0D0D" opacity="0.5"/>
  </svg>
</button>

<!-- NAV -->
<nav>
  <a href="#" class="nav-logo">
    <div class="nav-logo-hex">
      <svg viewBox="0 0 24 24" fill="none"><path d="M13 2L4.5 13.5H11L10 22L19.5 10H13L13 2Z" fill="#0D0D0D"/></svg>
    </div>
    <div class="nav-logo-text">
      Potência
      <span class="nav-logo-sub">Serviços Elétricos</span>
    </div>
  </a>
  <ul class="nav-links">
    <li><a href="#servicos">Serviços</a></li>
    <li><a href="#sobre">Sobre</a></li>
    <li><a href="#depoimentos">Depoimentos</a></li>
    <li><a href="#contato">Contato</a></li>
  </ul>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="hero-bg"></div>
  <div class="hero-content">
    <div>
      <div class="hero-tag"><span></span> Ubá e Região — MG</div>
      <h1>Potência<br><em>onde você</em><br>precisar</h1>
      <p class="hero-desc">Serviços elétricos residenciais, prediais e industriais com segurança, agilidade e garantia. Atendemos Ubá e toda a região.</p>
      <div class="hero-ctas">
        <a href="https://wa.me/32999485792?text=Olá!%20Vi%20o%20site%20e%20gostaria%20de%20um%20orçamento." class="btn-primary" target="_blank">
          <svg width="18" height="18" viewBox="0 0 24 24" fill="currentColor"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>
          Solicitar Orçamento
        </a>
        <a href="#servicos" class="btn-secondary">Ver Serviços →</a>
      </div>
    </div>

    <!-- LEAD FORM CARD -->
    <div class="hero-card" id="contato">
      <p class="hero-card-title">⚡ Orçamento Grátis</p>
      <div class="form-group">
        <label>Seu nome</label>
        <input type="text" placeholder="Como podemos te chamar?">
      </div>
      <div class="form-group">
        <label>WhatsApp</label>
        <input type="tel" placeholder="(32) 9 0000-0000">
      </div>
      <div class="form-group">
        <label>Tipo de serviço</label>
        <select>
          <option value="" disabled selected>Selecione...</option>
          <option>Instalação elétrica residencial</option>
          <option>Instalação predial</option>
          <option>Instalação industrial</option>
          <option>Manutenção / Reparo</option>
          <option>Quadro elétrico / SPDA</option>
          <option>Ar-condicionado / Chuveiro</option>
          <option>Outro</option>
        </select>
      </div>
      <div class="form-group">
        <label>Descreva o problema (opcional)</label>
        <textarea placeholder="Conte um pouco sobre o que precisa..."></textarea>
      </div>
      <a href="#" class="btn-primary" style="width:100%;justify-content:center;text-decoration:none;" onclick="sendLead(event)">
        Enviar pelo WhatsApp →
      </a>
    </div>
  </div>
</section>

<!-- STATS -->
<div class="stats">
  <div class="stats-inner">
    <div class="reveal"><div class="stat-num">5+</div><div class="stat-label">Anos de experiência</div></div>
    <div class="reveal"><div class="stat-num">300+</div><div class="stat-label">Clientes atendidos</div></div>
    <div class="reveal"><div class="stat-num">100%</div><div class="stat-label">Com garantia</div></div>
    <div class="reveal"><div class="stat-num">24h</div><div class="stat-label">Resposta rápida</div></div>
  </div>
</div>

<!-- SERVICES -->
<section class="services-bg" id="servicos">
  <div class="section-inner">
    <span class="section-tag reveal">O que fazemos</span>
    <h2 class="reveal">Nossos Serviços</h2>
    <p class="section-desc reveal">Soluções elétricas completas para residências, condomínios e indústrias em Ubá e toda a região.</p>
    <div class="services-grid">

      <div class="service-card reveal">
        <div class="service-icon">
          <svg viewBox="0 0 24 24" fill="none" stroke="var(--gold)" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M3 9l9-7 9 7v11a2 2 0 01-2 2H5a2 2 0 01-2-2z"/><polyline points="9 22 9 12 15 12 15 22"/></svg>
        </div>
        <div class="service-name">Residencial</div>
        <div class="service-desc">Instalações, reparos, tomadas, iluminação, quadros elétricos e tudo que sua casa precisa com segurança.</div>
      </div>

      <div class="service-card reveal">
        <div class="service-icon">
          <svg viewBox="0 0 24 24" fill="none" stroke="var(--gold)" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="3" width="20" height="14" rx="2"/><line x1="8" y1="21" x2="16" y2="21"/><line x1="12" y1="17" x2="12" y2="21"/></svg>
        </div>
        <div class="service-name">Predial</div>
        <div class="service-desc">Instalações em prédios comerciais, condomínios, escritórios e ambientes com alta demanda elétrica.</div>
      </div>

      <div class="service-card reveal">
        <div class="service-icon">
          <svg viewBox="0 0 24 24" fill="none" stroke="var(--gold)" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="7" width="20" height="14" rx="2"/><path d="M16 3l-4 4-4-4"/></svg>
        </div>
        <div class="service-name">Industrial</div>
        <div class="service-desc">Instalações de alta tensão, painéis, manutenção em equipamentos industriais e automação básica.</div>
      </div>

      <div class="service-card reveal">
        <div class="service-icon">
          <svg viewBox="0 0 24 24" fill="none" stroke="var(--gold)" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M13 2L3 14h9l-1 8 10-12h-9l1-8z"/></svg>
        </div>
        <div class="service-name">Quadro Elétrico</div>
        <div class="service-desc">Instalação, modernização e troca de quadros de distribuição — disjuntores, DPS e proteções NR-10.</div>
      </div>

      <div class="service-card reveal">
        <div class="service-icon">
          <svg viewBox="0 0 24 24" fill="none" stroke="var(--gold)" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="5"/><line x1="12" y1="1" x2="12" y2="3"/><line x1="12" y1="21" x2="12" y2="23"/><line x1="4.22" y1="4.22" x2="5.64" y2="5.64"/><line x1="18.36" y1="18.36" x2="19.78" y2="19.78"/><line x1="1" y1="12" x2="3" y2="12"/><line x1="21" y1="12" x2="23" y2="12"/></svg>
        </div>
        <div class="service-name">Iluminação</div>
        <div class="service-desc">Projetos de iluminação LED, decorativa, externa, jardim e sistemas de emergência para toda a propriedade.</div>
      </div>

      <div class="service-card reveal">
        <div class="service-icon">
          <svg viewBox="0 0 24 24" fill="none" stroke="var(--gold)" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M9.59 4.59A2 2 0 1111 8H2m10.59 11.41A2 2 0 1014 16H2m15.73-8.27A2.5 2.5 0 1119.5 12H2"/></svg>
        </div>
        <div class="service-name">Ar-cond. & Chuveiro</div>
        <div class="service-desc">Instalação elétrica para ar-condicionado split, chuveiro elétrico, aquecedores e equipamentos de alto consumo.</div>
      </div>

    </div>
  </div>
</section>

<!-- WHY US -->
<section class="why-bg" id="sobre">
  <div class="section-inner">
    <div class="why-grid">
      <div>
        <span class="section-tag reveal">Por que escolher</span>
        <h2 class="reveal">Segurança e<br>qualidade<br>em primeiro lugar</h2>
        <p class="section-desc reveal">Profissional qualificado, equipamentos certificados e compromisso com a sua segurança em cada serviço.</p>
        <div class="why-list">
          <div class="why-item reveal">
            <span class="why-num">01</span>
            <div>
              <div class="why-item-title">Profissional qualificado NR-10</div>
              <div class="why-item-desc">Treinamento e certificação em segurança elétrica. Trabalhamos dentro das normas da ABNT e ANEEL.</div>
            </div>
          </div>
          <div class="why-item reveal">
            <span class="why-num">02</span>
            <div>
              <div class="why-item-title">Orçamento gratuito e transparente</div>
              <div class="why-item-desc">Sem surpresas. Apresentamos o orçamento completo antes de começar qualquer serviço.</div>
            </div>
          </div>
          <div class="why-item reveal">
            <span class="why-num">03</span>
            <div>
              <div class="why-item-title">Garantia em todos os serviços</div>
              <div class="why-item-desc">Nosso trabalho tem garantia. Qualquer problema após o serviço, retornamos sem custo adicional.</div>
            </div>
          </div>
          <div class="why-item reveal">
            <span class="why-num">04</span>
            <div>
              <div class="why-item-title">Atendimento rápido</div>
              <div class="why-item-desc">Resposta em até 24 horas. Para emergências, entramos em contato o mais rápido possível.</div>
            </div>
          </div>
        </div>
      </div>
      <div class="big-hex reveal">
        <div class="hex-shape">
          <div class="hex-inner">
            <div class="hex-bolt">⚡</div>
            <div class="hex-brand">Potência</div>
            <div class="hex-sub">Serviços Elétricos</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- TESTIMONIALS -->
<section class="testimonials-bg" id="depoimentos">
  <div class="section-inner">
    <span class="section-tag reveal">Depoimentos</span>
    <h2 class="reveal">O que nossos<br>clientes dizem</h2>
    <p class="section-desc reveal">A satisfação de quem já usou nossos serviços é o nosso maior cartão de visita.</p>
    <div class="testimonials-grid">
      <div class="testimonial-card reveal">
        <div class="stars">★★★★★</div>
        <p class="testimonial-text">"Serviço impecável! Trocaram todo o quadro elétrico da minha casa, deixaram tudo organizado e explicaram cada detalhe. Super recomendo!"</p>
        <div class="testimonial-name">Ana Paula S.</div>
        <div class="testimonial-role">Cliente residencial · Ubá</div>
      </div>
      <div class="testimonial-card reveal">
        <div class="stars">★★★★★</div>
        <p class="testimonial-text">"Atendimento rápido e profissional. Resolveram um problema que outros eletricistas não conseguiam. Preço justo e trabalho garantido."</p>
        <div class="testimonial-name">Roberto M.</div>
        <div class="testimonial-role">Comércio · Ubá</div>
      </div>
      <div class="testimonial-card reveal">
        <div class="stars">★★★★★</div>
        <p class="testimonial-text">"Contratei para instalar os ares-condicionados do escritório. Chegaram no horário, trabalharam com cuidado e o serviço ficou perfeito. Muito satisfeito!"</p>
        <div class="testimonial-name">Marcos T.</div>
        <div class="testimonial-role">Escritório · Região de Ubá</div>
      </div>
    </div>
  </div>
</section>

<!-- CTA STRIP -->
<div class="cta-strip">
  <div class="section-inner" style="max-width:700px;text-align:center;">
    <h2>Precisa de um eletricista agora?</h2>
    <p>Entre em contato pelo WhatsApp e receba um orçamento gratuito. Atendemos Ubá e toda a região.</p>
    <a href="https://wa.me/32999485792?text=Olá!%20Vi%20o%20site%20e%20gostaria%20de%20um%20orçamento." class="btn-dark" target="_blank">
      <svg width="18" height="18" viewBox="0 0 24 24" fill="currentColor"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893a11.821 11.821 0 00-3.48-8.413z"/></svg>
      Chamar no WhatsApp
    </a>
  </div>
</div>

<!-- FOOTER -->
<footer>
  <div class="footer-inner">
    <div>
      <div class="footer-brand-name">⚡ Potência Serviços Elétricos</div>
      <p class="footer-brand-desc">Eletricista profissional em Ubá e região. Serviços residenciais, prediais e industriais com qualidade, segurança e garantia.</p>
    </div>
    <div>
      <div class="footer-col-title">Serviços</div>
      <ul class="footer-links">
        <li><a href="#servicos">Residencial</a></li>
        <li><a href="#servicos">Predial</a></li>
        <li><a href="#servicos">Industrial</a></li>
        <li><a href="#servicos">Quadro Elétrico</a></li>
        <li><a href="#servicos">Iluminação</a></li>
      </ul>
    </div>
    <div>
      <div class="footer-col-title">Contato</div>
      <div class="footer-contact-item">📱 (32) 99948-5792</div>
      <div class="footer-contact-item">📧 potenciaeletrik@gmail.com</div>
      <div class="footer-contact-item">📍 Ubá e região — MG</div>
      <div style="margin-top:16px;">
        <a href="https://www.instagram.com/potenciaeletrica.uba" target="_blank" style="font-size:13px;color:var(--gold);text-decoration:none;">@potenciaeletrica.uba →</a>
      </div>
    </div>
  </div>
  <div class="footer-bottom">
    <span>© 2025 Potência Serviços Elétricos. Todos os direitos reservados.</span>
    <span>Ubá — Minas Gerais</span>
  </div>
</footer>

<script src="js/main.js"></script>
</body>
</html>
