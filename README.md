<DOCTYPE html> 
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>اتصل بنا - شات الأقصى</title>
    <meta name="description" content="تواصل معنا عبر البريد الإلكتروني، سناب شات، أو إنستغرام - نحن هنا لمساعدتك">
    <style>
        :root {
            --primary: #2563eb;
            --primary-light: #3b82f6;
            --primary-dark: #1e40af;
            --secondary: #f97316;
            --secondary-light: #fb923c;
            --accent: #ef4444;
            --accent-light: #f87171;
            --success: #10b981;
            --success-light: #34d399;
            --warning: #f59e0b;
            --warning-light: #fbbf24;
            --bg: #fafafa;
            --card: #ffffff;
            --text: #1f2937;
            --text-light: #6b7280;
            --border: #e5e7eb;
            --shadow: rgba(37, 99, 235, 0.1);
        }

        body {
            -webkit-user-select: none;
            -ms-user-select: none;
            user-select: none;
            font-family: 'Tajawal', 'Segoe UI', Tahoma, sans-serif;
            background: linear-gradient(135deg, #fafafa 0%, #f3f4f6 100%);
            color: var(--text);
            line-height: 1.8;
            padding: 20px;
            min-height: 100vh;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }

        .container { max-width: 1000px; margin: 0 auto; }

        .back-btn {
            display: inline-flex;
            align-items: center;
            gap: 10px;
            background: linear-gradient(135deg, var(--primary) 0%, var(--primary-light) 100%);
            color: white;
            padding: 12px 28px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: 600;
            margin-bottom: 25px;
            transition: all 0.3s ease;
        }

        .hero-section {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
            padding: 50px 30px;
            border-radius: 25px;
            text-align: center;
            margin-bottom: 30px;
            position: relative;
            overflow: hidden;
        }

        .card {
            background: var(--card);
            border-radius: 20px;
            padding: 30px;
            margin-bottom: 25px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.06);
            border: 1px solid var(--border);
        }

        .section-title {
            color: var(--primary);
            font-size: 1.6em;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 3px solid var(--secondary);
            display: flex;
            align-items: center;
            gap: 10px;
        }

        .contact-methods {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
        }

        .contact-method {
            background: #fcfcfc;
            padding: 25px;
            border-radius: 15px;
            text-align: center;
            border: 2px solid var(--border);
        }

        .username { direction: ltr; font-weight: bold; color: var(--primary); margin: 10px 0; }

        .contact-link {
            display: inline-block;
            background: var(--primary);
            color: white !important;
            padding: 8px 20px;
            border-radius: 20px;
            text-decoration: none;
            font-size: 0.9em;
        }

        .info-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .info-list { list-style: none; }
        .info-list li {
            padding: 8px 0;
            display: flex;
            align-items: flex-start;
            gap: 10px;
            border-bottom: 1px dashed var(--border);
        }

        .response-time {
            background: #f0f7ff;
            padding: 15px;
            border-radius: 12px;
            border-right: 4px solid var(--primary);
        }

        .warning-box {
            background: #fff5f5;
            padding: 25px;
            border-radius: 15px;
            border: 1px solid #feb2b2;
        }

        .warning-item { color: #c53030; font-weight: 600; margin: 5px 0; }

        .footer { text-align: center; padding: 30px; color: var(--text-light); }
    </style>
</head>
<body oncontextmenu="return false;">
    <div class="container">
        <a href="https://www.chat-jawwal.com" class="back-btn"><span>←</span> العودة إلى الشات</a>

        <div class="hero-section">
            <h1>📞 اتصل بنا</h1>
            <p>نحن هنا لمساعدتك على مدار الساعة - تواصل معنا الآن!</p>
        </div>

        <div class="card">
            <h2 class="section-title">📧 قنوات التواصل الرسمية</h2>
            <div class="contact-methods">
                <div class="contact-method">
                    <div style="font-size: 2.5em;">📧</div>
                    <h4>البريد الإلكتروني</h4>
                    <div class="username">aboushisari6@gmail.com</div>
                    <a href="mailto:aboushisari6@gmail.com" class="contact-link">إرسال بريد</a>
                </div>
                <div class="contact-method">
                    <div style="font-size: 2.5em;">📱</div>
                    <h4>سناب شات</h4>
                    <div class="username">@sari_aboushi</div>
                    <a href="https://www.snapchat.com/add/sari_aboushi" class="contact-link">اضغط للانتقال</a>
                </div>
                <div class="contact-method">
                    <div style="font-size: 2.5em;">📷</div>
                    <h4>إنستغرام</h4>
                    <div class="username">@Chat_alaqssa</div>
                    <a href="https://www.instagram.com/Chat_alaqssa" class="contact-link">اضغط للانتقال</a>
                </div>
            </div>
        </div>

        <div class="info-grid">
            <div class="card">
                <h2 class="section-title">⏰ أوقات الاستجابة</h2>
                <div class="response-time">
                    <ul class="info-list">
                        <li><strong>البريد الإلكتروني:</strong> خلال 24-48 ساعة</li>
                        <li><strong>سناب شات:</strong> خلال 2-12 ساعة</li>
                        <li><strong>إنستغرام:</strong> خلال 2-12 ساعة</li>
                        <li><strong style="color: var(--accent);">الحالات الطارئة:</strong> خلال 1-4 ساعات</li>
                    </ul>
                    <p style="margin-top: 15px; font-size: 0.9em;">💡 نحن نعمل بجد لنكون معك دائماً - صبرك معنا يُقدّر!</p>
                </div>
            </div>

            <div class="card">
                <h2 class="section-title">🎯 متى تتواصل معنا؟</h2>
                <ul class="info-list">
                    <li>✔️ مشكلة تقنية في الموقع</li>
                    <li>✔️ الاستفسار عن الاشتراكات والباقات</li>
                    <li>✔️ الإبلاغ عن مخالفة أو سلوك غير لائق</li>
                    <li>✔️ تقديم اقتراحات لتحسين الخدمة</li>
                    <li>✔️ نسيان كلمة المرور أو مشاكل الدخول</li>
                    <li>✔️ الشكاوى أو المشاكل مع أعضاء آخرين</li>
                </ul>
            </div>
        </div>

        <div class="card">
            <h2 class="section-title">💡 إرشادات للتواصل الفعّال</h2>
            <div class="info-grid">
                <ul class="info-list">
                    <li>📝 اذكر اسم المستخدم الخاص بك بوضوح</li>
                    <li>📝 اشرح مشكلتك بشكل مفصل</li>
                    <li>📝 أرفق أي أدلة أو صور إذا لزم الأمر</li>
                </ul>
                <ul class="info-list">
                    <li>📝 استخدم قناة التواصل المناسبة</li>
                    <li>📝 تحلّى بالصبر أثناء انتظار الرد</li>
                    <li>📝 كن محترماً ومهذباً</li>
                </ul>
            </div>
        </div>

        <div class="card">
            <div class="warning-box">
                <h2 style="color: #c53030; margin-bottom: 15px;">⚠️ تحذير أمني مهم جداً</h2>
                <p>الإدارة لا تطلب منك أبداً المعلومات التالية:</p>
                <div class="info-grid" style="margin: 15px 0;">
                    <div>
                        <div class="warning-item">❌ أرقام الجوال الشخصية</div>
                        <div class="warning-item">❌ الحسابات البنكية أو بيانات الدفع</div>
                    </div>
                    <div>
                        <div class="warning-item">❌ كلمات المرور الخاصة بك</div>
                        <div class="warning-item">❌ أي معلومات شخصية حساسة</div>
                    </div>
                </div>
                <p style="background: #fff; padding: 10px; border-radius: 8px; font-size: 0.9em; border-right: 4px solid #c53030;">
                    ⚡ احذر من أي شخص يدعي أنه من الإدارة ويطلب مثل هذه المعلومات! تواصل معنا عبر القنوات الرسمية فقط للتأكد.
                </p>
            </div>
        </div>

        <div class="footer">
            <p>© 2026 <strong>شات الاقصى للجوال</strong> - جميع الحقوق محفوظة</p>
        </div>
    </div>

    <script>
        // 1. منع النقر الأيمن
        document.addEventListener('contextmenu', event => event.preventDefault());

        // 2. منع اختصارات لوحة المفاتيح بما فيها F12
        document.onkeydown = function(e) {
            // منع F12
            if (e.keyCode == 123) {
                return false;
            }
            // منع Ctrl+Shift+I (Inspect)
            if (e.ctrlKey && e.shiftKey && e.keyCode == 'I'.charCodeAt(0)) {
                return false;
            }
            // منع Ctrl+Shift+C (Inspect Element)
            if (e.ctrlKey && e.shiftKey && e.keyCode == 'C'.charCodeAt(0)) {
                return false;
            }
            // منع Ctrl+Shift+J (Console)
            if (e.ctrlKey && e.shiftKey && e.keyCode == 'J'.charCodeAt(0)) {
                return false;
            }
            // منع Ctrl+U (View Source)
            if (e.ctrlKey && e.keyCode == 'U'.charCodeAt(0)) {
                return false;
            }
            // منع Ctrl+S (Save)
            if (e.ctrlKey && e.keyCode == 'S'.charCodeAt(0)) {
                return false;
            }
        };

        // 3. حماية إضافية: كشف فتح أدوات المطورين وإيقاف الصفحة
        setInterval(function() {
            var before = new Date().getTime();
            debugger; // سيتوقف الكود هنا إذا كانت أدوات المطورين مفتوحة
            var after = new Date().getTime();
            if (after - before > 100) { // إذا استغرق الأمر وقتاً أطول، فالأدوات مفتوحة
                window.location.reload(); // إعادة تحميل الصفحة للتشويش
            }
        }, 100);
    </script>
</body>
</html>
