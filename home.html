<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Selamat Tahun Baru</title>
  <style>
    :root {
      --bg: #0b1020;
      --card: #12182b;
      --accent: #5ee5a9;
      --accent-2: #8bd3ff;
      --text: #e7ecf3;
      --muted: #a8b1c0;
      --ring: rgba(94, 229, 169, 0.3);
    }
    * { box-sizing: border-box; }
    html, body { height: 100%; }
    body {
      margin: 0;
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      color: var(--text);
      background: radial-gradient(1200px 600px at 80% -20%, #1a2442 0%, var(--bg) 45%),
                  radial-gradient(800px 400px at 10% 120%, #0d1530 0%, var(--bg) 55%);
    }
    .container {
      max-width: 700px;
      margin: 0 auto;
      padding: 20px;
    }
    header {
      text-align: center;
      margin-bottom: 20px;
    }
    .title {
      font-size: clamp(24px, 5vw, 42px);
      margin: 0;
      background: linear-gradient(90deg, #fff, var(--accent), var(--accent-2));
      -webkit-background-clip: text;
      background-clip: text;
      color: transparent;
      min-height: 50px;
    }
    .subtitle {
      font-size: clamp(13px, 2.2vw, 16px);
      color: var(--muted);
      margin: 0;
    }
    .card {
      background: color-mix(in oklab, var(--card) 92%, black 8%);
      border: 1px solid color-mix(in oklab, var(--card) 60%, #2a355a 40%);
      box-shadow: 0 0 0 1px var(--ring), 0 8px 24px rgba(0,0,0,0.35);
      border-radius: 12px;
      padding: 16px;
      backdrop-filter: saturate(1.1) blur(6px);
    }
    article {
      display: grid;
      gap: 14px;
      line-height: 1.6;
      font-size: clamp(14px, 2vw, 16px);
    }
    footer {
      text-align: center;
      color: var(--muted);
      font-size: 12px;
      padding: 20px 0 30px;
    }
    canvas#confetti {
      position: fixed; inset: 0;
      pointer-events: none; z-index: 1;
    }
    .btn {
      display: inline-block;
      margin-top: 12px;
      padding: 10px 16px;
      border-radius: 8px;
      border: none;
      font-weight: bold;
      cursor: pointer;
      background: linear-gradient(180deg, var(--accent), #3fd293);
      color: #0b1020;
      box-shadow: 0 4px 12px rgba(94,229,169,0.3);
    }
    .btn:hover { transform: translateY(-1px); }
  </style>
</head>
<body>
  <canvas id="confetti"></canvas>
  <div class="container">
    <header>
      <h1 class="title" id="interactiveTitle"></h1>
      <p class="subtitle">Untuk Lulu Safinatun Nazah, orang-orang yang kamu sayang, dan tujuan yang kamu jaga.</p>
    </header>

    <main class="card" role="main" aria-label="Ucapan Tahun Baru">
      <!-- Spotify embed -->
      <iframe style="border-radius:12px" src="https://open.spotify.com/embed/track/2QB8FwOszur18Ai7t2XnNi?utm_source=generator" width="100%" height="152" frameBorder="0" allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture" loading="lazy"></iframe>

      <article>
        <p>HALOOOWWW, selamat tahun baru 2026 untuk pacar akuu lulu safinatun nazah. Doa aku untuk kamu di tahun inii, semogaa kamu selalu diberi kesehatan, kekuatan, sertaa semua tujuan kamu dari tahun tahun sebelumnya bisaa tercapai.</p>

<p>Sayangg, terimakasii banyak untuk sudah selalu kuatt, aku bangga sama kamuu. Pastii banyak hal yang suda kamu lewatin di 2025 inii, aku bangga banget kamu bisa lewatin itu semuaa. Mungkin ini bukan tahun terbaik untuk kamu, tapii kamu sudah jadi diri kamu yang terbaik di tahun inii.</p>

<p>Terimakasiii juga suda selalu mau bareng bareng sama aku yang masih banyak kurangnya di tahun inii. Aku sayang bangett sama kamuu, tahun ini, tahun kemarin, dan tahun yang akan datang. Semogaa kita selalu bisa bareng bareng kedepannya yaaa!! I LOVEE YOUU CINTAKUUU 🤍</p>
        <!-- dst sesuai teks panjang Anda -->
      </article>

      <!-- Tombol toggle hujan kukang -->
      <button class="btn" id="startRain">HUJAN KUKANGG</button>
    </main>

    <footer>
      Dibuat dengan hangat oleh Indaka Rahman untuk menyambut awal yang baik. Semoga harimu ringan.
    </footer>
  </div>

  <script>
    // Emoji kukang 🦥
    const canvas = document.getElementById('confetti');
    const ctx = canvas.getContext('2d');
    let W, H, flakes = [];
    const currentEmoji = "🦥"; // kukang
    let raining = false;

    function resize() {
      W = canvas.width = window.innerWidth;
      H = canvas.height = window.innerHeight;
    }
    window.addEventListener('resize', resize);
    resize();

    function spawn(n=30) {
      flakes = Array.from({ length: n }, () => ({
        x: Math.random() * W,
        y: Math.random() * -H,
        s: 1 + Math.random() * 2,
        w: Math.random() * 2 - 1
      }));
    }

    function tick() {
      if (!raining) return;
      ctx.clearRect(0, 0, W, H);
      ctx.font = "28px serif";
      for (const f of flakes) {
        f.y += f.s;
        f.x += f.w;
        if (f.y > H) f.y = -10, f.x = Math.random() * W;
        ctx.fillText(currentEmoji, f.x, f.y);
      }
      requestAnimationFrame(tick);
    }

    const btn = document.getElementById('startRain');
    btn.addEventListener('click', () => {
      if (!raining) {
        raining = true;
        spawn();
        tick();
        btn.textContent = "HUJAN BERHENTI"; // ubah teks tombol
      } else {
        raining = false;
        ctx.clearRect(0, 0, W, H); // bersihkan canvas
        btn.textContent = "HUJAN KUKANGG"; // kembalikan teks tombol
      }
    });

    // Animasi interaktif judul
    const titleText = "Happy New Year 2026 Sayangkuuu";
    const titleEl = document.getElementById("interactiveTitle");
    let i = 0;
    function typeWriter() {
      if (i < titleText.length) {
        const span = document.createElement("span");
        span.textContent = titleText.charAt(i);
        span.onmouseover = () => { span.style.color = "var(--accent)"; };
        span.onmouseout = () => { span.style.color = "transparent"; span.style.backgroundClip="text"; };
        titleEl.appendChild(span);
        i++;
        setTimeout(typeWriter, 100);
      }
    }
    typeWriter();
  </script>
</body>
</html>
