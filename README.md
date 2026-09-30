<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>دار صوفيا | Dar Sofia</title>

    <meta
        name="description"
        content="دار صوفيا - منصة رقمية تساعد المستخدمين على اكتشاف فرص العمل والمهام الرقمية خطوة بخطوة."
    >

    <style>
        :root {
            --navy: #071a2b;
            --blue: #123b5d;
            --gold: #d4a72c;
            --light: #f5f7fa;
            --white: #ffffff;
            --text: #1f2937;
            --muted: #64748b;
            --border: #e2e8f0;
        }

        * {
            box-sizing: border-box;
        }

        body {
            margin: 0;
            font-family: Tahoma, Arial, sans-serif;
            background: var(--light);
            color: var(--text);
            line-height: 1.8;
        }

        /* Navigation */
        nav {
            background: var(--navy);
            color: white;
            padding: 16px 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        .brand {
            font-size: 1.3rem;
            font-weight: bold;
        }

        .brand span {
            color: var(--gold);
        }

        .nav-links a {
            color: white;
            text-decoration: none;
            margin-right: 18px;
            font-size: 0.95rem;
        }

        /* Hero */
        .hero {
            background: linear-gradient(135deg, var(--navy), var(--blue));
            color: white;
            text-align: center;
            padding: 75px 20px 85px;
        }

        .hero h1 {
            margin: 0 0 15px;
            font-size: 3rem;
        }

        .hero h1 span {
            color: var(--gold);
        }

        .hero h2 {
            margin: 0 auto 20px;
            font-size: 1.4rem;
            font-weight: normal;
            color: #e2e8f0;
        }

        .hero p {
            max-width: 700px;
            margin: 0 auto 30px;
            color: #cbd5e1;
            font-size: 1.05rem;
        }

        .button {
            display: inline-block;
            background: var(--gold);
            color: var(--navy);
            text-decoration: none;
            padding: 13px 28px;
            border-radius: 8px;
            font-weight: bold;
            margin: 5px;
        }

        .button.secondary {
            background: transparent;
            color: white;
            border: 1px solid #94a3b8;
        }

        /* Main */
        .container {
            max-width: 1050px;
            margin: auto;
            padding: 50px 20px;
        }

        .section-title {
            text-align: center;
            margin-bottom: 35px;
        }

        .section-title h2 {
            color: var(--navy);
            font-size: 2rem;
            margin-bottom: 8px;
        }

        .section-title p {
            color: var(--muted);
        }

        /* Cards */
        .cards {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }

        .card {
            background: var(--white);
            padding: 28px 22px;
            border-radius: 12px;
            border: 1px solid var(--border);
            text-align: center;
            box-shadow: 0 5px 15px rgba(0,0,0,0.04);
        }

        .card-icon {
            font-size: 2.4rem;
            margin-bottom: 10px;
        }

        .card h3 {
            color: var(--navy);
            margin: 8px 0;
        }

        .card p {
            color: var(--muted);
            font-size: 0.95rem;
        }

        /* How it works */
        .steps {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 15px;
        }

        .step {
            background: white;
            border-radius: 10px;
            padding: 22px 15px;
            text-align: center;
            border: 1px solid var(--border);
        }

        .number {
            width: 42px;
            height: 42px;
            line-height: 42px;
            margin: 0 auto 12px;
            border-radius: 50%;
            background: var(--navy);
            color: var(--gold);
            font-weight: bold;
        }

        /* Trust */
        .trust {
            background: var(--navy);
            color: white;
            border-radius: 14px;
            padding: 40px 25px;
            text-align: center;
            margin-top: 50px;
        }

        .trust h2 {
            color: var(--gold);
        }

        .trust p {
            max-width: 750px;
            margin: auto;
            color: #cbd5e1;
        }

        /* Footer */
        footer {
            background: #020b14;
            color: #94a3b8;
            text-align: center;
            padding: 30px 15px;
            font-size: 0.9rem;
        }

        footer strong {
            color: white;
        }

        /* Mobile */
        @media (max-width: 800px) {
            .cards {
                grid-template-columns: 1fr;
            }

            .steps {
                grid-template-columns: 1fr 1fr;
            }

            .hero h1 {
                font-size: 2.3rem;
            }

            .nav-links {
                display: none;
            }
        }

        @media (max-width: 500px) {
            .steps {
                grid-template-columns: 1fr;
            }

            .hero {
                padding: 55px 18px 65px;
            }
        }
    </style>
</head>

<body>

    <!-- Navigation -->
    <nav>
        <div class="brand">
            دار <span>صوفيا</span>
        </div>

        <div class="nav-links">
            <a href="#how">كيف تعمل؟</a>
            <a href="#services">الخدمات</a>
            <a href="#trust">الثقة والشفافية</a>
        </div>
    </nav>


    <!-- Hero -->
    <section class="hero">

        <h1>
            دار <span>صوفيا</span>
        </h1>

        <h2>
            ابدأ طريقك في العمل الرقمي خطوة بخطوة
        </h2>

        <p>
            منصة رقمية تهدف إلى مساعدة المستخدمين على اكتشاف
            فرص ومهام رقمية مناسبة لهم، مع بناء طريق واضح
            من أول تجربة إلى تطوير المهارات والعمل الحقيقي.
        </p>

        <a href="#services" class="button">
            اكتشف SofiaCash
        </a>

        <a href="#how" class="button secondary">
            كيف تعمل دار صوفيا؟
        </a>

    </section>


    <!-- Services -->
    <main class="container">

        <section id="services">

            <div class="section-title">
                <h2>ماذا ستجد في دار صوفيا؟</h2>
                <p>
                    نبدأ ببساطة، ثم نطور المنصة بناءً على التجربة الحقيقية للمستخدمين.
                </p>
            </div>

            <div class="cards">

                <div class="card">
                    <div class="card-icon">💰</div>

                    <h3>SofiaCash</h3>

                    <p>
                        اكتشاف المهام والعروض الرقمية المتاحة
                        للمستخدم، مع متابعة الإنجاز والرصيد.
                    </p>

                    <a href="#" class="button">
                        قريبًا
                    </a>
                </div>


                <div class="card">
                    <div class="card-icon">🎓</div>

                    <h3>SofiaLearn</h3>

                    <p>
                        تطوير المهارات التي يمكن أن تساعد المستخدم
                        على الانتقال من المهام البسيطة إلى فرص أفضل.
                    </p>

                    <a href="#" class="button">
                        قريبًا
                    </a>
                </div>


                <div class="card">
                    <div class="card-icon">🤖</div>

                    <h3>SofiaAI</h3>

                    <p>
                        مساعد رقمي مستقبلي يساعد المستخدم
                        على فهم الفرص وتطوير طريقه الرقمي.
                    </p>

                    <a href="#" class="button">
                        قريبًا
                    </a>
                </div>

            </div>

        </section>


        <!-- How it works -->
        <section id="how" style="margin-top: 65px;">

            <div class="section-title">
                <h2>كيف تبدأ؟</h2>

                <p>
                    لن نعطيك قائمة مهام فقط، بل نحاول بناء طريق واضح خطوة بخطوة.
                </p>
            </div>


            <div class="steps">

                <div class="step">
                    <div class="number">1</div>
                    <strong>أنشئ حسابك</strong>
                    <p>ابدأ بحساب بسيط وآمن.</p>
                </div>

                <div class="step">
                    <div class="number">2</div>
                    <strong>اكتشف الفرص</strong>
                    <p>شاهد المهام المتاحة لك.</p>
                </div>

                <div class="step">
                    <div class="number">3</div>
                    <strong>أنجز المهمة</strong>
                    <p>نفذ المهمة وفق شروطها.</p>
                </div>

                <div class="step">
                    <div class="number">4</div>
                    <strong>تابع تقدمك</strong>
                    <p>تابع الرصيد والإنجازات.</p>
                </div>

            </div>

        </section>


        <!-- Trust -->
        <section id="trust" class="trust">

            <h2>الثقة والشفافية أولًا</h2>

            <p>
                دار صوفيا لا تضمن مبلغًا ثابتًا أو عددًا ثابتًا من المهام.
                توفر العروض والأرباح تعتمد على البلد والجهاز والأهلية
                وتوفر الحملات لدى الشركات الشريكة.
                هدفنا هو عرض المعلومات بوضوح وبناء التجربة
                على نتائج حقيقية يمكن التحقق منها.
            </p>

        </section>

    </main>


    <!-- Footer -->
    <footer>

        <p>
            <strong>Dar Sofia</strong>
        </p>

        <p>
            ننجح عندما ينجح مستخدمونا
        </p>

        <p>
            © 2026 Dar Sofia. All rights reserved.
        </p>

    </footer>

</body>
</html>
