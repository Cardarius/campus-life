campus-life
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Campus Life | Dorm Room Essentials</title>
  <style>
    :root {
      --bg: #0f172a;
      --card: #1e293b;
      --text: #f8fafc;
      --muted: #94a3b8;
      --accent: #38bdf8;
      --accent-hover: #0284c7;
    }
    * { box-sizing: border-box; margin: 0; padding: 0; font-family: system-ui, -apple-system, sans-serif; }
    body { background: var(--bg); color: var(--text); line-height: 1.5; }
    header { padding: 1.5rem 2rem; border-bottom: 1px solid #334155; display: flex; justify-content: space-between; align-items: center; }
    .logo { font-size: 1.5rem; font-weight: 800; letter-spacing: -0.5px; color: var(--accent); }
    .hero { text-align: center; padding: 4rem 1.5rem 2.5rem; max-width: 720px; margin: 0 auto; }
    .hero h1 { font-size: 2.5rem; margin-bottom: 0.75rem; }
    .hero p { color: var(--muted); font-size: 1.1rem; }
    .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr)); gap: 1.5rem; max-width: 1100px; margin: 2rem auto 4rem; padding: 0 1.5rem; }
    .card { background: var(--card); border: 1px solid #334155; border-radius: 12px; padding: 1.5rem; display: flex; flex-direction: column; justify-content: space-between; }
    .badge { display: inline-block; background: rgba(56, 189, 248, 0.15); color: var(--accent); font-size: 0.75rem; font-weight: 700; padding: 0.25rem 0.6rem; border-radius: 999px; margin-bottom: 0.75rem; width: fit-content; }
    .card h2 { font-size: 1.2rem; margin-bottom: 0.5rem; }
    .card p { color: var(--muted); font-size: 0.92rem; margin-bottom: 1.25rem; }
    .price-row { display: flex; justify-content: space-between; align-items: center; margin-top: auto; }
    .price { font-size: 1.35rem; font-weight: 700; }
    .buy-btn { background: var(--accent); color: #0f172a; text-decoration: none; font-weight: 700; padding: 0.65rem 1.1rem; border-radius: 8px; transition: background 0.2s; }
    .buy-btn:hover { background: var(--accent-hover); color: #fff; }
    footer { text-align: center; padding: 2rem; border-top: 1px solid #334155; color: var(--muted); font-size: 0.85rem; }
  </style>
</head>
<body>
  <header>
    <div class="logo">CAMPUS LIFE</div>
    <span>Free Dorm Shipping</span>
  </header>

  <section class="hero">
    <h1>Upgrade Your Dorm Room</h1>
    <p>Damage-free lighting, space-saving organizers, and pocket projectors built for campus life.</p>
  </section>

  <main class="grid">
    <article class="card">
      <div>
        <span class="badge">Ambient Lighting</span>
        <h2>UV Sunset Projection Lamp</h2>
        <p>Tilting 180-degree lamp head casts warm sunset glows across cinderblock walls via USB power.</p>
      </div>
      <div class="price-row">
        <span class="price">$24.99</span>
        <!-- Replace # with your live Stripe Payment Link -->
        <a class="buy-btn" href="https://buy.stripe.com/YOUR_SUNSET_LINK" target="_blank" rel="noopener">Buy Now</a>
      </div>
    </article>

    <article class="card">
      <div>
        <span class="badge">Sleep & Study</span>
        <h2>Galaxy Star & Sound Projector</h2>
        <p>Projects 34 nebula and laser star modes on your ceiling with soothing soundscapes for noisy halls.</p>
      </div>
      <div class="price-row">
        <span class="price">$44.99</span>
        <a class="buy-btn" href="https://buy.stripe.com/YOUR_GALAXY_LINK" target="_blank" rel="noopener">Buy Now</a>
      </div>
    </article>

    <article class="card">
      <div>
        <span class="badge">Music Sync</span>
        <h2>25ft Smart RGBIC LED Strip</h2>
        <p>App-controlled color-chasing LEDs that pulse to your dorm playlist without damaging paint.</p>
      </div>
      <div class="price-row">
        <span class="price">$29.99</span>
        <a class="buy-btn" href="https://buy.stripe.com/YOUR_LED_LINK" target="_blank" rel="noopener">Buy Now</a>
      </div>
    </article>

    <article class="card">
      <div>
        <span class="badge">Dorm Cinema</span>
        <h2>Pocket 1080p Mini Projector</h2>
        <p>Rechargeable wireless projector mirrors your phone onto any wall for instant dorm movie nights.</p>
      </div>
      <div class="price-row">
        <span class="price">$149.99</span>
        <a class="buy-btn" href="https://buy.stripe.com/YOUR_PROJECTOR_LINK" target="_blank" rel="noopener">Buy Now</a>
      </div>
    </article>
  </main>

  <footer>
    &copy; 2026 Campus Life Store. Questions? Email support@campuslifestore.com
  </footer>
</body>
</html>
