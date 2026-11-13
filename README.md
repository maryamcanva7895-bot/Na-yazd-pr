# Na-yazd-pr
وب‌سایت روابط عمومی انجمن معتادان گمنام شورای منطقه یزد


<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="روابط عمومی انجمن معتادان گمنام شورای منطقه یزد؛ آشنایی با انجمن، پیام بهبودی، پرسش‌های متداول و دسترسی به منابع اطلاع‌رسانی">
  <meta name="theme-color" content="#101d38">
  <title>روابط عمومی انجمن معتادان گمنام | شورای منطقه یزد</title>

  <style>
    :root {
      --navy: #101d38;
      --navy2: #192c50;
      --gold: #d6b66c;
      --cream: #f7f5ef;
      --white: #ffffff;
      --text: #263247;
      --muted: #687386;
      --border: #e8e3d8;
    }

    * { box-sizing: border-box; scroll-behavior: smooth; }

    body {
      margin: 0;
      font-family: Tahoma, Arial, sans-serif;
      background: var(--cream);
      color: var(--text);
      line-height: 2;
    }

    a { color: inherit; text-decoration: none; }

    .topline {
      height: 5px;
      background: linear-gradient(90deg, var(--gold), #f5e4ae, var(--gold));
    }

    header {
      background: var(--navy);
      color: white;
      padding: 18px 6%;
      border-bottom: 2px solid var(--gold);
    }

    .header-inner {
      max-width: 1150px;
      margin: auto;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 20px;
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 13px;
    }

    .logos {
      display: flex;
      gap: 8px;
      align-items: center;
    }

    .logo-placeholder {
      width: 55px;
      height: 55px;
      border: 1px solid var(--gold);
      border-radius: 50%;
      display: grid;
      place-items: center;
      color: var(--gold);
      font-size: 12px;
      text-align: center;
      line-height: 1.3;
      padding: 4px;
    }

    .brand h1 {
      font-size: 16px;
      margin: 0;
      line-height: 1.8;
    }

    .brand p {
      margin: 2px 0 0;
      color: #d8dce5;
      font-size: 11px;
    }

    nav {
      display: flex;
      flex-wrap: wrap;
      gap: 5px;
      justify-content: center;
    }

    nav a {
      color: white;
      font-size: 12px;
      padding: 7px 10px;
      border-radius: 8px;
    }

    nav a:hover {
      background: var(--navy2);
      color: var(--gold);
    }

    .hero {
      background:
        linear-gradient(120deg, rgba(16,29,56,.97), rgba(25,44,80,.91));
      color: white;
      text-align: center;
      padding: 85px 20px 75px;
      border-bottom: 4px solid var(--gold);
    }

    .hero-content { max-width: 850px; margin: auto; }

    .hero .eyebrow {
      color: var(--gold);
      font-size: 14px;
      letter-spacing: 1px;
    }

    .hero h2 {
      font-size: clamp(26px, 5vw, 43px);
      line-height: 1.7;
      margin: 12px 0;
    }

    .hero p {
      color: #e1e5ed;
      font-size: 15px;
      max-width: 700px;
      margin: 10px auto 25px;
    }

    .button {
      display: inline-block;
      background: var(--gold);
      color: var(--navy);
      padding: 10px 22px;
      border-radius: 9px;
      font-weight: bold;
      margin: 5px;
      font-size: 13px;
      transition: .2s;
    }

    .button:hover { transform: translateY(-2px); }

    .button.outline {
      background: transparent;
      border: 1px solid var(--gold);
      color: var(--gold);
    }

    .quick {
      max-width: 1100px;
      margin: -27px auto 35px;
      padding: 0 18px;
      position: relative;
      display: grid;
      grid-template-columns: repeat(4, 1fr);
      gap: 12px;
    }

    .quick a {
      background: white;
      border: 1px solid var(--border);
      border-radius: 13px;
      padding: 17px 10px;
      text-align: center;
      box-shadow: 0 5px 18px rgba(16,29,56,.07);
      font-size: 13px;
      font-weight: bold;
    }

    .quick a:hover {
      border-color: var(--gold);
      color: var(--navy);
    }

    .quick span {
      display: block;
      font-size: 23px;
      margin-bottom: 5px;
    }

    main {
      max-width: 1100px;
      margin: auto;
      padding: 0 18px 45px;
    }

    section { padding: 38px 0; }

    .section-title {
      text-align: center;
      margin-bottom: 25px;
    }

    .section-title h2 {
      color: var(--navy);
      font-size: 24px;
      margin: 0 0 7px;
    }

    .section-title p {
      color: var(--muted);
      font-size: 13px;
      margin: 0;
    }

    .gold-line {
      width: 65px;
      height: 3px;
      background: var(--gold);
      margin: 12px auto;
      border-radius: 5px;
    }

    .card-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 16px;
    }

    .card {
      background: white;
      padding: 22px;
      border: 1px solid var(--border);
      border-radius: 14px;
      box-shadow: 0 4px 14px rgba(16,29,56,.035);
    }

    .card h3 {
      color: var(--navy);
      font-size: 16px;
      margin: 0 0 9px;
    }

    .card p {
      color: var(--muted);
      font-size: 13px;
      margin: 0;
    }

    .icon {
      font-size: 26px;
      margin-bottom: 8px;
    }

    .soft-section {
      background: #eeece5;
      border-radius: 18px;
      padding: 30px 25px;
      margin: 15px 0;
    }

    .history-box {
      background: white;
      padding: 25px;
      border-radius: 14px;
      border-right: 4px solid var(--gold);
    }

    .history-box p {
      font-size: 14px;
      color: var(--text);
    }

    .notice {
      font-size: 12px;
      color: var(--muted);
      background: #f7f5ef;
      padding: 12px;
      border-radius: 9px;
      margin-top: 15px;
    }

    .faq-item {
      background: white;
      border: 1px solid var(--border);
      border-radius: 10px;
      margin: 10px 0;
      overflow: hidden;
    }

    .faq-item summary {
      cursor: pointer;
      padding: 14px 18px;
      color: var(--navy);
      font-weight: bold;
      font-size: 14px;
    }

    .faq-answer {
      padding: 0 18px 15px;
      color: var(--muted);
      font-size: 13px;
    }

    .contact-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 15px;
    }

    .contact-card {
      background: white;
      border: 1px solid var(--border);
      border-radius: 13px;
      padding: 20px;
    }

    .contact-card h3 { color: var(--navy); margin-top: 0; }

    .contact-card a {
      color: #80652c;
      font-weight: bold;
    }

    .story-form {
      background: white;
      padding: 23px;
      border-radius: 14px;
      border: 1px solid var(--border);
    }

    .story-form label {
      display: block;
      font-size: 13px;
      margin: 12px 0 5px;
      color: var(--navy);
    }

    .story-form input,
    .story-form textarea {
      width: 100%;
      padding: 12px;
      border: 1px solid var(--border);
      border-radius: 8px;
      font-family: inherit;
      font-size: 13px;
      background: #fcfbf8;
    }

    .story-form textarea { min-height: 120px; resize: vertical; }

    .story-preview {
      display: none;
      background: #f2efe6;
      padding: 15px;
      margin-top: 15px;
      border-radius: 9px;
      white-space: pre-wrap;
      font-size: 13px;
    }

    footer {
      background: var(--navy);
      color: white;
      text-align: center;
      padding: 30px 18px;
      border-top: 3px solid var(--gold);
    }

    footer p {
      margin: 5px;
      font-size: 12px;
      color: #d9deea;
    }

    footer .registration {
      color: var(--gold);
      font-size: 12px;
    }

    .back-top {
      display: inline-block;
      margin-top: 12px;
      color: var(--gold);
      font-size: 12px;
    }

    @media (max-width: 760px) {
      .header-inner { flex-direction: column; }
      nav { gap: 2px; }
      nav a { font-size: 11px; padding: 6px 8px; }
      .quick { grid-template-columns: repeat(2, 1fr); }
      .card-grid { grid-template-columns: 1fr; }
      .contact-grid { grid-template-columns: 1fr; }
      .hero { padding: 65px 18px; }
      .brand h1 { font-size: 14px; }
    }
  </style>
</head>

<body>
  <div class="topline"></div>

  <header id="top">
    <div class="header-inner">
      <div class="brand">
        <div class="logos">
          <div class="logo-placeholder">لوگوی<br>NA</div>
          <div class="logo-placeholder">روابط<br>عمومی</div>
        </div>
        <div>
          <h1>روابط عمومی انجمن معتادان گمنام</h1>
          <p>شورای منطقه یزد</p>
        </div>
      </div>

      <nav>
        <a href="#home">صفحه اصلی</a>
        <a href="#about">درباره انجمن</a>
        <a href="#history">تاریخچه</a>
        <a href="#pr">روابط عمومی</a>
        <a href="#faq">پرسش‌ها</a>
        <a href="#stories">تجربه بهبودی</a>
        <a href="#contact">ارتباط با ما</a>
      </nav>
    </div>
  </header>

  <div class="hero" id="home">
    <div class="hero-content">
      <div class="eyebrow">تجربه • نیرو • امید</div>
      <h2>امید همیشه وجود دارد</h2>
      <p>
        انجمن معتادان گمنام، راهی برای رهایی از اعتیاد فعال و
        ساختن زندگی تازه در کنار کسانی است که تجربه بهبودی را با یکدیگر به اشتراک می‌گذارند.
      </p>
      <a class="button" href="https://nairan.org" target="_blank" rel="noopener">آشنایی با انجمن</a>
      <a class="button outline" href="#contact">ارتباط و اطلاعات بیشتر</a>
    </div>
  </div>

  <div class="quick">
    <a href="https://nairan.org" target="_blank" rel="noopener">
      <span>🌐</span>سایت رسمی NA ایران
    </a>
    <a href="http://telegram.me/paverkargah" target="_blank" rel="noopener">
      <span>📚</span>کارگاه‌های آموزشی
    </a>
    <a href="#faq">
      <span>❔</span>پرسش‌های متداول
    </a>
    <a href="#contact">
      <span>📍</span>ارتباط با ما
    </a>
  </div>

  <main>
    <section id="about">
      <div class="section-title">
        <h2>انجمن معتادان گمنام چیست؟</h2>
        <div class="gold-line"></div>
        <p>آشنایی با یک راه بهبودی و مشارکت</p>
      </div>

      <div class="card-grid">
        <div class="card">
          <div class="icon">🤝</div>
          <h3>همدلی و مشارکت</h3>
          <p>اعضا تجربه، نیرو و امید خود را با یکدیگر به اشتراک می‌گذارند.</p>
        </div>
        <div class="card">
          <div class="icon">🌱</div>
          <h3>بهبودی</h3>
          <p>بهبودی فرایندی روزانه است؛ تلاش برای زندگی بدون مصرف مواد مخدر.</p>
        </div>
        <div class="card">
          <div class="icon">💙</div>
          <h3>عضویت رایگان</h3>
          <p>تنها شرط عضویت، تمایل به قطع مصرف مواد مخدر است.</p>
        </div>
      </div>
    </section>

    <section id="history" class="soft-section">
      <div class="section-title">
        <h2>تاریخچه انجمن</h2>
        <div class="gold-line"></div>
        <p>آشنایی با مسیر شکل‌گیری و گسترش انجمن</p>
      </div>

      <div class="history-box">
        <h3>انجمن معتادان گمنام در جهان</h3>
        <p>
          انجمن معتادان گمنام در سال ۱۹۵۳ میلادی شکل گرفت.
          این انجمن با تکیه بر مشارکت اعضا و اصول برنامه، به‌تدریج
          در کشورهای مختلف گسترش یافت.
        </p>

        <h3>انجمن در ایران و استان یزد</h3>
        <p>
          این بخش برای ثبت تاریخچه فعالیت انجمن در ایران و یزد در نظر گرفته شده است.
          روایت شکل‌گیری گروه‌ها، نواحی و خدمات منطقه یزد باید بر اساس اسناد
          و اطلاعات تأییدشده انجمن تکمیل شود.
        </p>
        <div class="notice">
          یادآوری: برای حفظ دقت و اعتبار اطلاعات، تاریخ‌ها و آمار مربوط به ایران
          و یزد پس از بررسی منابع معتبر اضافه شوند.
        </div>
      </div>
    </section>

    <section id="pr">
      <div class="section-title">
        <h2>روابط عمومی و اطلاع‌رسانی</h2>
        <div class="gold-line"></div>
        <p>رساندن پیام انجمن با مسئولیت‌پذیری و اتحاد</p>
      </div>

      <div class="card-grid">
        <div class="card">
          <div class="icon">📢</div>
          <h3>اطلاع‌رسانی</h3>
          <p>معرفی صحیح انجمن و فراهم کردن دسترسی به اطلاعات معتبر برای عموم.</p>
        </div>
        <div class="card">
          <div class="icon">🧭</div>
          <h3>ارتباط با جامعه</h3>
          <p>ایجاد ارتباط مسئولانه و محترمانه با افراد و نهادهای جامعه.</p>
        </div>
        <div class="card">
          <div class="icon">📖</div>
          <h3>آموزش و تبادل تجربه</h3>
          <p>تقویت آگاهی خدمتگزاران از طریق آموزش، مطالعه راهنماها و تبادل تجربه.</p>
        </div>
      </div>
    </section>

    <section id="faq" class="soft-section">
      <div class="section-title">
        <h2>پرسش‌های متداول</h2>
        <div class="gold-line"></div>
        <p>پاسخ به پرسش‌های رایج درباره انجمن</p>
      </div>

      <details class="faq-item">
        <summary>آیا برای عضویت در انجمن هزینه‌ای وجود دارد؟</summary>
        <div class="faq-answer">
          خیر. عضویت در انجمن معتادان گمنام رایگان است.
          هزینه‌های گروه‌ها از طریق کمک‌های داوطلبانه اعضا تأمین می‌شود.
        </div>
      </details>

      <details class="faq-item">
        <summary>شرط عضویت در انجمن چیست؟</summary>
        <div class="faq-answer">
          تنها شرط عضویت، تمایل به قطع مصرف مواد مخدر است.
        </div>
      </details>

      <details class="faq-item">
        <summary>آیا برای حضور در جلسات باید کسی مرا معرفی کند؟</summary>
        <div class="faq-answer">
          برای آشنایی با جلسات و اطلاعات حضور، می‌توانی از منابع رسمی انجمن کمک بگیری.
        </div>
      </details>

      <details class="faq-item">
        <summary>آیا انجمن به مذهب یا سازمان خاصی وابسته است؟</summary>
        <div class="faq-answer">
          انجمن معتادان گمنام یک انجمن غیرانتفاعی و مستقل است و به سازمان‌ها،
          مذاهب یا گروه‌های سیاسی وابسته نیست.
        </div>
      </details>

      <details class="faq-item">
        <summary>چگونه می‌توانم درباره جلسات اطلاعات بگیرم؟</summary>
        <div class="faq-answer">
          برای دریافت اطلاعات به‌روز، به وب‌سایت رسمی انجمن معتادان گمنام ایران مراجعه کن.
          <a href="https://nairan.org" target="_blank" rel="noopener">ورود به سایت رسمی NA ایران</a>
        </div>
      </details>
    </section>

    <section id="stories">
      <div class="section-title">
        <h2>تجربه بهبودی</h2>
        <div class="gold-line"></div>
        <p>تجربه، نیرو و امید؛ روایت‌هایی از مسیر بهبودی</p>
      </div>

      <div class="card">
        <p>
          تجربه‌های بهبودی می‌توانند امیدبخش باشند و نشان دهند که تغییر امکان‌پذیر است.
          حفظ گمنامی و رعایت اصول انجمن در انتشار هر تجربه ضروری است.
        </p>
      </div>

      <div class="story-form" style="margin-top:16px">
        <h3>ارسال تجربه برای بررسی و انتشار</h3>
        <p style="font-size:12px;color:#687386">
          این فرم در حال حاضر فقط پیش‌نمایش متن را نمایش می‌دهد و اطلاعات را
          برای مدیر سایت ارسال یا ذخیره نمی‌کند. انتشار تجربه پس از ایجاد روش
          امن دریافت و تأیید مدیر انجام خواهد شد.
        </p>

        <label for="story">متن تجربه</label>
        <textarea id="story" placeholder="تجربه خود را بدون درج اطلاعات هویتی بنویسید..."></textarea>

        <button class="button" type="button" onclick="previewStory()">مشاهده پیش‌نمایش</button>
        <div class="story-preview" id="storyPreview"></div>
      </div>
    </section>

    <section id="contact" class="soft-section">
      <div class="section-title">
        <h2>ارتباط با ما</h2>
        <div class="gold-line"></div>
        <p>دسترسی به منابع اطلاع‌رسانی انجمن</p>
      </div>

      <div class="contact-grid">
        <div class="contact-card">
          <h3>🌐 وب‌سایت رسمی</h3>
          <p>برای اطلاعات رسمی انجمن معتادان گمنام ایران:</p>
          <a href="https://nairan.org" target="_blank" rel="noopener">nairan.org</a>
        </div>

        <div class="contact-card">
          <h3>📚 کارگاه‌های آموزشی</h3>
          <p>دسترسی به محتوای آموزشی و اطلاع‌رسانی کارگاه‌ها:</p>
          <a href="http://telegram.me/paverkargah" target="_blank" rel="noopener">ورود به کانال کارگاه‌ها</a>
        </div>
      </div>

      <div class="notice">
        برای افزودن شماره تماس، نشانی جلسات، QR Code و راه‌های ارتباطی تأییدشده
        شورای منطقه یزد، اطلاعات رسمی را در این قسمت قرار دهید.
      </div>
    </section>
  </main>

  <footer>
    <p>روابط عمومی انجمن معتادان گمنام شورای منطقه یزد</p>
    <p class="registration">شماره ثبت: ۲۱۰۶۵</p>
    <p>تجربه • نیرو • امید</p>
    <a class="back-top" href="#top">بازگشت به بالای صفحه ↑</a>
  </footer>

  <script>
    function previewStory() {
      const story = document.getElementById("story").value.trim();
      const preview = document.getElementById("storyPreview");

      if (!story) {
        alert("لطفاً ابتدا متن تجربه را بنویسید.");
        return;
      }

      preview.style.display = "block";
      preview.textContent = "پیش‌نمایش تجربه شما:\n\n" + story +
        "\n\nاین متن هنوز ارسال یا ذخیره نشده است.";
    }
  </script>
</body>
</html>
